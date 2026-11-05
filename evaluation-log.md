EVALUATION LOG

Practice comparisons: 10 mathematics, 10 statistics, 10 physics.

Judging order: accuracy, then instruction-following, then clarity.

MATHEMATICS

Comparison 1

Question: Differentiate y = e^(3x) cos x.

A: y' = e^(3x)(cos x − 3 sin x)

B: y' = 3e^(3x) cos x − e^(3x) sin x = e^(3x)(3 cos x − sin x)

Winner: B

Reason: B applies the product rule correctly (u'v + uv'). A put the 3 and the minus sign on the wrong terms.

Comparison 2

Question: Evaluate the integral of x e^x dx.

A: By parts (u = x, dv = e^x dx): x e^x − (integral of e^x dx) = x e^x − e^x + C

B: x e^x + e^x + C

Winner: A

Reason: Differentiating A gives x e^x, which matches the integrand. B has a sign error.

Comparison 3

Question: Find the limit of sin(3x)/x as x → 0.

A: 1, because sin x / x → 1.

B: sin(3x)/x = 3 · [sin(3x)/(3x)] → 3 · 1 = 3

Winner: B

Reason: The argument must match the denominator, so B rescales it. A used the standard limit without rescaling.

Comparison 4

Question: Solve x² − 5x + 6 = 0 and verify your roots by substitution.

A: (x − 2)(x − 3) = 0, so x = 2 or 3. Check: 4 − 10 + 6 = 0 and 9 − 15 + 6 = 0.

B: x = 2 or x = 3

Winner: A

Reason: Both are correct, but only A follows the instruction to verify.

Comparison 5

Question: Find the eigenvalues of the matrix [[4, 1], [2, 3]].

A: det(M − λI) = (4 − λ)(3 − λ) − 2 = λ² − 7λ + 10 = 0, so λ = 2 and 5.

B: λ = 4 and 3 (the diagonal entries)

Winner: A

Reason: The diagonal shortcut only works for triangular matrices.

Comparison 6

Question: Find the sum to infinity of 3 + 3/2 + 3/4 + ...

A: It diverges because there are infinitely many terms.

B: Geometric with a = 3 and r = 1/2. Since |r| < 1, S = a/(1 − r) = 3/(1/2) = 6.

Winner: B

Reason: Infinitely many terms do not mean divergence. This series converges because |r| < 1.

Comparison 7

Question: Compute the cross product (1, 2, 3) × (4, 5, 6).

A: (3, −6, 3)

B: (2·6 − 3·5, 3·4 − 1·6, 1·5 − 2·4) = (−3, 6, −3)

Winner: B

Reason: A computed b × a, which flips every sign.

Comparison 8

Question: Simplify (2 + 3i)(1 − i).

A: 2 − 2i + 3i − 3i² = 2 + i + 3 = 5 + i

B: 2 − 2i + 3i − 3i² = 2 + i − 3 = −1 + i

Winner: A

Reason: Since i² = −1, the term −3i² equals +3. B got the sign wrong.

Comparison 9

Question: Write the Maclaurin series of cos x up to the x⁴ term.

A: 1 − x²/2 + x⁴/4

B: 1 − x²/2! + x⁴/4! = 1 − x²/2 + x⁴/24

Winner: B

Reason: A dropped the factorial, since 4! = 24.

Comparison 10

Question: Find and classify the stationary points of f(x) = x³ − 3x.

A: f'(x) = 3x² − 3 = 0, so x = ±1. f''(x) = 6x. f''(−1) = −6 gives a local maximum at (−1, 2). f''(1) = 6 gives a local minimum at (1, −2).

B: x = ±1, local minimum at x = −1 and local maximum at x = 1.

Winner: A

Reason: A uses the second-derivative test correctly. B swapped the maximum and minimum.

STATISTICS

Comparison 11

Question: Find the mean and median of 2, 3, 3, 5, 7.

A: Mean = 4, median = 3.5

B: Mean = 20/5 = 4. With n = 5, the median is the 3rd value, which is 3.

Winner: B

Reason: For an odd n the median is the middle value, with no averaging.

Comparison 12

Question: Calculate the sample variance of 2, 4, 6.

A: (4 + 0 + 4)/3 = 2.67

B: Mean = 4, sum of squared deviations = 8, s² = 8/(n − 1) = 4

Winner: B

Reason: "Sample" means divide by n − 1. A gave the population variance.

Comparison 13

Question: Two fair dice are rolled. Find P(sum = 7).

A: Favourable outcomes: (1,6), (2,5), (3,4), (4,3), (5,2), (6,1). That is 6 out of 36, so 1/6.

B: There are 11 possible sums (2 to 12), so 1/11.

Winner: A

Reason: The sums are not equally likely. Count the 36 equally likely ordered outcomes.

Comparison 14

Question: X follows Bin(4, 0.5). Find P(X = 2).

A: C(4,2)(0.5)²(0.5)² = 6/16 = 0.375

B: (0.5)² = 0.25

Winner: A

Reason: B left out the binomial coefficient, which counts the 6 arrangements.

Comparison 15

Question: X follows N(50, 100). Find P(X > 70).

A: z = (70 − 50)/100 = 0.2, so P is about 0.42.

B: The variance is 100, so σ = 10. Then z = 2 and P(Z > 2) is about 0.0228.

Winner: B

Reason: N(μ, σ²) gives the variance, not the standard deviation. A used 100 as σ.

Comparison 16

Question: 1% of a population has a disease. A test has 95% sensitivity and a 5% false-positive rate. Find P(disease | positive).

A: 0.95(0.01) / [0.95(0.01) + 0.05(0.99)] = 0.0095/0.059, about 16%

B: 95%, because the test is 95% accurate.

Winner: A

Reason: B confuses P(positive | disease) with P(disease | positive) and ignores the low base rate.

Comparison 17

Question: A test gives p = 0.03 at α = 0.05. Interpret the result.

A: Reject H₀. There is a 3% probability that H₀ is true.

B: Reject H₀ since 0.03 is less than 0.05. If H₀ were true, data this extreme would occur about 3% of the time.

Winner: B

Reason: The p-value is not the probability that H₀ is true.

Comparison 18

Question: Interpret a correlation of r = −0.9.

A: Strong negative linear association: as x rises, y tends to fall. Correlation alone does not prove causation.

B: The relationship is weak because r is negative.

Winner: A

Reason: Strength comes from |r|. The sign only gives the direction.

Comparison 19

Question: n = 36, sample mean = 40, σ = 12 (known). Find the 95% confidence interval for μ.

A: 40 ± 1.96(12) = (16.48, 63.52)

B: SE = 12/√36 = 2, so 40 ± 1.96(2) = 40 ± 3.92 = (36.08, 43.92)

Winner: B

Reason: The margin of error uses the standard error σ/√n, not σ.

Comparison 20

Question: Find E(X) and Var(X) for a fair six-sided die.

A: E(X) = 3.5. E(X²) = 91/6. Var = 91/6 − 3.5² = 35/12, about 2.92.

B: E(X) = 3.5, Var = 91/6, about 15.17.

Winner: A

Reason: B gave E(X²) and did not subtract the squared mean.

PHYSICS

Comparison 21

Question: Find the total resistance of 2 Ω, 3 Ω and 6 Ω in parallel.

A: 1/R = 1/2 + 1/3 + 1/6 = 1, so R = 1 Ω

B: 2 + 3 + 6 = 11 Ω

Winner: A

Reason: B added them as if they were in series. In parallel the total is smaller than the smallest resistor.

Comparison 22

Question: Find the force between 2 μC and 3 μC separated by 0.3 m (k = 9×10⁹ N·m²/C²).

A: F = kq₁q₂/r = (9×10⁹)(6×10⁻¹²)/0.3 = 0.18 N

B: F = kq₁q₂/r² = 0.054/0.09 = 0.6 N

Winner: B

Reason: Coulomb's law is an inverse-square law. A forgot to square r.

Comparison 23

Question: Find the energy stored in a 10 μF capacitor charged to 100 V.

A: E = CV² = 10⁻⁵ × 10⁴ = 0.1 J

B: E = ½CV² = ½(10⁻⁵)(10⁴) = 0.05 J

Winner: B

Reason: The formula has a factor of ½, which A left out.

Comparison 24

Question: A proton moves at 2×10⁶ m/s perpendicular to a field of B = 0.5 T. Find the magnetic force.

A: F = qvB sin 90° = (1.6×10⁻¹⁹)(2×10⁶)(0.5) = 1.6×10⁻¹³ N

B: Zero, because the velocity is perpendicular to the field.

Winner: A

Reason: The force is zero only when v is parallel to B. It is maximum when they are perpendicular.

Comparison 25

Question: Sound of frequency 500 Hz has wavelength 0.68 m. Find its speed.

A: v = fλ = 500 × 0.68 = 340 m/s

B: v = f/λ = 735 m/s

Winner: A

Reason: The wave equation is v = fλ. B divided instead of multiplying.

Comparison 26

Question: Light in air hits glass (n = 1.5) at 30° incidence. Find the angle of refraction.

A: 30° × 1.5 = 45°

B: n₁ sin θ₁ = n₂ sin θ₂, so sin θ₂ = 0.5/1.5 = 0.333 and θ₂ is about 19.5°.

Winner: B

Reason: B uses Snell's law, and the ray bends toward the normal in glass. A multiplied the angle by n.

Comparison 27

Question: A 100-turn coil has its flux change from 0.02 Wb to 0.06 Wb in 0.2 s. Find the induced EMF.

A: |ε| = NΔΦ/Δt = 100 × 0.04/0.2 = 20 V

B: ΔΦ/Δt = 0.04/0.2 = 0.2 V

Winner: A

Reason: Faraday's law includes the number of turns N, which B left out.

Comparison 28

Question: Find the heat needed to raise 2 kg of water from 20 °C to 70 °C (c = 4200 J/kg·K).

A: Q = mcT = 2 × 4200 × 70 = 588 000 J

B: Q = mcΔT = 2 × 4200 × (70 − 20) = 420 000 J

Winner: B

Reason: The formula needs the temperature change ΔT, not the final temperature.

Comparison 29

Question: Find the period of a simple pendulum with L = 1.0 m and g = 9.8 m/s². Show your working and give units.

A: T ≈ 2

B: T = 2π√(L/g) = 2π√(1.0/9.8) = 2π(0.319), about 2.0 s

Winner: B

Reason: Both are numerically right, but A has no working and no units, so it fails the instruction.

Comparison 30

Question: A student says brighter light should make photoelectrons faster. Is the student right?

A: No. KE(max) = hf − φ depends on the frequency, not the intensity. Higher intensity means more photons per second, so more electrons and a larger current, but each photon has the same energy.

B: Yes. More intense light carries more energy, so each electron gets more energy and moves faster.

Winner: A

Reason: This is the classic evidence for the photon model of light.
