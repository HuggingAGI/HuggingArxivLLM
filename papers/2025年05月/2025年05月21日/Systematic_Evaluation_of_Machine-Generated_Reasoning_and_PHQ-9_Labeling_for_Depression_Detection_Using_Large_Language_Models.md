# 基于大型语言模型的抑郁症检测中机器推理与PHQ-9标签的系统性评估

发布时间：2025年05月21日

`LLM应用

理由：这篇论文探讨了大型语言模型在心理健康检测中的应用，特别是抑郁症的早期检测。研究者通过分析模型的推理能力，揭示其潜在弱点，并设计了优化策略如监督微调和直接偏好优化来提升性能。这些工作都属于将LLMs应用于特定任务，因此归类为LLM应用。` `心理健康`

> Systematic Evaluation of Machine-Generated Reasoning and PHQ-9 Labeling for Depression Detection Using Large Language Models

# 摘要

> 最近的研究利用大型语言模型（LLMs）进行抑郁症等早期心理健康检测，通常通过机器生成的数据进行优化。然而，这些模型的检测结果可能存在未知的弱点。与此同时，除了有限的人工验证外，尚未对这些生成语料库进行质量控制。我们旨在系统性地评估LLM推理能力并揭示潜在的弱点。为此，我们首先对机器生成的检测和解释推理进行了系统的评估。然后，我们利用模型的推理能力探索改进性能的缓解策略。具体来说，我们做了以下工作：1. 设计了一种LLM指令策略，允许通过将任务分解为多个子任务来系统性地分析检测结果。2. 通过选择检测推理中的典型正负例子，设计对比式少样本和链式思维提示。3. 对第一步识别出的子任务进行人工标注并评估性能。4. 从少样本生成中识别出符合期望逻辑推理的人类偏好检测，并利用它们探索不同的优化策略。我们在DepTweet数据集上进行了广泛的比较，涵盖了以下子任务：1. 判断说话者是否在描述自己的抑郁症状；2. 准确检测PHQ-9症状的存在；3. 最后，检测抑郁症。统计异常值的人工验证表明，LLMs在分析和检测显式的抑郁语言方面表现出更高的准确性，而非隐式的抑郁表达。为了提升性能并减少统计偏差，我们采用了两种优化方法：监督微调（SFT）和直接偏好优化（DPO）。值得注意的是，DPO方法在性能提升方面表现显著。


> Recent research leverages large language models (LLMs) for early mental health detection, such as depression, often optimized with machine-generated data. However, their detection may be subject to unknown weaknesses. Meanwhile, quality control has not been applied to these generated corpora besides limited human verifications. Our goal is to systematically evaluate LLM reasoning and reveal potential weaknesses. To this end, we first provide a systematic evaluation of the reasoning over machine-generated detection and interpretation. Then we use the models' reasoning abilities to explore mitigation strategies for enhanced performance. Specifically, we do the following: A. Design an LLM instruction strategy that allows for systematic analysis of the detection by breaking down the task into several subtasks. B. Design contrastive few-shot and chain-of-thought prompts by selecting typical positive and negative examples of detection reasoning. C. Perform human annotation for the subtasks identified in the first step and evaluate the performance. D. Identify human-preferred detection with desired logical reasoning from the few-shot generation and use them to explore different optimization strategies. We conducted extensive comparisons on the DepTweet dataset across the following subtasks: 1. identifying whether the speaker is describing their own depression; 2. accurately detecting the presence of PHQ-9 symptoms, and 3. finally, detecting depression. Human verification of statistical outliers shows that LLMs demonstrate greater accuracy in analyzing and detecting explicit language of depression as opposed to implicit expressions of depression. Two optimization methods are used for performance enhancement and reduction of the statistic bias: supervised fine-tuning (SFT) and direct preference optimization (DPO). Notably, the DPO approach achieves significant performance improvement.

[Arxiv](https://arxiv.org/abs/2505.17119)