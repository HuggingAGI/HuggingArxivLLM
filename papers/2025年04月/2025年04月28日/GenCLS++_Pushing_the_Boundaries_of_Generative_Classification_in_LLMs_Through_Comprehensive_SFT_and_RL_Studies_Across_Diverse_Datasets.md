# GenCLS++: 通过跨多样数据集的全面 SFT 与 RL 研究，突破 LLM 中生成分类的边界

发布时间：2025年04月28日

`LLM应用` `信息检索`

> GenCLS++: Pushing the Boundaries of Generative Classification in LLMs Through Comprehensive SFT and RL Studies Across Diverse Datasets

# 摘要

> 文本分类作为机器学习中的基础任务，在众多领域发挥着重要作用。随着大型语言模型（LLMs）的快速发展，尤其是通过强化学习（RL）实现的规模扩展，对更强大判别器的需求日益迫切。因此，分类技术的进步对于提升LLMs的整体能力至关重要。

传统判别方法将文本映射到标签，但忽视了LLMs内在的生成优势。生成式分类通过提示模型直接输出标签来弥补这一不足。然而，现有研究仍局限于简单的监督微调（SFT），很少探究训练提示与推理提示的相互作用。此外，目前还没有工作系统地将RL应用于生成式文本分类器，并在统一框架中整合SFT、RL和推理时的提示。我们提出的GenCLS++框架填补了这一空白。

GenCLS++框架在训练和推理过程中同时优化SFT和RL，并系统地探索五个高层次策略维度：上下文学习变体、类别定义、显式不确定性标签、语义无关的数值标签以及基于困惑度的解码。在SFT的“策略预热”阶段后，我们采用带有简单基于规则奖励的RL，取得了显著的额外增益。在七个数据集上，GenCLS++相对于简单的SFT基线平均准确率提高了3.46%；在公共数据集上，这一提升增加到4.00%。

值得注意的是，与受益于显式推理过程的推理密集型任务不同，我们发现分类任务在没有这些推理步骤的情况下表现更佳。这一发现关于显式推理作用的见解，为未来LLMs的应用提供了宝贵的指导。

> As a fundamental task in machine learning, text classification plays a crucial role in many areas. With the rapid scaling of Large Language Models (LLMs), particularly through reinforcement learning (RL), there is a growing need for more capable discriminators. Consequently, advances in classification are becoming increasingly vital for enhancing the overall capabilities of LLMs. Traditional discriminative methods map text to labels but overlook LLMs' intrinsic generative strengths. Generative classification addresses this by prompting the model to directly output labels. However, existing studies still rely on simple SFT alone, seldom probing the interplay between training and inference prompts, and no work has systematically leveraged RL for generative text classifiers and unified SFT, RL, and inference-time prompting in one framework. We bridge this gap with GenCLS++, a framework that jointly optimizes SFT and RL while systematically exploring five high-level strategy dimensions-in-context learning variants, category definitions, explicit uncertainty labels, semantically irrelevant numeric labels, and perplexity-based decoding-during both training and inference. After an SFT "policy warm-up," we apply RL with a simple rule-based reward, yielding sizable extra gains. Across seven datasets, GenCLS++ achieves an average accuracy improvement of 3.46% relative to the naive SFT baseline; on public datasets, this improvement rises to 4.00%. Notably, unlike reasoning-intensive tasks that benefit from explicit thinking processes, we find that classification tasks perform better without such reasoning steps. These insights into the role of explicit reasoning provide valuable guidance for future LLM applications.

[Arxiv](https://arxiv.org/abs/2504.19898)