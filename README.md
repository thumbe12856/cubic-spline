### Cubic Spline matlab code
matlab code most reference from http://web.cecs.pdx.edu/~gerry/nmm/

matlab script example:
- data: (1, 1), (2, 3), (3, 2), (4, 4)
- The slopes at x = 1 and x = 4 are 0

```sh
$ x = [1 2 3 4]
$ y = [1 3 2 4]
$ xhat = 1.5 	% x values where interpolant is evaluated 
$ fp1 = 0 	 	% slope of f(x1)
$ fpn = 0    	% slope of f(xn)
```