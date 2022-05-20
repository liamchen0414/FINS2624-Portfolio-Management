# Week 0

## Matrix Operation and Properties

#### Non-commutativity: 
$$AB \neq BA$$
$$A = \begin{pmatrix}0 & 1 \\
0 & 0 \end{pmatrix}
\space\space\space\space\space\space
B = \begin{pmatrix}0 & 0 \\
1 & 0 \end{pmatrix}
$$
$$
AB = \begin{pmatrix}1 & 0 \\
0 & 0 \end{pmatrix}
\space\space\space\space
AB = \begin{pmatrix}0 & 0 \\
0 & 1 \end{pmatrix}
$$

#### Distributivity
$$
{\mathbf {A} (\mathbf {B} +\mathbf {C} )=\mathbf {AB} +\mathbf {AC}}
$$

#### Product with a scalar
$$
{ c(\mathbf {AB} )=(c\mathbf {A} )\mathbf {B} \space} and {\space (\mathbf {A} \mathbf {B} )c=\mathbf {A} (\mathbf {B} c)}
$$

#### Transpose
$$
{ (\mathbf {AB} )^{\mathsf {T}}=\mathbf {B} ^{\mathsf {T}}\mathbf {A} ^{\mathsf {T}}}
$$

#### Associativity
$${ (\mathbf {AB} )\mathbf {C} =\mathbf {A} (\mathbf {BC} )}$$

#### Identity Matrix
  $$
    \mathbf {A\times I} =
    \begin{bmatrix}
         1 & 2\\
         3 & 4
    \end{bmatrix}
    \times
    \begin{bmatrix}
         1 & 0\\
         0 & 1
    \end{bmatrix}
      =
    \begin{bmatrix}
         1 & 2\\
         3 & 4
    \end{bmatrix} =
    \mathbf {I \times A}
  $$

## Random Variables
### Types of Random Variables

1. Discrete random variables: number of customers, number of accidents, etc
2. Continuous random variables: any of the points contained in an interval

### Probability Distributions

1. Discrete random variables: The probability associated with each value.
    - ${p(x) \geq 0 }$ for all values of x, and
    - ${\sum p(x) = 1 }$



2. Continuous random variables: 𝑃(${𝑎 \leq x \leq b}$), is the area under the curve between 𝑎 and 𝑏. 
    - ${f(x) \geq 0 }$ for all values of x, and
    - ${\int f(x)dx = 1 }$ 