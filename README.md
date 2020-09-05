Section 1.9 - Infinite Sets and the Axiom of Choice

Thm 9.1 － characterize infinite sets
(1)There exists an injective function f: Z+ -> A
(2)There exists a bijection of A with a proper subset of itself
(3) A is infinite

Proof logic:
Define a function g such that g:A -> A-{a1} （ g maps A to its proper subset,in order to show there is a bijection, note that this is impossible if A is finite) 
(This is how g looks like)

g(a(n))=a(n+1) for a(n) belong to B (skip a1 for one step) ---Implication: for all g domain, there's an unique map and given Z+ for B, B is infinite here.
g(x)=x for x belongs to A-B (no skip) ---Implication: outside of domain F, x to x -> should be bijective


  -> ->
a1 a2  a3 ... a5  x1 x2 x3..(unchange)
[-----B---------][-----A-B-----------] = [A]

Introducing f range as we are trying to prove A is infinite without using the fact that "A is infinite". f brings in property of infinite Z+. 
For all f domain(Z+) maps uniquely to an element in range A. As Z+ is countably infinite, Z+ can be mapped to A-a1 or A. 

