<div align="center">

<a href="https://phison.ai">
  <img src="docs/Phison-logo.svg" width="260" alt="Phison" />
</a>

# AI Data Platform

### Enterprise AI infrastructure — from prototype to production

*Deploy faster · Raise GPU utilization · Cut the cost and complexity of running AI at scale*

<strong>English</strong> · <a href="README.zh-TW.md">繁體中文</a>

[Website](https://phison.ai) · [Discussions](https://github.com/AIDataPlatform/Community/discussions) · [Phison](https://www.phison.com)

[GPU Server](https://phison.ai/gpu-server/) · [Cache Server](https://phison.ai/cache-server/) · [Storage Server](https://phison.ai/storage-server/) · [HCI](https://phison.ai/hci/)

[![Website](https://img.shields.io/badge/Website-Live-f7941d?style=flat-square)](https://phison.ai)
![Made by Phison](https://img.shields.io/badge/Made_by-Phison-f7941d?style=flat-square)
![Enterprise AI](https://img.shields.io/badge/Enterprise-AI_Infrastructure-1e202c?style=flat-square)

</div>

<p align="center">
  Most organizations can build an AI prototype, but far fewer can efficiently deploy, run, and scale AI in production.<br><br>
  Phison AI Data Platform unifies infrastructure, resource management, AI middleware, and application services into a single platform,<br>
  helping organizations deploy faster, raise GPU utilization, and lower the cost and complexity of running AI at scale.
</p>

<!-- TODO: add homepage hero screenshot or GIF -->

<br>

<table>
<tr>
<td align="center" width="33%">
  <h2><strong>Day 1</strong></h2>
  <h3>Ready to Run</h3>
  <p>More than a server — a turnkey AI department, ready out of the box. Scale seamlessly from infrastructure to applications, skipping months of complex system integration.</p>
</td>
<td align="center" width="33%">
  <h2><strong>1/5</strong></h2>
  <h3>Hardware Budget</h3>
  <p>Phison's pioneering Pascari aiDAPTIV™ technology delivers secure, enterprise-grade LLM fine-tuning and inference at one-fifth the hardware cost, putting AI within reach of every organization.</p>
</td>
<td align="center" width="33%">
  <h2><strong>Anywhere</strong></h2>
  <h3>Ask AI</h3>
  <p>Your data stays in place, secure. A zero-migration architecture lets you query distributed data directly in natural language — real-time business insight with nothing to move.</p>
</td>
</tr>
</table>

---

## What solutions does Phison provide?

<table>
<tr>
<td width="67%">
  <h3>One-Stop AI Solution</h3>
  <p>Hardware, platform, AI modules, and application services unified in a single platform — no need to stitch together multiple vendors and complex technology stacks.</p>
</td>
<td align="center" width="33%">
  <img src="docs/svg-one-stop.svg" alt="One-Stop AI Solution" width="480" />
</td>
</tr>
<tr>
<td width="67%">
  <h3>Unified GPU Management</h3>
  <p>Centrally manage GPUs/XPUs across brands and generations to raise overall resource utilization and scalability.</p>
</td>
<td align="center" width="33%">
  <img src="docs/svg-gpu.svg" alt="Unified GPU Management" width="480" />
</td>
</tr>
<tr>
<td width="67%">
  <h3>Lower Deployment Cost</h3>
  <p>Delivered as a pre-integrated private AI platform, helping enterprises move from PoC to production faster.</p>
</td>
<td align="center" width="33%">
  <img src="docs/svg-deployment.svg" alt="Lower Deployment Cost" width="480" />
</td>
</tr>
</table>

---

## AI Data Platform Architecture

Enterprises can flexibly choose the hardware, AI modules, and application services that best fit their AI use cases, existing IT environment, and budget. Whether GPU/CPU servers, Cache/Storage architecture, or AI vision, speech, and inference modules — all can be freely combined and scaled, helping enterprises build a scalable, manageable, and commercially viable on-premise AI foundation at the most appropriate cost.

<p align="center">
  <img src="docs/architecture-en.svg" alt="AI Data Platform architecture" width="720" />
</p>


### Flexible Deployment from Edge to Data Center

The same platform deploys consistently from edge sites to the central data center. Scale the four layers below — compute backbone, unified control, open-source components, and AI modules — in sequence, with no need to redesign the overall architecture.

<table>
<tr>
<td width="67%">
  <h3>L4 — Reusable AI Module Layer</h3>
  <p>Production-ready vision, speech, inference, and model-lifecycle modules, spanning training and optimization through deployment and operations.</p>
</td>
<td align="center" width="33%">
  <img src="docs/svg-arch-l4.svg" alt="L4 — Reusable AI Module Layer" width="480" />
</td>
</tr>
<tr>
<td width="67%">
  <h3>L3 — Reusable Open-Source Component Layer</h3>
  <p>Curated, AI-ready open-source components (frameworks, queues, databases, and tools), hardened as a composable workflow foundation.</p>
</td>
<td align="center" width="33%">
  <img src="docs/svg-arch-l3.svg" alt="L3 — Reusable Open-Source Component Layer" width="480" />
</td>
</tr>
<tr>
<td width="67%">
  <h3>L2 — Hyper-Converged Infrastructure Software Layer</h3>
  <p>A hyper-converged control plane managing heterogeneous GPU/XPU, storage, and VMs — pooling mixed-brand, mixed-generation hardware centrally.</p>
</td>
<td align="center" width="33%">
  <img src="docs/svg-arch-l2.svg" alt="L2 — Hyper-Converged Infrastructure Software Layer" width="480" />
</td>
</tr>
<tr>
<td width="67%">
  <h3>L1 — Infrastructure Layer</h3>
  <p>Integrates GPU, CPU, cache, and storage over high-speed interconnects to form the compute and data backbone.</p>
</td>
<td align="center" width="33%">
  <img src="docs/svg-arch-l1.svg" alt="L1 — Infrastructure Layer" width="480" />
</td>
</tr>
</table>

---

## Ecosystem & Application Services

Phison AI Data Platform supports various AI software platforms and SaaS services, including customized AI applications and industry solutions co-developed with customers.

---

## Technology Spotlight — Pascari aiDAPTIV™

> **Tiered AI memory · Save VRAM · Faster inference**

aiDAPTIV Cache Memory extends effective AI memory across GPU memory, system memory, and flash storage to support larger models, longer context windows, KV cache reuse, and memory-intensive AI workloads.

<p align="center">
  <img src="docs/svg-training-compare-en.svg" alt="Traditional vs Phison aiDAPTIV training architecture" width="800" />
</p>

<table>
<tr>
<td width="33%" valign="top">
  <h3>Disaggregated AI Infrastructure</h3>
  <p>Disaggregated architecture raises the scalability and resource utilization of AI systems.</p>
</td>
<td width="33%" valign="top">
  <h3>One-Stop AI Deployment Platform</h3>
  <p>Provides a complete one-stop AI solution spanning hardware, platform, aiDAPTIV, AI modules, and SaaS applications to significantly shorten the AI adoption lifecycle.</p>
</td>
<td width="33%" valign="top">
  <h3>AI Software Ecosystem Integration</h3>
  <p>Integrates ISVs, SIs, open-source components, and AI ecosystem partners to accelerate enterprise AI commercialization and deployment.</p>
</td>
</tr>
</table>

---

## Quantifiable Technical and Business Outcomes

> Real performance gains from production deployments.

<table>
<tr><td colspan="2"><strong>Performance Metrics</strong></td></tr>
<tr>
<td width="50%">
  <h2><strong>200% UP</strong></h2>
  <h3>Concurrent User Capacity</h3>
  <p>More than 2× concurrent capacity on the same GPU cluster. Fine-grained scheduling maximizes throughput without adding GPUs.</p>
</td>
<td width="50%">
  <h2><strong>500% UP</strong></h2>
  <h3>Faster Time-to-First-Token</h3>
  <p>Cache hits replace recomputation — 5× faster and more. A cluster-shared KV cache cuts time-to-first-token immediately.</p>
</td>
</tr>
<tr><td colspan="2"><strong>Business Value</strong></td></tr>
<tr>
<td width="50%">
  <h3>Higher ROI</h3>
  <p>aiDAPTIV reduces reliance on high-end GPUs and VRAM waste, cutting cost while sustaining throughput. As demand grows, the platform scales out with no architectural redesign — keeping your initial investment productive.</p>
</td>
<td width="50%">
  <h3>Rapid Deployment</h3>
  <p>Compress traditional AI platform rollout from months to days; pre-integrated modules shorten the path from PoC to production.</p>
</td>
</tr>
</table>

---

## Storage in Place of Compute — Save Massive GPU Compute

Dedicate the GPU's precious compute to generating replies, and offload the input ingestion workload to aiDAPTIV Cache Memory. Especially under the default 32K long context window (such as multi-turn conversations and long document analysis) while maintaining a smooth experience of Time-to-First-Token (TTFT) ≤ 10.0s and throughput (TP) ≥ 20 t/s, aiDAPTIV saves 66.1% of GPU compute and increases concurrent user capacity by 295%, making your AI Agent run fuller, steadier, and more cost-effectively.

<p align="center">
  <img src="docs/svg-inference-capacity-en.svg" alt="Inference Capacity Explorer" width="800" />
</p>

---

## Who It's For

<table>
<tr>
<td width="50%">
  <h3>Large Enterprises — Mission-Critical Scale</h3>
  <p>Financial services · High-tech manufacturing · Healthcare · Government · Telecom · Large data centers</p>
</td>
<td width="50%">
  <h3>SMBs — Built for Speed</h3>
  <p>AI startups · System integrators / ISVs · SMB AI adoption · AI agent / GenAI app development</p>
</td>
</tr>
</table>

### Common Use Cases — Production-Proven

Private enterprise AI · Generative AI platforms · AI agents · RAG search · AI meeting assistants · Visual recognition · AI inference / edge computing

---
