# 多智能体 LLM 评估器：用于自然语言生成应用评估的自动个性化 LLM 评估器设计

发布时间：2025年04月01日

`LLM应用` `评估方法`

> Multi-Agent LLM Judge: automatic personalized LLM judge design for evaluating natural language generation applications

# 摘要

> 大型语言模型（LLMs）在多领域展现了卓越性能，但实际应用中仍面临领域知识不足、偏见及幻觉等挑战。这凸显了建立 robust 评估方法的重要性，以准确评估 LLM 应用。传统依赖词重叠或文本嵌入的方法难以捕捉动态开放文本生成的细微语义信息。近期研究探索了利用 LLM 模拟人类推理与决策过程的评估框架（LLM 作为评估者），但现有框架存在两大局限：首先，缺乏灵活性以适应不同文本风格（包括答案与真实结果风格），影响了泛化性能；其次，评估分数往往有偏差且难以解释，与人类判断相关性较低。

为解决这些问题，我们提出了一种新型动态多智能体系统，能够为各类自然语言生成应用自动设计个性化的 LLM 评估者。该系统通过迭代优化评估提示，平衡下游任务的自适应需求与与人类感知的一致性。实验结果表明，我们的多智能体 LLM 评估框架不仅在评估准确性上优于现有方法，还生成了与人类感知更一致的评估分数。

> Large Language Models (LLMs) have demonstrated impressive performance across diverse domains, yet they still encounter challenges such as insufficient domain-specific knowledge, biases, and hallucinations. This underscores the need for robust evaluation methodologies to accurately assess LLM-based applications. Traditional evaluation methods, which rely on word overlap or text embeddings, are inadequate for capturing the nuanced semantic information necessary to evaluate dynamic, open-ended text generation. Recent research has explored leveraging LLMs to mimic human reasoning and decision-making processes for evaluation purposes known as LLM-as-a-judge framework. However, these existing frameworks have two significant limitations. First, they lack the flexibility to adapt to different text styles, including various answer and ground truth styles, thereby reducing their generalization performance. Second, the evaluation scores produced by these frameworks are often skewed and hard to interpret, showing a low correlation with human judgment. To address these challenges, we propose a novel dynamic multi-agent system that automatically designs personalized LLM judges for various natural language generation applications. This system iteratively refines evaluation prompts and balances the trade-off between the adaptive requirements of downstream tasks and the alignment with human perception. Our experimental results show that the proposed multi-agent LLM Judge framework not only enhances evaluation accuracy compared to existing methods but also produces evaluation scores that better align with human perception.

[Arxiv](https://arxiv.org/abs/2504.02867)