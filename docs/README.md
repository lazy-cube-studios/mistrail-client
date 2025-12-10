## What is Terrain and how to generate it?

- It is a `Plane Geometory Mesh` but if we use this mesh as it is, then it will not look real because real terrain is
  not ideally flat.
- So to make it look like a real one, we make it **uneven** or in technical terms we **displace** vertices of
  the same mesh.
- There could be a lot of ways in which vertices of a mesh can be displaced. Apparently I know only one way to do it
  which is `heightmap`. These are just **gray scale** images in which every pixel is mapped to the corresponding
  displacement in the mesh. Magnitude of the displacement is directly proportional to intensity of the pixel and
  direction of the displacement can be determined by shade (Lighter or Darker).

> [!IMPORTANT]
> **For this project we don't need a dynamic terrain generation, which means the whole terrain will be created in 3D
> graphics software like `Blender`**
