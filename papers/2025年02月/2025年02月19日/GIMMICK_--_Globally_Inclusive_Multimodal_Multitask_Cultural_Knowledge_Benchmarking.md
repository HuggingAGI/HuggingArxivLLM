# GIMMICK——全球包容性多模态多任务文化知识评测

发布时间：2025年02月19日

`LLM应用

理由：这篇论文主要探讨了大型视觉语言模型（LVLMs）在不同文化背景下的表现，并通过GIMMICK基准测试评估了这些模型的文化偏见、模型规模影响等因素。研究集中在模型的应用评估和文化适应性，属于LLM的应用层面研究。` `文化多样性` `人工智能`

> GIMMICK -- Globally Inclusive Multimodal Multitask Cultural Knowledge Benchmarking

# 摘要

> 大型视觉语言模型（LVLMs）因其独特的性能和广泛应用而备受关注。然而，尽管之前的研究表明这些模型在非西方语境下的表现不足，现有研究的范围仍然有限，仅涉及少数文化、少量文化方面，或在单一任务上评估了有限的模型。为了推动全球包容性的 LVLM 研究，我们推出了 GIMMICK，这是一个全面的多模态基准测试，旨在评估涵盖全球六大宏观区域、144个国家的广泛文化知识。GIMMICK 包含六个任务，这些任务基于三个新的数据集，涵盖了 728 个独特文化事件或文化层面。我们在这些数据集上评估了 20 个 LVLMs 和 11 个 LLMs，包括五种专有模型和 26 种各种规模的开源模型。我们系统地考察了（1）区域文化偏见，（2）模型规模的影响，（3）输入模态，以及（4）外部提示。分析结果显示，模型和任务中普遍存在对西方文化的偏见，并且模型规模与性能之间存在强关联。此外，多模态输入和外部地理提示显示出有效性。进一步发现，模型对有形文化方面（如食物）的了解比无形文化方面（如仪式）更丰富，并且在识别广泛的文化起源方面表现出色，但在更细微的理解上则显得力不从心。

> Large Vision-Language Models (LVLMs) have recently gained attention due to their distinctive performance and broad applicability. While it has been previously shown that their efficacy in usage scenarios involving non-Western contexts falls short, existing studies are limited in scope, covering just a narrow range of cultures, focusing exclusively on a small number of cultural aspects, or evaluating a limited selection of models on a single task only. Towards globally inclusive LVLM research, we introduce GIMMICK, an extensive multimodal benchmark designed to assess a broad spectrum of cultural knowledge across 144 countries representing six global macro-regions. GIMMICK comprises six tasks built upon three new datasets that span 728 unique cultural events or facets on which we evaluated 20 LVLMs and 11 LLMs, including five proprietary and 26 open-weight models of all sizes. We systematically examine (1) regional cultural biases, (2) the influence of model size, (3) input modalities, and (4) external cues. Our analyses reveal strong biases toward Western cultures across models and tasks and highlight strong correlations between model size and performance, as well as the effectiveness of multimodal input and external geographic cues. We further find that models have more knowledge of tangible than intangible aspects (e.g., food vs. rituals) and that they excel in recognizing broad cultural origins but struggle with a more nuanced understanding.

[Arxiv](https://arxiv.org/abs/2502.13766)