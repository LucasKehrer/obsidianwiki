Categories are the basic building blocks in Category theory. 

## Definition

A category is a collection of **objects** and **morphism**. 
For the later, we always specify a **domain** and a **codomain**. 
- For $f: X\to Y$, the domain of $f$ is $X$, the codomain is $Y$. 
- We can **compose** two morphisms  $f: X\to Y$ and $g: Y\to Z$, if the codomain of $f$ matches the domain of $g$, we then write $gf: X\to Z$. 
- For every object, there exits an identity morphism $\mathcal 1_X: X\to X$.  

## Examples

- The category of types, where:
	- objects are types like int, bool, etc.
	- objects are typed functions
- Monads, where:
	- there is one object  ${*}$ 
	- the morphisms are the "elements", i.e. all actions are unique morphism on $*$
- Groups, which are monads, where every morphism is an isomorphism

