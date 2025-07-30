# AU-LLM：增强型LLM特征融合驱动的微表情动作单元检测

发布时间：2025年07月29日

`LLM应用` `情感计算` `计算机视觉`

> AU-LLM: Micro-Expression Action Unit Detection via Enhanced LLM-Based Feature Fusion

# 摘要

> 微表情动作单元（AUs）的检测是情感计算领域的重大挑战，对解析人类微妙、非自主的情绪至关重要。尽管大型语言模型（LLMs）展现了强大的推理能力，但其在微表情AU检测这一精细且低强度领域的应用尚未被探索。本文开拓性地提出了	extbf{AU-LLM}，一个首次利用LLM检测微表情数据集中的AUs的新型框架，这些数据集具有微妙的强度和数据稀缺性。我们特别针对关键的视觉-语言语义差距，提出了	extbf{增强融合投影器（EFP）}。EFP采用多层感知机（MLP）智能融合来自专用3D-CNN主干网络的中层（局部纹理）和高层（全局语义）视觉特征，整合为一个信息密集的单一标记。这一紧凑的表示有效赋能LLM，使其能够对微妙的面部肌肉运动进行细致推理。通过在基准CASME II和SAMM数据集上的全面评估，包括严格的Leave-One-Subject-Out（LOSO）和跨域协议，AU-LLM确立了新的最先进水平，验证了基于LLM推理在微表情分析中的巨大潜力和鲁棒性。代码可在https://github.com/ZS-liu-JLU/AU-LLMs获取。

> The detection of micro-expression Action Units (AUs) is a formidable challenge in affective computing, pivotal for decoding subtle, involuntary human emotions. While Large Language Models (LLMs) demonstrate profound reasoning abilities, their application to the fine-grained, low-intensity domain of micro-expression AU detection remains unexplored. This paper pioneers this direction by introducing \textbf{AU-LLM}, a novel framework that for the first time uses LLM to detect AUs in micro-expression datasets with subtle intensities and the scarcity of data. We specifically address the critical vision-language semantic gap, the \textbf{Enhanced Fusion Projector (EFP)}. The EFP employs a Multi-Layer Perceptron (MLP) to intelligently fuse mid-level (local texture) and high-level (global semantics) visual features from a specialized 3D-CNN backbone into a single, information-dense token. This compact representation effectively empowers the LLM to perform nuanced reasoning over subtle facial muscle movements.Through extensive evaluations on the benchmark CASME II and SAMM datasets, including stringent Leave-One-Subject-Out (LOSO) and cross-domain protocols, AU-LLM establishes a new state-of-the-art, validating the significant potential and robustness of LLM-based reasoning for micro-expression analysis. The codes are available at https://github.com/ZS-liu-JLU/AU-LLMs.

[Arxiv](https://arxiv.org/abs/2507.21778)