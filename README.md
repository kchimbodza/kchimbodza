# Kudzayi Chimbodza

**Software & AI engineer · Computer vision · IoT · Accessible, privacy-first technology**

🎓 M.S. Cyber-Physical Systems (IoT), Northeastern University, finishing **Dec 2026** (GPA 4.0) &nbsp;·&nbsp; 🛡️ CCNA &nbsp;·&nbsp; 📍 Ontario, Canada

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/kudzayichimbodza)
[![Blog](https://img.shields.io/badge/Blog-myviewsontech.com-555?logo=wordpress&logoColor=white)](https://myviewsontech.com)
![Open to work](https://img.shields.io/badge/Open%20to-full--time%20roles-2EA44F)

---

### What I do

- **Build AI that can be trusted.** At StrataVeda I built LLM pipelines where every answer must point back to its source, or it gets dropped. I also build AI agents that check their own evidence and are measured with evals.
- **Build devices that sense and help.** I work on computer vision, radar sensing and secure IoT, from firmware to cloud to phone app.
- **Design for real people.** I aim for low cost, privacy by default, and accessibility (WCAG 2.1 AA).

---

### ⭐ Featured projects

| Project | What it does | Built with |
|---|---|---|
| 🔎 **[Agentic Researcher](https://github.com/kchimbodza/agentic-researcher)** | AI agents answer research questions across hardware datasheets and papers. Every quote is checked against its page before it is used, and a person signs off. Reading the eval failures instead of buying a bigger model took Claude Haiku from **60% to 95%** on 21 test questions for about **$0.08 a run**, scoring as well as Sonnet and Opus at a fraction of the cost. **0** made-up answers, **12/12** prompt-injection attacks resisted, and a held-out question set to check the gains are not just tuned to the test. | LangGraph · MCP · Claude API · Agent evals · Ollama · LoRA fine-tuning · Docker · GitHub Actions |
| 🎥 **[AISS: Accessible AI Surveillance](https://github.com/kchimbodza/aiss-accessible-vision)** | Turns ordinary webcams and old phones into a smart CCTV network that spots intruders and texts the owner. A pretrained neural network confirms it's a person before alerting. **97% accuracy over 100 field trials.** | Python · OpenCV · Deep learning (NanoDet) · Twilio |
| 🧓 **SmartScan: Radar Fall Detection** *(M.S. capstone, in progress)* | A camera-free ceiling sensor that detects falls and alerts family caregivers. Source is private until grading; demo available on request. | ESP32-S3 · C++ · 60 GHz radar · MQTT · Firebase · Android |
| 🏭 **[Infra Topology Generator](https://github.com/kchimbodza/infra-topology-generator)** | Describe an industrial site in plain English and get a network design, checked against IEC 62443 security rules. | Python · Claude API · IEC 62443 |
| 🧠 **[Local LLM Benchmarks](https://github.com/kchimbodza/local-llm-benchmarks-arc-b390)** | Found which open-source AI models run well fully offline on a 16GB laptop GPU, with a pick for each task. Generated code was compiled and run, not just read; tuning raised prompt speed from 33 to 193 tokens/sec. | llama.cpp · Vulkan · Intel Arc · Linux |
| 🚀 **[K-Flix DevOps Pipeline](https://github.com/kchimbodza/k-flix-devops-cicd-pipeline)** | Every push is tested, scanned and deployed to Kubernetes automatically, with monitoring and Slack alerts. | GitHub Actions · ArgoCD · Terraform · AWS EKS |
| 💳 **[Fraud Detection on Kubernetes](https://github.com/kchimbodza/fintech-fraud-detection)** | A fraud-check API that scales from 1 to 5 copies under load and heals itself on a 3-node cluster. | FastAPI · Docker · k3s · HPA |
| ☁️ **[Scalable AWS Web Infrastructure](https://github.com/kchimbodza/aws-scalable-webapp-infra)** | A web stack across 3 data centres that adds servers when traffic rises, all built as code. | Terraform · AWS VPC · ALB · RDS |

<details>
<summary><b>More projects</b> (IoT, networking, testing, web)</summary>

- **[Datasheet Answer Finder](https://github.com/kchimbodza/datasheet-answer-finder)**: ask a question about a hardware datasheet and get the exact quote and page. The single-step baseline for Agentic Researcher.
- **[SmartScan Node](https://github.com/kchimbodza/smartscan-node-aws)**: the first SmartScan prototype (ESP32, AWS IoT Core, Lambda, Terraform). Husky Pitch Summit 2025 semi-finalist.
- **[Network API Test Automation](https://github.com/kchimbodza/network-api-test-automation)**: 42 automated tests for a network management API, run on every push.
- **IoT system**: [edge device](https://github.com/kchimbodza/iot-edge-device-simulation) · [gateway to cloud](https://github.com/kchimbodza/iot-gateway-cloud-bridge) · [protocol analysis with Wireshark](https://github.com/kchimbodza/iot-network-protocol-analysis)
- **Networking labs**: [ESXi homelab](https://github.com/kchimbodza/esxi-npi-lab) · [DNS server](https://github.com/kchimbodza/dns-lab-config) · [subnetting plan](https://github.com/kchimbodza/network-subnetting-lab)
- **Web apps**: [K-Flix movie app](https://github.com/kchimbodza/k-flix-react-app) · [Library app](https://github.com/kchimbodza/library-app)
- **[Visual Player](https://github.com/kchimbodza/visualplayer)**: a Linux media player for HDR video and Dolby Atmos.

</details>

---

### 💼 Experience

| Role | Where | When |
|---|---|---|
| **AI Engineer Co-op** | StrataVeda, Toronto | Jun – Aug 2026 |
| **Graduate Teaching Assistant**, IoT & Embedded Systems | Northeastern University, Toronto | Jan – Apr 2026 |
| **IT Product Security Consultant** (volunteer) | Built For Impact, Toronto | Mar – May 2025 |
| **IT Support Analyst** | Creativ Momentum, Harare | 2019 – 2024 |

---

### 🧰 Toolbox

**AI & agents:** Claude API · LangGraph multi-agent workflows · MCP servers · RAG · Agent evals & guardrails · LoRA fine-tuning (PyTorch) · Local LLMs (Ollama, llama.cpp) · OpenCV · AI coding agents (Claude Code)<br>
**Software:** Python · TypeScript · C++ · Node.js · React / Next.js · Kotlin · FastAPI · pytest<br>
**Cloud & DevOps:** AWS · Terraform · Docker · Kubernetes · GitHub Actions · ArgoCD<br>
**IoT & networks:** ESP32 · FreeRTOS · MQTT / TLS · Firebase · CCNA · IEC 62443
