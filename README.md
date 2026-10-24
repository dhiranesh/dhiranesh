<div align="center">

<img src="./assets/inference-hero.svg" alt="Dhiranesh K M | AI research, LLM inference and GPU infrastructure" width="100%" />

<p>
  <a href="https://github.com/dhiranesh"><img src="https://img.shields.io/badge/GitHub-Profile-101827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" /></a>
  <a href="https://www.linkedin.com/in/dhiranesh-k-m-ba3a22291/"><img src="https://img.shields.io/badge/LinkedIn-Connect-101827?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn" /></a>
  <a href="mailto:dhiranesh2017@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-101827?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email" /></a>
</p>

<sub>AI Research Intern · K. S. Rangasamy College of Technology · India</sub>

</div>

---

## About

I'm a B.Tech Artificial Intelligence and Data Science student and an **AI Research Intern at IITM Pravartak Technologies Foundation**. I’m interested in building AI systems that are faster, observable, and reliable, from model serving to GPU data movement.

## Core contribution areas

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>01 / LLM inference</h3>
      Serving with <code>vLLM</code> and <code>SGLang</code>, request routing, continuous batching, scheduling, KV-cache management, and prefill/decode disaggregation.
    </td>
    <td width="50%" valign="top">
      <h3>02 / GPU infrastructure</h3>
      Multi-GPU execution, GPU utilization, PCIe peer-to-peer (P2P), RDMA, and GPU-to-GPU data movement research.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>03 / Performance engineering</h3>
      C++17, AVX2/SIMD, model optimization, profiling, and reproducible latency/throughput benchmarks.
    </td>
    <td width="50%" valign="top">
      <h3>04 / Observability & AI research</h3>
      Request tracing and metrics with the LGTM stack, plus work in computer vision, reinforcement learning, OCR, and document intelligence.
    </td>
  </tr>
</table>

## How I think about inference systems

<img src="./assets/inference-architecture.svg" alt="LLM inference architecture: requests flow through a router and scheduler to model workers and GPUs, with telemetry and GPU data movement tracked across the system" width="100%" />

My interests sit at the boundaries between **model serving, scheduling, GPU memory movement, and observability**. I like measuring how an infrastructure decision changes latency, throughput, GPU utilization, and reliability under a real workload.

## Selected engineering work

<table>
  <tr>
    <td align="center" width="33%" valign="top">
      <h2>2.4×</h2>
      <strong>Faster tokenizer encoding</strong><br />
      <sub>SIMD-accelerated Qwen3 BPE tokenizer in C++17, benchmarked against Hugging Face tokenizers.</sub>
    </td>
    <td align="center" width="33%" valign="top">
      <h2>72%</h2>
      <strong>Smaller vision model</strong><br />
      <sub>Compressed a 1.2 GB model to 340 MB using 4-bit post-training quantization for edge deployment.</sub>
    </td>
    <td align="center" width="33%" valign="top">
      <h2>~1.2K</h2>
      <strong>Requests per second</strong><br />
      <sub>Measured in an experimental LLM serving setup; results depend on workload and hardware configuration.</sub>
    </td>
  </tr>
</table>

## Technology stack

<p>
  <strong>Inference & ML</strong><br />
  <img src="https://img.shields.io/badge/PyTorch-172033?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" />
  <img src="https://img.shields.io/badge/vLLM-172033?style=flat-square&logoColor=white" alt="vLLM" />
  <img src="https://img.shields.io/badge/SGLang-172033?style=flat-square&logoColor=white" alt="SGLang" />
  <img src="https://img.shields.io/badge/CUDA-172033?style=flat-square&logo=nvidia&logoColor=76B900" alt="CUDA" />
  <img src="https://img.shields.io/badge/Computer_Vision-172033?style=flat-square&logo=opencv&logoColor=white" alt="Computer vision" />
</p>
<p>
  <strong>Systems & infrastructure</strong><br />
  <img src="https://img.shields.io/badge/C%2B%2B17-172033?style=flat-square&logo=c%2B%2B&logoColor=9BD3FF" alt="C++17" />
  <img src="https://img.shields.io/badge/Python-172033?style=flat-square&logo=python&logoColor=FACC15" alt="Python" />
  <img src="https://img.shields.io/badge/Linux-172033?style=flat-square&logo=linux&logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/Docker-172033?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-172033?style=flat-square&logo=kubernetes&logoColor=326CE5" alt="Kubernetes" />
</p>
<p>
  <strong>Observability & tools</strong><br />
  <img src="https://img.shields.io/badge/Grafana-172033?style=flat-square&logo=grafana&logoColor=F46800" alt="Grafana" />
  <img src="https://img.shields.io/badge/Prometheus-172033?style=flat-square&logo=prometheus&logoColor=E6522C" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Git-172033?style=flat-square&logo=git&logoColor=F05032" alt="Git" />
  <img src="https://img.shields.io/badge/Qdrant-172033?style=flat-square&logoColor=white" alt="Qdrant" />
</p>

## 3D contribution graph

<div align="center">
  <img src="./profile-3d-contrib/profile-green-animate.svg" alt="3D GitHub contribution graph. The setup preview is replaced by your contribution graph after the workflow runs." width="100%" />
  <sub>Generated from GitHub contribution activity. The first successful workflow run replaces the setup preview with your graph.</sub>
</div>

---

<div align="center">
  <sub>Interested in efficient inference, GPU systems, and performance engineering.</sub>
</div>
