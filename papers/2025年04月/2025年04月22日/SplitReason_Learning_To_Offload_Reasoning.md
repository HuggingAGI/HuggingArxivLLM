# SplitReason：学习如何卸载推理任务

发布时间：2025年04月22日

`LLM应用` `数学推理` `计算机科学`

> SplitReason: Learning To Offload Reasoning

# 摘要

> 大型语言模型 (LLMs) 中的推理往往会生成比简单语言建模任务长得多的 token 生成序列。这种较长的生成长度反映了推理的多步骤、组合性本质，通常与更高的解决方案准确性相关。然而，从效率角度来看，更长的 token 生成会加剧 LLM 本身固有的顺序性和内存占用的解码阶段。

我们发现，并非推理过程中所有昂贵的部分都同样难以生成。于是，我们仅将推理过程中最具挑战性的部分卸载到一个更大、能力更强的模型上，而大部分生成则由一个更小、更高效的模型完成。更进一步，我们还教会了这个小型模型识别这些困难段落，并在需要时独立触发卸载。

为了实现这一目标，我们从 OpenR1-Math-220k 的链式思维 (CoT) 数据集中标注了 1.8 万个推理轨迹中的困难段落。然后，我们对一个 15 亿参数的推理模型进行了有监督微调 (SFT) 和强化学习微调 (RLFT)，训练它学会将推理过程中最具挑战性的部分卸载到一个更大的模型上。

实验结果表明，在卸载 1.35% 和 5% 的生成 token 的情况下，这种方法分别将 AIME24 推理准确性提高了 24% 和 28.3%。我们开源了我们的 SplitReason 模型、数据、代码和日志，以促进相关研究的进一步发展。


> Reasoning in large language models (LLMs) tends to produce substantially longer token generation sequences than simpler language modeling tasks. This extended generation length reflects the multi-step, compositional nature of reasoning and is often correlated with higher solution accuracy. From an efficiency perspective, longer token generation exacerbates the inherently sequential and memory-bound decoding phase of LLMs. However, not all parts of this expensive reasoning process are equally difficult to generate. We leverage this observation by offloading only the most challenging parts of the reasoning process to a larger, more capable model, while performing most of the generation with a smaller, more efficient model; furthermore, we teach the smaller model to identify these difficult segments and independently trigger offloading when needed. To enable this behavior, we annotate difficult segments across 18k reasoning traces from the OpenR1-Math-220k chain-of-thought (CoT) dataset. We then apply supervised fine-tuning (SFT) and reinforcement learning fine-tuning (RLFT) to a 1.5B-parameter reasoning model, training it to learn to offload the most challenging parts of its own reasoning process to a larger model. This approach improves AIME24 reasoning accuracy by 24% and 28.3% while offloading 1.35% and 5% of the generated tokens respectively. We open-source our SplitReason model, data, code and logs.

[Arxiv](https://arxiv.org/abs/2504.16379)