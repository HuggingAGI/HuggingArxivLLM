# 无需标准答案反馈的大型语言模型评估：基于无监督一致性信号的智能体标注评估

发布时间：2025年09月10日

`Agent` `基础理论`

> Evaluating LLMs Without Oracle Feedback: Agentic Annotation Evaluation Through Unsupervised Consistency Signals

# 摘要

> 大型语言模型（LLMs）与提示任务结合后，大幅降低了数据标注成本及对人工标注的依赖。然而，在动态无监督环境中，由于真实反馈稀缺且传统方法失效，评估标注质量仍颇具挑战。为此，我们提出一种全新的智能体标注范式：学生模型与噪声教师（LLM）协作，无需真实反馈即可评估并优化标注质量。学生模型作为无监督反馈机制，通过基于用户偏好的多数投票策略评估LLM输出的一致性。为系统衡量LLM生成标注的可靠性，我们还提出了一致与不一致（CAI）比率——一种全新的无监督评估指标。CAI比率不仅能量化有限用户偏好下噪声教师的标注质量，还能在模型选择中发挥关键作用，助力在动态无监督环境中识别出稳健的LLMs。

> Large Language Models (LLMs), when paired with prompt-based tasks, have significantly reduced data annotation costs and reliance on human annotators. However, evaluating the quality of their annotations remains challenging in dynamic, unsupervised environments where oracle feedback is scarce and conventional methods fail. To address this challenge, we propose a novel agentic annotation paradigm, where a student model collaborates with a noisy teacher (the LLM) to assess and refine annotation quality without relying on oracle feedback. The student model, acting as an unsupervised feedback mechanism, employs a user preference-based majority voting strategy to evaluate the consistency of the LLM outputs. To systematically measure the reliability of LLM-generated annotations, we introduce the Consistent and Inconsistent (CAI) Ratio, a novel unsupervised evaluation metric. The CAI Ratio not only quantifies the annotation quality of the noisy teacher under limited user preferences but also plays a critical role in model selection, enabling the identification of robust LLMs in dynamic, unsupervised environments. Applied to ten open-domain NLP datasets across four LLMs, the CAI Ratio demonstrates a strong positive correlation with LLM accuracy, establishing it as an essential tool for unsupervised evaluation and model selection in real-world settings.

[Arxiv](https://arxiv.org/abs/2509.08809)