# 自训练让大型语言模型展现清晰简洁的推理过程

发布时间：2025年02月27日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在推理过程中的优化，特别是如何减少冗余令牌以提高效率。它通过分析输出分布和提出微调方法来优化推理路径，属于对LLMs内在机制和优化的研究，因此归类为LLM理论。` `人工智能`

> Self-Training Elicits Concise Reasoning in Large Language Models

# 摘要

> 链式思维（CoT）推理使大型语言模型（LLMs）能够通过中间令牌进行额外计算，从而解决复杂任务。然而，我们认为典型的推理轨迹包含大量冗余令牌，导致不必要的推理成本。通过对当前LLMs输出分布的分析，我们发现它们相对于默认行为具有潜在的更简洁推理能力。为了激发这种能力，我们在特定任务环境中提出了简单的微调方法，这些方法利用通过最佳N采样和少量样本条件获得的自动生成的简洁推理路径。我们的综合方法在GSM8K和MATH上，五个模型家族平均输出令牌减少了30%，同时保持平均准确率。通过利用LLMs的基本随机性和上下文学习能力，我们的自训练方法在各种模型上稳健地激发了简洁推理，包括那些经过大量后训练的模型。代码可在https://github.com/TergelMunkhbat/concise-reasoning获取。

> Chain-of-thought (CoT) reasoning has enabled large language models (LLMs) to utilize additional computation through intermediate tokens to solve complex tasks. However, we posit that typical reasoning traces contain many redundant tokens, incurring extraneous inference costs. Upon examination of the output distribution of current LLMs, we find evidence on their latent ability to reason more concisely, relative to their default behavior. To elicit this capability, we propose simple fine-tuning methods which leverage self-generated concise reasoning paths obtained by best-of-N sampling and few-shot conditioning, in task-specific settings. Our combined method achieves a 30% reduction in output tokens on average, across five model families on GSM8K and MATH, while maintaining average accuracy. By exploiting the fundamental stochasticity and in-context learning capabilities of LLMs, our self-training approach robustly elicits concise reasoning on a wide range of models, including those with extensive post-training. Code is available at https://github.com/TergelMunkhbat/concise-reasoning

[Arxiv](https://arxiv.org/abs/2502.20122)