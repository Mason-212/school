# Misses on 8/27 15 Question Drill
## Common Mistakes:
1. Not factoring Completely
2. Mixing up Multiplying and dividing
3. Mixing up Subtraction and Divsion
---

## 1. Simplify

**Question:** `((-2x^3 y)^(-2) * 3x^(-2) y^4) / (3x)^(-2)`

**Your answer:** `y^2 / (12x^6)`

**Correct answer:** `(27 y^2) / (4 x^6)`

**How to do it:** Turn every negative exponent into a multiply. Dividing by `(3x)^(-2)` means multiply by `(3x)^2 = 9x^2`. Then:

- numbers: `(1/4) * 3 * 9 = 27/4`
- x: `-6 + -2 + 2 = -6` → `1/x^6`
- y: `-2 + 4 = 2` → `y^2`

**Where you went wrong:** You divided by 9 instead of multiplying by 9. A negative exponent on the bottom is a multiply, not another divide.

---

## 2. Factor completely

**Question:** `x^4 - 7x^2 - 18`

**Your answer:** `(x^2 - 9)(x^2 + 2)`

**Correct answer:** `(x - 3)(x + 3)(x^2 + 2)`

**How to do it:** Treat it as a quadratic in `x^2`: `(x^2 - 9)(x^2 + 2)`. Then factor difference of squares: `x^2 - 9 = (x - 3)(x + 3)`. Leave `x^2 + 2` (sum of squares does not factor over the reals).

**Where you went wrong:** You stopped after the `x^2` step. “Completely” means keep going when something is difference of squares.

---

## 3. Divide (rationalize)

**Question:** `(√5 - 2) / (-1 - √5)`

**Your answer:** `(4 - 3√5) / 6`

**Correct answer:** `(3√5 - 7) / 4`

**How to do it:** Multiply top and bottom by the conjugate of the bottom, `-1 + √5`.

- bottom: `(-1)^2 - (√5)^2 = 1 - 5 = -4`
- top: `(√5 - 2)(-1 + √5) = 7 - 3√5`

So `(7 - 3√5) / (-4)`, which is the same as `(3√5 - 7) / 4`.

**Where you went wrong:** The new denominator is just a number. You still have to expand the numerator. The 6 in your answer is not from this conjugate.

---

## 4. Domain

**Question:** `√(6 - x) / (x - 2)`

**Your answer:** `(-∞, 2) U (2, ∞)`

**Correct answer:** `(-∞, 2) U (2, 6]`

**How to do it:** Two rules, then combine.

1. Inside the square root ≥ 0: `6 - x ≥ 0` → `x ≤ 6`
2. Denominator ≠ 0: `x ≠ 2`

Cut `x = 2` out of `(-∞, 6]`.

**Where you went wrong:** You only banned the denominator. You ignored the square root, which also bans `x > 6`.

---

## 5. Factor completely

**Question:** `3x^3 + 81`

**Your answer:** `3(x + 3)(x^2 + 3x + 9)`

**Correct answer:** `3(x + 3)(x^2 - 3x + 9)`

**How to do it:** Pull out 3: `3(x^3 + 27)`. That is a **sum** of cubes. SOAP = Same, Opposite, Always Positive:

`x^3 + 27 = (x + 3)(x^2 - 3x + 9)`

**Where you went wrong:** The first factor `(x + 3)` is right (Same). The middle term of the quadratic should be **Opposite**, so `-3x`, not `+3x`. You used difference-of-cubes signs on a sum.

---

## 6. Simplify

**Question:** `(4x^(-2) y^3)^2 / (2x y^(-1))^(-3)`

**Your answer:** `(128 y^3) / x^4`

**Correct answer:** `(128 y^3) / x`

**How to do it:** Dividing by `(…)^(-3)` means multiply by `(…)^3`:

`(4x^(-2) y^3)^2 * (2x y^(-1))^3 = (16 x^(-4) y^6)(8 x^3 y^(-3)) = 128 y^3 / x`

**Where you went wrong:** Numbers and y are right. You kept `x^(-4)` from the square and forgot the `x^3` from multiplying by `(2x y^(-1))^3`.

---

## 8. Domain

**Question:** `x / √(3 - 2x)`

**Your answer:** `(-∞, -3/2) U (-3/2, ∞)`

**Correct answer:** `(-∞, 3/2)`

**How to do it:** The square root is the whole denominator, so the inside must be **positive** (not zero):

`3 - 2x > 0` → `x < 3/2`

**Where you went wrong:** You treated it like “exclude one x-value” (`x ≠ -3/2`). The cutoff is `3/2`, not `-3/2`, and everything to the right of `3/2` is illegal because the inside of the root would be negative.

---

## 9. Factor completely

**Question:** `x^4 - 13x^2 + 36`

**Your answer:** `(x^2 + 9)(x^2 + 4)`

**Correct answer:** `(x - 3)(x + 3)(x - 2)(x + 2)`

**How to do it:** Quadratic in `x^2`: `(x^2 - 9)(x^2 - 4)`. Both are difference of squares, so factor again.

**Where you went wrong:** You used pluses. `(x^2 + 9)(x^2 + 4)` expands to `x^4 + 13x^2 + 36` (the middle sign flipped). This problem is minuses.

---

## 10. Simplify

**Question:** `√75 * 2√3 - 4√48`

**Your answer:** `90 - 4√3`

**Correct answer:** `30 - 16√3`

**How to do it:**

- `√75 = 5√3`, so `5√3 * 2√3 = 10 * 3 = 30` (because `√3 * √3 = 3`, not 9)
- `4√48 = 4 * 4√3 = 16√3`

**Where you went wrong:** `√3 * √3` is 3, not 9, so the first term is 30, not 90. Also simplify `√48` all the way: `4√48 = 16√3`, not `4√3`.

---

## 12. Reduce

**Question:** `(x^2 - 9) / (x^2 + x - 12)` (include restrictions)

**Your answer:** `(x + 3)/(x + 4)`, `x ≠ -4`

**Correct answer:** `(x + 3)/(x + 4)`, `x ≠ -4` and `x ≠ 3`

**How to do it:** Factor: `(x - 3)(x + 3) / ((x + 4)(x - 3))`. Cancel `(x - 3)`. The original bottom was zero at both `x = -4` and `x = 3`, so both stay banned.

**Where you went wrong:** The simplified fraction is right. You only listed the factor that was still visible. Cancelled holes still count.

---

## 13. Divide (rationalize)

**Question:** `(2 - √3) / (-4 - √3)`

**Your answer:** `-1/2`

**Correct answer:** `(-11 + 6√3) / 13`

**How to do it:** Multiply by the conjugate `-4 + √3`.

- bottom: `(-4)^2 - (√3)^2 = 16 - 3 = 13`
- top: `(2 - √3)(-4 + √3) = -11 + 6√3`

**Where you went wrong:** This does not simplify to a plain fraction like `-1/2`. After the conjugate you still have a `√3` in the numerator.

---

## 14. Domain

**Question:** `√(2x + 8) / (x^2 - 16)`

**Your answer:** `(-∞, -4) U (-4, 4) U (4, ∞)`

**Correct answer:** `(-4, 4) U (4, ∞)`

**How to do it:**

1. Inside the root ≥ 0: `2x + 8 ≥ 0` → `x ≥ -4`
2. Bottom ≠ 0: `x ≠ 4` and `x ≠ -4`

Start at `-4` and go right, but skip `±4`. That leaves `(-4, 4) U (4, ∞)`.

**Where you went wrong:** You only punched holes at `±4` and allowed everything else. Left of `-4`, the square root is not real.

---

## 15. Simplify

**Question:** `((-3x y^2)^2 * 2 x^(-4) y) / (2y)^(-3)`

**Your answer:** `9 y^8 / x^2`

**Correct answer:** `144 y^8 / x^2`

**How to do it:** Dividing by `(2y)^(-3)` means multiply by `(2y)^3 = 8 y^3`.

- numbers: `9 * 2 * 8 = 144`
- x: `2 + (-4) = -2` → `1/x^2`
- y: `4 + 1 + 3 = 8` → `y^8`

**Where you went wrong:** The letters are right. You kept the `9` from squaring `-3` and dropped the extra `2` and the `8` from `(2y)^3`.

---

# Misses on 8/27 20 Question Drill

You got **#1, #2, #4, #5, #6, #10, #16, #17** right (not listed).

## Common mistakes this round
1. Dropping the minus after a conjugate (denominator `a^2 - b` came out negative)
2. Domain: sqrt in the denominator, and `x ≥ …` from a radical in the numerator
3. Factoring `x^4` as if it were `x^2`, or stopping before difference of squares
4. Restrictions: banned the leftover **numerator** instead of the cancelled **denominator** factor
5. Dropping extra numbers after a square; not finishing radical simplification

---

## 3. Divide (rationalize)

**Question:** `(√7 - 3) / (-2 - √7)`

**Your answer:** `(13 - 5√7) / 3`

**Correct answer:** `(13 - 5√7) / (-3)` or `(5√7 - 13) / 3`

**How to do it:** Multiply by `-2 + √7`. Top: `(√7 - 3)(-2 + √7) = 13 - 5√7`. Bottom: `4 - 7 = -3`.

**Where you went wrong:** The numerator is right. The new denominator is `-3`, not `3`. You dropped the minus.

---

## 7. Simplify (rationalize)

**Question:** `6 / (4 + √5)`

**Your answer:** `(8 - 2√5) / (-3)`

**Correct answer:** `(24 - 6√5) / 11` or `6(4 - √5) / 11`

**How to do it:** Multiply by `4 - √5`. Bottom: `16 - 5 = 11`. Top: `6(4 - √5) = 24 - 6√5`.

**Where you went wrong:** The conjugate of `4 + √5` is `4 - √5`. Bottom must be `16 - 5 = 11`, not `-3`.

---

## 8. Domain

**Question:** `x / √(5 - x)`

**Your answer:** `[0, 5) U (5, ∞)`

**Correct answer:** `(-∞, 5)`

**How to do it:** The sqrt is the whole denominator, so `5 - x > 0` → `x < 5`. Negative x is fine (`x` is only on top).

**Where you went wrong:** You started at 0 for no reason, and you allowed `x > 5`, where the inside of the root is negative. Cut off everything to the **right** of 5, not a hole at 5.

---

## 9. Factor completely

**Question:** `x^4 - 10x^2 + 9`

**Your answer:** `(x + 9)(x + 1)`

**Correct answer:** `(x - 3)(x + 3)(x - 1)(x + 1)`

**How to do it:** Let `u = x^2`: `u^2 - 10u + 9 = (u - 9)(u - 1) = (x^2 - 9)(x^2 - 1)`. Then difference of squares on both.

**Where you went wrong:** You factored it like a quadratic in `x`, not in `x^2`. `(x + 9)(x + 1)` is for `x^2 + 10x + 9`, a different problem.

---

## 11. Factor completely

**Question:** `x^4 - x^2 - 12`

**Your answer:** `(x^2 - 4)(x + 3)`

**Correct answer:** `(x - 2)(x + 2)(x^2 + 3)`

**How to do it:** `(x^2 - 4)(x^2 + 3)`. Then `x^2 - 4 = (x - 2)(x + 2)`. Leave `x^2 + 3`.

**Where you went wrong:** Second factor is `x^2 + 3`, not `x + 3`. Also factor `x^2 - 4` all the way.

---

## 12. Reduce

**Question:** `(x^2 - 16) / (x^2 - x - 12)` (include restrictions)

**Your answer:** `(x + 4)/(x + 3)`, `x ≠ -4` or `-3`

**Correct answer:** `(x + 4)/(x + 3)`, `x ≠ 4` and `x ≠ -3`

**How to do it:** `(x - 4)(x + 4) / ((x - 4)(x + 3))`. Cancel `(x - 4)`. Original bottom is 0 at `x = 4` and `x = -3`.

**Where you went wrong:** The reduced fraction is right. You banned `x = -4` (a leftover top factor) instead of `x = 4` (the cancelled bottom factor).

---

## 13. Divide (rationalize)

**Question:** `(3 - √2) / (-5 - √2)`

**Your answer:** `(11 - 2√2) / 23`

**Correct answer:** `(-17 + 8√2) / 23`

**How to do it:** Multiply by `-5 + √2`. Bottom: `25 - 2 = 23`. Top: `(3 - √2)(-5 + √2) = -17 + 8√2`.

**Where you went wrong:** Denominator 23 is right. The numerator expansion is `-15 + 3√2 + 5√2 - 2 = -17 + 8√2`, not `11 - 2√2`.

---

## 14. Domain

**Question:** `√(x + 6) / (x^2 - 9)`

**Your answer:** `(-∞, -3) U (-3, 3) U (3, ∞)`

**Correct answer:** `[-6, -3) U (-3, 3) U (3, ∞)`

**How to do it:** Inside the root ≥ 0: `x ≥ -6`. Bottom ≠ 0: `x ≠ ±3`. Include `-6` (root is 0, bottom is not 0).

**Where you went wrong:** You only punched holes at `±3`. Left of `-6` the square root is not real.

---

## 15. Simplify

**Question:** `((-2x^2 y)^2 * 3 x^(-5) y^2) / (3y)^(-2)`

**Your answer:** `(4 y^10) / x`

**Correct answer:** `(108 y^6) / x`

**How to do it:** Dividing by `(3y)^(-2)` means multiply by `(3y)^2 = 9y^2`.

- numbers: `4 * 3 * 9 = 108`
- x: `4 + (-5) = -1` → `1/x`
- y: `2 + 2 + 2 = 6` → `y^6`

**Where you went wrong:** The `1/x` is right. You kept the `4` from squaring `-2` and dropped the `3` and the `9`. y exponents add to 6, not 10.

---

## 18. Simplify

**Question:** `√48 * 2√3 - 3√27`

**Your answer:** `24 - 3√3`

**Correct answer:** `24 - 9√3`

**How to do it:** `√48 = 4√3`, so `4√3 * 2√3 = 8 * 3 = 24`. Then `3√27 = 3 * 3√3 = 9√3`.

**Where you went wrong:** First term 24 is right. `√27 = 3√3`, so you still have to multiply by the 3 in front: `9√3`, not `3√3`.

---

## 19. Reduce

**Question:** `(x^2 - 25) / (x^2 + 2x - 15)` (include restrictions)

**Your answer:** `(x - 5)/(x - 3)`, `x ≠ 5` or `3`

**Correct answer:** `(x - 5)/(x - 3)`, `x ≠ -5` and `x ≠ 3`

**How to do it:** `(x - 5)(x + 5) / ((x + 5)(x - 3))`. Cancel `(x + 5)`. Original bottom is 0 at `x = -5` and `x = 3`. `x = 5` is a zero of the answer, not a hole.

**Where you went wrong:** The reduced fraction is right. You banned `x = 5` (numerator) instead of `x = -5` (cancelled factor).

---

## 20. Divide (rationalize)

**Question:** `(√3 - 1) / (-3 - √3)`

**Your answer:** `-√3 / 3`

**Correct answer:** `(3 - 2√3) / 3` or `(6 - 4√3) / 6`

**How to do it:** Multiply by `-3 + √3`. Bottom: `9 - 3 = 6`. Top: `(√3 - 1)(-3 + √3) = 6 - 4√3`. Then divide by 6: `(3 - 2√3) / 3`.

**Where you went wrong:** This still has a number and a √3 after you simplify. It does not collapse to `-√3 / 3`.

---

# Misses on 8/29 20 Question Drill

In progress. Logged so far: **#1, #2, #3, #6, #8**. You got **#4, #5, #7** right.

---

## 1. Divide (rationalize)

**Question:** `(√6 - 2) / (-1 - √6)`

**Your answer:** `(-3√6 + 8) / 5` which is the same as `(8 - 3√6) / 5`

**Correct answer:** `(8 - 3√6) / (-5)` or `(3√6 - 8) / 5`

**How to do it:** Multiply top and bottom by `-1 + √6`.

- top: `(√6 - 2)(-1 + √6) = 8 - 3√6`
- bottom: `(-1)^2 - (√6)^2 = 1 - 6 = -5`

That already is the value: `(8 - 3√6) / (-5)`.

To make the bottom positive, multiply the **whole numerator** by `-1`:

`(8 - 3√6) / (-5) = (-8 + 3√6) / 5 = (3√6 - 8) / 5`

Both terms flip: `8` → `-8`, and `-3√6` → `+3√6`.

**Where you went wrong:** The numerator `8 - 3√6` is right. You moved the minus off the bottom but did not change the top, so you only did half of “divide by `-5`.”

`(-3√6 + 8) / 5` is the **opposite** of `(3√6 - 8) / 5`. Those two are not the same.

Check: original is about `(2.45 - 2) / (-1 - 2.45) ≈ -0.13`. Yours is about `+0.13`.

**Rule:** if the new denominator is negative, either leave `top / (negative number)`, or flip **every** sign on top when you make the bottom positive.

---

## 2. Domain

**Question:** `x / √(7 - x)`

**Your answer:** `[0, 7) U (7, ∞)`

**Correct answer:** `(-∞, 7)`

**How to do it:** The square root is the whole denominator, so the inside must be **positive** (not zero):

`7 - x > 0` → `x < 7`

`x` is only on top, so negatives are allowed.

**Where you went wrong:** You started at 0 for no reason, and you allowed `x > 7`, where `7 - x` is negative. Cut off everything to the **right** of 7. It is not “all reals except 7.”

---

## 3. Factor completely

**Question:** `x^4 - 5x^2 - 36`

**Your answer:** `(x^2 - 9)(x^2 + 4)` (earlier try: `(x^4 + 4)(x^2 - 9)`)

**Correct answer:** `(x - 3)(x + 3)(x^2 + 4)`

**How to do it:** Let `u = x^2`: `(x^2 - 9)(x^2 + 4)`. Then difference of squares: `x^2 - 9 = (x - 3)(x + 3)`. Leave `x^2 + 4`.

**Where you went wrong:** The `x^2` step is right. “Completely” means keep going when something is difference of squares. First try had `x^4 + 4` instead of `x^2 + 4`.

---

## 6. Reduce

**Question:** `(x^2 - 36) / (x^2 + x - 30)` (include restrictions)

**Your answer:** `(x - 6)/(x - 5)`, `x ≠ 6` or `5`

**Correct answer:** `(x - 6)/(x - 5)`, `x ≠ -6` and `x ≠ 5`

**How to do it:** `(x - 6)(x + 6) / ((x + 6)(x - 5))`. Cancel `(x + 6)`. Original bottom is 0 at `x = -6` and `x = 5`. `x = 6` is a zero of the answer, not a hole.

**Where you went wrong:** The reduced fraction is right. You banned `x = 6` (numerator) instead of `x = -6` (cancelled factor). Same restriction mix-up as the last drill.

---

## 8. Domain

**Question:** `2x / √(4 - 2x)`

**Your answer:** `[0, 2)`

**Correct answer:** `(-∞, 2)`

**How to do it:** The sqrt is the whole denominator, so `4 - 2x > 0` → `x < 2`. The `2x` on top does not restrict domain. `x = 0` just makes the value `0`.

**Where you went wrong:** You started at 0 because of the `x` on top. Domain is “what can I plug in,” not “where is the output positive.” A lone `x` on top is fine when it is negative. Same start-at-0 miss as **#2**.

---

# Misses on 8/29 Domain and Rationalize 10 question Drill

You got **#2, #3, #4, #8, #9, #10** right. Logged: **#1, #5, #6, #7**.

## Common mistakes this round
1. Sqrt on the bottom: one cutoff (`x < a`), not a hole, not start at 0
2. Dropping the coefficient on the radical after dividing
3. Radical + denominator: only punch holes that sit inside the radical’s allowed set

---

## 1. Domain

**Question:** `x / √(8 - x)`

**Your answer:** `(-∞, 8) U (8, -∞)` (meant all reals except 8)

**Correct answer:** `(-∞, 8)`

**How to do it:** The sqrt is the whole denominator, so `8 - x > 0` → `x < 8`. The `x` on top does not restrict domain.

**Where you went wrong:** A union that goes both sides of 8 is “all reals except 8.” For `x > 8` the inside of the root is negative. Write the cutoff once: `x < 8`. There is no interval from 8 back to `-∞`.

---

## 5. Domain

**Question:** `3x / √(6 - 2x)`

**Your answer:** `[0, 3) U (3, ∞)`

**Correct answer:** `(-∞, 3)`

**How to do it:** `6 - 2x > 0` → `x < 3`. The `3x` on top is allowed to be 0 or negative. `x = 0` just makes the value 0.

**Where you went wrong:** Started at 0 because of the `x` on top, and allowed `x > 3` (root not real). Same two slips as **#1** and the earlier sqrt-on-bottom problems.

---

## 6. Divide (rationalize)

**Question:** `(√3 - 5) / (-1 - √3)`

**Your answer:** `√3 - 4`

**Correct answer:** `3√3 - 4`

**How to do it:** Multiply by `-1 + √3`. Top: `8 - 6√3`. Bottom: `1 - 3 = -2`. Then `(8 - 6√3) / (-2) = -4 + 3√3 = 3√3 - 4`.

**Where you went wrong:** `8 / (-2) = -4` is right. `-6√3 / (-2) = 3√3`, not `√3`. You dropped the 3.

---

## 7. Domain

**Question:** `√(x + 2) / (x^2 - 16)`

**Your answer:** `(-4, 2] U [2, 4)` (basically `(-4, 4)`)

**Correct answer:** `[-2, 4) U (4, ∞)`

**How to do it:**

1. Inside the root ≥ 0: `x + 2 ≥ 0` → `x ≥ -2` (include `-2`)
2. Bottom ≠ 0: `x ≠ ±4`

`-4` is already left of `-2`, so the radical knocks it out. The only hole still inside the allowed set is `x = 4`.

**Where you went wrong:** You treated `±4` as the whole story and invented a split at 2. That lets in `(-4, -2)` (root not real) and drops `(4, ∞)`. You do not list `-4` as a hole in the final interval — you never reach it.

---

# Misses on 8/30 Mixed 15 Drill

You got **#2, #4, #5, #12, #14, #15** right. Logged: **#1, #3, #6, #7, #8, #9, #10, #11, #13**.

## Common mistakes this round
1. Complex fractions: keep every leftover factor and the sign from `b - a`
2. Factor completely: finish difference of squares; SOAP last term is Always Positive
3. Restrictions: ban original denominator zeros, not numerator zeros
4. Domain: punch holes that sit inside the radical’s allowed set
5. Scientific notation: divide coefficients; `5 - (-3) = 8`

---

## 1. Simplify (complex fraction)

**Question:** `(a/b - b/a) / (1/a - 1/b)`

**Your answer:** `a - b`

**Correct answer:** `-(a + b)`

**How to do it:** Top: `(a^2 - b^2) / (ab) = (a - b)(a + b) / (ab)`. Bottom: `(b - a) / (ab) = -(a - b) / (ab)`. Flip and multiply; `ab` cancels: `(a - b)(a + b) / -(a - b) = -(a + b)` (`a ≠ b`).

**Where you went wrong:** You cancelled `a - b` and dropped both the `a + b` and the minus from `b - a`.

---

## 3. Factor completely

**Question:** `4x^3 - 32`

**Your answer:** `4(x - 2)(x^2 + 2x - 4)`

**Correct answer:** `4(x - 2)(x^2 + 2x + 4)`

**How to do it:** GCF 4: `4(x^3 - 8)`. Difference of cubes, SOAP: Same, Opposite, Always Positive → `(x - 2)(x^2 + 2x + 4)`.

**Where you went wrong:** GCF and `x - 2` are right. The last term of the quadratic must be `+4`, not `-4`. `(x - 2)(x^2 + 2x - 4) = x^3 - 8x + 8`, not `x^3 - 8`.

---

## 6. Factor completely

**Question:** `x^4 - 11x^2 + 18`

**Your answer:** `(x^2 - 9)(x^2 - 2)`

**Correct answer:** `(x - 3)(x + 3)(x^2 - 2)`

**How to do it:** Let `u = x^2`: `(x^2 - 9)(x^2 - 2)`. Then `x^2 - 9 = (x - 3)(x + 3)`. Leave `x^2 - 2`.

**Where you went wrong:** The `x^2` step is right. “Completely” means keep going on difference of squares.

---

## 7. Reduce

**Question:** `(x^2 - 25) / (x^2 + 3x - 10)` (include restrictions)

**Your answer:** `(x - 5)/(x - 2)` (no restrictions)

**Correct answer:** `(x - 5)/(x - 2)`, `x ≠ -5` and `x ≠ 2`

**How to do it:** `(x - 5)(x + 5) / ((x + 5)(x - 2))`. Cancel `(x + 5)`. Original bottom is 0 at `-5` and `2`. `x = 5` is a zero of the answer (`0/30 = 0`), not a hole.

**Where you went wrong:** The reduced fraction is right. You skipped restrictions. Ban original denominator zeros, not the leftover numerator factor.

---

## 8. Add

**Question:** `(x + 2)/x + 3 / (x^2 - 2x)`

**Your answer:** `(x^3 - 2x^2 - 4x + 9) / (3x(x - 2))`

**Correct answer:** `(x^2 - 1) / (x(x - 2))` or `(x - 1)(x + 1) / (x(x - 2))`

**How to do it:** `x^2 - 2x = x(x - 2)`. LCD is `x(x - 2)`, not `3x(x - 2)`. `(x + 2)(x - 2) + 3 = x^2 - 4 + 3 = x^2 - 1`.

**Where you went wrong:** The `3` stays on top. It is not part of the LCD. You put a 3 in the bottom and expanded into a cubic.

---

## 9. Domain

**Question:** `√(x + 5) / (x^2 - 9)`

**Your answer:** `[-5, 3) U (3, ∞)`

**Correct answer:** `[-5, -3) U (-3, 3) U (3, ∞)`

**How to do it:** `x + 5 ≥ 0` → `x ≥ -5`. Bottom: `x ≠ ±3`. `-3` sits inside `[-5, ∞)`, so cut it out. Include `-5`.

**Where you went wrong:** You had `x ≥ -5` and the hole at `3`. You left `x = -3` in. Punch holes that lie inside the radical’s allowed set.

---

## 10. Simplify (complex fraction)

**Question:** `(1 + 1/x) / (1 - 1/x^2)`

**Your answer:** `-x`

**Correct answer:** `x / (x - 1)`

**How to do it:** Top: `(x + 1)/x`. Bottom: `(x^2 - 1)/x^2 = (x - 1)(x + 1)/x^2`. Flip: `(x + 1)/x * x^2 / ((x - 1)(x + 1)) = x / (x - 1)` (`x ≠ 0, ±1`).

**Where you went wrong:** After `x + 1` cancels you still have `x` over `x - 1`, not `-x`.

---

## 11. Scientific notation

**Question:** `(6.4 * 10^5) / (2 * 10^(-3))`

**Your answer:** `1.28 * 10^3`

**Correct answer:** `3.2 * 10^8`

**How to do it:** Divide coefficients: `6.4 / 2 = 3.2`. Subtract exponents: `5 - (-3) = 8`. Dividing by `10^(-3)` multiplies by `10^3`.

**Where you went wrong:** You treated `-3` as `+3` (`5 - 3 = 2`) and multiplied by 2 instead of dividing.

---

## 13. Factor completely

**Question:** `x^3 + 5x^2 - 4x - 20`

**Your answer:** `(x^2 - 4)(x + 5)`

**Correct answer:** `(x - 2)(x + 2)(x + 5)`

**How to do it:** Group: `x^2(x + 5) - 4(x + 5) = (x^2 - 4)(x + 5)`. Then `x^2 - 4 = (x - 2)(x + 2)`.

**Where you went wrong:** Grouping is right. Finish difference of squares. Same “not completely” slip as **#6**.

---

# Misses on 8/30 Scrambled Review

The 43-question reshuffle of this file. Logged only what you missed **this pass**: **#20, #23, #25, #27, #29, #32, #37, #38, #42, #43**.

## Common mistakes this pass
1. Domain: do not add the illegal side of a sqrt-in-the-denominator cutoff; start at the radical, only punch holes inside that set
2. Complex fraction `(a/b - b/a) / (1/a - 1/b)` is still `-(a + b)`, not `a - b`
3. Conjugate: keep every term after expanding; don’t swap √3 for √2
4. Exponent coefficients: multiply *all* the numbers (`9 * 2 * 8 = 144`)

---

## 20. Domain

**Question:** `√(2x + 8) / (x^2 - 16)`

**Your answer:** `(-∞, -4) U (-4, 4]`

**Correct answer:** `(-4, 4) U (4, ∞)`

**How to do it:** `2x + 8 ≥ 0` → `x ≥ -4`. Bottom: `x ≠ ±4`. Open at `-4` (bottom is 0 there). Skip `4`. Keep going right.

**Where you went wrong:** You let in `x < -4` (root not real), included `x = 4` (divide by 0), and dropped `(4, ∞)`.

---

## 23. Domain

**Question:** `x / √(5 - x)`

**Your answer:** `(-∞, 5) U (5, ∞)`

**Correct answer:** `(-∞, 5)`

**How to do it:** `5 - x > 0` → `x < 5`. The `x` on top does not restrict domain.

**Where you went wrong:** Cutoff 5 is right, and you did not start at 0. `(5, ∞)` is still illegal (inside the root is negative).

---

## 25. Simplify (complex fraction)

**Question:** `(a/b - b/a) / (1/a - 1/b)`

**Your answer:** `a - b`

**Correct answer:** `-(a + b)`

**How to do it:** Top: `(a - b)(a + b) / (ab)`. Bottom: `-(a - b) / (ab)`. Cancel `a - b`: `-(a + b)`.

**Where you went wrong:** Same as the 8/30 mixed drill. After canceling `a - b` you still have `a + b` and the minus from `b - a`.

---

## 27. Divide (rationalize)

**Question:** `(3 - √2) / (-5 - √2)`

**Your answer:** `(8√2 - 19) / 23`

**Correct answer:** `(-17 + 8√2) / 23`

**How to do it:** Multiply by `-5 + √2`. Bottom: `25 - 2 = 23`. Top: `-15 + 3√2 + 5√2 - 2 = -17 + 8√2`.

**Where you went wrong:** 23 and `8√2` are right. `-15 - 2 = -17`, not `-19`.

---

## 29. Simplify

**Question:** `((-2x^2 y)^2 * 3 x^(-5) y^2) / (3y)^(-2)`

**Your answer:** `(132 y^6) / x`

**Correct answer:** `(108 y^6) / x`

**How to do it:** Multiply by `(3y)^2 = 9y^2`. Numbers: `4 * 3 * 9 = 108`. x: `4 - 5 = -1`. y: `2 + 2 + 2 = 6`.

**Where you went wrong:** Letters and `1/x` are right. `4 * 3 * 9` is 108, not 132.

---

## 32. Divide (rationalize)

**Question:** `(√3 - 1) / (-3 - √3)`

**Your answer:** `-4√3`

**Correct answer:** `(3 - 2√3) / 3` or `(6 - 4√3) / 6`

**How to do it:** Multiply by `-3 + √3`. Top: `6 - 4√3`. Bottom: `9 - 3 = 6`. Then divide by 6.

**Where you went wrong:** `-4√3` is only one piece of the numerator. Keep `6 - 4√3` over 6.

---

## 37. Divide (rationalize)

**Question:** `(√3 - 5) / (-1 - √3)`

**Your answer:** `3√2 - 4`

**Correct answer:** `3√3 - 4`

**How to do it:** Top: `8 - 6√3`. Bottom: `-2`. `(8 - 6√3) / (-2) = 3√3 - 4`.

**Where you went wrong:** You have the `3` and the `-4`. The radical is still `√3`, not `√2`.

---

## 38. Domain

**Question:** `√(x + 2) / (x^2 - 16)`

**Your answer:** `(-∞, -4) U (-4, -2] U [-2, 4)`

**Correct answer:** `[-2, 4) U (4, ∞)`

**How to do it:** `x + 2 ≥ 0` → `x ≥ -2`. `x ≠ ±4`. `-4` is already left of `-2`. Only punch `4`. Include `-2`.

**Where you went wrong:** You let in `x < -2` and dropped `(4, ∞)`. Don’t list `-4` — you never reach it.

---

## 42. Simplify

**Question:** `((-3x y^2)^2 * 2 x^(-4) y) / (2y)^(-3)`

**Your answer:** `(9 y^8) / x^2`

**Correct answer:** `(144 y^8) / x^2`

**How to do it:** Multiply by `(2y)^3 = 8y^3`. Numbers: `9 * 2 * 8 = 144`. x: `2 - 4 = -2`. y: `4 + 1 + 3 = 8`.

**Where you went wrong:** Same as the first time you saw this. Letters are right. You kept the `9` and dropped the `2` and the `8`.

---

## 43. Divide (rationalize)

**Question:** `(√7 - 3) / (-2 - √7)`

**Your answer:** `(5√7 - 12) / 3`

**Correct answer:** `(5√7 - 13) / 3`

**How to do it:** Multiply by `-2 + √7`. Top: `7 + 6 - 5√7 = 13 - 5√7`. Bottom: `4 - 7 = -3`. Flip both signs: `(5√7 - 13) / 3`.

**Where you went wrong:** Shape is right (`5√7` over 3). Constants: `7 + 6 = 13`, not 12.

---

# Misses on 8/30 Follow-up 10 

The 10 new problems from those misses. You got **2, 8, 10**. Logged **#1, #3, #4, #5, #6, #7, #9**.

## Common mistakes this pass
1. Domain: start at the radical, only punch holes inside that set
2. When you expand a conjugate, `√a · √a = a` (not `a^2`)
3. A negative exponent on the bottom is a multiply — use every coefficient
4. Complex fraction: after canceling `p - q` you still have `p + q` and the minus

---

## 1. Domain

**Question:** `√(x + 4) / (x^2 - 25)`

**Your answer:** `(-∞, -5) U (-5, 4] U [4, 5)`

**Correct answer:** `[-4, 5) U (5, ∞)`

**How to do it:** `x + 4 ≥ 0` → `x ≥ -4`. Bottom: `x ≠ ±5`. `-5` is already left of `-4`. Punch `5`. Include `-4`.

**Where you went wrong:** You let in `x < -4`, invented a hole at `-5` and a split at `4`, and dropped `(5, ∞)`.

---

## 3. Simplify (complex fraction)

**Question:** `(p/q - q/p) / (1/p - 1/q)`

**Your answer:** `-(p - q)`

**Correct answer:** `-(p + q)`

**How to do it:** Top: `(p - q)(p + q) / (pq)`. Bottom: `-(p - q) / (pq)`. Cancel `p - q`: `-(p + q)`.

**Where you went wrong:** You got the minus this time. After canceling `p - q` the leftover is `p + q`, not `p - q`.

---

## 4. Divide (rationalize)

**Question:** `(2 - √3) / (-4 - √3)`

**Your answer:** `(6√3 - 17) / 13`

**Correct answer:** `(6√3 - 11) / 13`

**How to do it:** Multiply by `-4 + √3`. Bottom: `16 - 3 = 13`. Top: `-8 + 6√3 - 3 = -11 + 6√3`.

**Where you went wrong:** 13 and `6√3` are right. `√3 · √3 = 3`, not `9`. That is why you have `17` instead of `11`.

---

## 5. Simplify

**Question:** `((-2x y^3)^2 * 3 x^(-3) y) / (3y)^(-2)`

**Your answer:** `(4 y^9) / x`

**Correct answer:** `(108 y^9) / x`

**How to do it:** Square: `4x^2 y^6`. Times `3 x^(-3) y`. Dividing by `(3y)^(-2)` multiplies by `9y^2`. Numbers: `4 * 3 * 9 = 108`.

**Where you went wrong:** Letters and `1/x` are right. You kept the `4` and dropped the `3` and the `9`.

---

## 6. Divide (rationalize)

**Question:** `(√2 - 1) / (-2 - √2)`

**Your answer:** `(6 - 3√2) / 2`

**Correct answer:** `(4 - 3√2) / 2`

**How to do it:** Multiply by `-2 + √2`. Bottom: `4 - 2 = 2`. Top: `-2√2 + 2 + 2 - √2 = 4 - 3√2`.

**Where you went wrong:** `/2` and `3√2` are right. `√2 · √2 = 2`, not `4`. That extra `2` is how you got `6`.

---

## 7. Divide (rationalize)

**Question:** `(√2 - 3) / (-1 - √2)`

**Your answer:** `(4 - 3√2) / 2`

**Correct answer:** `4√2 - 5`

**How to do it:** Multiply by `-1 + √2`. Bottom: `1 - 2 = -1`. Top: `-√2 + 2 + 3 - 3√2 = 5 - 4√2`. Divide by `-1`.

**Where you went wrong:** Keep both terms after expanding, then the sign flip from the `-1`.

---

## 9. Simplify

**Question:** `((-2x^2 y)^2 * 5 x^(-3) y) / (2y)^(-2)`

**Your answer:** `10 x y^5`

**Correct answer:** `80 x y^5`

**How to do it:** Square: `4x^4 y^2`. Times `5 x^(-3) y`. Multiply by `(2y)^2 = 4y^2`. Numbers: `4 * 5 * 4 = 80`.

**Where you went wrong:** Letters are right. Bottom negative exponent is a multiply by `4`, not a divide by `2`.

---

# Misses on 8/31 5 Question Domain

Domain drill from the notes. You got the first three (`√(9-3x)/(x+2)`, `√(x+3)/(x^2-16)`, `x/√(12-3x)`) and **#2–#4** of the `1/√` set.

## Common mistakes this pass
1. If the cutoff is also a zero of the bottom, it is open even when the root is on top
2. `1/√(ax+b)` with `a > 0`: solve `ax+b > 0` → domain opens to the **right** of the cutoff (keep the minus on the number)

---

## 4. Domain

**Question:** `√(8 - 2x) / (x^2 - 16)`

**Your answer:** `(-∞, -4) U (-4, 4]`

**Correct answer:** `(-∞, -4) U (-4, 4)`

**How to do it:** `8 - 2x ≥ 0` → `x ≤ 4`. Bottom: `x ≠ ±4`. At `x = 4` the root is 0 **and** the bottom is 0, so open there.

**Where you went wrong:** Holes at `±4` are right. You closed at `4`. Divide by 0 is still illegal.

---

## 1. Domain (`1` over a square root)

**Question:** `1 / √(5x + 10)`

**Your answer:** `(-∞, 2)`

**Correct answer:** `(-2, ∞)`

**How to do it:** `5x + 10 > 0` → `x > -2`. Open at `-2` because the root is the whole denominator.

**Where you went wrong:** You flipped the inequality and dropped the minus: `(-∞, 2)` instead of `(-2, ∞)`.

---

## 5. Domain (`1` over a square root)

**Question:** `1 / √(x + 7)`

**Your answer:** `(-∞, 7)`

**Correct answer:** `(-7, ∞)`

**How to do it:** `x + 7 > 0` → `x > -7`. Open at `-7`.

**Where you went wrong:** Same as #1. Direction and sign both flipped: `(-∞, 7)` instead of `(-7, ∞)`.

---

# Misses on 8/31 20 Question Weak-spots Drill

You got **2, 3, 7, 8, 10, 11, 14, 15, 16, 17, 19, 20**. Logged **#1, #4, #5, #6, #9, #12, #13, #18**.

## Common mistakes this pass
1. Domain: start at the radical, not at `-∞` or at the first hole
2. `1/√(x - 5)` with positive coeff: opens **right** → `(5, ∞)`
3. Complex fraction: leftover is `-(m + n)` — keep the plus **and** the minus
4. Exponents: multiply every coefficient (`9 * 2 * 4 = 72`), not just the squared one

---

## 1. Domain

**Question:** `√(x + 6) / (x^2 - 9)`

**Your answer:** `(-∞, -3) U (-3, 3) U (3, 6]`

**Correct answer:** `[-6, -3) U (-3, 3) U (3, ∞)`

**How to do it:** `x + 6 ≥ 0` → `x ≥ -6`. Bottom: `x ≠ ±3`. Both holes sit inside. Include `-6`. Keep going past `3`.

**Where you went wrong:** You opened at `-∞` (root not real), invented a cutoff at `6`, and dropped `(6, ∞)`. The `+ 6` is `x ≥ -6`, not `x ≤ 6`.

---

## 4. Divide (rationalize)

**Question:** `(4 - √5) / (-3 - √5)`

**Your answer:** `(8√5 - 17) / 4`

**Correct answer:** `(7√5 - 17) / 4`

**How to do it:** Multiply by `-3 + √5`. Bottom: `9 - 5 = 4`. Top: `-12 + 4√5 + 3√5 - 5 = -17 + 7√5`.

**Where you went wrong:** `/4` and `-17` are right. `4√5 + 3√5 = 7√5`, not `8√5`.

---

## 5. Simplify

**Question:** `((-3x y^2)^2 * 2 x^(-5) y) / (2y)^(-2)`

**Your answer:** `(9 y^7) / x^3`

**Correct answer:** `(72 y^7) / x^3`

**How to do it:** Square: `9x^2 y^4`. Times `2 x^(-5) y`. Multiply by `(2y)^2 = 4y^2`. Numbers: `9 * 2 * 4 = 72`.

**Where you went wrong:** Letters and `1/x^3` are right. You kept the `9` and dropped the `2` and the `4`.

---

## 6. Simplify (complex fraction)

**Question:** `(m/n - n/m) / (1/m - 1/n)`

**Your answer:** `-(m - n)`

**Correct answer:** `-(m + n)`

**How to do it:** Top: `(m - n)(m + n) / (mn)`. Bottom: `-(m - n) / (mn)`. Cancel `m - n`: `-(m + n)`.

**Where you went wrong:** You got the minus. After the cancel, leftover is `m + n`, not `m - n`.

---

## 9. Domain (`1` over a square root)

**Question:** `1 / √(x - 5)`

**Your answer:** `(-∞, 5)`

**Correct answer:** `(5, ∞)`

**How to do it:** `x - 5 > 0` → `x > 5`. Open at `5` because the root is the whole denominator.

**Where you went wrong:** Positive coeff opens to the **right**. You wrote `(-∞, 5)` instead of `(5, ∞)`.

---

## 12. Domain

**Question:** `√(2x + 8) / (x + 5)`

**Your answer:** `(-∞, -5) U (-5, -4]`

**Correct answer:** `[-4, ∞)`

**How to do it:** `2x + 8 ≥ 0` → `x ≥ -4`. `x ≠ -5`, but `-5` is already left of `-4`. Include `-4`.

**Where you went wrong:** You went left of `-4` (root not real) and punched a hole you never reach.

---

## 13. Simplify (complex fraction)

**Question:** `(c/d - d/c) / (1/c - 1/d)`

**Your answer:** `c + d`

**Correct answer:** `-(c + d)`

**How to do it:** Top: `(c - d)(c + d) / (cd)`. Bottom: `-(c - d) / (cd)`. Cancel `c - d`. The minus from `d - c` stays.

**Where you went wrong:** You have the `c + d`. Keep the minus.

---

## 18. Domain

**Question:** `√(3x + 12) / (x^2 - 4)`

**Your answer:** `(-2, 2) U (2, ∞)`

**Correct answer:** `[-4, -2) U (-2, 2) U (2, ∞)`

**How to do it:** `3x + 12 ≥ 0` → `x ≥ -4`. Bottom: `x ≠ ±2`. Both holes sit inside. Include `-4`.

**Where you went wrong:** You punched `±2` and kept `(2, ∞)`. Start at the radical: you dropped `[-4, -2)`.

---

# Misses on 8/31 Full Notes 20 Drill

Practice across all Ch. P topics. You got **2, 3, 5, 7–9, 11–19**. Logged **#1, #4, #6, #10, #20**.

## Common mistakes this pass
1. Exponents: multiply every coefficient when a negative exponent flips
2. Cube roots: leave the leftover inside (`∛(2x²)`, not `∛(2x)`)
3. Like radicals: finish with the last `±1` on the coefficient
4. Domain: cutoff that is also a bottom zero stays open
5. Rational division: flip, cancel, then count leftover factors

---
## 1. Simplify (exponents)

**Question:** `((-3x^2 y)^{-2} * 2 x^{-1} y^3) / (2x)^{-2}`

**Your answer:** `(4y)/(9x^3)`

**Correct answer:** `(8y)/(9x^3)`

**How to do it:** `(−3x²y)^(−2) = 1/(9x⁴y²)`. Times `2 x^(−1) y³`. Multiply by `(2x)^2 = 4x²`. Numbers: `(1/9) * 2 * 4 = 8/9`.

**Where you went wrong:** Letters and `/9` are right. You dropped the middle `2`, so you have `4` instead of `8`.

---

## 4. Simplify (cube roots)

**Question:** `∛(54 x^5) - 2 ∛(2 x^2)`

**Your answer:** `(3x - 2) ∛(2x)`

**Correct answer:** `(3x - 2) ∛(2x²)`

**How to do it:** `∛(54x⁵) = 3x ∛(2x²)`. Factor: `(3x - 2) ∛(2x²)`.

**Where you went wrong:** You pulled `∛(2x)` instead of `∛(2x²)`.

---

## 6. Simplify (like radicals)

**Question:** `3√12 + 5√27 - √3`

**Your answer:** `23√3`

**Correct answer:** `20√3`

**How to do it:** `3(2√3) + 5(3√3) - √3 = 6√3 + 15√3 - √3 = 20√3`.

**Where you went wrong:** `6 + 15 − 1 = 20`, not `23`.

---

## 10. Domain

**Question:** `√(6 - 2x) / (x^2 - 9)`

**Your answer:** `(-∞, -3) U (-3, 3]`

**Correct answer:** `(-∞, -3) U (-3, 3)`

**How to do it:** `x ≤ 3`. Bottom: `x ≠ ±3`. At `x = 3` the root is 0 and the bottom is 0, so open there.

**Where you went wrong:** Holes are right. You closed at `3`. Divide by 0 is still illegal.

---

## 20. Simplify (rational division)

**Question:** `(x^2 - 16)/(2x) ÷ (x^2 - 4x)/(4x + 4)`

**Your answer:** `((x-4)(x+4))/(x(x-2))`

**Correct answer:** `2(x+4)(x+1)/x²`

**How to do it:** Flip: `(x−4)(x+4)/(2x) · 4(x+1)/[x(x−4)]`. Cancel `(x−4)`: `4(x+4)(x+1)/(2x²) = 2(x+4)(x+1)/x²`.

**Where you went wrong:** You kept `(x−4)` and invented `(x−2)`. After canceling, leftover bottom is `x · x`, and `4/2` puts a `2` in front with `(x+1)`.

