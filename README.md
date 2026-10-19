# Hey, I'm Darren

Independent game developer in Tokyo. I'm building **Crucible**, a C++/DirectX 12 voxel engine with a real-time DXR path
tracer and GPU fluid simulation, and open-sourcing the tools I make along the way.

### Open source

- **[Forge](https://github.com/WizardsForgeGames/Forge)** — CUDA library for training and inference: fused MLP kernels,
  CUDA Graph training loop, INT8 dense / 2:4-sparse / dp4a GEMM, PyTorch extension.
- **[sparsemma](https://github.com/WizardsForgeGames/sparsemma)** — 2:4-sparse INT8 Tensor Core GEMM for PyTorch on Windows,
  where PyTorch's own semi-structured sparsity backends don't ship. Hand-written PTX `mma.sp`.
- **[Hunyuan3D-Tools](https://github.com/WizardsForgeGames/Hunyuan3D-Tools)** — Hunyuan3D-2.1 image-to-PBR-3D on a single
  24 GB RTX 4090 with custom INT8 Tensor Core kernels.
- **[FSR4All](https://github.com/WizardsForgeGames/FSR4All)** — drop-in D3D12 DLL that runs AMD's FSR4 INT8 upscaler on
  non-AMD GPUs (prototype).

These are tools I built for my own projects and share in case they're useful. They get updated when I pick them up again.

### Interests

Graphics programming · Game engines · Game development · Machine learning · GPU compute · CUDA and PTX kernels ·
Algorithmic optimization · GPU profiling · Real-time path tracing

---

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/thewizardsforge)
