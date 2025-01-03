# 思维树何时成功：大模型擅长生成，而非判别

发布时间：2024年10月23日

`LLM理论

理由：这篇论文主要讨论了思维树（ToT）作为一种推理策略在大型语言模型（LLMs）中的应用，并探讨了生成器和判别器在ToT中的作用。论文的核心在于研究ToT的理论基础和性能优化，特别是生成器和判别器的规模对ToT性能的影响。这些内容属于对LLM推理策略的理论研究，因此归类为“LLM理论”。` `人工智能`

> Understanding When Tree of Thoughts Succeeds: Larger Models Excel in Generation, Not Discrimination

# 摘要

> # 思维树 (ToT)
思维树（ToT）是一种用于大型语言模型（LLMs）的推理策略，通过生成器提出推理步骤，判别器决定实施哪些步骤。ToT在推理任务中表现优异，常超越简单的IO提示和CoT推理。然而，ToT并非在所有模型中都优于这些简单方法，关于其最佳适用条件仍存在大量未知。本文分别探讨了生成器和判别器的作用，发现生成器对ToT的成功更为关键。即使使用较小的判别器模型，扩展生成器也能显著提升ToT性能，而固定生成器扩展判别器则效果有限。研究表明，不同规模的模型在判别能力上相当，但在ToT的生成性能上差异显著。

> Tree of Thoughts (ToT) is a reasoning strategy for Large Language Models (LLMs) that employs a generator to suggest reasoning steps and a discriminator to decide which steps to implement. ToT demonstrates strong performance on reasoning tasks, often surpassing simple methods such as Input-Output (IO) prompting and Chain-of-Thought (CoT) reasoning. However, ToT does not consistently outperform such simpler methods across all models, leaving large knowledge gaps on the conditions under which ToT is most beneficial. In this paper, we analyze the roles of the generator and discriminator separately to better understand the conditions when ToT is beneficial. We find that the generator plays a more critical role than the discriminator in driving the success of ToT. While using even a smaller model as the discriminator, scaling the generator leads to notable improvements in ToT performance, whereas scaling the discriminator with a fixed generator yields only marginal gains. Our results show that models across different scales exhibit comparable discrimination capabilities, yet differ significantly in their generative performance for ToT.

[Arxiv](https://arxiv.org/abs/2410.17820)