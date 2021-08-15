### Function
A relation that assigns every element in the Domain (x, input, independent variable, abscissa) 
to a unique element in the Range (y, output, dependent variable, ordinate).
^a8cf35

  ### Interval notation
  Used to denote a continuous interval. For instance, to denote the interval from 0 (inclusive) to infinity, the interval notation representation can be written like so:$$[0,\infty)$$ The distinction between square brackets and parentheses is that square brackets denote numbers included in the interval, while parentheses exclude the number. Different intervals can be joined with the $\cup$ (union) symbol like so: $$[-1,1]\hspace{1mm}\cup\hspace{1mm}[2,\infty)$$ *(This denotes an interval from -1 –> 1 (inclusive), and 2 –> $\infty$ combined.*
   ^ddac6c
   
   ### Set Notation
   Used to denote a set of solutions. Uses a logical approach to defining the set. As all sets, it is surrounded by a pair of curly braces ($\{\}$). $$$$ There are many different symbols used. An example of a set of numbers where the real number $x$ is less than 10 is written like so: $$\{x |x\in R, x<10\}$$This can be translated from left to right as "x, where x is in the set of real numbers, and x is less than 10". ^472a8b

### Continuous
This function can be drawn throughout its' entire domain such that you don't have to pick up your pencil. That is, $$\lim_{x \to a} f(x) = f(a)$$ for all inputs $a$. ^eea61d

### Discontinuity (Removable)
A discontinuity where while $\lim_{x \to a^-} f(x) =\lim_{x \to a^+} f(x)$, $f(a)$ is a different value. This is usually exemplified by a "hole", where filling in a single point in the graph renders it continuous. ^68f8a5
```ad-note
title: Example graph
<iframe src="https://www.desmos.com/calculator/juqvnxms0c?embed" width="400" height="200" style="border: 1px solid #ccc" frameborder=0></iframe>
```

### Discontinuity (Non-removable)
A discontinuity which *cannot* be filled in by adding a single point, usually exemplified by *jump* or *infinite* discontinuities. In a non-removable discontinuity, $\lim_{x \to a^-} f(x) \neq \lim_{x \to a^+} f(x)$ ^360cb2
```ad-note
title: Example graph

*This "jump" discontinuity is non-removable because adding a point to it would make it not a function.*

<iframe src="https://www.desmos.com/calculator/igu8wpbtge?embed" width="400" height="200" style="border: 1px solid #ccc" frameborder=0></iframe>
```

### Bounded

This definition is split into three seperate definitions:
`Bounded below`: There is a number that is less than or equal to every number in the range. Or formally defined as: 
$$\exists n \mid n \leq \{\forall x \mid x \in codom(f)\}$$
`Bounded above`: There is a number that is greater than or equal to every number in the range. Or formally defined as:
$$\exists n \mid n \geq \{\forall x \mid x \in codom(f)\}$$
`Bounded`: When either of the above conditions apply.
$$\exists n \mid n \not\in codom(f)$$ ^829e75

### Even function
Defined as $\forall x, f(x) = f(-x)$. These functions are symmetrical about the y-axis. ^a47077

### Odd function
Defined as $\forall x, f(-x) = -f(x)$. These functions are symmetrical about the origin. ^9284c6

   ---
   Definitions from notes by Matthew Medansky (Teacher), and Michael Karpov