# 大型语言模型能理解隐性文化价值吗？用CQ-Bench评估LLMs的文化智能能力

发布时间：2025年04月01日

`LLM应用` `跨文化交流` `文化价值观`

> Can LLMs Grasp Implicit Cultural Values? Benchmarking LLMs' Metacognitive Cultural Intelligence with CQ-Bench

# 摘要

> 文化智力（CQ）是指理解不同文化背景的能力，这对大型语言模型（LLMs）与全球用户有效沟通至关重要。现有研究多关注显性文化规范，却忽视了潜在的隐性价值观——这些价值观在实际交流中起关键作用。为弥补这一不足，我们推出CQ-Bench，一个专为评估LLMs从自然对话中推断隐性文化价值观能力而设计的基准测试。

我们基于世界价值观调查（World Value Survey）和全球观点（GlobalOpinions）数据集中的价值观，构建了一个涵盖伦理、宗教、社会和政治等主题的多角色对话故事数据集。数据集构建流程严格，包含融入性、一致性和隐性检查，借助GPT-4o验证，最终实现98.2%的人与模型一致率。

CQ-Bench包含三个难度递增的任务：态度检测、价值观选择和价值观提取。研究发现，o1和Deepseek-R1模型在价值观选择任务中表现接近人类水平（0.809和0.814），但在细微态度检测上仍有欠缺，F1分数分别为0.622和0.635。在价值观提取任务中，GPT-4o-mini和o3-mini得分分别为0.602和0.598，凸显开放性文化推理的难度。

值得注意的是，仅使用500个文化丰富案例微调较小模型（如LLaMA-3.2-3B），性能提升超10%，甚至在某些情况下超越更强基线模型（o3-mini）。通过CQ-Bench，我们揭示了LLMs文化智力研究的当前挑战，并为提升其跨文化推理能力提供了实用方案。


> Cultural Intelligence (CQ) refers to the ability to understand unfamiliar cultural contexts-a crucial skill for large language models (LLMs) to effectively engage with globally diverse users. While existing research often focuses on explicitly stated cultural norms, such approaches fail to capture the subtle, implicit values that underlie real-world conversations. To address this gap, we introduce CQ-Bench, a benchmark specifically designed to assess LLMs' capability to infer implicit cultural values from natural conversational contexts. We generate a multi-character conversation-based stories dataset using values from the World Value Survey and GlobalOpinions datasets, with topics including ethical, religious, social, and political. Our dataset construction pipeline includes rigorous validation procedures-incorporation, consistency, and implicitness checks-using GPT-4o, with 98.2% human-model agreement in the final validation. Our benchmark consists of three tasks of increasing complexity: attitude detection, value selection, and value extraction. We find that while o1 and Deepseek-R1 models reach human-level performance in value selection (0.809 and 0.814), they still fall short in nuanced attitude detection, with F1 scores of 0.622 and 0.635, respectively. In the value extraction task, GPT-4o-mini and o3-mini score 0.602 and 0.598, highlighting the difficulty of open-ended cultural reasoning. Notably, fine-tuning smaller models (e.g., LLaMA-3.2-3B) on only 500 culturally rich examples improves performance by over 10%, even outperforming stronger baselines (o3-mini) in some cases. Using CQ-Bench, we provide insights into the current challenges in LLMs' CQ research and suggest practical pathways for enhancing LLMs' cross-cultural reasoning abilities.

[Arxiv](https://arxiv.org/abs/2504.01127)