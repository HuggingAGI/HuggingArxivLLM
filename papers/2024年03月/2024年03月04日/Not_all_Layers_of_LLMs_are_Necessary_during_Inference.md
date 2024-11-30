# 对于LLM的推理阶段，并非所有层级都不可或缺。

发布时间：2024年03月04日

`LLM应用`

> Not all Layers of LLMs are Necessary during Inference

# 摘要

> LLMs的推理过程开销巨大，理想情况下，其推理阶段应能在确保模型能力（如泛化性和上下文学习能力）的前提下减少计算资源消耗。本文探讨的核心问题是：“在LLM推理时，是否可以根据实例难度灵活采用浅层或深层网络？”我们首先通过对各任务激活层的统计分析揭示了一个事实：推理阶段并非所有层次都不可或缺。接着，我们创新性地提出了AdaInfer算法，该算法能依据输入实例动态决定推理停止的时机，且无需修改LLM原有参数，确保了跨任务的泛化性能。实验证明，在诸如Llama2系列和OPT等知名LLMs上，AdaInfer平均可节约14.8%的计算资源，而在情感类任务上最高可达50%，与此同时还能维持与原模型相当的表现水平。值得注意的是，AdaInfer与其它模型加速技术相辅相成，有望进一步提高推理效率。

> The inference phase of Large Language Models (LLMs) is very expensive. An ideal inference stage of LLMs could utilize fewer computational resources while still maintaining its capabilities (e.g., generalization and in-context learning ability). In this paper, we try to answer the question, "During LLM inference, can we use shallow layers for easy instances; and deep layers for hard ones?" To answer this question, we first indicate that Not all Layers are Necessary during Inference by statistically analyzing the activated layers across tasks. Then, we propose a simple algorithm named AdaInfer to determine the inference termination moment based on the input instance adaptively. More importantly, AdaInfer does not alter LLM parameters and maintains generalizability across tasks. Experiments on well-known LLMs (i.e., Llama2 series and OPT) show that AdaInfer saves an average of 14.8% of computational resources, even up to 50% on sentiment tasks, while maintaining comparable performance. Additionally, this method is orthogonal to other model acceleration techniques, potentially boosting inference efficiency further.

[Arxiv](https://arxiv.org/abs/2403.02181)