# 高效打造电信领域专用大型语言模型：TSLAM-Mini结合QLoRA技术与数字孪生数据

发布时间：2025年05月10日

`LLM应用`

> Efficient Telecom Specific LLM: TSLAM-Mini with QLoRA and Digital Twin Data

# 摘要

> 通用大型语言模型（LLMs）尽管能力出众，但在实时电信应用中表现欠佳。为解决这一问题，我们对NetoAI开发的TSLAM-Mini进行了精细微调。TSLAM-Mini是一个基于Phi-4 Mini Instruct 4B的紧凑型因果语言模型，参数量为38亿。微调使用了一个包含100,000个样本的定制数据集，涵盖网络基础、IP路由、MPLS、网络安全、自动化、OSS/BSS、RAN、移动核心、卫星通信和伦理AI等20个关键场景。数据集通过NetoAI的DigiTwin平台整理，结合了网络主题专家（SMEs）的粒度见解和权威RFC文档，通过数字孪生范式启发的仿真，捕捉高保真的网络动态。采用最先进的参数高效微调（PEFT）技术——量化低秩适配（QLoRA），显著提升了训练效率，使模型能够在资源受限的硬件上部署。我们还建立了一个基于高容量LLM（Qwen3-235B-A22B）的自动化仲裁者框架，严格评估电信应用场景中的指令遵循准确性和响应质量。实证结果表明，TSLAM-Mini在电信应用中表现出色，凸显了领域特定数据集和PEFT方法在推动智能网络管理方面的巨大潜力。

> General-purpose large language models (LLMs), despite their broad capabilities accrued from open-world data, frequently exhibit suboptimal performance when confronted with the nuanced and specialized demands inherent in real-time telecommunications applications. This investigation addresses this critical limitation through the meticulous fine-tuning of TSLAM-Mini developed by NetoAI, a compact (3.8-billion parameter) causal language model architecturally derived from Phi-4 Mini Instruct 4B. The fine-tuning regimen leverages a bespoke dataset comprising 100,000 samples, strategically engineered to address 20 pivotal telecommunications use-cases, encompassing domains such as Network Fundamentals, IP Routing, MPLS, Network Security, Automation, OSS/BSS, RAN, Mobile Core, Satellite Communications, and Ethical AI. This dataset was curated utilizing NetoAI's DigiTwin platform, enriched with granular insights from venerated network Subject Matter Experts (SMEs) and authoritative RFC documents, thereby capturing high-fidelity representations of real-world network dynamics through simulations inspired by digital twin paradigms. Employing Quantized Low-Rank Adaptation (QLoRA), a state-of-the-art Parameter Efficient Fine-Tuning (PEFT) technique, we achieved substantial training efficiency and enabled prospective deployment on resource-constrained hardware. A novel evaluation framework, predicated on a high-capacity LLM (Qwen3-235B-A22B) functioning as an automated adjudicator, was instituted to rigorously assess instruction-following fidelity and response quality across the specified telecom use-cases. Empirical results unequivocally demonstrate TSLAM-Mini's superior aptitude in telecom-centric applications, underscoring the profound efficacy of domain-specific datasets and PEFT methodologies for advancing intelligent network management.

[Arxiv](https://arxiv.org/abs/2505.07877)