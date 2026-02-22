## Geometry

### Vector exercise problems
---
### Problem 12 (projections)

**Problem:** Calculate the projection of $\mathbf{v} = \begin{pmatrix} 2 \\ 3 \end{pmatrix}$ onto vector $\mathbf{w} = \begin{pmatrix} -1 \\ 2 \end{pmatrix}$.

**Step 1: Recall the projection formula** The vector projection of $\mathbf{v}$ onto $\mathbf{w}$ is calculated as:

$$\text{proj}_{\mathbf{w}}(\mathbf{v}) = \frac{\mathbf{v} \cdot \mathbf{w}}{||\mathbf{w}||^2} \mathbf{w}$$

**Step 2: Calculate the dot product ($\mathbf{v} \cdot \mathbf{w}$)**

$$\mathbf{v} \cdot \mathbf{w} = (2)(-1) + (3)(2)$$

$$\mathbf{v} \cdot \mathbf{w} = -2 + 6 = 4$$

**Step 3: Calculate the squared magnitude of $\mathbf{w}$ ($||\mathbf{w}||^2$)**

$$||\mathbf{w}||^2 = (-1)^2 + (2)^2$$

$$||\mathbf{w}||^2 = 1 + 4 = 5$$

**Step 4: Multiply the resulting scalar by vector $\mathbf{w}$**

$$\text{proj}_{\mathbf{w}}(\mathbf{v}) = \frac{4}{5} \begin{pmatrix} -1 \\ 2 \end{pmatrix}$$

$$\text{proj}_{\mathbf{w}}(\mathbf{v}) = \begin{pmatrix} -4/5 \\ 8/5 \end{pmatrix}$$

**Final Answers for the boxes:**

-   **First component:** $-4/5$ (or $-0.8$)
    
-   **Second component:** $8/5$ (or $1.6$)
    
---

### Problem 13
Here is the step-by-step solution for calculating the angle $\alpha$ in the regular hexagon:

**Step 1: Identify the coordinates of the three vertices**

The problem gives the formula for the vertices: $(\cos(60k^\circ), \sin(60k^\circ))$.

-   **Vertex at $\alpha$ (Right-most):** This is at $k=0$.
    
    $C = (\cos(0^\circ), \sin(0^\circ)) = (1, 0)$
    
-   **Top-left vertex:** This is at $k=2$.
    
    $B = (\cos(120^\circ), \sin(120^\circ)) = (-0.5, \frac{\sqrt{3}}{2})$
    
-   **Left-most vertex:** This is at $k=3$.
    
    $A = (\cos(180^\circ), \sin(180^\circ)) = (-1, 0)$
    

**Step 2: Define the vectors forming the angle**

Since the angle $\alpha$ originates at vertex $C$, we need vectors $\vec{CA}$ and $\vec{CB}$.

-   $\vec{CA} = A - C = (-1 - 1, 0 - 0) = (-2, 0)$
    
-   $\vec{CB} = B - C = (-0.5 - 1, \frac{\sqrt{3}}{2} - 0) = (-1.5, \frac{\sqrt{3}}{2})$
    

**Step 3: Calculate the dot product and magnitudes**

-   **Dot Product:** $\vec{CA} \cdot \vec{CB} = (-2)(-1.5) + (0)(\frac{\sqrt{3}}{2}) = 3$
    
-   **Magnitude of $\vec{CA}$:** $||\vec{CA}|| = \sqrt{(-2)^2 + 0^2} = \sqrt{4} = 2$
    
-   **Magnitude of $\vec{CB}$:** $||\vec{CB}|| = \sqrt{(-1.5)^2 + (\frac{\sqrt{3}}{2})^2} = \sqrt{2.25 + 0.75} = \sqrt{3}$
    

**Step 4: Apply the vector angle formula**

$$\cos(\alpha) = \frac{\vec{CA} \cdot \vec{CB}}{||\vec{CA}|| \cdot ||\vec{CB}||}$$

$$\cos(\alpha) = \frac{3}{2\sqrt{3}} = \frac{\sqrt{3}}{2}$$

The angle whose cosine is $\frac{\sqrt{3}}{2}$ is **30°**.

----------

> **Tutor Tip (The Geometric Lens Shortcut!):** You can also solve this instantly using circle geometry! A regular hexagon's vertices all touch a circumscribed circle. The angle $\alpha$ is an inscribed angle that "opens up" to the arc between $k=2$ (120°) and $k=3$ (180°). That arc is 60°. A geometry rule states that an inscribed angle is always exactly half of the arc it opens up to. Half of 60° is 30°!

---

### Problem 14
### Step-by-Step Solution: Scalar Projection

**Step 1: Find the Displacement Vector ($\mathbf{v}$)**

First, we need the vector representing the actual movement. Remember our rule from the very first problem: "Head minus Tail" (Destination minus Origin).

-   Origin $A = (2, 4)$
    
-   Destination $B = (3, -4)$
    
-   Displacement $\mathbf{v} = B - A = \begin{pmatrix} 3 - 2 \\ -4 - 4 \end{pmatrix} = \begin{pmatrix} 1 \\ -8 \end{pmatrix}$
    

**Step 2: Identify the Force Vector ($\mathbf{F}$)**

The problem gives us the force vector directly, which will act as our base vector $\mathbf{w}$ in the formula:

-   Force $\mathbf{F} = \begin{pmatrix} 3 \\ 4 \end{pmatrix}$
    

**Step 3: Calculate the Dot Product ($\mathbf{v} \cdot \mathbf{F}$)**

Multiply the corresponding components and add them together:

-   $\mathbf{v} \cdot \mathbf{F} = (1)(3) + (-8)(4)$
    
-   $\mathbf{v} \cdot \mathbf{F} = 3 - 32 = -29$
    

**Step 4: Calculate the Magnitude of the Force Vector ($||\mathbf{F}||$)**

We need the length of the vector we are projecting _onto_.

-   $||\mathbf{F}|| = \sqrt{3^2 + 4^2}$
    
-   $||\mathbf{F}|| = \sqrt{9 + 16} = \sqrt{25} = 5$
    

**Step 5: Calculate the Scalar Projection**

Now, just plug the values into the formula provided in the problem:

-   $\text{sc. proj.} = \frac{\mathbf{v} \cdot \mathbf{F}}{||\mathbf{F}||} = \frac{-29}{5}$
    

The final answer to enter into the box is **$-29/5$** (or **$-5.8$**).

----------

### The Geometric Lens (What does this mean physically?)

> **Tutor Tip:** Your student might ask, "How can a length be negative?"
> 
> Explain that a _scalar projection_ isn't just a pure distance; it includes a directional sign! Because the dot product is negative ($-29$), the angle between the movement and the force is _obtuse_ (greater than 90 degrees).
> 
> Physically, this means the object is moving generally in the _opposite_ direction of the force being applied. The force is actively resisting the movement (like friction or air resistance), which means the force is doing **negative work** on the object!

---
---
---
---
---

### Problem 1

### **Part A: Analyzing Triangle ABC**

**Given Points:**

-   $A = (-5, 0)$
    
-   $B = (-1, 2)$
    
-   $C = (1, -2)$
    

**Step 1: Calculate the squared lengths of the sides.**

Using the distance formula $d^2 = (x_2 - x_1)^2 + (y_2 - y_1)^2$:

1.  **Side $AB$:**
    
    $$|AB|^2 = (-1 - (-5))^2 + (2 - 0)^2$$
    
    $$|AB|^2 = (4)^2 + (2)^2 = 16 + 4 = 20$$
    
    $$|AB| = \sqrt{20}$$
    
2.  **Side $BC$:**
    
    $$|BC|^2 = (1 - (-1))^2 + (-2 - 2)^2$$
    
    $$|BC|^2 = (2)^2 + (-4)^2 = 4 + 16 = 20$$
    
    $$|BC| = \sqrt{20}$$
    
3.  **Side $AC$:**
    
    $$|AC|^2 = (1 - (-5))^2 + (-2 - 0)^2$$
    
    $$|AC|^2 = (6)^2 + (-2)^2 = 36 + 4 = 40$$
    
    $$|AC| = \sqrt{40}$$
    

**Step 2: Check triangle properties.**

-   **Isosceles:**
    
    Since $|AB| = \sqrt{20}$ and $|BC| = \sqrt{20}$, we have $|AB| = |BC|$.
    
    $\rightarrow$ **True**: "$ABC$ is an isosceles triangle: $AB$ and $BC$ have equal length."
    
-   **Right Triangle:**
    
    Check the Pythagorean theorem ($a^2 + b^2 = c^2$).
    
    $$|AB|^2 + |BC|^2 = 20 + 20 = 40$$
    
    $$|AC|^2 = 40$$
    
    Since $|AB|^2 + |BC|^2 = |AC|^2$, the triangle is a right-angled triangle. The hypotenuse is $AC$, which means the right angle is at vertex $B$ (opposite the hypotenuse).
    
    $\rightarrow$ **True**: "$ABC$ is a right triangle: it has a right angle at $B$."
    

**Correct Selections for Part A:**

-   $\checkmark$ **$ABC$ is an isosceles triangle: $AB$ and $BC$ have equal length.**
    
-   $\checkmark$ **$ABC$ is a right triangle: it has a right angle at $B$.**
    


### **Part B: Finding the Equilateral Point**

**Given:**

-   Points $B(-1, 2)$ and $C(1, -2)$
    
-   We need to find point $P(x, y)$ with $x > 0$ and $y > 0$ such that triangle $BCP$ is equilateral.
    

**Condition for Equilateral Triangle:**

All sides must have equal length. From Part A, we know $|BC|^2 = 20$.

Therefore, $|BP|^2 = 20$ and $|CP|^2 = 20$.

**Step 1: Set up the distance equations.**

1.  **Distance from B:**
    
    $$(x - (-1))^2 + (y - 2)^2 = 20$$
    
    $$(x + 1)^2 + (y - 2)^2 = 20 \quad \dots \text{(Eq. 1)}$$
    
2.  **Distance from C:**
    
    $$(x - 1)^2 + (y - (-2))^2 = 20$$
    
    $$(x - 1)^2 + (y + 2)^2 = 20 \quad \dots \text{(Eq. 2)}$$
    

**Step 2: Solve the system.**

Expand both equations:

-   (Eq. 1): $x^2 + 2x + 1 + y^2 - 4y + 4 = 20 \Rightarrow x^2 + y^2 + 2x - 4y = 15$
    
-   (Eq. 2): $x^2 - 2x + 1 + y^2 + 4y + 4 = 20 \Rightarrow x^2 + y^2 - 2x + 4y = 15$
    

Subtract (Eq. 2) from (Eq. 1):

$$(x^2 + y^2 + 2x - 4y) - (x^2 + y^2 - 2x + 4y) = 15 - 15$$

$$4x - 8y = 0$$

$$4x = 8y$$

$$x = 2y$$

**Step 3: Find the values of $x$ and $y$.**

Substitute $x = 2y$ back into (Eq. 2):

$$(2y - 1)^2 + (y + 2)^2 = 20$$

$$(4y^2 - 4y + 1) + (y^2 + 4y + 4) = 20$$

$$5y^2 + 5 = 20$$

$$5y^2 = 15$$

$$y^2 = 3$$

Since the problem states $y > 0$:

$$y = \sqrt{3}$$

Now find $x$ using $x = 2y$:

$$x = 2\sqrt{3}$$

**Final Answer for Part B:**

-   $x = 2\sqrt{3}$
    
-   $y = \sqrt{3}$

---
### Problem 2

Here are the step-by-step solutions for the four new problems involving vectors and lines.

### **Problem A: Angle Between Vectors**

**Given:**

-   Origin $O = (0,0)$.
    
-   Point $A = (1, 2) \Rightarrow \text{Vector } \vec{OA} = \binom{1}{2}$.
    
-   Point $B = (4, 3) \Rightarrow \text{Vector } \vec{OB} = \binom{4}{3}$.
    

**Formula:**

The dot product relates the magnitudes of two vectors and the cosine of the angle $\theta$ between them:

$$\vec{a} \cdot \vec{b} = ||\vec{a}|| \cdot ||\vec{b}|| \cos(\theta)$$

**Step 1: Calculate the Dot Product ($\vec{OA} \cdot \vec{OB}$)**

$$\vec{OA} \cdot \vec{OB} = (1)(4) + (2)(3) = 4 + 6 = 10$$

**Step 2: Calculate the Magnitudes ($||\vec{OA}||$ and $||\vec{OB}||$)**

$$||\vec{OA}|| = \sqrt{1^2 + 2^2} = \sqrt{1 + 4} = \sqrt{5}$$

$$||\vec{OB}|| = \sqrt{4^2 + 3^2} = \sqrt{16 + 9} = \sqrt{25} = 5$$

**Step 3: Solve for $\theta$**

$$10 = (\sqrt{5})(5) \cos(\theta)$$

$$\cos(\theta) = \frac{10}{5\sqrt{5}} = \frac{2}{\sqrt{5}}$$

Using a calculator (as permitted):

$$\frac{2}{\sqrt{5}} \approx 0.8944$$

$$\theta = \arccos(0.8944) \approx 26.565^\circ$$

**Final Answer:**

Rounding to the nearest degree:

**$\theta = 27^\circ$**

----------

### **Problem B: Parametrization of Line L**

**Given:**

-   Line $L$ passes through $A(1, 2)$ and $B(4, 3)$.
    
-   Parametrization given: $x(t) = 1 + 3t$.
    

**Analysis:**

The standard form for a line parametrization starting at point $A$ with direction vector $\vec{d}$ is:

$$\vec{r}(t) = A + t\vec{d}$$

$$\binom{x(t)}{y(t)} = \binom{1}{2} + t\binom{d_x}{d_y}$$

Looking at $x(t) = 1 + 3t$, we can see the x-component of the direction vector is $3$.

Let's find the full direction vector $\vec{AB}$:

$$\vec{AB} = B - A = \binom{4-1}{3-2} = \binom{3}{1}$$

Substitute this back into the vector equation:

$$\binom{x(t)}{y(t)} = \binom{1}{2} + t\binom{3}{1}$$

$$x(t) = 1 + 3t$$

$$y(t) = 2 + 1t$$

**Final Answer:**

**$y(t) = 2 + t$**

----------

### **Problem C: Orthogonal Point P**

**Given:**

-   Point $P(P_x, P_y)$ lies on line $L$. From Problem B, we know:
    
    -   $P_x = 1 + 3t$
        
    -   $P_y = 2 + t$
        
-   Vector $\vec{OP}$ is orthogonal to $\vec{OB}$.
    

**Condition for Orthogonality:**

Two vectors are orthogonal if their dot product is 0.

$$\vec{OP} \cdot \vec{OB} = 0$$

**Step 1: Set up the equation**

$\vec{OP} = \binom{1+3t}{2+t}$ and $\vec{OB} = \binom{4}{3}$.

$$(1+3t)(4) + (2+t)(3) = 0$$

**Step 2: Solve for $t$**

$$4 + 12t + 6 + 3t = 0$$

$$15t + 10 = 0$$

$$15t = -10$$

$$t = -\frac{10}{15} = -\frac{2}{3}$$

**Step 3: Find Coordinates of P**

Substitute $t = -2/3$ back into the expressions for $P_x$ and $P_y$:

$$P_x = 1 + 3\left(-\frac{2}{3}\right) = 1 - 2 = -1$$

$$P_y = 2 + \left(-\frac{2}{3}\right) = \frac{6}{3} - \frac{2}{3} = \frac{4}{3}$$

**Final Answer:**

**$P_x = -1$**

**$P_y = 4/3$**

----------

### **Problem D: Point Q with Angle $\pi/4$**

**Given:**

-   Point $Q(Q_x, Q_y)$ is on line $L$, so $\vec{OQ} = \binom{1+3t}{2+t}$.
    
-   Angle between $\vec{OQ}$ and $\vec{OB}$ is $\frac{\pi}{4}$ ($45^\circ$).
    
-   $\vec{OB} = \binom{4}{3}$, $||\vec{OB}|| = 5$.
    

**Step 1: Set up the Dot Product Formula**

$$\vec{OQ} \cdot \vec{OB} = ||\vec{OQ}|| \cdot ||\vec{OB}|| \cos(45^\circ)$$

Calculations we already know:

-   $\vec{OQ} \cdot \vec{OB} = 15t + 10$ (from Problem C step 1).
    
-   $\cos(45^\circ) = \frac{1}{\sqrt{2}}$.
    
-   $||\vec{OQ}|| = \sqrt{(1+3t)^2 + (2+t)^2}$.
    

The Equation:

$$15t + 10 = \sqrt{(1+3t)^2 + (2+t)^2} \cdot 5 \cdot \frac{1}{\sqrt{2}}$$

**Step 2: Solve for $t$**

Divide by 5 to simplify:

$$3t + 2 = \sqrt{(1+3t)^2 + (2+t)^2} \cdot \frac{1}{\sqrt{2}}$$

Square both sides (Note: $3t+2$ must be positive for valid $t$):

$$(3t+2)^2 = \frac{1}{2} \left[ (1+3t)^2 + (2+t)^2 \right]$$

$$2(3t+2)^2 = (1+3t)^2 + (2+t)^2$$

Expand:

$$2(9t^2 + 12t + 4) = (1 + 6t + 9t^2) + (4 + 4t + t^2)$$

$$18t^2 + 24t + 8 = 10t^2 + 10t + 5$$

Move terms to one side:

$$8t^2 + 14t + 3 = 0$$

Use quadratic formula:

$$t = \frac{-14 \pm \sqrt{14^2 - 4(8)(3)}}{2(8)}$$

$$t = \frac{-14 \pm \sqrt{196 - 96}}{16} = \frac{-14 \pm 10}{16}$$

Two possible solutions:

1.  $t = \frac{-4}{16} = -\frac{1}{4}$
    
2.  $t = \frac{-24}{16} = -\frac{3}{2}$
    

**Step 3: Check Validity**

The dot product term ($15t+10$) must be positive because the angle is acute ($45^\circ$).

-   For $t = -1/4$: $15(-0.25) + 10 = 6.25$ (Positive, Valid).
    
-   For $t = -3/2$: $15(-1.5) + 10 = -12.5$ (Negative, Invalid—this would be $135^\circ$).
    

So, **$t = -1/4$**.

**Step 4: Find Coordinates of Q**

$$Q_x = 1 + 3\left(-\frac{1}{4}\right) = 1 - \frac{3}{4} = \frac{1}{4}$$

$$Q_y = 2 + \left(-\frac{1}{4}\right) = 2 - \frac{1}{4} = \frac{7}{4}$$

**Final Answer:**

**$Q_x = 1/4$** (or $0.25$)

**$Q_y = 7/4$** (or $1.75$)

---

### Problem 3 

Here is the final, consolidated answer key for all four curves based on our algebraic breakdowns:

-   **Curve 1:** * **Equation:** $y = -0.5x - 2.5$
    
    -   **Description:** A straight line with a shallow negative slope, crossing the negative x-axis at -5 and the negative y-axis at -2.5.
        
    -   **Final Match:** The image showing a line passing entirely through the bottom-left section (**Quadrant III**).
        
-   **Curve 2:** * **Equation:** $y = 2x + 5$
    
    -   **Description:** A straight line with a steep positive slope, crossing the negative x-axis at -2.5 and the positive y-axis at +5.
        
    -   **Final Match:** The image showing a steep upward line crossing the top-left section (crossing positive y and negative x).
        
-   **Curve 3:** * **Equation:** $(x - 4)^2 + (y - 3)^2 = 4$
    
    -   **Description:** A circle with a radius of 2 and a center at $(4, 3)$. Because both coordinates of the center are positive, it sits entirely in the top-right section.
        
    -   **Final Match:** The image showing a circle in the top-right (**Quadrant I**).
        
-   **Curve 4:** * **Equation:** $(x + 4)^2 + (y - 3)^2 = 4$
    
    -   **Description:** A circle with a radius of 2 and a center at $(-4, 3)$. Because the x-coordinate is negative and the y-coordinate is positive, it sits entirely in the top-left section.
        
    -   **Final Match:** The image showing a circle in the top-left (**Quadrant II**).
        

Curve 1: 4, Curve 2: 7, Curve 3: 1, Curve 4: 8

---

### Problem 4
Here are the step-by-step solutions for Problem 4, which is broken down into four parts (A, B, C, D).

**Given Points:**

-   $A = (1, 0)$
    
-   $B = (3, 4)$
    
-   $C = (7, 0)$
    


### **Part A: Perpendicular Bisector of AB**

**Step 1: Find the Midpoint of AB.**

The perpendicular bisector passes through the midpoint.

$$M_{AB} = \left( \frac{1+3}{2}, \frac{0+4}{2} \right) = \left( \frac{4}{2}, \frac{4}{2} \right) = (2, 2)$$

**Step 2: Find the Slope of AB.**

$$m_{AB} = \frac{4 - 0}{3 - 1} = \frac{4}{2} = 2$$

**Step 3: Find the Slope of the Perpendicular Bisector.**

The slope of a perpendicular line is the negative reciprocal.

$$m_{\perp} = -\frac{1}{m_{AB}} = -\frac{1}{2}$$

**Step 4: Find the Equation.**

Use the Point-Slope form ($y - y_1 = m(x - x_1)$) with the midpoint $(2, 2)$ and slope $-\frac{1}{2}$.

$$y - 2 = -\frac{1}{2}(x - 2)$$

Multiply everything by 2 to remove the fraction:

$$2(y - 2) = -1(x - 2)$$

$$2y - 4 = -x + 2$$

Rearrange into $ax + by = c$ form:

$$x + 2y = 6$$

**Step 5: Calculate Ratios.**

Here $a = 1$, $b = 2$, and $c = 6$.

-   $\frac{a}{c} = \frac{1}{6}$
    
-   $\frac{b}{c} = \frac{2}{6} = \frac{1}{3}$
    

**Answer Part A:**

-   $\frac{a}{c} = 1/6$
    
-   $\frac{b}{c} = 1/3$
    



### **Part B: Perpendicular Bisector of AC**

**Step 1: Find the Midpoint of AC.**

$$M_{AC} = \left( \frac{1+7}{2}, \frac{0+0}{2} \right) = \left( \frac{8}{2}, 0 \right) = (4, 0)$$

**Step 2: Find the Slope of AC.**

$$m_{AC} = \frac{0 - 0}{7 - 1} = 0$$

Since the slope is 0, the line $AC$ is **horizontal** (it lies on the x-axis).

**Step 3: Find the Slope of the Perpendicular Bisector.**

The line perpendicular to a horizontal line is a **vertical line**. Its slope is undefined.

The equation of a vertical line passing through $x = 4$ is simply:

$$x = 4$$

**Step 4: Formulate as $ax + by = c$.**

$$1x + 0y = 4$$

Here $a = 1$, $b = 0$, $c = 4$.

**Step 5: Calculate Ratios.**

-   $\frac{a}{c} = \frac{1}{4}$
    
-   $\frac{b}{c} = \frac{0}{4} = 0$
    

**Answer Part B:**

-   $\frac{a}{c} = 1/4$
    
-   $\frac{b}{c} = 0$
    


### **Part C: Intersection Point M**

We need to find the intersection of the two bisector lines found in Parts A and B.

1.  Line 1: $x + 2y = 6$
    
2.  Line 2: $x = 4$
    

Substitute $x = 4$ into the first equation:

$$4 + 2y = 6$$

$$2y = 2$$

$$y = 1$$

So the intersection point is $M(4, 1)$.

**Answer Part C:**

-   x-coordinate of M: **4**
    
-   y-coordinate of M: **1**
    

### **Part D: Circle Equation**

The intersection of perpendicular bisectors ($M$) is the center of the circumscribed circle (circumcenter).

The equation is given as $(x-a)^2 + (y-b)^2 = c$. (Note: In this context, $a$ and $b$ are the center coordinates, and $c$ is the radius squared, $r^2$).

**Step 1: Identify Center $(a, b)$.**

From Part C, the center $M$ is $(4, 1)$.

So, $a = 4$ and $b = 1$.

**Step 2: Calculate Radius Squared ($c$).**

Calculate the distance squared from the center $M(4,1)$ to any point on the circle (e.g., $A(1,0)$).

$$r^2 = (x_2 - x_1)^2 + (y_2 - y_1)^2$$

$$c = (1 - 4)^2 + (0 - 1)^2$$

$$c = (-3)^2 + (-1)^2$$

$$c = 9 + 1 = 10$$

(You can check with point B: $(3-4)^2 + (4-1)^2 = 1 + 9 = 10$. It matches).

**Answer Part D:**

-   $a = 4$
    
-   $b = 1$
    
-   $c = 10$

---
### Problem 5
Here are the step-by-step solutions for the final problem set involving the curve $C$ and line $L$.



### **Part A: Find Intersection Point P**

**Given:**

-   **Curve $C$:** $\begin{cases} x(t) = \frac{1}{2}\cos(t) \\ y(t) = \cos(t - \frac{2}{3}\pi) \end{cases}$
    
-   **Line $L$:** $y = 2x$
    

**Step 1: Substitute $x(t)$ and $y(t)$ into the line equation.**

$$y(t) = 2x(t)$$

$$\cos\left(t - \frac{2}{3}\pi\right) = 2\left( \frac{1}{2}\cos(t) \right)$$

$$\cos\left(t - \frac{2}{3}\pi\right) = \cos(t)$$

**Step 2: Solve for $t$.**

The general solution for $\cos(A) = \cos(B)$ is $A = \pm B + 2k\pi$.

-   **Case 1:** $t - \frac{2}{3}\pi = t + 2k\pi \Rightarrow -\frac{2}{3}\pi = 2k\pi$ (No integer solution).
    
-   **Case 2:** $t - \frac{2}{3}\pi = -t + 2k\pi$
    
    $$2t = \frac{2}{3}\pi + 2k\pi$$
    
    $$t = \frac{\pi}{3} + k\pi$$
    

**Step 3: Identify the valid $t$ for Point P.**

We are looking for point $P$ in the first quadrant (from the picture), where $x > 0$ and $y > 0$.

-   If $k=0$, $t = \frac{\pi}{3}$:
    
    -   $x = \frac{1}{2}\cos(60^\circ) = \frac{1}{2}(\frac{1}{2}) = \frac{1}{4}$ (Positive)
        
    -   $y = \cos(60^\circ - 120^\circ) = \cos(-60^\circ) = \frac{1}{2}$ (Positive)
        
    -   This matches point $P$.
        
-   If $k=1$, $t = \frac{4\pi}{3}$:
    
    -   $x$ would be negative (Quadrant 3), which is the other intersection point.
        

**Step 4: Final Coordinates.**

-   **$P_x = 1/4$**
    
-   **$P_y = 1/2$**
    


### **Part B: Tangent Line Parametrization**

**Given:**

-   Parametrization form: $\begin{cases} x(t) = \frac{1}{4} - t \\ y(t) = \dots \end{cases}$
    
-   Note: The variable $t$ here describes the line, it is different from the curve's parameter.
    

**Step 1: Calculate the slope of the tangent at P.**

We need derivatives of the curve at $t = \frac{\pi}{3}$.

-   $x'(t) = -\frac{1}{2}\sin(t) \Rightarrow x'(\frac{\pi}{3}) = -\frac{1}{2}(\frac{\sqrt{3}}{2}) = -\frac{\sqrt{3}}{4}$
    
-   $y'(t) = -\sin(t - \frac{2}{3}\pi) \Rightarrow y'(\frac{\pi}{3}) = -\sin(-\frac{\pi}{3}) = \sin(\frac{\pi}{3}) = \frac{\sqrt{3}}{2}$
    

**Step 2: Find the direction vector of the line.**

The tangent vector is $\vec{v} = \binom{x'}{y'} = \binom{-\sqrt{3}/4}{\sqrt{3}/2}$.

We need to rescale this vector to match the given form $x(t) = \frac{1}{4} - 1t$.

The given $x$-direction component is **$-1$**.

To get from $-\frac{\sqrt{3}}{4}$ to $-1$, we multiply by the scalar $k = \frac{4}{\sqrt{3}}$.

Apply this same scalar to the y-component:

$$\text{New } y\text{-direction} = \left(\frac{\sqrt{3}}{2}\right) \cdot \left(\frac{4}{\sqrt{3}}\right) = \frac{4}{2} = 2$$

**Step 3: Construct the equation.**

The line starts at $P_y = \frac{1}{2}$ and moves with direction $2$.

$$y(t) = \frac{1}{2} + 2t$$

**Answer:**

**$y(t) = 1/2 + 2t$**


### **Part C: Angle of Intersection**

**Step 1: Identify Direction Vectors.**

-   **Curve Tangent ($\vec{v}_C$):** From Part B, the simplified direction vector is $\binom{-1}{2}$.
    
-   **Line $L$ ($\vec{v}_L$):** The line is $y=2x$ (slope 2). A direction vector for this is $\binom{1}{2}$ (1 unit right, 2 units up).
    

**Step 2: Use the Dot Product Formula.**

$$\cos(\theta) = \frac{|\vec{v}_C \cdot \vec{v}_L|}{||\vec{v}_C|| \cdot ||\vec{v}_L||}$$

-   **Dot Product:** $(-1)(1) + (2)(2) = -1 + 4 = 3$
    
-   **Magnitude of $\vec{v}_C$:** $\sqrt{(-1)^2 + 2^2} = \sqrt{5}$
    
-   **Magnitude of $\vec{v}_L$:** $\sqrt{1^2 + 2^2} = \sqrt{5}$
    

**Step 3: Solve for $\theta$.**

$$\cos(\theta) = \frac{3}{\sqrt{5} \cdot \sqrt{5}} = \frac{3}{5} = 0.6$$

**Step 4: Calculate Angle.**

$$\theta = \arccos(0.6)$$

Using the standard 3-4-5 triangle or a calculator approximation:

$\theta \approx 53.13^\circ$

**Answer:**

**$\theta = 53$** (rounded to nearest degree)

---
### Problem 6

This problem analyzes the motion of an object defined by the parametrization:

$$\begin{cases} x(t) = \sin(t) \\ y(t) = \sin(2t) \end{cases}$$

for the domain $0 \le t \le \pi$.

Here are the step-by-step solutions for each part.



### **Part A: Points $P_1$ and $P_2$ (Parallel to x-axis)**

**Concept:**

The object moves parallel to the x-axis when the vertical velocity is zero (the tangent is horizontal).

Condition: $y'(t) = 0$ (and $x'(t) \neq 0$).

**Step 1: Calculate the derivatives.**

-   $x'(t) = \cos(t)$
    
-   $y'(t) = \frac{d}{dt}(\sin(2t)) = 2\cos(2t)$
    

**Step 2: Solve $y'(t) = 0$.**

$$2\cos(2t) = 0$$

$$\cos(2t) = 0$$

The general solutions for $2t$ are $\frac{\pi}{2}, \frac{3\pi}{2}, \dots$

$$2t = \frac{\pi}{2} \Rightarrow t = \frac{\pi}{4}$$

$$2t = \frac{3\pi}{2} \Rightarrow t = \frac{3\pi}{4}$$

Both values are within the domain $0 \le t \le \pi$.

**Step 3: Find Coordinates.**

-   **For $t = \frac{\pi}{4}$:**
    
    -   $x = \sin(\frac{\pi}{4}) = \frac{\sqrt{2}}{2}$
        
    -   $y = \sin(2 \cdot \frac{\pi}{4}) = \sin(\frac{\pi}{2}) = 1$
        
    -   Point: $(\frac{\sqrt{2}}{2}, 1)$
        
-   **For $t = \frac{3\pi}{4}$:**
    
    -   $x = \sin(\frac{3\pi}{4}) = \frac{\sqrt{2}}{2}$
        
    -   $y = \sin(2 \cdot \frac{3\pi}{4}) = \sin(\frac{3\pi}{2}) = -1$
        
    -   Point: $(\frac{\sqrt{2}}{2}, -1)$
        

**Step 4: Assign $P_1$ and $P_2$.**

The problem states: _"let $P_1$ be the point with lowest y-coordinate."_

-   $P_1$ is $(\frac{\sqrt{2}}{2}, -1)$.
    
-   $P_2$ is $(\frac{\sqrt{2}}{2}, 1)$.
    

**Answer Part A:**

-   **$x$-coordinate $P_1$:** $\sqrt{2}/2$
    
-   **$y$-coordinate $P_1$:** $-1$
    
-   **$x$-coordinate $P_2$:** $\sqrt{2}/2$
    
-   **$y$-coordinate $P_2$:** $1$
    



### **Part B: Point $Q$ (Parallel to y-axis)**

**Concept:**

The object moves parallel to the y-axis when the horizontal velocity is zero (the tangent is vertical).

Condition: $x'(t) = 0$ (and $y'(t) \neq 0$).

**Step 1: Solve $x'(t) = 0$.**

$$\cos(t) = 0$$

In the domain $0 \le t \le \pi$, the only solution is:

$$t = \frac{\pi}{2}$$

**Step 2: Find Coordinates.**

-   $x = \sin(\frac{\pi}{2}) = 1$
    
-   $y = \sin(2 \cdot \frac{\pi}{2}) = \sin(\pi) = 0$
    

**Answer Part B:**

-   **$x$-coordinate $Q$:** $1$
    
-   **$y$-coordinate $Q$:** $0$
    



### **Part C: Calculate Speed**

**Concept:**

Speed is the magnitude of the velocity vector:

$$\text{Speed} = \sqrt{(x'(t))^2 + (y'(t))^2}$$

**Step 1: Identify $t$ for point $(\frac{1}{2}, \frac{1}{2}\sqrt{3})$.**

-   $x(t) = \sin(t) = \frac{1}{2}$. In the domain $[0, \pi]$, $t$ can be $\frac{\pi}{6}$ or $\frac{5\pi}{6}$.
    
-   Check $y(t)$:
    
    -   If $t = \frac{\pi}{6}$, $y = \sin(2 \cdot \frac{\pi}{6}) = \sin(\frac{\pi}{3}) = \frac{\sqrt{3}}{2}$. (Matches $\frac{1}{2}\sqrt{3}$).
        
    -   If $t = \frac{5\pi}{6}$, $y = \sin(\frac{5\pi}{3}) = -\frac{\sqrt{3}}{2}$. (Does not match).
        
-   So, we use **$t = \frac{\pi}{6}$**.
    

**Step 2: Calculate derivative values at $t = \frac{\pi}{6}$.**

-   $x'(\frac{\pi}{6}) = \cos(\frac{\pi}{6}) = \frac{\sqrt{3}}{2}$
    
-   $y'(\frac{\pi}{6}) = 2\cos(\frac{\pi}{3}) = 2(\frac{1}{2}) = 1$
    

**Step 3: Calculate Speed.**

$$\text{Speed} = \sqrt{\left(\frac{\sqrt{3}}{2}\right)^2 + (1)^2}$$

$$\text{Speed} = \sqrt{\frac{3}{4} + 1}$$

$$\text{Speed} = \sqrt{\frac{7}{4}} = \frac{\sqrt{7}}{2}$$

**Answer Part C:**

-   **speed:** $\frac{\sqrt{7}}{2}$




<!--stackedit_data:
eyJoaXN0b3J5IjpbMzEzMTMxMzI4XX0=
-->