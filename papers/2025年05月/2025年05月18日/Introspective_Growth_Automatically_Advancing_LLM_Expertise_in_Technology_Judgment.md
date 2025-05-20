# 内省式成长：自动增强LLM的技术判断能力

发布时间：2025年05月18日

`LLM理论` `计算机科学`

> Introspective Growth: Automatically Advancing LLM Expertise in Technology Judgment

# 摘要

> 大型语言模型 (LLMs) 虽然在概念理解上表现出色，但其内部知识仍存在结构松散、难以评估的问题。我们提出了一种轻量级的自我提问策略，旨在提升 LLMs 在依赖细微语义区分领域的理解能力。为此，我们构建了一个包含130万项2015年后计算机科学专利配对的基准测试，这些专利以复杂的技术术语为特点。该基准测试的核心任务是：模型能否准确区分实质上不同的发明？研究发现，引导 LLMs 生成并回答自己的问题能显著提升性能，尤其是针对任务所需的知识。这些自动生成的问题和答案激活了模型内部未被充分利用的知识。此外，允许 LLMs 从外部科学文本中检索答案进一步提升了性能，表明模型知识是压缩过的，缺乏训练数据的丰富性。我们还发现，思维链提示与自我提问在效果上趋于一致，但自我提问在改善技术概念理解方面仍更具优势。值得注意的是，我们发现了一个提示策略的不对称现象：较小规模的模型往往能为中型模型生成更基础、更开放、更对齐的问题，这为跨模型协作提供了新的策略。综上所述，我们的研究结果表明，自我提问不仅是一种提升 LLM 理解能力的实用机制，特别是在知识稀疏且代表性不足的领域，还揭示了内部与外部知识组织方式的诊断探针。


> Large language models (LLMs) increasingly demonstrate signs of conceptual understanding, yet much of their internal knowledge remains latent, loosely structured, and difficult to access or evaluate. We propose self-questioning as a lightweight and scalable strategy to improve LLMs' understanding, particularly in domains where success depends on fine-grained semantic distinctions. To evaluate this approach, we introduce a challenging new benchmark of 1.3 million post-2015 computer science patent pairs, characterized by dense technical jargon and strategically complex writing. The benchmark centers on a pairwise differentiation task: can a model distinguish between closely related but substantively different inventions? We show that prompting LLMs to generate and answer their own questions - targeting the background knowledge required for the task - significantly improves performance. These self-generated questions and answers activate otherwise underutilized internal knowledge. Allowing LLMs to retrieve answers from external scientific texts further enhances performance, suggesting that model knowledge is compressed and lacks the full richness of the training data. We also find that chain-of-thought prompting and self-questioning converge, though self-questioning remains more effective for improving understanding of technical concepts. Notably, we uncover an asymmetry in prompting: smaller models often generate more fundamental, more open-ended, better-aligned questions for mid-sized models than large models with better understanding do, revealing a new strategy for cross-model collaboration. Altogether, our findings establish self-questioning as both a practical mechanism for automatically improving LLM comprehension, especially in domains with sparse and underrepresented knowledge, and a diagnostic probe of how internal and external knowledge are organized.

[Arxiv](https://arxiv.org/abs/2505.12452)