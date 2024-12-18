# 借助常识推理来检测讽刺中的情感不一致

发布时间：2024年12月17日

`LLM应用` `情感分析`

> Detecting Emotional Incongruity of Sarcasm by Commonsense Reasoning

# 摘要

> 这篇论文重点研究讽刺检测，旨在判别给定陈述是否传递了批评、嘲讽或其他与字面意思相反的负面情感。检测讽刺时，人类往往需要全面理解陈述中的语义，甚至借助外部常识来推断细微的不一致之处。然而，现有方法在应对复杂的现实场景时，常识推断能力不足，致使性能欠佳。为解决此问题，我们提出了一个用于讽刺检测的新颖框架——EICR，它基于常识增强进行不一致推理。具体而言，我们先是运用检索增强型大型语言模型来补充缺失但不可或缺的常识背景知识。为捕捉复杂的上下文关联，构建了依赖图，并通过图优化获得最优拓扑。还进一步引入了整合先前规则的自适应推理框架，以明确提取情感不一致的子图。为消除单词和标签间可能的虚假关系，采用对抗对比学习来增强检测器的稳健性。在五个数据集上开展的实验表明了 EICR 的有效性。

> This paper focuses on sarcasm detection, which aims to identify whether given statements convey criticism, mockery, or other negative sentiment opposite to the literal meaning. To detect sarcasm, humans often require a comprehensive understanding of the semantics in the statement and even resort to external commonsense to infer the fine-grained incongruity. However, existing methods lack commonsense inferential ability when they face complex real-world scenarios, leading to unsatisfactory performance. To address this problem, we propose a novel framework for sarcasm detection, which conducts incongruity reasoning based on commonsense augmentation, called EICR. Concretely, we first employ retrieval-augmented large language models to supplement the missing but indispensable commonsense background knowledge. To capture complex contextual associations, we construct a dependency graph and obtain the optimized topology via graph refinement. We further introduce an adaptive reasoning skeleton that integrates prior rules to extract sentiment-inconsistent subgraphs explicitly. To eliminate the possible spurious relations between words and labels, we employ adversarial contrastive learning to enhance the robustness of the detector. Experiments conducted on five datasets demonstrate the effectiveness of EICR.

[Arxiv](https://arxiv.org/abs/2412.12808)