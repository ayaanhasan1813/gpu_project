# GaussianBlur using CUDA

Using parallelized CUDA kernels integrated with OpenCV, the Gaussian blur technique is applied to reduce image noise effectively.

<img src="/balloons.png" alt="Original" height="318" />&nbsp;&nbsp;->&nbsp;&nbsp;<img src="/output.png" alt="Blurred" height="318"/> <br />

### Objectives<br />
- Convert RGBA to Array of Structures (AoS) <br />
- Apply Gaussian Blur method to each channel <br />
- Parallelize using kernels <br />
