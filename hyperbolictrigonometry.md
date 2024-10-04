# Hyperbolic Triginometric Useful Properties

## Definitions:
1. **Hyperbolic Sine (sinh)**:
   $$
   \sinh(x) = \frac{e^x - e^{-x}}{2}
   $$
   
2. **Hyperbolic Cosine (cosh)**:
   $$
   \cosh(x) = \frac{e^x + e^{-x}}{2}
   $$
   
3. **Hyperbolic Tangent (tanh)**:
   $$
   \tanh(x) = \frac{\sinh(x)}{\cosh(x)} = \frac{e^x - e^{-x}}{e^x + e^{-x}}
   $$
   
4. **Hyperbolic Cotangent (coth)**:
   $$
   \coth(x) = \frac{\cosh(x)}{\sinh(x)} = \frac{e^x + e^{-x}}{e^x - e^{-x}}
   $$
   
5. **Hyperbolic Secant (sech)**:
   $$
   sech(x) = \frac{1}{\cosh(x)} = \frac{2}{e^x + e^{-x}}
   $$
   
6. **Hyperbolic Cosecant (csch)**:
   $$
   csch(x) = \frac{1}{\sinh(x)} = \frac{2}{e^x - e^{-x}}
   $$

## Basic Identities:
1. **Fundamental Identity**:
   $$
   \cosh^2(x) - \sinh^2(x) = 1
   $$
   
2. **Relationship between tanh and sech**:
   $$
   \tanh^2(x) + sech^2(x) = 1
   $$
   
3. **Relationship between coth and csch**:
   $$
   \coth^2(x) - csch^2(x) = 1
   $$

## Addition Formulas:
1. **Hyperbolic Sine Addition**:
   $$
   \sinh(x + y) = \sinh(x) \cosh(y) + \cosh(x) \sinh(y)
   $$
   
2. **Hyperbolic Cosine Addition**:
   $$
   \cosh(x + y) = \cosh(x) \cosh(y) + \sinh(x) \sinh(y)
   $$
   
3. **Hyperbolic Tangent Addition**:
   $$
   \tanh(x + y) = \frac{\tanh(x) + \tanh(y)}{1 + \tanh(x)\tanh(y)}
   $$

## Double Angle Formulas:
1. **Double Angle for sinh**:
   $$
   \sinh(2x) = 2\sinh(x)\cosh(x)
   $$
   
2. **Double Angle for cosh**:
   $$
   \cosh(2x) = \cosh^2(x) + \sinh^2(x)
   $$
   
3. **Double Angle for tanh**:
   $$
   \tanh(2x) = \frac{2\tanh(x)}{1 + \tanh^2(x)}
   $$

## Derivatives:
1. **Derivative of sinh**:
   $$
   \frac{d}{dx} \sinh(x) = \cosh(x)
   $$
   
2. **Derivative of cosh**:
   $$
   \frac{d}{dx} \cosh(x) = \sinh(x)
   $$
   
3. **Derivative of tanh**:
   $$
   \frac{d}{dx} \tanh(x) = sech^2(x)
   $$
   
4. **Derivative of coth**:
   $$
   \frac{d}{dx} \coth(x) = -csch^2(x)
   $$
   
5. **Derivative of sech**:
   $$
   \frac{d}{dx} sech(x) = -sech(x)\tanh(x)
   $$
   
6. **Derivative of csch**:
   $$
   \frac{d}{dx} csch(x) = -csch(x)\coth(x)
   $$

## Inverse Hyperbolic Functions:
1. **Inverse sinh**:
   $$
   \sinh^{-1}(x) = \ln(x + \sqrt{x^2 + 1})
   $$
   
2. **Inverse cosh**:
   $$
   \cosh^{-1}(x) = \ln(x + \sqrt{x^2 - 1})
   \quad (x \geq 1)
   $$
   
3. **Inverse tanh**:
   $$
   \tanh^{-1}(x) = \frac{1}{2} \ln\left(\frac{1 + x}{1 - x}\right)
   \quad (-1 < x < 1)
   $$
   
4. **Inverse coth**:
   $$
   \coth^{-1}(x) = \frac{1}{2} \ln\left(\frac{x + 1}{x - 1}\right)
   \quad (x > 1 \, \text{or} \, x < -1)
   $$
   
5. **Inverse sech**:
   $$
   sech^{-1}(x) = \ln\left(\frac{1 + \sqrt{1 - x^2}}{x}\right)
   \quad (0 < x \leq 1)
   $$
   
6. **Inverse csch**:
   $$
   csch^{-1}(x) = \ln\left(\frac{1}{x} + \sqrt{\frac{1}{x^2} + 1}\right)
   $$

---
## Integral Formulae
1. $$
   \int \sinh(x) \, dx = \cosh(x) + C
   $$

2. $$
   \int \cosh(x) \, dx = \sinh(x) + C
   $$

3. $$
   \int \tanh(x) \, dx = \ln|\cosh(x)| + C
   $$

4. $$
   \int \coth(x) \, dx = \ln|\sinh(x)| + C
   $$

5. $$
   \int sech(x) \, dx = 2 \, \arctan(\tanh(\frac{x}{2})) + C
   $$

6. $$
   \int csch(x) \, dx = \ln|\tanh(\frac{x}{2})| + C
   $$

7. $$
   \int sech^2(x) \, dx = \tanh(x) + C
   $$

8. $$
   \int csch^2(x) \, dx = -\coth(x) + C
   $$

9. $$
   \int \sinh^2(x) \, dx = \frac{x}{2} - \frac{\sinh(2x)}{4} + C
   $$

10. $$
    \int \cosh^2(x) \, dx = \frac{x}{2} + \frac{\sinh(2x)}{4} + C
    $$

11. $$
    \int \sinh^n(x) \, dx = \frac{1}{n} \sinh^{n-1}(x) \cosh(x) - \frac{n-1}{n} \int \sinh^{n-2}(x) \, dx
    $$

12. $$
    \int \cosh^n(x) \, dx = \frac{1}{n} \cosh^{n-1}(x) \sinh(x) + \frac{n-1}{n} \int \cosh^{n-2}(x) \, dx
    $$

---

## Some Tricky Questions To practice
---

### &#10004; Question 1:
Evaluate the following integral:
$$
\int \frac{\sinh(x)}{\cosh^2(x)} \, dx
$$

**Solution:**

We can rewrite the integrand using the identity \(\tanh(x) = \frac{\sinh(x)}{\cosh(x)}\):
$$
\frac{\sinh(x)}{\cosh^2(x)} = \frac{\tanh(x)}{\cosh(x)}
$$

Now the integral becomes:
$$
\int \frac{\tanh(x)}{\cosh(x)} \, dx
$$

Let \( u = \cosh(x) \), so that \( du = \sinh(x) \, dx \). Rewriting the integral in terms of \( u \):
$$
\int \frac{1}{u^2} \, du = -\frac{1}{u} + C
$$

Substitute back \( u = \cosh(x) \):
$$
-\frac{1}{\cosh(x)} + C
$$

Thus, the solution is:
$$
-sech(x) + C
$$

---

### &#10004; Question 2:
Evaluate the integral:
$$
\int \frac{dx}{\cosh(x) \sinh(x)}
$$

**Solution:**

We can express the integrand using a hyperbolic identity:
$$
\frac{1}{\cosh(x)\sinh(x)} = \frac{2}{\sinh(2x)}
$$

Now the integral becomes:
$$
\int \frac{2}{\sinh(2x)} \, dx
$$

This is a standard integral, and we know:
$$
\int \frac{1}{\sinh(x)} \, dx = \ln\left|\tanh\left(\frac{x}{2}\right)\right|
$$

So, applying this:
$$
2 \int \frac{1}{\sinh(2x)} \, dx = \ln\left|\tanh(x)\right| + C
$$

Thus, the solution is:
$$
\ln\left|\tanh(x)\right| + C
$$

---

### &#10004; Question 3:
Evaluate the integral:
$$
\int \tanh^2(x) \, dx
$$

**Solution:**

We start by using the identity:
$$
\tanh^2(x) = 1 - sech^2(x)
$$

Now the integral becomes:
$$
\int (1 - sech^2(x)) \, dx = \int 1 \, dx - \int sech^2(x) \, dx
$$

We know:
$$
\int 1 \, dx = x \quad \text{and} \quad \int sech^2(x) \, dx = \tanh(x)
$$

Thus, the solution is:
$$
x - \tanh(x) + C
$$

---

### &#10004; Question 4:
Evaluate the integral:
$$
\int sech(x) \tanh(x) \, dx
$$

**Solution:**

This is a straightforward integral as it follows directly from the derivative of \(\sech(x)\):
$$
\frac{d}{dx} sech(x) = -sech(x) \tanh(x)
$$

Thus, the integral is:
$$
\int sech(x) \tanh(x) \, dx = -sech(x) + C
$$

---

 ### &#10004; **Question 5:**
Evaluate the integral:
$$
\int \cosh^3(x) \, dx
$$

**Solution:**

We can rewrite \(\cosh^3(x)\) as:
$$
\cosh^3(x) = \cosh(x) \cdot \cosh^2(x)
$$
Now, use the identity:
$$
\cosh^2(x) = 1 + \sinh^2(x)
$$
This gives:
$$
\int \cosh^3(x) \, dx = \int \cosh(x)(1 + \sinh^2(x)) \, dx
$$
Now split the integral:
$$
\int \cosh^3(x) \, dx = \int \cosh(x) \, dx + \int \cosh(x) \sinh^2(x) \, dx
$$

The first integral is straightforward:
$$
\int \cosh(x) \, dx = \sinh(x)
$$

For the second integral, use the substitution \( u = \sinh(x) \), so that \( du = \cosh(x) \, dx \):
$$
\int \sinh^2(x) \cosh(x) \, dx = \int u^2 \, du = \frac{u^3}{3} = \frac{\sinh^3(x)}{3}
$$

Thus, the solution is:
$$
\sinh(x) + \frac{\sinh^3(x)}{3} + C
$$

---

&copy; 2024, &#9989; GONGO BONGO. All rights reserved ......... &#9997;

---
