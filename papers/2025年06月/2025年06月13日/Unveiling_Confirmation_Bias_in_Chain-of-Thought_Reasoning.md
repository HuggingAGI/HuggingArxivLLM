# 揭示链式推理中的确认偏误

发布时间：2025年06月13日

`LLM理论` `人工智能`

> Unveiling Confirmation Bias in Chain-of-Thought Reasoning

# 摘要

> # 摘要
链式思维（Chain-of-thought, CoT）提示方法在增强大型语言模型（LLMs）推理能力方面得到了广泛应用。然而，CoT推理的效果在不同推理类型的任务中表现不一。本研究从认知心理学中的	extit{确认偏见}视角，提出了一种全新方法来深入理解CoT的行为机制。

具体而言，我们研究了模型内部信念（通过直接问答概率近似）如何影响CoT推理生成（$Q 	o R$）和推理引导的答案预测（$QR 	o A$）。通过将CoT分解为两阶段过程，我们系统分析了模型信念、推理属性与阶段性表现之间的关联。研究结果表明，LLMs中存在显著的确认偏见：模型信念不仅会扭曲推理过程，还会左右推理结果在答案预测中的应用方式。

此外，任务对确认偏见的敏感性与信念强度之间的相互作用，为不同推理任务和模型中CoT效果的差异提供了合理解释。总体而言，这项研究为制定更有效的提示策略以缓解确认偏见、提升推理性能提供了宝贵见解。代码已开源，地址为	extit{https://github.com/yuewan2/biasedcot}。


> Chain-of-thought (CoT) prompting has been widely adopted to enhance the reasoning capabilities of large language models (LLMs). However, the effectiveness of CoT reasoning is inconsistent across tasks with different reasoning types. This work presents a novel perspective to understand CoT behavior through the lens of \textit{confirmation bias} in cognitive psychology. Specifically, we examine how model internal beliefs, approximated by direct question-answering probabilities, affect both reasoning generation ($Q \to R$) and reasoning-guided answer prediction ($QR \to A$) in CoT. By decomposing CoT into a two-stage process, we conduct a thorough correlation analysis in model beliefs, rationale attributes, and stage-wise performance. Our results provide strong evidence of confirmation bias in LLMs, such that model beliefs not only skew the reasoning process but also influence how rationales are utilized for answer prediction. Furthermore, the interplay between task vulnerability to confirmation bias and the strength of beliefs also provides explanations for CoT effectiveness across reasoning tasks and models. Overall, this study provides a valuable insight for the needs of better prompting strategies that mitigate confirmation bias to enhance reasoning performance. Code is available at \textit{https://github.com/yuewan2/biasedcot}.

[Arxiv](https://arxiv.org/abs/2506.12301)