<!-- ===================================================== -->
<!--                JATIN MAHAJAN README                   -->
<!-- ===================================================== -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0d1117&text=Jatin%20Mahajan&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Systems%20Programming%20•%20Storage%20Engines%20•%20ML%20Infrastructure&descAlignY=60&theme=tokyonight" width="100%" />
</p>

<p align="center">
  <b>Building high-performance storage engines, distributed event systems, and GPU-accelerated ML infrastructure from first principles.</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jatin-mahajan711/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="https://twitter.com/jatinmahajan712"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white"/></a>
  <a href="mailto:jatinmahajan711@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

---

### ⚡ Featured Systems & Engineering

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🦀 <a href="https://github.com/jatin711-debug/TurboSupermemory">TurboSuperMemory</a></h3>
      <p><b>High-performance cognitive memory & vector storage engine written in Rust & CUDA.</b></p>
      <ul>
        <li><b>32× TurboQuant Compression</b>: 1M vectors in ~61 MB using Polar Fast Walsh-Hadamard Transforms (FWHT) + Lloyd-Max codebooks.</li>
        <li><b>2-Stage Hybrid Retrieval</b>: Sub-ms SIMD candidate scan + Stage-2 token MaxSim late interaction (ColBERT).</li>
        <li><b>Cognitive Graph</b>: In-memory spreading activation, ACT-R power-law decay, and NLI-based belief revision with $0.00 write-time LLM cost.</li>
      </ul>
      <p><code>Rust</code> <code>CUDA</code> <code>C++</code> <code>SIMD</code> <code>PyO3</code> <code>gRPC / Axum</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>🗄️ CronosDB</h3>
      <p><b>Timestamp-triggered pub/sub database engineered for precise time-scheduled event delivery.</b></p>
      <ul>
        <li>At-least-once delivery semantics with persistent event replay.</li>
        <li>Custom file-backed storage engine with low operational overhead.</li>
        <li>High-throughput gRPC subscriber pipeline & scheduling engine.</li>
      </ul>
      <p><code>Go</code> <code>gRPC</code> <code>Kafka</code> <code>PostgreSQL</code> <code>SQLC</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🩺 Medical Multimodal AI</h3>
      <p><b>Vision-language fine-tuning & explainable medical imaging pipelines.</b></p>
      <ul>
        <li>Fine-tuned <b>Med-GEMMA</b> models for pneumothorax and clinical diagnosis.</li>
        <li>Attention heatmap extraction and GPU memory footprint optimization.</li>
      </ul>
      <p><code>PyTorch</code> <code>Med-GEMMA</code> <code>HuggingFace</code> <code>CUDA</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>🎥 GPU Video AI Pipelines</h3>
      <p><b>Low-latency hardware-accelerated media preprocessing and inference.</b></p>
      <ul>
        <li>Hardware-accelerated decoding/encoding via NVIDIA NVENC/NVDEC.</li>
        <li>High-throughput frame extraction for vision-language models.</li>
      </ul>
      <p><code>C++</code> <code>Python</code> <code>FFmpeg</code> <code>OpenCV</code> <code>NVIDIA Video Codec SDK</code></p>
    </td>
  </tr>
</table>

---

### 🧰 Core Toolchain & Technologies

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,go,cpp,python,cuda,postgres,kafka,redis,docker,kubernetes,pytorch,linux" />
</p>

```txt
• Systems & Storage : Rust, Go, C++, CUDA, SIMD/AVX2, PostgreSQL, Kafka, Redis, SQLite/redb
• ML & Inference    : PyTorch, vLLM, Triton Inference Server, SGLang, SentenceTransformers, HuggingFace
• Infra & Media     : Docker, Kubernetes, Linux, gRPC, Axum, FFmpeg, NVIDIA NVDEC
