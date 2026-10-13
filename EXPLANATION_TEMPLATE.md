# EXPLANATION — My Algorithm Worksheet

> Copy this file to `EXPLANATION.md` in **your own fork**. Write in English. Do not put private student details in a public repository.

**GitHub username:** joannaehandoko-max  
**Exercises completed:** Exercises 01–09 and Task 2
**Most surprising bug:** I learned that Go does not automatically convert an int to a float64. Even though both types represent numbers, I had to convert the integer explicitly using float64(qty) before multiplying it by a floating-point value.

For each exercise you completed, copy and fill in this mini-report:

# EXPLANATION — My Algorithm Worksheet

## Exercise 01 — Data Types

- **Story in my words:** The program stores a student's age, mass, registration status, and student ID.
- **Inputs and types:** Age uses int, mass uses float64, checked-in status uses bool, and student ID uses string.
- **Processing:** Assign the values to variables and print them.
- **Expected output:** 19 | 62.5 | true | 00123
- **Normal test:** All values are displayed correctly.
- **Boundary test:** Storing an ID such as 00123 as an integer would remove the leading zeros.
- **Why the result is correct:** Each variable uses a suitable data type.

## Exercise 02 — Campus Café

- **Story in my words:** The program calculates the cost of two coffees after a discount.
- **Inputs:** Unit price = 18000, quantity = 2, discount = 5000.
- **Processing:** Multiply the unit price by the quantity, then subtract the discount.
- **Expected output:** Subtotal = 36000, Total = 31000.
- **Normal test:** The output matches the expected calculation.
- **Boundary test:** If the discount is greater than the subtotal, the program could produce a negative total.
- **Why the result is correct:** The subtotal must be calculated before the discount is applied.

## Exercise 03 — Factor Checker

- **Story in my words:** The program checks whether one positive integer divides another evenly.
- **Inputs:** Two integers, x and y.
- **Processing:** Validate the inputs, then check whether y % x == 0.
- **Expected output:** Input 5 20 produces true.
- **Boundary test:** Input 0 20 produces invalid input.
- **Why the result is correct:** A remainder of zero means the division has no remainder. Validation prevents division by zero.

## Exercise 04 — Population

- **Story in my words:** The program estimates a population after births, arrivals, deaths, and departures.
- **Inputs:** Initial population = 1000, births = 20, arrivals = 5, deaths = 10, departures = 4.
- **Processing:** Add births and arrivals, then subtract deaths and departures.
- **Expected output:** Population: 1011
- **Boundary test:** A negative population indicates invalid data or an unrealistic model.
- **Why the result is correct:** The calculation follows the population formula.

## Exercise 05 — Number Sequence

- **Story in my words:** Each new number is the sum of the previous two numbers.
- **Inputs:** Two starting numbers, 5 and 3.
- **Processing:** Calculate the third, fourth, and fifth numbers in sequence.
- **Expected output:** 8 11 19
- **Boundary test:** Different starting numbers produce different sequences.
- **Why the result is correct:** Each calculation uses the two most recent numbers.

## Exercise 06 — Gravity

- **Story in my words:** The program calculates weight on Earth and Mars using mass and gravity.
- **Input:** Mass = 70 kg.
- **Processing:** Earth weight = mass × 9.8. Mars weight = Earth weight × 0.38.
- **Expected output:** Earth = 686.0 N; Mars = 260.7 N.
- **Why the result is correct:** Weight depends on gravitational acceleration, while mass stays the same.

## Exercise 07 — Genetic Algorithm Demonstration

- **Story in my words:** The program demonstrates fitness, crossover, and mutation using four-bit strings.
- **Processing:** Count the number of 1 bits, combine parts of two parents, and mutate one bit.
- **Expected output:** Child 1010 has fitness 2. Mutated child 1110 has fitness 3.
- **Why the result is correct:** Fitness is calculated by counting the number of ones.
- **Limitation:** This demonstrates genetic algorithm operations but is not a complete genetic search.

## Exercise 08 — Cube-root Check

- **Story in my words:** The program checks whether x cubed equals y.
- **Inputs:** Two integers, x and y.
- **Processing:** Compare x*x*x with y.
- **Expected output:** Input -3 -27 produces true; input 12 12 produces false.
- **Boundary test:** Very large integers may overflow.
- **Why the result is correct:** The program checks the cube using integer multiplication.

## Exercise 09 — Genetic Search

- **Story in my words:** The program searches for a four-bit candidate with the target value 1111.
- **Processing:** Evaluate fitness, select parents, perform crossover, and sometimes mutate candidates.
- **Testing:** Check that the program prints the generation number and best fitness.
- **Limitation:** Random changes do not always improve fitness, and the search may not find the target before reaching its generation limit.

## Task 2 — Fill in the Blank

### Git and GitHub

1. fork
2. clone
3. switch
4. status, diff
5. add
6. push
7. main
8. origin

### Go Types, Constants, and Operators

9. 3, int
10. 1, remainder
11. 3.5, automatically
12. rune, byte
13. string, zeros
14. const, compile-time
15. false, true, false
16. not
17. assigns, compares
18. 14, 20
19. false, approximately
20. A, Itoa

### Complete the Program

21. const, float64, >
22. 66000 true
23. The multiplication line needs float64(qty) because Go does not automatically convert an integer to a floating-point value.

## Mini Defense

### 1. What did you learn from this worksheet?
I learned how to use data types, operators, and conditional statements in Go. I also learned how to test programs and fix errors.

### 2. What was the most difficult exercise?
The genetic algorithm exercise was the most difficult because I had to understand fitness, crossover, and mutation.

### 3. What was the most surprising bug you found?
I learned that Go does not automatically convert an `int` to a `float64`. I had to use `float64(qty)` to make the calculation work correctly.

### 4. Why is testing important?
Testing helps me find errors and check whether my program produces the expected output.

**Terminal evidence:** put at least three screenshots under `evidence/` in your fork, or provide terminal output text. Avoid private information in screenshots.

> Predict first. Run second. Explain third.
