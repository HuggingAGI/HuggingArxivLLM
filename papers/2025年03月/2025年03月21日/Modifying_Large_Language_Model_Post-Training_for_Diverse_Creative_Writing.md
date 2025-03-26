# 优化大型语言模型的后训练，助力多样化的创意写作

发布时间：2025年03月21日

`LLM应用

摘要中提到，论文专注于改进大型语言模型在创意写作任务中的生成多样性和质量，提出了一种新的后训练方法，并通过实验证明了其有效性。这属于LLM的应用层面研究，因此归类为LLM应用。` `创意产业` `人工智能`

> Modifying Large Language Model Post-Training for Diverse Creative Writing

# 摘要

> 创意写作任务没有单一正确的答案，因此用于执行这些任务的大型语言模型（LLMs）应该能够生成多样化的有效输出。然而，LLMs的后训练通常侧重于提高生成质量，却忽视了促进输出多样性。因此，在创意写作生成中，我们研究了后训练方法，以同时提升输出多样性和质量。我们的核心理念是将偏差（即训练样本与其相同提示的其他样本之间的差异程度）纳入训练目标，以便从稀有的高质量实例中学习。通过将我们的方法应用于直接偏好优化（DPO）和几率比偏好优化（ORPO），我们证明可以在对质量影响最小的情况下，促进训练模型的输出多样性。我们拥有80亿参数的最佳模型能够在多样性上与人工创作的数据集相媲美，同时输出质量与我们评估的最佳指令微调模型（GPT-4o 和 DeepSeek-R1）相当。我们进一步通过人类评估、消融实验和与现有多样化方法（DivPO）的比较，验证了我们的方法。

> As creative writing tasks do not have singular correct answers, large language models (LLMs) trained to perform these tasks should be able to generate diverse valid outputs. However, LLM post-training often focuses on improving generation quality but neglects to facilitate output diversity. Hence, in creative writing generation, we investigate post-training approaches to promote both output diversity and quality. Our core idea is to include deviation -- the degree of difference between a training sample and all other samples with the same prompt -- in the training objective to facilitate learning from rare high-quality instances. By adopting our approach to direct preference optimization (DPO) and odds ratio preference optimization (ORPO), we demonstrate that we can promote the output diversity of trained models while minimally decreasing quality. Our best model with 8B parameters could achieve on-par diversity as a human-created dataset while having output quality similar to the best instruction-tuned models we examined, GPT-4o and DeepSeek-R1. We further validate our approaches with a human evaluation, an ablation, and a comparison to an existing diversification approach, DivPO.

[Arxiv](https://arxiv.org/abs/2503.17126)