# DiffusionAttacker：用于 LLM 越狱的扩散驱动式提示操纵

发布时间：2024年12月23日

`LLM应用` `语言模型` `安全性`

> DiffusionAttacker: Diffusion-Driven Prompt Manipulation for LLM Jailbreak

# 摘要

> 大型语言模型（LLMs）在接收到精心设计的输入时，容易生成有害内容，此漏洞被称作 LLM 越狱。随着 LLMs 愈发强大，研究越狱方法对于提升安全性以及让模型契合人类价值观极为关键。传统的越狱技术依赖于后缀添加或提示模板，然而这些方法的攻击多样性有限。本文引入了 DiffusionAttacker，这是一种受扩散模型启发的端到端越狱重写生成方法。我们的方法采用序列到序列（seq2seq）文本扩散模型作为生成器，以原始提示为条件，并通过新颖的攻击损失来引导去噪过程。与以往使用自回归 LLMs 生成越狱提示的方法不同，那些方法限制了已生成标记的修改，也限制了重写空间，而 DiffusionAttacker 运用了 seq2seq 扩散模型，能够进行更灵活的标记修改。这种方法在保留原始提示语义内容的同时生成有害内容。此外，我们借助 Gumbel-Softmax 技术，使从扩散模型输出分布中采样的过程可微，无需进行迭代标记搜索。在 Advbench 和 Harmbench 上开展的大量实验表明，DiffusionAttacker 在包括攻击成功率（ASR）、流畅性和多样性等各种评估指标上均优于以往的方法。

> Large Language Models (LLMs) are susceptible to generating harmful content when prompted with carefully crafted inputs, a vulnerability known as LLM jailbreaking. As LLMs become more powerful, studying jailbreak methods is critical to enhancing security and aligning models with human values. Traditionally, jailbreak techniques have relied on suffix addition or prompt templates, but these methods suffer from limited attack diversity. This paper introduces DiffusionAttacker, an end-to-end generative approach for jailbreak rewriting inspired by diffusion models. Our method employs a sequence-to-sequence (seq2seq) text diffusion model as a generator, conditioning on the original prompt and guiding the denoising process with a novel attack loss. Unlike previous approaches that use autoregressive LLMs to generate jailbreak prompts, which limit the modification of already generated tokens and restrict the rewriting space, DiffusionAttacker utilizes a seq2seq diffusion model, allowing more flexible token modifications. This approach preserves the semantic content of the original prompt while producing harmful content. Additionally, we leverage the Gumbel-Softmax technique to make the sampling process from the diffusion model's output distribution differentiable, eliminating the need for iterative token search. Extensive experiments on Advbench and Harmbench demonstrate that DiffusionAttacker outperforms previous methods across various evaluation metrics, including attack success rate (ASR), fluency, and diversity.

[Arxiv](https://arxiv.org/abs/2412.17522)