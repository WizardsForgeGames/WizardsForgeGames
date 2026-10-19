# Darren Sander

GPU engineer in Tokyo. I write CUDA, PTX and HLSL for my own engine and ML projects, profile with Nsight Compute and
NvPerf, and check every optimization against a numerical reference.

### Open source

- **[sparsemma](https://github.com/WizardsForgeGames/sparsemma)** — 2:4-sparse INT8 Tensor Core GEMM for PyTorch on Windows,
  where PyTorch's own semi-structured sparsity backends don't ship. Hand-written PTX `mma.sp`, fused dequant + bias;
  1.3–1.5x faster than cuBLAS FP16 at large batch with 69% less weight memory (RTX 4090).
- **[Hunyuan3D-Tools](https://github.com/WizardsForgeGames/Hunyuan3D-Tools)** — Hunyuan3D-2.1 image-to-PBR-3D on a single
  24 GB RTX 4090 with custom INT8 Tensor Core kernels; ~80 s per model end-to-end.

These are tools I built for my own projects and share in case they're useful. They get updated when I pick them up again.

### Other work

- **Crucible** — C++/DirectX 12 voxel engine with a wavefront DXR path tracer (ReSTIR, DLSS Ray Reconstruction, NRD, SHARC)
  and GPU FLIP fluids. Private, in development since 2018.

### Interests

Graphics programming · Game engines · Game Development · Machine learning · GPU compute · CUDA and PTX kernels · Algorithmic optimization · GPU profiling · Real-time path tracing 
