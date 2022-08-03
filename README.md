# Calculator
A calculator that can parse written text to compute the value.

## Support constants:
- e
- π / pi
- ϕ / golden
- eulermascheroni
- apery

## Support operators:
- a + b
    > Sum of a and b.
- a - b
    > Difference of a by b.
- a * b
    > Product of a and b.
- a / b
    > Divide a by b.
- a % b
    > The remainder of the division of a by b.
- a!
    > The factorial of a.
- a°
    > Convert the angle a in degree to radian.
- a rad
    > Convert the angle a in radian to degree.

## Supported functions

### Classical operations
- abs(x)
    > The absolute value of x.
    - x: value
- floor(x)
    > Greatest integer less than or equal to x.
    - x: value
- ceil(x)
    > Lowest integer greater than or equal to x.
    - x: value
- round(x)
    > Closest integer to x.
    - x: value
- square(x)
    > x squared.
    - x: value
- sqrt(x)
    > Square root of x.
    - x: value
- root(x, n)
    > n-th root of x.
    - x: value
    - n: nth root
- pow(x, n)
    > x raised to the n.
    - x: value
    - n: raised to
- exp(x)
    > Exponential of x.
    - x: value
- ln(x)
    > Natural logarithm of x.
    - x: value
- log(x, b)
    > Logarithm of x in base b.
    - x: value
    - b: base
- factorial(x)
    > n!
    - x: value
- gamma(x)
    > The gamma function of x.
    - x: value
- lambertW(x)
    > The LambertW function of x.
    - x: value
- ilog(x, b)
    > The iterated logarithm of x in base b.
    - x: value
    - b: base
- random(a, b)
    > A random value between a and b.
    - a: min value
    - b: max value


### Statistics
- avg(...a)
    > The average of all values.
    - a: values
- avgAD(m, ...a)
    > The average of the absolute deviations from a central point m.
    - m: Measure of central tendency.
    - a: values
- median(...a)
    > The median of all values.
    - a: values
- midway(...a)
    > A value midway between the min and max of all values.
    - a: values

### Trigonometry
- sin(θ)
    - θ: angle in radian
- cos(θ)
    - θ: angle in radian
- tan(θ)
    - θ: angle in radian
- sinh(θ)
    - θ: hyperbolic angle
- cosh(θ)
    - θ: hyperbolic angle
- tanh(θ)
    - θ: hyperbolic angle
- asin(x)
    - x: sin value
- acos(x)
    - x: cos value
- atan(x)
    - x: tan value
- arsinh(x)
    - x: sinh value
- arcosh(x)
    - x: cosh value
- artanh(x)
    - x: tanh value