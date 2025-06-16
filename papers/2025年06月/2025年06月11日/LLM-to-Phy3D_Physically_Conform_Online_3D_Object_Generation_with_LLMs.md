# # LLM-to-Phy3D：基于LLMs的在线物理符合3D物体生成

发布时间：2025年06月11日

`LLM应用

论文摘要：生成式人工智能 (GenAI) 和大型语言模型 (LLMs) 的出现彻底改变了多模态数字内容创作的格局。然而，在工程设计领域的物理 AI 中，GenAI 的潜在应用仍未得到充分探索，尤其是在生成具有物理可行性的产品方面。现有 LLM-to-3D 模型缺乏物理知识，导致生成结果往往脱离现实世界的物理约束。为了解决这一问题，我们提出了 LLM-to-Phy3D，这是一种在线物理符合的 3D 对象生成方法，使现有的 LLM-to-3D 模型能够实时生成物理符合的 3D 对象。LLM-to-Phy3D 引入了一种新型的在线黑箱优化循环，通过协同的视觉和物理评估增强大型语言模型的能力。通过在迭代优化过程中提供方向性反馈，LLM-to-Phy3D 主动推动发现能够生成相对于参考对象具有更优物理性能和更高几何新颖性的 3D 产物的提示词，为 AI 驱动的生成设计做出了重大贡献。通过车辆设计优化的消融研究支持的系统评估表明，与传统 LLM-to-3D 模型相比，LLM-to-Phy3D 在生成物理符合的目标域 3D 设计方面带来了 4.5% 到 106.7% 的 LLM 性能提升。这些令人鼓舞的结果表明，LLM-to-Phy3D 在科学和工程应用中的物理 AI 中具有潜在的广泛应用前景。

LLM应用` `工程设计` `物理AI`

> LLM-to-Phy3D: Physically Conform Online 3D Object Generation with LLMs

# 摘要

> 生成式人工智能 (GenAI) 和大型语言模型 (LLMs) 的出现彻底改变了多模态数字内容创作的格局。然而，在工程设计领域的物理 AI 中，GenAI 的潜在应用仍未得到充分探索，尤其是在生成具有物理可行性的产品方面。现有 LLM-to-3D 模型缺乏物理知识，导致生成结果往往脱离现实世界的物理约束。为了解决这一问题，我们提出了 LLM-to-Phy3D，这是一种在线物理符合的 3D 对象生成方法，使现有的 LLM-to-3D 模型能够实时生成物理符合的 3D 对象。LLM-to-Phy3D 引入了一种新型的在线黑箱优化循环，通过协同的视觉和物理评估增强大型语言模型的能力。通过在迭代优化过程中提供方向性反馈，LLM-to-Phy3D 主动推动发现能够生成相对于参考对象具有更优物理性能和更高几何新颖性的 3D 产物的提示词，为 AI 驱动的生成设计做出了重大贡献。通过车辆设计优化的消融研究支持的系统评估表明，与传统 LLM-to-3D 模型相比，LLM-to-Phy3D 在生成物理符合的目标域 3D 设计方面带来了 4.5% 到 106.7% 的 LLM 性能提升。这些令人鼓舞的结果表明，LLM-to-Phy3D 在科学和工程应用中的物理 AI 中具有潜在的广泛应用前景。

> The emergence of generative artificial intelligence (GenAI) and large language models (LLMs) has revolutionized the landscape of digital content creation in different modalities. However, its potential use in Physical AI for engineering design, where the production of physically viable artifacts is paramount, remains vastly underexplored. The absence of physical knowledge in existing LLM-to-3D models often results in outputs detached from real-world physical constraints. To address this gap, we introduce LLM-to-Phy3D, a physically conform online 3D object generation that enables existing LLM-to-3D models to produce physically conforming 3D objects on the fly. LLM-to-Phy3D introduces a novel online black-box refinement loop that empowers large language models (LLMs) through synergistic visual and physics-based evaluations. By delivering directional feedback in an iterative refinement process, LLM-to-Phy3D actively drives the discovery of prompts that yield 3D artifacts with enhanced physical performance and greater geometric novelty relative to reference objects, marking a substantial contribution to AI-driven generative design. Systematic evaluations of LLM-to-Phy3D, supported by ablation studies in vehicle design optimization, reveal various LLM improvements gained by 4.5% to 106.7% in producing physically conform target domain 3D designs over conventional LLM-to-3D models. The encouraging results suggest the potential general use of LLM-to-Phy3D in Physical AI for scientific and engineering applications.

[Arxiv](https://arxiv.org/abs/2506.11148)