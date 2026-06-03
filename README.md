# Aviad Rossmann

**Senior ML / Systems Engineer — High-Performance Inference, ML Infrastructure, GPUs & Accelerators**

Tel Aviv District, Israel · [aviad.rossmann@gmail.com](mailto:aviad.rossmann@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aviadrossmann) · [GitHub](https://github.com/DEADC0DEx)

---

## Summary

Senior software engineer with 10+ years building high-performance systems in C/C++ and Python,
with deep hands-on experience in LLM inference and the ML infrastructure underneath it — serving,
data paths, benchmarking, and performance optimization on Linux across GPUs and accelerators.
I reshape serving architectures, eliminate systemic bottlenecks, and deliver measurable gains under
real workloads. I work fluently across the hardware/software boundary and like the messy,
undocumented problems: if it's broken I'll fix it, if it's undocumented I'll reverse it.

## Core Skills

- **Languages:** C++ (11/14/17), C, Python, C#, Bash
- **Performance:** Benchmarking & profiling (perf, py-spy), bottleneck analysis, low-latency & high-throughput systems
- **ML infrastructure:** LLM inference & serving (vLLM, OpenAI-compatible APIs), ML inference pipelines, tokenizers, model-quality evaluation
- **Systems:** Linux, distributed & scalable systems, multi-threaded / real-time systems, DMA & host-device data movement, embedded / SoC
- **Hardware:** Qualcomm AI100, GPUs, ARM Neoverse, NEON, OpenCL
- **Tooling:** Docker, OpenCV, Boost, Jinja2 code generation, QNX

## Experience

### Senior Machine Learning Engineer — NeuReality
*Jan 2026 – Present · Tel Aviv District, Israel (promoted from Senior Software Engineer, Feb 2025)*

- Senior runtime engineer for high-performance LLM inference on Qualcomm AI100 accelerators and ARM Neoverse servers.
- Profiled the serving path with perf and py-spy (CPU utilization, cache thrashing, wait states) and delivered a **17% throughput gain per server instance** — enough for an 8-core ARM Neoverse server to outperform a 128-core x86 server across 1–3 concurrent instances.
- Designed and implemented **DMA-based buffer integration** for the Qualcomm AI100, cutting host-device transfer overhead and inference latency.
- Implemented changes to an internal vLLM fork and its OpenAI-compatible server, reshaping how inference requests are served end to end.
- Led system-wide performance investigations across hardware pipelines and tokenizer stages; benchmarked alternatives, selected a more efficient tokenizer, and removed preprocessing bottlenecks.

### Senior Software Engineer — LeddarTech
*Oct 2021 – Feb 2025 · Israel*

- Developed and optimized real-time ML inference workflows in C++ and Python for ADAS automotive systems.
- Designed features improving reliability and scalability; profiled and optimized GPU workloads.
- Delivered production solutions on Linux with OpenCV and embedded systems.

### SDK Lead — Zixi (Software-Defined Video Platform)
*Jan 2021 – Sep 2021 · Tel Aviv, Israel*

- Managed SDK releases and led technical partner integrations across multiple platforms.
- Built Docker build systems for cross-version Linux compatibility; optimized core C++ functionality.

### Senior Staff Software Engineer — Palo Alto Networks
*Jun 2019 – Mar 2020 · Tel Aviv, Israel*

- Built cross-platform infrastructure for enterprise endpoint security in C++14/Boost with substantial CPU and memory gains.
- Automated infrastructure and deployment workflows with Python.

### Software Engineer — Samsung Israel R&D Center (SIRC)
*Aug 2015 – May 2019 · Israel*

- Built real-time, multi-threaded C++ systems for embedded platforms.
- Optimized algorithms on ARM using NEON and OpenCL; built Python code generation with Jinja2; implemented image-processing HAL and Android camera HAL.

### Software Engineer / System Engineer — Israel Defense Forces
*2009 – 2015*

- Took multiple systems from concept to field deployment; managed rapid development across C, C++, Arduino, Android, and C#.
- Audited software across projects and supported field teams in deploying operational systems.

### Software Engineer — Elisra
*May 2011 – Aug 2013*

- C/C++ firmware and C# infrastructure; QNX OS integration and full system testing.

## Education

**B.Sc., Electrical Engineering** — Bar-Ilan University · 2005–2009

## Languages

Hebrew (Native) · English (Full Professional)
