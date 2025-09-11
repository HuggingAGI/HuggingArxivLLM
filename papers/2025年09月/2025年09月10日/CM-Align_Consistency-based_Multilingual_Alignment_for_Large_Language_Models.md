# CM-Align：基于一致性的大型语言模型多语言对齐

发布时间：2025年09月10日

`LLM应用` `基础理论`

> CM-Align: Consistency-based Multilingual Alignment for Large Language Models

# 摘要

> 当前大型语言模型（LLMs）在英语与其他语言的对齐性能上普遍存在显著差距。为弥合这一鸿沟，现有研究常以模型的英语响应为参考，筛选其他语言的最佳/最差响应用于直接偏好优化（DPO）训练。然而，我们发现当前方法存在两点局限：一是生成的多语言偏好数据噪声较大，二是对齐性能因此受限。具体表现为：1) 并非所有英语响应都质量上乘，低质量的英语参考可能误导其他语言的对齐方向；2) 当前方法构建多语言偏好对时，多采用有偏或启发式策略。为此，我们提出一种基于一致性的数据选择方法（CM-Align），旨在构建高质量多语言偏好数据以提升多语言对齐效果。该方法包含两个核心部分：一致性引导的英语参考筛选，以及基于跨语言一致性的多语言偏好数据构建。在三个LLM模型和三类常见任务上的实验结果表明，我们的方法有效且性能更优，这也进一步印证了构建高质量偏好数据的必要性。

> Current large language models (LLMs) generally show a significant performance gap in alignment between English and other languages. To bridge this gap, existing research typically leverages the model's responses in English as a reference to select the best/worst responses in other languages, which are then used for Direct Preference Optimization (DPO) training. However, we argue that there are two limitations in the current methods that result in noisy multilingual preference data and further limited alignment performance: 1) Not all English responses are of high quality, and using a response with low quality may mislead the alignment for other languages. 2) Current methods usually use biased or heuristic approaches to construct multilingual preference pairs. To address these limitations, we design a consistency-based data selection method to construct high-quality multilingual preference data for improving multilingual alignment (CM-Align). Specifically, our method includes two parts: consistency-guided English reference selection and cross-lingual consistency-based multilingual preference data construction. Experimental results on three LLMs and three common tasks demonstrate the effectiveness and superiority of our method, which further indicates the necessity of constructing high-quality preference data.

[Arxiv](https://arxiv.org/abs/2509.08541)