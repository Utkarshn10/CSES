/*

  1,  2,  9, 10, 25, 26, 49,
  4,  3,  8, 11, 24, 27, 48,
  5,  6,  7, 12, 23, 28, 47,
 16, 15, 14, 13, 22, 29, 46,
 17, 18, 19, 20, 21, 30, 45,
 36, 35, 34, 33, 32, 31, 44,
 37, 38, 39, 40, 41, 42, 43,



 */

y > x
	y is odd  : y^2 - (x-1)
	y is even : (y-1)^2+1 + (x-1)

y < x
	x is odd  : x^2 - (x-1) - (x-y)
	x is even : (x-1)^2+1 + (x-1) + (x-y)


