# 多项选择题：推理让大型语言模型（LLMs）更加自信，即便它们错了。

发布时间：2025年01月16日

`LLM理论

理由：这篇论文主要研究了大型语言模型（LLMs）在回答多项选择题时的信心表现，特别是探讨了提供推理（思维链）对LLM信心评估的影响。论文的核心关注点是LLM的内部机制和理论理解，特别是LLM如何通过推理过程修改其答案的概率分布，以及这种修改如何影响其信心评估。因此，这篇论文属于LLM理论分类，因为它深入探讨了LLM的行为和理论机制，而不是具体的应用或技术实现。` `心理学`

> Multiple Choice Questions: Reasoning Makes Large Language Models (LLMs) More Self-Confident Even When They Are Wrong

# 摘要

> 评估大型语言模型（LLMs）的常用方法之一是多项选择题（MCQ）测试。MCQ基准测试能够大规模测试LLM在几乎任何主题上的知识，因为结果可以自动处理。为了辅助LLM回答问题，提示中可以包含少量示例，称为few shots。此外，可以要求LLM直接选择答案，或先提供推理再选择答案，这被称为思维链。除了检查答案是否正确外，评估还可以参考LLM对其响应的估计概率，作为其信心的指标。本文研究了LLM对其答案的信心如何取决于是否在回答前提供推理。对七个不同模型中广泛主题问题的评估结果显示，当LLM在回答前提供推理时，它们对自己的答案更有信心，无论答案是否正确。我们假设，这种行为是因为推理修改了所选答案的概率，LLM基于输入问题和支持所选答案的推理来预测答案。因此，LLM估计的概率存在内在局限性，应在评估程序中加以理解。有趣的是，人类中也存在类似现象，解释答案会增加对其正确性的信心。

> One of the most widely used methods to evaluate LLMs are Multiple Choice Question (MCQ) tests. MCQ benchmarks enable the testing of LLM knowledge on almost any topic at scale as the results can be processed automatically. To help the LLM answer, a few examples called few shots can be included in the prompt. Moreover, the LLM can be asked to answer the question directly with the selected option or to first provide the reasoning and then the selected answer, which is known as chain of thought. In addition to checking whether the selected answer is correct, the evaluation can look at the LLM-estimated probability of its response as an indication of the confidence of the LLM in the response. In this paper, we study how the LLM confidence in its answer depends on whether the model has been asked to answer directly or to provide the reasoning before answering. The results of the evaluation of questions on a wide range of topics in seven different models show that LLMs are more confident in their answers when they provide reasoning before the answer. This occurs regardless of whether the selected answer is correct. Our hypothesis is that this behavior is due to the reasoning that modifies the probability of the selected answer, as the LLM predicts the answer based on the input question and the reasoning that supports the selection made. Therefore, LLM estimated probabilities seem to have intrinsic limitations that should be understood in order to use them in evaluation procedures. Interestingly, the same behavior has been observed in humans, for whom explaining an answer increases confidence in its correctness.

[Arxiv](https://arxiv.org/abs/2501.09775)