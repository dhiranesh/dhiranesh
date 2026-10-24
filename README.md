<!--
  Profile README for github.com/dhiranesh
  (GitHub only shows this on your profile if the repo is named exactly "dhiranesh/dhiranesh" and is public.)
  HTML comments like this one are invisible on GitHub; they explain the choices so you can edit safely.
-->

<div align="center">

<!-- Banner: kept your design. The tagline now matches your resume (LLM inference, GPU infrastructure, performance). -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,45:0F766E,100:0891B2&height=170&section=header&text=Dhiranesh%20K%20M&fontSize=42&fontColor=F8FAFC&fontAlignY=37&desc=AI%20and%20Deep%20Learning%20Engineer%20%7C%20LLM%20Inference%20%7C%20GPU%20Infrastructure&descAlignY=59&descSize=14&animation=twinkling" width="100%" alt="Dhiranesh K M | AI and Deep Learning Engineer, LLM Inference and GPU Infrastructure" />

<!-- Typing tagline: lines are separated by ";" and "+" is a space. "C%2B%2B" renders as C++. -->
<a href="https://readme-typing-svg.demolab.com"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=2600&pause=800&color=22D3EE&center=true&vCenter=true&width=760&height=30&lines=Serving+LLMs+with+vLLM+and+SGLang+on+Kubernetes;Building+SIMD-fast+C%2B%2B+systems+tooling;Making+AI+inference+observable+and+reliable;Open+to+ML+and+AI+infrastructure+roles" alt="Animated tagline" /></a>

<br />

<a href="https://github.com/dhiranesh"><img src="https://img.shields.io/badge/GitHub-0B1220?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<a href="https://www.linkedin.com/in/dhiranesh-k-m-ba3a22291/"><img src="https://img.shields.io/badge/LinkedIn-0B1220?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn" /></a>
<a href="mailto:dhiranesh2017@gmail.com"><img src="https://img.shields.io/badge/Email-0B1220?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email" /></a>

</div>

## About

I'm a final-year B.Tech student in Artificial Intelligence and Data Science at **K. S. Rangasamy College of Technology**, and an **AI Research Intern at IITM Pravartak Technologies Foundation**.

I work on the part of ML that starts after training: serving models fast, keeping them observable, and getting more out of the GPUs. Day to day that means running **vLLM** and **SGLang** on **Kubernetes**, tuning batching, KV-cache use and scheduling, and building the tooling to measure what actually changed.

## Highlights

<!-- Every number below comes from your own benchmarks/resume. Keep this table in sync with the resume. -->

| Area | Result |
| :-- | :-- |
| **LLM serving** (vLLM, SGLang, Kubernetes) | About **1,200 requests per second**, with KV-cache management and request batching giving **2.4x throughput** over the baseline setup; load balancing and scheduling gave roughly **2x** performance. <!-- TODO: name the baseline and the GPU/model used, then replace "the baseline setup". --> |
| **SIMD BPE tokenizer** (C++17, Qwen3) | **2.4x faster encode** and **1.9x faster decode** on average than Hugging Face tokenizers (Rust); **48 MB/s on 14 threads**; 11 of 11 unit tests match token-for-token and 1,119 documents (109 MB) round-trip losslessly. |
| **Edge computer vision** | Model compressed from **1.2 GB to 340 MB** (about 72% smaller) with 4-bit post-training quantization. |

## Focus Areas

<!-- Kept your 2x2 grid layout; wording is tighter and each cell names concrete tools. -->
<table>
  <tr>
    <td width="50%" valign="top">
      <strong>LLM inference</strong><br />
      Model serving with <code>vLLM</code> and <code>SGLang</code>, workload-aware routing, batching, SLO-aware scheduling, KV-cache management, and prefill-decode disaggregation.
    </td>
    <td width="50%" valign="top">
      <strong>GPU infrastructure</strong><br />
      Multi-GPU workflows, GPU-aware pod placement on Kubernetes, and research into PCIe peer-to-peer transfers, RDMA and GPU-to-GPU data movement.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Performance engineering</strong><br />
      C++17, AVX2 SIMD, multithreading, CUDA basics, latency and throughput benchmarking, quantization and model optimization.
    </td>
    <td width="50%" valign="top">
      <strong>Observability</strong><br />
      Request tracing, metrics, logs and dashboards for inference systems on the LGTM stack (Loki, Grafana, Tempo, Mimir).
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <strong>Applied AI</strong><br />
      Deep learning, computer vision and pose estimation, reinforcement learning, OCR, RAG and document intelligence, geospatial AI, and agentic systems.
    </td>
  </tr>
</table>

## Featured Projects

<!-- TODO: link each project name to its repository, for example [Qwen3 BPE Tokenizer](https://github.com/dhiranesh/<repo-name>). -->

| Project | What it is | Status |
| :-- | :-- | :-- |
| **SIMD-Accelerated Qwen3 BPE Tokenizer** | C++17 tokenizer with AVX2 byte classification, a thread-local arena allocator and a thread-safe design, benchmarked against Hugging Face tokenizers. | Working, benchmarked |
| **AI Inference Observability Platform** | Request tracing, metrics, analytics and alerting for a Rust scheduler/router in front of vLLM serving, deployed on the LGTM stack. | In progress |
| **AgentShield** | Framework that adjusts the trust and autonomy of Model Context Protocol (MCP) agents at run time. | Final-year project, IEEE-format manuscript |
| **AMSTER-FM** | Earth-observation foundation model with multimodal, spatio-temporal representations and reliability-aware observation routing. | Paper in preparation |
| **DOOM-Laya** | Hierarchical ViZDoom agent where the Laya System-1 model picks high-level intents and dedicated controllers execute them. | Ongoing |

## Technology Stack

<!-- Grouped by purpose instead of one long row, so a visitor can scan it. All badges use your navy colour (172554). -->
<table>
  <tr>
    <td width="22%" valign="top"><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Python-172554?style=flat-square&logo=python&logoColor=FACC15" alt="Python" />
      <img src="https://img.shields.io/badge/C%2B%2B17-172554?style=flat-square&logo=c%2B%2B&logoColor=9BD3FF" alt="C++17" />
      <img src="https://img.shields.io/badge/Rust-172554?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
      <img src="https://img.shields.io/badge/Go-172554?style=flat-square&logo=go&logoColor=00ADD8" alt="Go" />
      <img src="https://img.shields.io/badge/C-172554?style=flat-square&logo=c&logoColor=A8B9CC" alt="C" />
      <img src="https://img.shields.io/badge/SQL-172554?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>ML and LLM serving</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-172554?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" />
      <img src="https://img.shields.io/badge/TensorFlow-172554?style=flat-square&logo=tensorflow&logoColor=FF6F00" alt="TensorFlow" />
      <img src="https://img.shields.io/badge/vLLM-172554?style=flat-square&logoColor=white" alt="vLLM" />
      <img src="https://img.shields.io/badge/SGLang-172554?style=flat-square&logoColor=white" alt="SGLang" />
      <img src="https://img.shields.io/badge/CUDA-172554?style=flat-square&logo=nvidia&logoColor=76B900" alt="CUDA" />
      <img src="https://img.shields.io/badge/Ollama-172554?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
      <img src="https://img.shields.io/badge/Qdrant-172554?style=flat-square&logo=qdrant&logoColor=DC244C" alt="Qdrant" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Infrastructure and observability</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Linux-172554?style=flat-square&logo=linux&logoColor=white" alt="Linux" />
      <img src="https://img.shields.io/badge/Docker-172554?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
      <img src="https://img.shields.io/badge/Kubernetes-172554?style=flat-square&logo=kubernetes&logoColor=326CE5" alt="Kubernetes" />
      <img src="https://img.shields.io/badge/LGTM%20(Loki%20%C2%B7%20Grafana%20%C2%B7%20Tempo%20%C2%B7%20Mimir)-172554?style=flat-square&logo=grafana&logoColor=F46800" alt="LGTM stack: Loki, Grafana, Tempo, Mimir" />
      <img src="https://img.shields.io/badge/Git-172554?style=flat-square&logo=git&logoColor=F05032" alt="Git" />
    </td>
  </tr>
</table>

## Currently Exploring

<!-- Short and honest: these are research areas, not claims of finished work. -->
- Prefill-decode disaggregation: separate worker pools, KV-cache transfer and workload-aware batching
- PCIe peer-to-peer and RDMA data movement between GPUs, with benchmarks for bandwidth, latency, goodput and SLO attainment
- GPU-aware, SLO-aware scheduling for heterogeneous LLM serving on Kubernetes

## Connect

I'm open to machine learning and AI infrastructure engineering opportunities. The best way to reach me is email or LinkedIn.

<div align="center">

<a href="https://www.linkedin.com/in/dhiranesh-k-m-ba3a22291/"><img src="https://img.shields.io/badge/LinkedIn-0B1220?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn" /></a>
<a href="mailto:dhiranesh2017@gmail.com"><img src="https://img.shields.io/badge/Email-0B1220?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,45:0F766E,100:0891B2&height=90&section=footer" width="100%" alt="" />

</div>
