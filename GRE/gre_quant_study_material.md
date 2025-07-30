## GRE Quantitative Reasoning: A Comprehensive Study Guide

This guide organizes the essential concepts, formulas, and problem-solving strategies for the GRE Quantitative Reasoning section. The material is structured to build from foundational concepts to more complex applications.

---

### I. Arithmetic & Number Properties

This section covers the fundamental building blocks of GRE Quant: the properties of numbers and the rules for manipulating them.

***

#### **1. Core Concepts**

* **Types of Numbers**:
    * **Integers**: All whole numbers, including zero and negative numbers (e.g., -3, 0, 45).
    * **Rational Numbers**: Any number that can be written as a fraction $\frac{a}{b}$, where $a$ and $b$ are integers and $b \neq 0$ (e.g., $\frac{1}{2}$, $0.75$, -5).
    * **Irrational Numbers**: Numbers that cannot be expressed as a simple fraction (e.g., $\sqrt{2}$, $\pi$).
* **Order of Operations (PEMDAS)**: The sequence for performing calculations:
    1.  **P**arentheses
    2.  **E**xponents
    3.  **M**ultiplication & **D**ivision (from left to right)
    4.  **A**ddition & **S**ubtraction (from left to right)
* **Fundamental Properties**:
    * **Commutative**: $a + b = b + a$; $ab = ba$
    * **Associative**: $(a + b) + c = a + (b + c)$; $(ab)c = a(bc)$
    * **Distributive**: $a(b + c) = ab + ac$
* **Absolute Value**: The distance of a number from zero.
    * $|x| = x$ if $x \geq 0$
    * $|x| = -x$ if $x < 0$
    * **Example**: $|5| = 5$ and $|-5| = 5$.

---

#### **2. Divisibility & Factors**

* **Prime Numbers**: An integer greater than 1 with only two positive divisors: 1 and itself (e.g., 2, 3, 5, 7, 11, 13...). **Note**: 2 is the only even prime number.
* **Prime Factorization**: Expressing an integer as a product of its prime factors.
    * **Example**: The prime factorization of 60 is $2 \times 2 \times 3 \times 5 = 2^2 \times 3 \times 5$.
* **Greatest Common Factor (GCF)**: The largest positive integer that divides two or more integers without a remainder. Find by identifying the common prime factors raised to their lowest powers.
* **Least Common Multiple (LCM)**: The smallest positive integer that is a multiple of two or more integers. Find by identifying all prime factors from both numbers raised to their highest powers.
* **GCF & LCM Relationship**: For any two positive integers $a$ and $b$: $a \times b = GCF(a, b) \times LCM(a, b)$.
    * **Comprehensive Example**: Find the GCF and LCM of 12 and 18.
        1.  Prime Factorization: $12 = 2^2 \times 3^1$ and $18 = 2^1 \times 3^2$.
        2.  **GCF**: The common prime factors are 2 and 3. Their lowest powers are $2^1$ and $3^1$.
            $GCF(12, 18) = 2^1 \times 3^1 = 6$.
        3.  **LCM**: All prime factors are 2 and 3. Their highest powers are $2^2$ and $3^2$.
            $LCM(12, 18) = 2^2 \times 3^2 = 4 \times 9 = 36$.
* **Divisibility Rules**:
    * **Divisible by 2**: The last digit is even (0, 2, 4, 6, 8).
    * **Divisible by 3**: The sum of the digits is divisible by 3.
    * **Divisible by 4**: The last two digits form a number divisible by 4.
    * **Divisible by 5**: The last digit is 0 or 5.
    * **Divisible by 6**: The number is divisible by both 2 and 3.
    * **Divisible by 9**: The sum of the digits is divisible by 9.

***

### II. Algebra

Algebra questions test your ability to work with variables, expressions, equations, functions, and sequences.

***

#### **1. Exponents & Roots**

* **Exponent Rules**:
    * $x^a \cdot x^b = x^{a+b}$
    * $\frac{x^a}{x^b} = x^{a-b}$
    * $(x^a)^b = x^{ab}$
    * $(xy)^a = x^a y^a$
    * $x^0 = 1$ (for $x \neq 0$)
    * $x^{-a} = \frac{1}{x^a}$
* **Roots (Radicals)**:
    * $\sqrt[n]{x} = x^{\frac{1}{n}}$
    * $\sqrt{xy} = \sqrt{x}\sqrt{y}$
    * $\sqrt{\frac{x}{y}} = \frac{\sqrt{x}}{\sqrt{y}}$
    * **Comprehensive Example**: Simplify $(\frac{8x^6}{27})^{-1/3}$.
        1.  Apply the negative exponent rule: $(\frac{27}{8x^6})^{1/3}$.
        2.  Apply the fractional exponent (cube root) to each part: $\frac{\sqrt[3]{27}}{\sqrt[3]{8}\sqrt[3]{x^6}}$.
        3.  Simplify: $\frac{3}{2x^{(6 \times 1/3)}} = \frac{3}{2x^2}$.

---

#### **2. Algebraic Expressions & Factoring**

* **Key Factoring Identities**:
    * **Difference of Squares**: $a^2 - b^2 = (a-b)(a+b)$
    * **Perfect Square Trinomials**: $a^2 + 2ab + b^2 = (a+b)^2$ and $a^2 - 2ab + b^2 = (a-b)^2$
    * **General Quadratic**: To factor $x^2 + bx + c$, find two numbers that multiply to $c$ and add to $b$.
    * **Sum/Difference of Cubes (Less Common)**:
        * $a^3 + b^3 = (a+b)(a^2 - ab + b^2)$
        * $a^3 - b^3 = (a-b)(a^2 + ab + b^2)$
* **Comprehensive Example**: Factor $2x^2 - 50$.
    1.  First, factor out the GCF: $2(x^2 - 25)$.
    2.  Recognize the difference of squares $(x^2 - 5^2)$: $2(x-5)(x+5)$.

---

#### **3. Equations & Inequalities**

* **Linear Equations**: Isolate the variable.
    * **Example**: Solve $3(x-2) = x+4$.
        $3x - 6 = x + 4 \implies 2x = 10 \implies x=5$.
* **Quadratic Equations ($ax^2 + bx + c = 0$)**:
    * **Method 1: Factoring**: Set the equation to 0 and factor.
    * **Method 2: Quadratic Formula**: Use when factoring is difficult.
        $$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$
        The **discriminant** ($b^2 - 4ac$) determines the number of real solutions: positive (2 solutions), zero (1 solution), or negative (0 real solutions).
    * **Example**: Solve $x^2 - 3x - 10 = 0$.
        Factoring: Find two numbers that multiply to -10 and add to -3 (which are -5 and 2).
        $(x-5)(x+2) = 0$. The solutions are $x=5$ and $x=-2$.
* **Inequalities**: Solve like an equation, but **flip the inequality sign** if you multiply or divide by a negative number.
    * **Example**: Solve $-2x + 5 > 11$.
        $-2x > 6 \implies x < -3$ (sign flips when dividing by -2).
* **Absolute Value Equations**: Isolate the absolute value expression and solve for both the positive and negative cases.
    * **Example**: Solve $|x-3| = 7$.
        Case 1: $x-3 = 7 \implies x = 10$.
        Case 2: $x-3 = -7 \implies x = -4$.

---

#### **4. Functions & Sequences**

* **Functions**: A rule that assigns exactly one output ($f(x)$ or $y$) for each input ($x$).
    * **Composition**: $(f \circ g)(x) = f(g(x))$. First apply $g$, then apply $f$ to the result.
    * **Domain**: The set of all valid input values. Watch for:
        1.  Denominators cannot be zero.
        2.  The value inside a square root cannot be negative.
    * **Example**: If $f(x) = \sqrt{x-1}$ and $g(x)=x^2$, find $f(g(5))$.
        1.  First, find $g(5) = 5^2 = 25$.
        2.  Then, find $f(25) = \sqrt{25-1} = \sqrt{24}$.
* **Sequences**:
    * **Arithmetic Sequence**: A constant difference ($d$) is added to each term.
        * Formula: $a_n = a_1 + (n-1)d$.
    * **Geometric Sequence**: Each term is multiplied by a constant ratio ($r$).
        * Formula: $a_n = a_1 \cdot r^{n-1}$.

***

### III. Geometry

This section covers the properties of shapes, from simple lines and angles to 3D solids.

***

#### **1. Lines, Angles, & Polygons**

* **Angles**:
    * A straight line has an angle of $180^\circ$.
    * Intersecting lines create **vertical angles**, which are equal.
    * When parallel lines are crossed by a transversal, all acute angles are equal and all obtuse angles are equal.
* **Polygons**:
    * **Sum of Interior Angles**: For an $n$-sided polygon, the sum is $(n-2) \times 180^\circ$.
    * **Example (Hexagon, n=6)**: $(6-2) \times 180^\circ = 4 \times 180^\circ = 720^\circ$.

---

#### **2. Triangles & Quadrilaterals**

* **Triangles**:
    * The sum of angles is always $180^\circ$. The length of any side is less than the sum of the other two sides.
    * **Area**: $A = \frac{1}{2} \times \text{base} \times \text{height}$.
    * **Pythagorean Theorem** (Right Triangles Only): $a^2 + b^2 = c^2$, where $a$ and $b$ are the legs and $c$ is the hypotenuse.
    * **Special Right Triangles**:
        * **45-45-90**: Sides are in the ratio $x : x : x\sqrt{2}$.
        * **30-60-90**: Sides opposite the angles are in the ratio $x : x\sqrt{3} : 2x$.
* **Quadrilaterals**:
    * **Parallelogram**: Area = base $\times$ height.
    * **Rectangle**: Area = length $\times$ width.
    * **Square**: Area = side$^2$.
    * **Trapezoid**: Area = $\frac{1}{2}(b_1 + b_2)h$.

---

#### **3. Circles**

* **Radius (r)** and **Diameter (d)**: $d=2r$.
* **Area**: $A = \pi r^2$.
* **Circumference**: $C = 2\pi r = \pi d$.
* **Arc Length & Sector Area**: An arc or sector is a fraction of the circle determined by the central angle $\theta$.
    * **Arc Length** = $(\frac{\theta}{360^\circ}) \times 2\pi r$.
    * **Sector Area** = $(\frac{\theta}{360^\circ}) \times \pi r^2$.
    * **Comprehensive Example**: A circle has a radius of 6. Find the area of a sector with a central angle of $60^\circ$.
        1.  Fraction of the circle: $\frac{60^\circ}{360^\circ} = \frac{1}{6}$.
        2.  Total area of the circle: $A = \pi (6^2) = 36\pi$.
        3.  Sector Area: $\frac{1}{6} \times 36\pi = 6\pi$.

---

#### **4. Coordinate Geometry**

* **Distance Formula**: The distance between points $(x_1, y_1)$ and $(x_2, y_2)$ is $\sqrt{(x_2-x_1)^2 + (y_2-y_1)^2}$.
* **Midpoint Formula**: The midpoint is $(\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2})$.
* **Slope of a Line (m)**: $m = \frac{\text{rise}}{\text{run}} = \frac{y_2 - y_1}{x_2 - x_1}$.
    * **Parallel lines** have equal slopes ($m_1 = m_2$).
    * **Perpendicular lines** have negative reciprocal slopes ($m_1 \cdot m_2 = -1$).
* **Equation of a Line**:
    * **Slope-Intercept Form**: $y = mx + b$, where $m$ is the slope and $b$ is the y-intercept.
    * **Example**: Find the equation of a line that is perpendicular to $y=2x+5$ and passes through the point $(4, 1)$.
        1.  The slope of the given line is 2. The perpendicular slope is $m = -\frac{1}{2}$.
        2.  Use the point-slope form $y - y_1 = m(x - x_1)$: $y - 1 = -\frac{1}{2}(x - 4)$.
        3.  Simplify to slope-intercept form: $y - 1 = -\frac{1}{2}x + 2 \implies y = -\frac{1}{2}x + 3$.

---

#### **5. 3D Solids**

* **Rectangular Solid**:
    * Volume: $V = \text{length} \times \text{width} \times \text{height}$.
    * Surface Area: $SA = 2(lw + lh + wh)$.
* **Cube**:
    * Volume: $V = s^3$.
    * Surface Area: $SA = 6s^2$.
* **Cylinder**:
    * Volume: $V = \pi r^2 h$.
    * Surface Area: $SA = 2\pi r^2 + 2\pi rh$.

***

### IV. Data Analysis

This section covers statistics, probability, counting methods, and interpreting graphical data.

***

#### **1. Descriptive Statistics**

* **Measures of Central Tendency**:
    * **Mean (Average)**: Sum of terms / Number of terms.
    * **Median**: The middle value in a sorted data set.
    * **Mode**: The most frequently occurring value.
* **Measures of Spread**:
    * **Range**: Maximum value - Minimum value.
    * **Standard Deviation (SD)**: Measures how spread out the data is from the mean.
        * A low SD means data is clustered around the mean.
        * A high SD means data is spread out.
        * If all values in a set are identical, the SD is 0.
        * Adding a constant to every value does **not** change the SD.
        * Multiplying every value by a constant $k$ multiplies the SD by $|k|$.
* **Normal Distribution**: A bell-shaped curve. The **Empirical Rule** states:
    * ~68% of data falls within 1 SD of the mean.
    * ~95% of data falls within 2 SDs of the mean.
    * ~99.7% of data falls within 3 SDs of the mean.

---

#### **2. Counting Methods & Probability**

* **Fundamental Counting Principle**: If there are $A$ ways to do one thing and $B$ ways to do another, there are $A \times B$ ways to do both.
* **Permutations (Order Matters)**: The number of ways to arrange $k$ items from a set of $n$.
    * Formula: $P(n, k) = \frac{n!}{(n-k)!}$.
    * **Example**: How many ways can a President and VP be chosen from 5 candidates?
        $P(5, 2) = \frac{5!}{(5-2)!} = \frac{5!}{3!} = 5 \times 4 = 20$.
* **Combinations (Order Doesn't Matter)**: The number of ways to choose $k$ items from a set of $n$.
    * Formula: $C(n, k) = \binom{n}{k} = \frac{n!}{k!(n-k)!}$.
    * **Example**: How many ways can a 2-person committee be chosen from 5 candidates?
        $C(5, 2) = \frac{5!}{2!(5-2)!} = \frac{120}{2 \times 6} = 10$.
* **Basic Probability**:
    * $P(\text{Event}) = \frac{\text{Number of Favorable Outcomes}}{\text{Total Number of Possible Outcomes}}$. The probability is always between 0 and 1.
    * $P(\text{Event does not happen}) = 1 - P(\text{Event happens})$.
* **Probability of Multiple Events**:
    * **Mutually Exclusive Events ("OR")**: $P(A \text{ or } B) = P(A) + P(B)$.
    * **Non-Exclusive Events ("OR")**: $P(A \text{ or } B) = P(A) + P(B) - P(A \text{ and } B)$.
    * **Independent Events ("AND")**: $P(A \text{ and } B) = P(A) \times P(B)$.

---

#### **3. Data Interpretation**

The GRE uses various charts and graphs. The key is to read carefully and extract the correct information.
* **Pie Charts**: Show parts of a whole (percentages or proportions).
* **Bar Charts**: Compare quantities across different categories.
* **Line Graphs**: Show trends over time.
* **Scatterplots**: Show the relationship between two variables.
* **Tables**: Present data in rows and columns.
**Strategy**: Always read the title, labels on the axes, units, and any footnotes before attempting to answer the question.

***

### V. Word Problems

Word problems integrate concepts from all other areas. The key is to translate words into mathematical expressions.

***

#### **1. Ratios, Proportions, & Percentages**

* **Ratio**: Compares two quantities (e.g., $a:b$ or $\frac{a}{b}$).
* **Proportion**: An equation stating that two ratios are equal ($\frac{a}{b} = \frac{c}{d}$).
* **Percentages**: A special ratio where the denominator is 100.
    * **Percent Change**: $\frac{\text{New Value} - \text{Old Value}}{\text{Old Value}} \times 100\%$.
    * **Example**: A price increases from $80 to $100. What is the percent increase?
        $\frac{100 - 80}{80} \times 100\% = \frac{20}{80} \times 100\% = 0.25 \times 100\% = 25\%$.

---

#### **2. Rates & Interest**

* **Rate Problems**: The core formula is **Distance = Rate $\times$ Time**. This can be adapted for any "amount" being produced.
* **Work-Rate Problems**: The rate of work is the amount of work done per unit of time.
    * **Combined Work Rate**: $\frac{1}{T_{\text{total}}} = \frac{1}{T_A} + \frac{1}{T_B}$, where $T_A$ and $T_B$ are the times it takes individuals A and B to complete the job alone.
* **Interest**:
    * **Simple Interest**: $I = P \times r \times t$, where $P$ is principal, $r$ is the annual rate, and $t$ is time in years.
    * **Compound Interest**: $A = P(1 + \frac{r}{n})^{nt}$, where $A$ is the final amount, and $n$ is the number of times interest is compounded per year.

---

#### **3. Sets (Venn Diagrams)**

* **Two-Set Formula**: Total = |Group A| + |Group B| - |Both| + |Neither|.
* **Three-Set Formula (Inclusion-Exclusion)**:
    $|A \cup B \cup C| = |A| + |B| + |C| - (|A \cap B| + |A \cap C| + |B \cap C|) + |A \cap B \cap C|$.
* **Example**: In a class of 100 students, 60 take Spanish, 40 take French, and 15 take both. How many take neither?
    1.  Find the number who take at least one language: Total in languages = Spanish + French - Both = $60 + 40 - 15 = 85$.
    2.  Find the number who take neither: Total Students - Total in languages = $100 - 85 = 15$.