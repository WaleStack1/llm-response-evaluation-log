# llm-response-evaluation-log
Practice log of 30 LLM response comparisons in mathematics, statistics and physics, with a winner and written justification for each.
# LLM Response Evaluation Log

Practice log for RLHF-style response evaluation. Each entry has a Question and two candidate answers (A and B). I pick the better one and explain why.

## Scope
- 10 mathematics, 10 statistics, 10 physics comparisons
- Question and candidate answers come from an AI-assisted practice set
- Verdicts and justifications are written by me

## How I judge
1. Accuracy: is the method accurate is it correct ?
2. Instruction-following: did it according to the instructions of the questions (show working, give units, verify)
3. Clarity: is it structured properly and easy to follow up ?

## Example
Question : Differentiate y = e^(3x) cos x.
A: e^(3x)(cos x − 3 sin x)
B: e^(3x)(3 cos x − sin x)
Winner: B. It applies the product rule correctly (u'v + uv'). A put the 3 and the minus sign on the wrong terms.

## Files
- evaluation-log.md: all 30 comparisons with verdicts

## Author
Ola Wale, Software Engineering student, OAU
