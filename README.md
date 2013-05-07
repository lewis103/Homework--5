Homework--5
===========

Crack an RSA cryptosystem by factoring a 154 digit integer.
===========================================================

(a) Show how to use Fermat's little theorem to prove that n is composite without factoring n

In order to prove that n is composite without factoring, we would need to find some number x such 
that x is not a multiple of n and a^(n-1) is not congruent to 1 mod n. In order to do this by using 
"square and multiply"

(b) Crack the RSA cryptosystem

Using the method above and your hint (I knew it had to be the next prime becuase you said NOT to do that 
in lecture 16) I found the the factor of n is
(68222080226222296181917368518534332259513625527062166102114730123514248558349) 
* (68222080226222296181917368518534332259513625527062166102114730123514248558499)

Thus p = 68222080226222296181917368518534332259513625527062166102114730123514248558349
     q = 68222080226222296181917368518534332259513625527062166102114730123514248558499


