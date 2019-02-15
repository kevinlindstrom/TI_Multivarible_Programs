#### Kevin Lindstrom 2019

Released under the MIT license:
The following programs are to be run after they are uploaded to the TI89 calculator.

You are free to use, edit, and distrubute the code located in this repository.

### main.vd.89p: Volume from Double Integral:
Input: type = 1, 2, or 3, f(x,y) = ee, bounds (i indicates min, a indicates max — you can integrate with bounds as functions)
(type 1 integrates over y first, type 2 integrates over x first, type 3 switches to polar coordinates — treat x bounds as angle in radians and y bounds as the radius)
Output: v = volume

### main.te.89p: Test Critical Points:
(store critical point and then run the program, will return the its classification, need to run the previous script first)

### main.mf.89p: Directional Derivative and Gradient:
Input: vector = uu (automatically converts to unit vector), function = ee
Output: duf = directional derivative, df = gradient

### main.mm.89p: Arc Length, Unit Tangent, Unit Normal, Unit Binormal, Curvature:
Input: Vector Function f(t) as x, y, z
Output: |r'(t)| = rptm, T(t) = tt, unit normal = n, unit binormal = bn, curvature = k
Arc Length: integrate rptm over the window for the arc (in terms of t)

