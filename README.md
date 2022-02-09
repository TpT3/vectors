# Vectors
SPWN Library that adds vectors and tools to use them in GD
`0.7 ONLY (0.8 on mac when)`

# Functions (prefix `vectors.` by default):
## Main
`Vector(x: @number, y: @number)` - Returns new vector

`add(vec: [@Vector])` - Returns a sum of all input[] vectors

`sub(a: @Vector, b: @Vector)` - Substracts 2 vectors, output vector has a direction from 2nd to 1st

`mult(vec1: @Vector, multiplier)` - Multiplies vector by number or other vector

`length(vec: @Vector)` - Returns the length of the vector

`norm(vec: @Vector)` - Normalizes vector (sets the length to 1)

`isNorm(vec: @Vector)` - Returns true/false based on it's normalization

`rot(a: @Vector, b: @Vector)` - Returns the angle of vector/angle between 2 vectors

`distance(a: @Vector, b: @Vector)` - Returns the distance between 2 vectors

`dot(a: @Vector, b: @Vector)` - Returns the length of the projection of a vector onto another

## Transform
`toObj(vec: @Vector, objectID: @number)` - Transforms vector to object position & rotation

`toMove(vec: @Vector)` - Transforms vector to move trigger

`toRot(vec: @Vector)` - Transforms vector angle to rotate trigger

`formObj(object: @object)` - Transforms object to vector
