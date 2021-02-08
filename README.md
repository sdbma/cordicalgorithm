# cordicalgorithm

# CORDIC Algorithm

[Cordic][Cordic] is a popular algorithm to calculate trigonometric functions, hyperbolic functions, square roots, multiplications, divisions, exponentials and logarithms. Cordic algorithms in present forms were first described by [Volder][Volder] in 1959.

This [notebook][notebook] is divided into the following sections:
1. Overview of Cordic Algorithm
2. Implementation of CORDIC algorithm that supports circular, hyperbolic and linear coordinate system.
3. Verification including plotting for different iterations of cordic algorithm and functional accuracy range testing.

It is assumed that the reader has basic understandings of CORDIC algorithm. The [notebook's][notebook] attempt is to implement the collection of higher level mathematical functions from the CORDIC algorithm. CORDIC algorithm are very useful when no hardware multiplier is available, (e.g. in simple microcontrollers and FPGAs), as the only operations it requires are additions, subtractions, bitshifts and lookup tables.


Please contact [Shomit Dutta](mailto:shomitdutta@gmail.com) for any follow-up on this page.



License
----
MIT

[Cordic]:<https://en.wikipedia.org/wiki/CORDIC>
[Volder]:<https://www.computer.org/csdl/proceedings-article/afips/1959/50540257/12OmNqN6QXX>
[notebook]:<https://github.com/sdbma/cordicalgorithm/blob/master/CordicAlgorithm.ipynb>
