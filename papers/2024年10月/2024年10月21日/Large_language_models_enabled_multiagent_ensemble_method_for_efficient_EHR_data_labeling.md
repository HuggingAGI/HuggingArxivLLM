# 基于大型语言模型的多智能体集成方法，实现高效的电子健康记录（EHR）数据标注

发布时间：2024年10月21日

`Agent

理由：这篇论文提出了一种基于LLMs的多智能体集成方法，用于解决数据标注问题。该方法涉及多个智能体（LLMs）的协作和集成，通过多数投票机制进行决策，这符合“Agent”分类的定义，即涉及多个智能体的协作和决策过程。虽然LLMs是核心组件，但论文的重点在于多智能体的集成和应用，而不是LLM的理论或单一应用场景。` `数据标注`

> Large language models enabled multiagent ensemble method for efficient EHR data labeling

# 摘要

> 本研究提出了一种基于LLMs的多智能体集成方法，旨在解决机器学习中的关键挑战——数据标注，尤其是大规模电子健康记录（EHR）数据集。手动标注不仅需要专业知识，还费时费力、成本高且易出错。为此，我们开发了一种集成LLMs的方法，并在两个实际任务中验证了其有效性：（1）标注MIMIC-IV中的大规模未标注心电图数据集；（2）从EHR临床笔记中识别健康的社会决定因素（SDOH）。我们精选了一组性能优异的开源LLMs，采用多数投票机制进行集成，并开发了用于EHR数据标注的集成LLMs应用。通过该方法，我们成功标注了MIMIC-IV中的623,566份心电图报告，准确率高达98.2%，并在1,405份EHR临床笔记中识别SDOH，表现优异。实验表明，集成LLMs不仅超越了单个LLM（包括最佳商业LLM），还显著减少了幻觉错误。研究发现：（1）集成LLMs大幅降低了大规模EHR数据标注的时间和成本，实现了高精度自动化；（2）该方法在SDOH识别等文本标注任务中表现出良好的泛化能力；（3）多样化LLMs的集成可超越或匹配最佳单个LLM；（4）集成方法有效减少了幻觉错误。这一方法为数据标注挑战提供了高效且可扩展的解决方案。

> This study introduces a novel multiagent ensemble method powered by LLMs to address a key challenge in ML - data labeling, particularly in large-scale EHR datasets. Manual labeling of such datasets requires domain expertise and is labor-intensive, time-consuming, expensive, and error-prone. To overcome this bottleneck, we developed an ensemble LLMs method and demonstrated its effectiveness in two real-world tasks: (1) labeling a large-scale unlabeled ECG dataset in MIMIC-IV; (2) identifying social determinants of health (SDOH) from the clinical notes of EHR. Trading off benefits and cost, we selected a pool of diverse open source LLMs with satisfactory performance. We treat each LLM's prediction as a vote and apply a mechanism of majority voting with minimal winning threshold for ensemble. We implemented an ensemble LLMs application for EHR data labeling tasks. By using the ensemble LLMs and natural language processing, we labeled MIMIC-IV ECG dataset of 623,566 ECG reports with an estimated accuracy of 98.2%. We applied the ensemble LLMs method to identify SDOH from social history sections of 1,405 EHR clinical notes, also achieving competitive performance. Our experiments show that the ensemble LLMs can outperform individual LLM even the best commercial one, and the method reduces hallucination errors. From the research, we found that (1) the ensemble LLMs method significantly reduces the time and effort required for labeling large-scale EHR data, automating the process with high accuracy and quality; (2) the method generalizes well to other text data labeling tasks, as shown by its application to SDOH identification; (3) the ensemble of a group of diverse LLMs can outperform or match the performance of the best individual LLM; and (4) the ensemble method substantially reduces hallucination errors. This approach provides a scalable and efficient solution to data-labeling challenges.

[Arxiv](https://arxiv.org/abs/2410.16543)