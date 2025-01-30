# CHiP: 多模态LLMs的跨模态分层直接偏好优化

发布时间：2025年01月27日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）中的幻觉问题，并提出了一种新的优化方法（CHiP）来减少幻觉。论文的核心在于如何改进现有的LLM技术（特别是多模态场景下的应用），以提高模型的性能和减少幻觉。因此，这篇论文属于LLM应用领域。` `多模态学习`

> CHiP: Cross-modal Hierarchical Direct Preference Optimization for Multimodal LLMs

# 摘要

> # 摘要
尽管多模态大型语言模型（MLLMs）能力出众，但幻觉问题依然棘手。近期研究尝试通过在多模态场景中应用直接偏好优化（DPO）来缓解这一问题，利用基于文本响应的偏好对。然而，我们的表示分布分析显示，多模态DPO在图像与文本表示的对齐以及区分幻觉与非幻觉描述方面表现不佳。为此，我们提出了一种跨模态分层直接偏好优化（CHiP）来解决这些挑战。我们在DPO框架中引入了视觉偏好优化模块，使MLLMs能够同时学习文本和视觉偏好。此外，我们还提出了分层文本偏好优化模块，使模型能够在响应、段落和标记等多个粒度级别上捕捉偏好。通过定量和定性分析，我们评估了CHiP，多个基准测试的结果表明其在减少幻觉方面效果显著。在Object HalBench数据集上，CHiP在幻觉减少方面优于DPO，基于Muffin和LLaVA模型分别实现了52.7%和55.5%的相对改进。我们已公开所有数据集和代码：https://github.com/LVUGAI/CHiP。

> Multimodal Large Language Models (MLLMs) still struggle with hallucinations despite their impressive capabilities. Recent studies have attempted to mitigate this by applying Direct Preference Optimization (DPO) to multimodal scenarios using preference pairs from text-based responses. However, our analysis of representation distributions reveals that multimodal DPO struggles to align image and text representations and to distinguish between hallucinated and non-hallucinated descriptions. To address these challenges, in this work, we propose a Cross-modal Hierarchical Direct Preference Optimization (CHiP) to address these limitations. We introduce a visual preference optimization module within the DPO framework, enabling MLLMs to learn from both textual and visual preferences simultaneously. Furthermore, we propose a hierarchical textual preference optimization module that allows the model to capture preferences at multiple granular levels, including response, segment, and token levels. We evaluate CHiP through both quantitative and qualitative analyses, with results across multiple benchmarks demonstrating its effectiveness in reducing hallucinations. On the Object HalBench dataset, CHiP outperforms DPO in hallucination reduction, achieving improvements of 52.7% and 55.5% relative points based on the base model Muffin and LLaVA models, respectively. We make all our datasets and code publicly available: https://github.com/LVUGAI/CHiP.

[Arxiv](https://arxiv.org/abs/2501.16629)