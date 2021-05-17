# Figures.-Extra-Challenge

Given: class Point, abstract class Figure, skeletons of classes Triangle, Quadrilateral, Circle.

Make Triangle, Quadrilateral, Circle extend Figure class.

Implement methods in Triangle, Quadrilateral, Circle.

Given a class Point, an abstract class Figure, skeletons of classes Triangle, Quadrilateral, Circle, implement the following.
Make Triangle, Quadrilateral, Circle extend Figure class.
Implement methods in Triangle, Quadrilateral, Circle:

Constructors with following parameters:


Triangle - three vertices (points) as parameters.


Quadrilateral - four vertices (points) as parameters.


Circle - point of the center and double value of the radius.
Ensure figures are not degenerative.
All of them must have non-zero area.
Quadrilateral is also must be convex.
If a figure is not good, throw an IllegalArgumentException.
Note: A non-degenerative convex quadrilateral is divided into four non-degenerative triangles by its diagonals.
Note: double calculations are not completely accurate, use error delta, where applies.




public Point centroid()
  Return the centroid of the figure.
  Centroid refers to center of mass of the plain figure, not the baricenter.
  In other words it should be "area centroid".

public boolean isTheSame(Figure figure)
  Two figures are considered to be the same only:


if they have the same type


and if they coincide (e.g. have same vertices).
Note: order of the vertices have not to be the same.
Note: double calculations are not completely accurate, use error delta, where applies.




Note for curious: it is almost like equals() but it is not. Method equals requires consistent behavior alongside hashCode() and it is quite complicated to establish in terms of approximate equality like in this exercise
You may use main method of Figure class to tryout your code.
Hints:

Degeneracy reference
Convex quadrilateral reference
Circle centroid reference
Triangle centroid reference
Quadrilateral centroid reference
Quadrilateral centroid reference 2
