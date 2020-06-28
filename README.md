# Voxelized3D-Rust

# Dependencies
* rust
* glfw3
* OpenGL >= 3.3.0
* cmake
* blas, lapack, lapacke

# Platforms
* tested on mac
* should(probably) work on linux without code changes provided that all depencies above are found(there may be a problem with GL though ...)
* won't work on windows without code changes (this concerns matrix libraries and GL)

![UMDC + signed field geometry](imgs/uniform_manifold_dual_contouring.png)

![UMDC + perlin noise](imgs/umdc_perlin_noise.png)

![blocky terrain + perlin noise](imgs/cubic_terrain.png)

![perlin noise minus sphere](imgs/umdc_noise_minus_sphere.png)


