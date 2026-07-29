# Python Learning

## Introduction

This repository aims to provide a complete introduction to the Python programming language. Python is a popular, open-source language known for its versatility and ease of use. It is used in a wide range of applications, from web development to artificial intelligence and data science. In this project, we will learn from the fundamentals to more advanced concepts through Jupyter notebooks that make understanding and hands-on practice easier.

## Description

Python is an object-oriented programming language at its core. Its class model supports advanced features such as **polymorphism**, **multiple inheritance**, and **operator overloading**. This repository is based on the official Python documentation and aims to offer clear explanations and practical examples to reinforce learning.

### Python Standard Library

The Python Standard Library is available here: https://docs.python.org/3/library/index.html, and all the documentation in this section is based on the page of python.

### Quick Reference

| Topic | What you will learn |
| --- | --- |
| Variables and Data Types | Integers, floats, strings, booleans, and complex numbers |
| Collections | Lists, tuples, dictionaries, sets, and ranges |
| Flow Control | Conditional statements, loops, and iteration |
| Functions | Reusable blocks of code with parameters and return values |
| Classes and Objects | Encapsulation, inheritance, and object-oriented design |
| Modules and Imports | Organizing code with reusable modules and packages |

| Module | Focus |
| --- | --- |
| statistics | Measures of central tendency, dispersion, and relationships |
| math | Mathematical functions and constants |
| cmath | Mathematical functions for complex numbers |

#### statistics — Mathematical statistics functions

The statistics module provides tools for descriptive analysis and statistical relationships. You can explore it here: https://docs.python.org/3/library/statistics.html

##### Measures of central tendency

| Function | Description |
| --- | --- |
| `mean()` | Arithmetic mean of the data |
| `fmean()` | Fast floating-point arithmetic mean with optional weighting |
| `geometric_mean()` | Geometric mean of the data |
| `harmonic_mean()` | Harmonic mean of the data |
| `kde()` | Estimates the probability density distribution |
| `kde_random()` | Random sampling from the KDE-generated distribution |
| `median()` | Median value of the data |
| `median_low()` | Low median value |
| `median_high()` | High median value |
| `median_grouped()` | Median for grouped data at the 50th percentile |
| `mode()` | Single mode of discrete or nominal data |
| `multimode()` | List of all modes |
| `quantiles()` | Divides data into equal-probability intervals |

##### Measures of spread

| Function | Description |
| --- | --- |
| `pstdev()` | Population standard deviation |
| `pvariance()` | Population variance |
| `stdev()` | Sample standard deviation |
| `variance()` | Sample variance |

##### Statistics for relationships between two inputs

| Function | Description |
| --- | --- |
| `covariance()` | Sample covariance for two variables |
| `correlation()` | Pearson and Spearman correlation coefficients |
| `linear_regression()` | Slope and intercept for simple linear regression |

#### math — Mathematical functions

This module provides access to common mathematical functions and constants, including those defined by the C standard.

The following functions are grouped by purpose for easier reference.

##### Number-theoretic functions

| Function | Description |
| --- | --- |
| `comb(n, k)` | Number of ways to choose `k` items from `n` without repetition and without order |
| `factorial(n)` | Factorial of `n` |
| `gcd(*integers)` | Greatest common divisor of the provided integers |
| `isqrt(n)` | Integer square root of a non-negative integer |
| `lcm(*integers)` | Least common multiple of the provided integers |
| `perm(n, k)` | Number of ways to choose `k` items from `n` with order |

##### Floating-point arithmetic

| Function | Description |
| --- | --- |
| `ceil(x)` | Smallest integer greater than or equal to `x` |
| `fabs(x)` | Absolute value of `x` |
| `floor(x)` | Largest integer less than or equal to `x` |
| `fma(x, y, z)` | Fused multiply-add: `(x * y) + z` |
| `fmod(x, y)` | Remainder of `x / y` |
| `modf(x)` | Fractional and integer parts of `x` |
| `remainder(x, y)` | Remainder of `x` with respect to `y` |
| `trunc(x)` | Integer part of `x` |

##### Floating-point manipulation

| Function | Description |
| --- | --- |
| `copysign(x, y)` | Absolute value of `x` with the sign of `y` |
| `frexp(x)` | Mantissa and exponent of `x` |
| `isclose(a, b, rel_tol, abs_tol)` | Checks whether two values are close |
| `isfinite(x)` | Checks whether `x` is finite |
| `isinf(x)` | Checks whether `x` is positive or negative infinity |
| `isnan(x)` | Checks whether `x` is a NaN |
| `ldexp(x, i)` | Computes `x * (2**i)` |
| `nextafter(x, y, steps)` | Returns the next floating-point value toward `y` |
| `ulp(x)` | Value of the least significant bit of `x` |

##### Power, exponential, and logarithmic functions

| Function | Description |
| --- | --- |
| `cbrt(x)` | Cube root of `x` |
| `exp(x)` | Exponential function |
| `exp2(x)` | Base-2 exponential function |
| `expm1(x)` | `exp(x) - 1` |
| `log(x, base)` | Logarithm of `x` to the given base |
| `log1p(x)` | Natural logarithm of `1 + x` |
| `log2(x)` | Base-2 logarithm |
| `log10(x)` | Base-10 logarithm |
| `pow(x, y)` | Power function: `x` raised to `y` |
| `sqrt(x)` | Square root of `x` |

##### Summation and product functions

| Function | Description |
| --- | --- |
| `dist(p, q)` | Euclidean distance between two points |
| `fsum(iterable)` | Sum of values in an iterable |
| `hypot(*coordinates)` | Euclidean norm of coordinates |
| `prod(iterable, start)` | Product of iterable elements with a start value |
| `sumprod(p, q)` | Sum of products from two iterables |

##### Angular conversion and trigonometric functions

| Function | Description |
| --- | --- |
| `degrees(x)` | Converts radians to degrees |
| `radians(x)` | Converts degrees to radians |
| `acos(x)` | Arc cosine |
| `asin(x)` | Arc sine |
| `atan(x)` | Arc tangent |
| `atan2(y, x)` | Arctangent of `y / x` |
| `cos(x)` | Cosine |
| `sin(x)` | Sine |
| `tan(x)` | Tangent |

##### Hyperbolic functions

| Function | Description |
| --- | --- |
| `acosh(x)` | Inverse hyperbolic cosine |
| `asinh(x)` | Inverse hyperbolic sine |
| `atanh(x)` | Inverse hyperbolic tangent |
| `cosh(x)` | Hyperbolic cosine |
| `sinh(x)` | Hyperbolic sine |
| `tanh(x)` | Hyperbolic tangent |

##### Special functions and constants

| Function / Constant | Description |
| --- | --- |
| `erf(x)` | Error function |
| `erfc(x)` | Complementary error function |
| `gamma(x)` | Gamma function |
| `lgamma(x)` | Natural logarithm of the absolute value of the gamma function |
| `pi` | Mathematical constant $\pi$ |
| `e` | Mathematical constant $e$ |
| `tau` | Mathematical constant $\tau$ |
| `inf` | Positive infinity |
| `nan` | Not a number |
#### cmath — Mathematical functions for complex numbers

This module provides access to mathematical functions for complex numbers. It is especially useful when working with complex values in Python.

##### Polar and rectangular conversions

| Function | Description |
| --- | --- |
| `phase(z)` | Returns the phase of `z` |
| `polar(z)` | Returns the representation of `z` in polar coordinates |
| `rect(r, phi)` | Returns the complex number with polar coordinates `r` and `phi` |

##### Power and logarithmic functions

| Function | Description |
| --- | --- |
| `exp(z)` | Returns $e$ raised to the power `z` |
| `log(z[, base])` | Returns the logarithm of `z` to the given base |
| `log10(z)` | Returns the base-10 logarithm of `z` |
| `sqrt(z)` | Returns the square root of `z` |

##### Trigonometric functions

| Function | Description |
| --- | --- |
| `acos(z)` | Returns the arc cosine of `z` |
| `asin(z)` | Returns the arc sine of `z` |
| `atan(z)` | Returns the arc tangent of `z` |
| `cos(z)` | Returns the cosine of `z` |
| `sin(z)` | Returns the sine of `z` |
| `tan(z)` | Returns the tangent of `z` |

##### Hyperbolic functions

| Function | Description |
| --- | --- |
| `acosh(z)` | Returns the inverse hyperbolic cosine of `z` |
| `asinh(z)` | Returns the inverse hyperbolic sine of `z` |
| `atanh(z)` | Returns the inverse hyperbolic tangent of `z` |
| `cosh(z)` | Returns the hyperbolic cosine of `z` |
| `sinh(z)` | Returns the hyperbolic sine of `z` |
| `tanh(z)` | Returns the hyperbolic tangent of `z` |

##### Classification functions

| Function | Description |
| --- | --- |
| `isfinite(z)` | Checks whether all components of `z` are finite |
| `isinf(z)` | Checks whether any component of `z` is infinite |
| `isnan(z)` | Checks whether any component of `z` is a NaN |
| `isclose(a, b, rel_tol, abs_tol)` | Checks whether two values are close |

##### Constants

| Constant | Value |
| --- | --- |
| `pi` | $\pi = 3.141592\ldots$ |
| `e` | $e = 2.718281\ldots$ |
| `tau` | $\tau = 2\pi = 6.283185\ldots$ |
| `inf` | Positive infinity |
| `infj` | Pure imaginary infinity |
| `nan` | Not a number |
| `nanj` | Pure imaginary NaN |


## Table of Contents

- **Introduction to Python**
  - Python comments
  - Basic data types in Python
    - Numbers
      - Integers
      - Floats
      - Complex numbers
    - Strings
    - Booleans
  - Collections
    - Lists
    - Tuples
    - Dictionaries
    - Range
  - Flow control
    - Conditionals
      - if
      - if/else
      - if/elif/else
    - Loops
      - while
      - for

