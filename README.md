# TopologialManifoldVisualization

## Manifolds
In topology, a Manifold is a real n-dimensional space that is homeomorphic to the Euclidean space E<sup>n</sup>. This means that one can move from a point in the manifold some distance away and still be in the manifold. Examples of n-dimensional manifolds are:
* R<sup>n</sup> coordinate systems (1-manifold)
* Circle (1-manifold)
* Torus/Donut (2-manifold)
* and more

#### Torus Construction
Anything that has a border cannot be a manifold. We can see how this works by constructing the torus 2-manifold. First we start with a square. Right now the square has four borders, so by itselfwe cannot call it a manifold at all. We can define two sets of two edges to be neighbors so that we satisfy the rule that given a point, moving from said point the new point is still in the manifold. Here we have a 2-manifold that has preserved our property of being a manifold. Note that any
2-manifold is a 2-dimensional space, so when referring to the torus we only speak of its surface, even though it may appear to be a 3-dimensional object.

#### P(R<sup>2</sup>) construction and basics of projective spaces
Quickly let us look at P(R<sup>2</sup>). R<sup>2</sup> is a 2-dimensional space that has a projective space that only consists of a 1-dimensional line. Let us define the projective space P<sup>1</sup> as y = 1 on the coordinate grid. Then lets add some points out in the 2D space of the line. Imagine we are 2D creature, our eye is at the origin looking in the positive y direction, and the y = 1 line is a wide screen 1-dimensional television. Anything past the television will intersect the television when traveling to our eye.

Now something that may not be obvious from this description is that the objects that move toward the right or left of the television to infinity will eventually wrap back to the other side of the television. Why is this? First we need to preserve the fact that if we move a point in a manifold we should still be in the manifold. The points past the television can be represented as lines that pass through the origin and the point itself. This line will intersect the television even at infinity. As the point of intersection between line and the television approaches infinity the opposite side of the line will intersect the television on the other side.

How is this a manifold? We can call this a manifold because any point on the line y = 1 can be move along the line for ever and eventually loop back around, just like a circle. Therefore the line y = 1 is a manifold and a projective space, represented as a circle where the points at infinity are equal.

#### P(R<sup>3</sup>) construction
We have a few options in representing the projective space of R<sup>3</sup>. Remember that this projective space will be a 2-manifold or a surface that has no borders. This is going to be similar to the torus in its construction and function exactly the same as our 1-dimensional television but 2-dimensional, like a real television. 

Lets start with a square again. The difference this time will be that we will put a twist in the the sides when attaching opposite sides. If we only attach one set of sides together we get what is called a modius strip. 

This strip has one side which one can notice if you follow the side all the way around the strip. This alone is not a manifold since it has a border. Once we attach the other edges as well we will have what is called a klein bottle.

Now lets address why this obscure shape is a projective space. Similar to the projective line, but we have a plane, lets call P, defined by z = 1, and call the x-axis the horizon. Now this plane P is like the greatest movie theater screen ever since it goes on forever, but remember that points at infinity are connected according to the edges in the first diagram. So lets observe what happends when a point (a line) just above the horizion approaches infinity.

We see that the point reappears below the horizon. This makes sense since the opposite side of the line is below the horizon after it passed through the origin. Since we are using the same definition as the klein bottle before construction we actually would see the same behavior tracing our finger around the klein bottle, but it would not seem so strange since everything this connected. The important thing to notice is that below the horizon everything flips orientation passing infinity. The same thing would occur in the 1-dimensional projective plane, but there is no "up" direction so orientation does not actually exist in that plane.

## The Visualization of the R<sup>4</sup>'s Projective Space, P(R<sup>4</sup>)

#### 3-manifold Torus
So far we have made surfaces that have properties that appear to have no edges. Now we will talk about 3-dimensional spaces that have no edges. Similar to constructing the 2-manifold torus, we will start with a cube and identify opposite sides of the cube to be connected.

This can be imagined by stretching one side of the cube to its opposite side, and doing this until all sides have been met. Now unlike the 2-manifold shapes, we now have a 3-dimensional space that one can move up, down, left, right, forward, and backward. To actually experience this space we have created a simulation in the form of a game. A view of the space from the outside is below. Once one reaches the edge of the cube they walk into the antipodal part of the map as defined by how the opposite edges connect.

#### P(R<sup>4</sup>)
In both lower dimensional projective spaces we saw a wrap around effect and a change of orientation when wrapping around. We can get the same properties by rotating opposite sides of the cube 180<sup>o</sup> before connecting them and this will create the change of orientation and wrap around effect, though visualizing why this occurs in this projective space requires visualizing a graph with a 4th dimension. This is not possible but the projective space can be experienced through our simulation.

## Our Simulation
This repository includes a copy of the .blend file for the visualization. To play, make sure you are in Blender Game mode and then press "P" on your keyboard with your mouse in the 3D View window.

To navigate the menu use the UP, Down, and Enter keys.

When playing, use the "W", "A", "S", "D" keys to move around and the UP, Down, Left, and Right keys to rotate the player. Pressing the Tab key will switch between the different maps in the HUD. To get back to the menu, press the "M" key.
