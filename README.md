<!-- ===================================================== -->
<!--                JATIN MAHAJAN · PROFILE README          -->
<!-- ===================================================== -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=240&color=0:0d1117,50:1a1b26,100:7aa2f7&text=Jatin%20Mahajan&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Systems%20Programming%20%E2%80%A2%20Storage%20Engines%20%E2%80%A2%20ML%20Infrastructure&descSize=17&descAlignY=58" width="100%" alt="Jatin Mahajan banner" />
</p>

<p align="center">
  <a href="https://github.com/jatin711-debug">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=7AA2F7&center=true&vCenter=true&width=760&height=40&lines=Building+storage+engines+from+first+principles;Distributed+event+systems+%26+time-scheduled+delivery;GPU-accelerated+ML+%26+video+inference+pipelines;Rust+%E2%80%A2+Go+%E2%80%A2+C%2B%2B+%E2%80%A2+CUDA" alt="Typing animation" />
  </a>
</p>

<p align="center">
  <b>Building high-performance storage engines, distributed event systems, and GPU-accelerated ML infrastructure from first principles.</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jatin-mahajan711/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://twitter.com/jatinmahajan712"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>
  <a href="mailto:jatinmahajan711@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=jatin711-debug&label=Profile%20views&color=7aa2f7&style=flat-square" alt="Profile views" />
  <a href="https://github.com/jatin711-debug?tab=followers"><img src="https://img.shields.io/github/followers/jatin711-debug?style=flat-square&logo=github&color=7aa2f7&label=Followers" alt="Followers" /></a>
  <a href="https://github.com/jatin711-debug?tab=repositories"><img src="https://img.shields.io/badge/Focus-Rust%20%7C%20Go%20%7C%20CUDA-1a1b26?style=flat-square&labelColor=7aa2f7" alt="Focus" /></a>
</p>

<p align="center">
  <a href="#featured"><b>Featured Systems</b></a> &nbsp;•&nbsp;
  <a href="#repos"><b>Repositories</b></a> &nbsp;•&nbsp;
  <a href="#architecture"><b>Architecture</b></a> &nbsp;•&nbsp;
  <a href="#stack"><b>Toolchain</b></a> &nbsp;•&nbsp;
  <a href="#stats"><b>GitHub Stats</b></a> &nbsp;•&nbsp;
  <a href="#connect"><b>Connect</b></a>
</p>

---

<a id="featured"></a>

## ⚡ Featured Systems & Engineering

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🦀 <a href="https://github.com/jatin711-debug/TurboSupermemory">TurboSuperMemory</a></h3>
      <p><b>High-performance cognitive memory &amp; vector storage engine written in Rust &amp; CUDA.</b></p>
      <ul>
        <li><b>32× TurboQuant Compression</b>: 1M vectors in ~61 MB using Polar Fast Walsh-Hadamard Transforms (FWHT) + Lloyd-Max codebooks.</li>
        <li><b>2-Stage Hybrid Retrieval</b>: Sub-ms SIMD candidate scan + Stage-2 token MaxSim late interaction (ColBERT).</li>
        <li><b>Cognitive Graph</b>: In-memory spreading activation, ACT-R power-law decay, and NLI-based belief revision with &#36;0.00 write-time LLM cost.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
        <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
        <img src="https://img.shields.io/badge/SIMD-7aa2f7?style=flat-square" />
        <img src="https://img.shields.io/badge/PyO3-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/gRPC%20%2F%20Axum-244c5a?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🗄️ <a href="https://github.com/jatin711-debug/CronosDB">CronosDB</a></h3>
      <p><b>Timestamp-triggered pub/sub database engineered for precise time-scheduled event delivery.</b></p>
      <ul>
        <li>At-least-once delivery semantics with persistent event replay.</li>
        <li>Custom file-backed storage engine with low operational overhead.</li>
        <li>High-throughput gRPC subscriber pipeline &amp; scheduling engine.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
        <img src="https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white" />
        <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/SQLC-7aa2f7?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🩺 Medical Multimodal AI</h3>
      <p><b>Vision-language fine-tuning &amp; explainable medical imaging pipelines.</b></p>
      <ul>
        <li>Fine-tuned <b>Med-GEMMA</b> models for pneumothorax and clinical diagnosis.</li>
        <li>Attention heatmap extraction and GPU memory footprint optimization.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/Med--GEMMA-4285F4?style=flat-square&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
        <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🎥 GPU Video AI Pipelines</h3>
      <p><b>Low-latency hardware-accelerated media preprocessing and inference.</b></p>
      <ul>
        <li>Hardware-accelerated decoding/encoding via NVIDIA NVENC/NVDEC.</li>
        <li>High-throughput frame extraction for vision-language models.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white" />
        <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
        <img src="https://img.shields.io/badge/NVIDIA%20Video%20Codec%20SDK-76B900?style=flat-square&logo=nvidia&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

---

<a id="repos"></a>

## 📌 Pinned Repositories

<p align="center">
  <a href="https://github.com/jatin711-debug/TurboSupermemory">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=jatin711-debug&repo=TurboSupermemory&theme=tokyonight&hide_border=true&show_owner=false" alt="TurboSupermemory" />
  </a>
  <a href="https://github.com/jatin711-debug/CronosDB">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=jatin711-debug&repo=CronosDB&theme=tokyonight&hide_border=true&show_owner=false" alt="CronosDB" />
  </a>
</p>

---

<a id="architecture"></a>

## 🧠 Architecture at a Glance

> Click to expand the system diagrams.

<details>
<summary><b>🦀 TurboSuperMemory: retrieval &amp; cognition pipeline</b></summary>

<br/>

```mermaid
flowchart LR
    Q([Query]) --> E[Embedding]
    E --> S1["Stage 1<br/>SIMD candidate scan<br/>(sub-ms)"]
    subgraph STORE["Compressed Vector Store"]
        direction TB
        F["Polar FWHT<br/>rotation"] --> L["Lloyd-Max<br/>codebooks"] --> C["~32x compression<br/>1M vectors in ~61 MB"]
    end
    STORE -.-> S1
    S1 --> S2["Stage 2<br/>Token MaxSim<br/>(ColBERT late interaction)"]
    S2 --> G["Cognitive Graph<br/>spreading activation<br/>ACT-R decay<br/>NLI belief revision"]
    G --> R([Ranked Memories])
```

</details>

<details>
<summary><b>🗄️ CronosDB: time-scheduled event delivery</b></summary>

<br/>

```mermaid
flowchart LR
    P([Publisher]) -->|event + timestamp| API[gRPC API]
    API --> ST[("File-backed<br/>storage engine")]
    ST --> SCH["Scheduling engine<br/>timestamp trigger"]
    SCH -->|due events| SUB([gRPC Subscribers])
    SUB -->|ack| SCH
    ST -.->|replay| SUB
```

At-least-once delivery: events are persisted before dispatch and replayed until acknowledged.

</details>

<details>
<summary><b>🎥 GPU video pipeline: decode → extract → infer</b></summary>

<br/>

```mermaid
flowchart LR
    V([Video Stream]) --> D["NVDEC<br/>hardware decode"]
    D --> X["Frame extraction<br/>OpenCV / FFmpeg"]
    X --> M["Vision-language<br/>model inference"]
    M --> O([Results])
    X -.-> EN["NVENC<br/>hardware encode"]
```

</details>

---

<a id="stack"></a>

## 🧰 Core Toolchain & Technologies

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,go,cpp,python,cuda,postgres,kafka,redis,docker,kubernetes,pytorch,linux&perline=12" alt="Tech stack icons" />
</p>

| Domain | Technologies |
| :--- | :--- |
| **⚙️ Systems & Storage** | `Rust` `Go` `C++` `CUDA` `SIMD/AVX2` `PostgreSQL` `Kafka` `Redis` `SQLite` `redb` |
| **🤖 ML & Inference** | `PyTorch` `vLLM` `Triton Inference Server` `SGLang` `SentenceTransformers` `HuggingFace` |
| **🏗️ Infra & Media** | `Docker` `Kubernetes` `Linux` `gRPC` `Axum` `FFmpeg` `NVIDIA NVDEC` |

---

<a id="stats"></a>

## 📊 GitHub Stats

<p align="center">
  <img height="195" src="https://github-readme-stats.vercel.app/api?username=jatin711-debug&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" alt="GitHub stats (stars, commits, PRs, issues)" />
  <img height="195" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jatin711-debug&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=jatin711-debug&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=jatin711-debug&theme=tokyo-night&hide_border=true&area=true&radius=8" alt="Contribution activity graph" />
</p>

---

<a id="connect"></a>

## 🤝 Let's Connect

Always up for conversations about storage engines, distributed systems, GPU pipelines, and ML infrastructure.

<p align="center">
  <a href="https://www.linkedin.com/in/jatin-mahajan711/"><img src="https://img.shields.io/badge/Connect%20on-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://twitter.com/jatinmahajan712"><img src="https://img.shields.io/badge/Follow%20on-X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>
  <a href="mailto:jatinmahajan711@gmail.com"><img src="https://img.shields.io/badge/Send-an%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:7aa2f7,50:1a1b26,100:0d1117&section=footer" width="100%" alt="footer" />
</p>
