
# Image Transformations

## Similarity Transformations

This set of transformations includes scaling, translation, rotation and reflection. 

- Scaling: A linear transformation taht englarges or shinks the object by a scale factor
- Translation: A linear transformation that moves every point by the same distance in a given direction
- Rotation: A linear transformation that rotates all points about a fixed point
- Reflection: A linear transformation that reflects all points relative to a plane

Each of these transformations can be represented by a matrix. Using an affine transformation with matrices all these transformations can be representd by a single matrix multiplication.

```
s = scale
r = rotation
tx = translation[0]
ty = translation[1]
H = [[s*cos(r), -s*sin(r), tx],
     [s*sin(r), s*cos(r),  ty],
     [0.0,        0.0,    1.0]]
```