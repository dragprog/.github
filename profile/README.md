<!-- Animated Header Banner — warm amber gradient -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:fffbb0,50:f7d49e,100:e8a87c&height=220&section=header&text=dragprog&fontSize=75&fontColor=0f0b05&animation=fadeIn&fontAlignY=35&desc=Systems%20%7C%20Graphics%20%7C%20Backend&descAlignY=58&descSize=18" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=3000&pause=1000&color=FFFBB0&center=true&vCenter=true&width=650&lines=High-Performance+Computing;Low-Level+Graphics+Pipelines;Distributed+Backend+Architectures;Zero-Cost+Abstractions;Systems+Engineering;Compiler+Design+%26+Toolchains" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C++-Developer-fffbb0?style=for-the-badge&logo=cplusplus&logoColor=0f0b05&labelColor=1a1408" />
  <img src="https://img.shields.io/badge/Systems-Engineer-f7d49e?style=for-the-badge&logo=linux&logoColor=0f0b05&labelColor=1a1408" />
  <img src="https://img.shields.io/badge/Graphics-Programmer-e8a87c?style=for-the-badge&logo=opengl&logoColor=0f0b05&labelColor=1a1408" />
  <img src="https://img.shields.io/github/followers/dragprog?style=for-the-badge&logo=github&labelColor=1a1408&color=fffbb0" />
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dragprog/dragprog/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dragprog/dragprog/output/github-contribution-grid-snake.svg" />
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/dragprog/dragprog/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

## 🚀 About Me

I am a passionate software engineer deeply fascinated by the intersection of **high-performance computing**, **hardware-adjacent systems**, and **scalable infrastructure**. Whether I'm micro-optimizing memory layouts, rendering real-time scenes, or architecting robust backend services, I love building software that is fast, reliable, and elegant from the metal all the way up to the cloud.

<div align="center">

| 🔭 **Currently exploring** | ⚡ **Core Philosophy** | 💬 **Ask me about** |
|:---:|:---:|:---:|
| Advanced template metaprogramming, low-level graphics pipelines, and distributed backend architectures. | Clean code, zero-cost abstractions, and writing software that respects hardware limits. | C++, systems engineering, compiler design, or custom toolchains! |

</div>

---

## 🔬 What I Actually Do

### ⚙️ Systems Engineering — Making Hardware Sing

I build software that lives as close to the metal as possible. My day-to-day involves:

- **Memory layout optimization** — Designing cache-friendly data structures, minimizing allocations, and eliminating false sharing in multi-threaded contexts. I profile cache miss rates and redesign layouts to maximize L1/L2 utilization.
- **Concurrency & parallelism** — Lock-free algorithms, thread pools, work-stealing schedulers, and NUMA-aware task distribution. I reason about memory ordering, atomics, and cache coherency protocols.
- **Zero-cost abstractions** — Heavy use of C++20/23 concepts, constexpr evaluation, and compile-time polymorphism to push as much work as possible to compile-time. If it doesn't optimize away, it doesn't ship.
- **Performance profiling** — Intel VTune, `perf`, Tracy, and custom instrumentation to find and eliminate bottlenecks at the instruction level. I read assembly to verify the compiler did what I asked.
- **Hardware integration** — Writing kernel modules and userspace drivers, interfacing with DMA engines, and understanding microarchitectural behavior: branch prediction, prefetching, out-of-order execution, and SIMD utilization.

### 🎨 Graphics Programming — Pushing Pixels with Purpose

Real-time rendering is where math meets the GPU. Here's what that looks like in practice:

- **Graphics API mastery** — **Vulkan** is my primary API. I write render passes, manage descriptor sets, optimize command buffer submission, and handle synchronization with semaphores and fences. OpenGL for legacy and rapid prototyping.
- **Shader development** — GLSL/HLSL for vertex, fragment, compute, and ray-tracing pipelines. I write physically-based shading models (Cook-Torrance, GGX), custom lighting equations, and procedural texture generation.
- **Pipeline architecture** — Deferred rendering, clustered forward shading, bindless resource management, and multi-pass post-processing chains (bloom, SSAO, tone mapping, FXAA/TAA).
- **GPU optimization** — Reducing render state changes, batching draw calls, GPU-driven rendering with indirect draws, and profiling with RenderDoc & Nsight. I optimize for occupancy and memory bandwidth, not just ALU throughput.
- **Cross-platform** — Ensuring consistent behavior across Linux (Wayland/X11), Windows, and embedded targets. Handling swapchain recreation, surface formats, and platform-specific quirks.

### ☁️ Cloud Backend Architecture — Scale Without Compromise

On the other end of the stack, I design services that handle thousands of concurrent connections without breaking a sweat:

- **High-throughput services** — Building async I/O servers using `epoll`/`kqueue`/`io_uring` in C++ and Python. Handling 100k+ concurrent connections with minimal memory overhead per connection.
- **Container orchestration** — Docker for reproducible builds, multi-stage images for minimal attack surface, and efficient layer caching. CI/CD pipelines with GitHub Actions for automated testing and deployment.
- **API design** — RESTful and gRPC APIs with strict versioning, OpenAPI specs, comprehensive load testing (k6, Locust), and backward compatibility guarantees.
- **Observability** — Structured logging (JSON), distributed tracing with OpenTelemetry, and metrics dashboards (Prometheus/Grafana). I believe you can't optimize what you can't measure.
- **Resilience patterns** — Circuit breakers, rate limiting, backpressure handling, and graceful degradation under load. Services that fail gracefully, not catastrophically.

### 🛠️ Tooling & Compiler Design — Building the Build

Beyond application code, I invest heavily in the developer experience:

- **Custom toolchains** — Clang/LLVM plugins for static analysis, source-to-source transformation tools, and custom compiler passes for domain-specific optimizations.
- **Build systems** — CMake power-user (modern target-based approach), Bazel migration expert for hermetic builds, and custom build graph optimizers to reduce incremental build times.
- **Language experimentation** — Designing small DSLs and toy compilers to explore type systems, IR generation (LLVM IR, SPIR-V), and optimization passes. Understanding how high-level code maps to machine code.
- **Scripting & automation** — Python and Bash for build orchestration, code generation, deployment pipelines, and infrastructure-as-code.

---

## 🛠️ Technical Expertise

<div align="center">

### Systems & Languages
<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=fffbb0&labelColor=1a1408" />
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=f7d49e&labelColor=1a1408" />
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=e8a87c&labelColor=1a1408" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=fffbb0&labelColor=1a1408" />
</p>

### Graphics & Low-Level
<p>
  <img src="https://img.shields.io/badge/OpenGL-555555?style=for-the-badge&logo=opengl&logoColor=f7d49e&labelColor=1a1408" />
  <img src="https://img.shields.io/badge/Vulkan-DE3163?style=for-the-badge&logo=vulkan&logoColor=e8a87c&labelColor=1a1408" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=0f0b05&labelColor=fffbb0" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=f7d49e&labelColor=1a1408" />
</p>

### Cloud & Backend
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=fffbb0&labelColor=1a1408" />
  <img src="https://img.shields.io/badge/Linux%20Server-FCC624?style=for-the-badge&logo=linux&logoColor=0f0b05&labelColor=f7d49e" />
  <img src="https://img.shields.io/badge/REST%20API-005571?style=for-the-badge&logo=postman&logoColor=e8a87c&labelColor=1a1408" />
  <img src="https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=grpc&logoColor=fffbb0&labelColor=1a1408" />
</p>

</div>

---

## 🎯 What I Focus On

<div align="center">

| ⚙️ Systems Engineering | 🎨 Graphics Programming | ☁️ Cloud Backend Architecture |
|:---:|:---:|:---:|
| Building robust, low-latency applications where every cycle and byte matters. Deep dives into memory management, concurrency models, and hardware-software integration. | Pushing pixels and harnessing the GPU. Writing shaders, managing rendering pipelines, and mastering Vulkan & OpenGL for real-time visuals. | Designing scalable, resilient, high-throughput backend services handling heavy concurrent workloads with minimal latency. |

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dragprog&show_icons=true&theme=dark&hide_border=true&bg_color=0f0b05&title_color=fffbb0&icon_color=f7d49e&text_color=f5e6c8&ring=fffbb0&border_radius=12" height="180" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dragprog&layout=compact&theme=dark&hide_border=true&bg_color=0f0b05&title_color=fffbb0&text_color=f5e6c8&border_radius=12" height="180" />
</div>

<div align="center" style="margin-top: 12px;">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dragprog&theme=dark&hide_border=true&background=0f0b05&stroke=fffbb0&ring=f7d49e&fire=e8a87c&currStreakLabel=fffbb0&sideLabels=f5e6c8&dates=b8a88a" />
</div>

---

## 📈 GitHub Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=dragprog&theme=react-dark&hide_border=true&line=fffbb0&point=f7d49e&area=true&area_color=fffbb020&bg_color=0f0b05&color=f5e6c8" />
</div>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:fffbb0,50:f7d49e,100:e8a87c&height=100&section=footer" />
</p>
