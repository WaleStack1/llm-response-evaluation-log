LLM Response Evaluation Log

Practice log for RLHF-style response evaluation. Each entry has a question and two candidate answers (A and B). I pick the better one and explain why.

SCOPE

- 10 mathematics, 10 statistics, 10 physics comparisons
- Questions and candidate answers come from an AI-assisted practice set
- I reviewed each verdict and reasoning and corrected some mistakes also 
HOW I JUDGE

1. Accuracy: is the method and the final answer correct?
2. Instruction-following: did it do what the question asked (show working, give units, verify)?
3. Clarity: is it well structured and easy to follow?

EXAMPLE

Question: Differentiate y = e^(3x) cos x.

A: e^(3x)(cos x − 3 sin x)

B: e^(3x)(3 cos x − sin x)

Winner: B

Reason: B applies the product rule correctly (u'v + uv'). A put the 3 and the minus sign on the wrong terms.

FILES

evaluation-log.md  :all 30 comparisons with verdicts

AUTHOR

Ola Wale, Software Engineering student, OAU
