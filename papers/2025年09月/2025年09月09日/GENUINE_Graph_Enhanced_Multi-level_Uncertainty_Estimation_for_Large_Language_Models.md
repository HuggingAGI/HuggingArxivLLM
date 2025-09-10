# GENUINE：面向大型语言模型的图增强多层次不确定性估计

发布时间：2025年09月09日

`LLM应用` `基础理论`

> GENUINE: Graph Enhanced Multi-level Uncertainty Estimation for Large Language Models

# 摘要

> 不确定性估计对提升大型语言模型（LLMs）的可靠性至关重要，在高风险应用场景中更是如此。现有方法常忽略语义依赖，仅依赖 token 级概率度量，难以捕捉生成文本中的结构关系。为此，我们提出 GENUINE——大型语言模型的图增强多级不确定性估计（Graph ENhanced mUlti-level uncertaINty Estimation for Large Language Models），这是一种结构感知框架，通过依赖解析树与层次图池化来优化不确定性量化。GENUINE 整合监督学习，能有效建模语义与结构关系，从而提升置信度评估效果。在多项 NLP 任务上的大量实验显示，GENUINE 相比基于语义熵的方法，AUROC 提升最高达 29%，校准误差减少超 15%，充分验证了基于图的不确定性建模的有效性。代码已开源，地址为 https://github.com/ODYSSEYWT/GUQ。

> Uncertainty estimation is essential for enhancing the reliability of Large Language Models (LLMs), particularly in high-stakes applications. Existing methods often overlook semantic dependencies, relying on token-level probability measures that fail to capture structural relationships within the generated text. We propose GENUINE: Graph ENhanced mUlti-level uncertaINty Estimation for Large Language Models, a structure-aware framework that leverages dependency parse trees and hierarchical graph pooling to refine uncertainty quantification. By incorporating supervised learning, GENUINE effectively models semantic and structural relationships, improving confidence assessments. Extensive experiments across NLP tasks show that GENUINE achieves up to 29% higher AUROC than semantic entropy-based approaches and reduces calibration errors by over 15%, demonstrating the effectiveness of graph-based uncertainty modeling. The code is available at https://github.com/ODYSSEYWT/GUQ.

[Arxiv](https://arxiv.org/abs/2509.07925)