# Operations with Operators Programs in C++

## Tools Used
- **Language:** C++
- **Compiler:** g++ (GNU Compiler Collection)
- **IDE:** Any text editor or IDE such as VS Code, Code::Blocks, or Turbo C++

## Theory

### Topic Overview
This experiment demonstrates the use of **arithmetic**, **relational**, and **logical operators** through simple C++ programs. The goal is to understand how conditional expressions and branching logic work using these operators.

These programs allow students to practice:
- Decision making using `if`, `else if`, and `else`
- Logical grouping of conditions using `&&`, `||`, and relational comparisons
- Basic control flow based on input values

---

### Program 1: `exp3A.cpp` – Check if Number is Positive, Negative, or Zero
This program:
- Accepts an integer input
- Uses relational and conditional operators to check whether the number is:
  - Positive
  - Negative
  - Zero

#### Algorithm:
1. Take input number from user
2. Use `if-else` statements with relational operators (`>`, `<`, `==`)
3. Print the result accordingly

---

### Program 2: `exp3B.cpp` – Grade Calculation Based on Marks
This program:
- Accepts marks (0–100) as input
- Uses relational and logical operators to assign grades:
  - A (90+)
  - B (80–89)
  - C (70–79)
  - D (60–69)
  - F (<60)

#### Algorithm:
1. Input marks
2. Use chained `if-else` blocks to compare ranges
3. Output grade

---

### Program 3: `exp3C.cpp` – Determine Quadrant of a Point
This program:
- Accepts `x` and `y` coordinates as input
- Uses logical operators (`&&`) and equality checks to determine:
  - Which quadrant the point lies in (I to IV)
  - If it's on X-axis, Y-axis, or Origin

#### Algorithm:
1. Take x and y as input
2. Check combinations using `if-else if`:
   - `x > 0 && y > 0` → Quadrant I
   - `x < 0 && y > 0` → Quadrant II
   - `x < 0 && y < 0` → Quadrant III
   - `x > 0 && y < 0` → Quadrant IV
   - `x == 0 && y == 0` → Origin
   - `x == 0` or `y == 0` → On axis
3. Output the result

---

## Conclusion
This experiment gives me practical understanding of how operators in C++ influence program logic. By working with:
- Relational (`==`, `<`, `>`, etc.)
- Logical (`&&`, `||`)
- Conditional branching

I have built a strong foundation in writing interactive and decision-based C++ programs.
