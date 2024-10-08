# Lagrange Multipliers
https://medium.com/@andrew.chamberlain/a-simple-explanation-of-why-lagrange-multipliers-works-253e2cdcbf74

Here, $g(x,y)=c$ represents a constraint. That is, the variables $x,y$ must be points that satisfy the equation above.

The gradient of $g$ would give you the change in $c$ if it were to move in that direction.

There are points on the curve traced out by $g$ whose tangent space is the same as a level curve on $F$. At these points, $g$ has therefore reached a maximum because movement along level curves result in zero increase in $c$.

# The Gradient
The gradient is the generalization of the derivative to geometric objects with more than one dimension. 
Given a smooth, open domain of dimension $r$ "$U$", and a $C^1$ parameterization "$f$", onto the smooth, open domain "$V$" (which is the geometric object) also of dimension $r$, but possibly embedded within a space of higher dimension, we may define the derivative operator as:$$\nabla =v^i\partial_{u_{i}}$$
Let's look at the entire class of such functions $f$ which map onto $V$. For each point in $V$, there is exactly one point in $U$ which maps onto that point. We assume that $f$ is therefore surjective. 

, which takes $U \to V$, where both $U$ and $V$ are open sets of the same dimension