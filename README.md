<div align="center">

# 💫 Akash Kumar
### AI Systems & GPU Infrastructure • Low-Level Systems • Deep Learning Runtimes

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=76B900&center=true&vcenter=true&width=750&lines=High-Throughput+LLM+Serving+%26+Paged+KV-Cache+(nano-vllm);Low-Latency+Systems+%26+Bare-Metal+x86+Assembly;Deep+Learning+Infrastructure+%26+GPU+Memory+Management;Author+of+Crimson+Orbit+(IEEE+Conference+Paper))](https://github.com/akash20065ray-sys)

<p align="center">
  <a href="mailto:akash20065ray@gmail.com"><img src="https://img.shields.io/badge/Email-akash20065ray%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/akash20065ray-sys"><img src="https://img.shields.io/badge/GitHub-akash20065ray--sys-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://github.com/akash20065ray-sys/nano-vllm"><img src="https://img.shields.io/badge/Flagship-nano--vllm-76b900?style=flat-square&logo=nvidia&logoColor=white" alt="nano-vllm" /></a>
  <a href="https://akash20065ray-sys.github.io/Crimson_Orbit/"><img src="https://img.shields.io/badge/Live%20Demo-Crimson%20Orbit-crimson?style=flat-square&logo=googlechrome&logoColor=white" alt="Live Demo" /></a>
</p>

</div>

---

### 👨‍💻 About Me

I am a systems and AI infrastructure engineer focused on **GPU memory architectures**, **high-throughput LLM serving runtimes**, **low-latency computer architecture**, and **bare-metal systems programming**.

- 🚀 **AI Systems & Deep Learning**: Engineering paged memory allocators, continuous batching schedulers, and Copy-On-Write prefix caches for autoregressive transformers.
- ⚡ **Low-Level Architecture**: Bare-metal x86 firmware, bus-cycle hardware interception, and high-performance digital signal processing (DSP).
- 📜 **Research**: Author of ***Targeted Bus-Cycle Interception: A Low-Latency WebAssembly Bridge for 16-Bit Bare-Metal Audio Synthesis and Multi-Timbral Acoustic Resynthesis*** (Camera-Ready IEEE Conference Publication).
- 🔬 **Engineering Philosophy**: Building transparent, hardware-conscious systems software, measuring nanosecond-level empirical telemetry, and crafting rich observability interfaces.

---

### 🌟 Featured Flagship Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/akash20065ray-sys/nano-vllm">nano-vllm</a></h3>
      <p><b>High-Throughput Paged KV-Cache LLM Inference Engine & Memory Management Runtime</b></p>
      <ul>
        <li>🧠 <b>Paged Memory Allocation:</b> Adapts OS virtual memory paging to GPU VRAM, eliminating internal & external fragmentation.</li>
        <li>⚡ <b>Copy-On-Write (CoW) Prefix Sharing:</b> Shares immutable system prompt blocks across sessions; drops TTFT to near-zero.</li>
        <li>🔄 <b>Iteration-Level Continuous Batching:</b> Retires completed sequences dynamically on every token step, maximizing GPU compute utilization.</li>
        <li>🛡️ <b>Fault-Tolerant Preemption:</b> Gracefully evicts cold prefixes via LRU and pauses requests under 100% saturation without CUDA OOM.</li>
        <li>📊 <b>Systems Observability Matrix:</b> Real-time 2D physical VRAM block visualizer & per-request latency diagnostics HUD.</li>
      </ul>
      <p>
        <a href="https://github.com/akash20065ray-sys/nano-vllm"><b>[View Repository]</b></a> • 
        <a href="https://github.com/akash20065ray-sys/nano-vllm/blob/main/prd/system_architecture.md"><b>[Architecture Specification]</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🎵 <a href="https://github.com/akash20065ray-sys/Crimson_Orbit">Crimson Orbit</a></h3>
      <p><b>Low-Latency Bare-Metal 8086 Audio Synthesis & Acoustic Resynthesis Platform</b></p>
      <ul>
        <li>⚡ <b>11.8 ms</b> end-to-end audio latency (6.3× faster than monolithic emulators).</li>
        <li>⏱️ <b>0.889 µs</b> targeted I/O bus-cycle interceptor (PIT 8253 / PPI 61h).</li>
        <li>💾 Custom 512-byte MBR bootloader running autonomous real-mode x86 kernel.</li>
        <li>🎹 Multi-timbral acoustic resynthesis engine (Steinway Piano, Martin Guitar, Ludwig Drums).</li>
        <li>📄 Accompanied by camera-ready 6-page IEEE conference paper & Turnitin verification.</li>
      </ul>
      <p>
        <a href="https://akash20065ray-sys.github.io/Crimson_Orbit/"><b>[Live Web Studio]</b></a> • 
        <a href="https://github.com/akash20065ray-sys/Crimson_Orbit/releases/tag/v1.0.0"><b>[Download v1.0.0 Bootable FLP]</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>👁️ <a href="https://github.com/akash20065ray-sys/Argus-ML">Argus-ML</a></h3>
      <p><b>Production Machine Learning Observability & Statistical Drift Detection Engine</b></p>
      <ul>
        <li>📊 Real-time covariate and concept drift detection on streaming datasets.</li>
        <li>📈 Kolmogorov-Smirnov (KS) & Population Stability Index (PSI) testing pipelines.</li>
        <li>📉 Automated model performance degradation alerts and telemetry dash.</li>
        <li>🛡️ Zero-trust statistical guardrails for mission-critical inference pipelines.</li>
      </ul>
      <p><a href="https://github.com/akash20065ray-sys/Argus-ML"><b>[View Repository]</b></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/akash20065ray-sys/Logic_verse">Logic_verse</a></h3>
      <p><b>Interactive Discrete Logic & Digital Circuit Simulation System</b></p>
      <ul>
        <li>🔌 Gate-level dynamic propagation delays and clock phase generation.</li>
        <li>📐 Modular schematic builder with interactive truth-table verification.</li>
      </ul>
      <p><a href="https://github.com/akash20065ray-sys/Logic_verse"><b>[View Repository]</b></a></p>
    </td>
  </tr>
</table>

---

### 🛠️ Technical Arsenal & Competencies

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **AI Systems & Inference Infrastructure** | ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch%20(2.x)-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![PagedAttention](https://img.shields.io/badge/PagedAttention%20%2F%20vLLM-blueviolet?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI%20(SSE)-009688?style=flat-square&logo=fastapi&logoColor=white) ![KV-Cache](https://img.shields.io/badge/KV--Cache%20Management-informational?style=flat-square) |
| **Low-Level & Computer Architecture** | ![x86](https://img.shields.io/badge/x86%20Real--Mode%20ASM-red?style=flat-square&logo=assemblyscript&logoColor=white) ![C/C++](https://img.shields.io/badge/C%20%2F%20C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![Wasm](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white) ![MBR](https://img.shields.io/badge/MBR%20Bootloaders-333333?style=flat-square) ![PIT8253](https://img.shields.io/badge/PIT%208253%20%2F%208255-critical?style=flat-square) |
| **Machine Learning & Observability** | ![Python](https://img.shields.io/badge/Python%203.13-3776AB?style=flat-square&logo=python&logoColor=white) ![ScikitLearn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Drift](https://img.shields.io/badge/Statistical%20Drift%20Detection-critical?style=flat-square) |
| **Web & Systems Visualization** | ![JavaScript](https://img.shields.io/badge/JavaScript%20(ES6%2B)-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5%20Canvas-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/Vanilla%20CSS%20Glassmorphism-1572B6?style=flat-square&logo=css3&logoColor=white) ![SSE](https://img.shields.io/badge/Server--Sent%20Events-9333ea?style=flat-square) |
| **Tooling & Environments** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![QEMU](https://img.shields.io/badge/QEMU%20Hypervisor-FF6600?style=flat-square&logo=qemu&logoColor=white) |

</div>

---

### 📊 GitHub Activity & Telemetry

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=akash20065ray-sys&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=76b900&icon_color=76b900" alt="Akash's GitHub Stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=akash20065ray-sys&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=76b900" alt="Top Languages" width="48%" />

</div>

---

### 📜 Publications & Research Manuscripts

```bibtex
@inproceedings{crimsonorbit2026,
  author    = {Aher, Krishna and Bhargude, Sanskar and Agaldare, Ghansham and Birare, Hari and Kumar, Akash},
  title     = {Targeted Bus-Cycle Interception: A Low-Latency WebAssembly Bridge for 16-Bit Bare-Metal Audio Synthesis and Multi-Timbral Acoustic Resynthesis},
  booktitle = {Proceedings of the IEEE Conference on Computer Systems and Multidisciplinary Engineering},
  year      = {2026},
  pages     = {1--6},
  publisher = {IEEE}
}
```

<div align="center">
  <sub>Designed with precision by Akash Kumar • AI Systems & GPU Infrastructure</sub>
</div>
