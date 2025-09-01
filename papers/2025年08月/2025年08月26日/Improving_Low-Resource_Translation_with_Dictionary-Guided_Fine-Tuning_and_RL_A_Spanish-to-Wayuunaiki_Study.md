# 基于词典引导微调和强化学习提升低资源翻译性能：以西班牙语-瓦尤纳伊基语为例的研究

发布时间：2025年08月26日

`强化学习` `基础理论`

> Improving Low-Resource Translation with Dictionary-Guided Fine-Tuning and RL: A Spanish-to-Wayuunaiki Study

# 摘要

> 低资源机器翻译仍是大型语言模型（LLMs）面临的一大挑战——这些模型在预训练阶段通常接触不到低资源语言，用于微调的平行数据也很有限。为此，我们提出一种新方法：除监督微调外，还通过整合外部词典工具并利用强化学习对模型进行端到端训练，以提升低资源语言的翻译质量。我们以西班牙语-瓦尤纳伊基语语言对为研究对象，将翻译构建为工具增强型决策问题，使模型在生成过程中能选择性查阅双语词典。该方法结合监督指令微调与引导奖励策略优化（GRPO），让模型学会何时及如何高效使用词典工具。我们将BLEU相似度分数用作奖励信号指导学习过程。在AmericasNLP 2025共享任务的西班牙语-瓦尤纳伊基语测试集上，工具增强模型表现显著：相比以往工作BLEU值提升高达3.37，与无词典访问的监督基线相比相对增益达18%。此外，我们还开展消融研究，对比Qwen2.5-0.5B-Instruct与LLaMA等模型及先前基于NLLB的系统，以评估模型架构和训练策略的影响。

> Low-resource machine translation remains a significant challenge for large language models (LLMs), which often lack exposure to these languages during pretraining and have limited parallel data for fine-tuning. We propose a novel approach that enhances translation for low-resource languages by integrating an external dictionary tool and training models end-to-end using reinforcement learning, in addition to supervised fine-tuning. Focusing on the Spanish-Wayuunaiki language pair, we frame translation as a tool-augmented decision-making problem in which the model can selectively consult a bilingual dictionary during generation. Our method combines supervised instruction tuning with Guided Reward Policy Optimization (GRPO), enabling the model to learn both when and how to use the tool effectively. BLEU similarity scores are used as rewards to guide this learning process. Preliminary results show that our tool-augmented models achieve up to +3.37 BLEU improvement over previous work, and a 18% relative gain compared to a supervised baseline without dictionary access, on the Spanish-Wayuunaiki test set from the AmericasNLP 2025 Shared Task. We also conduct ablation studies to assess the effects of model architecture and training strategy, comparing Qwen2.5-0.5B-Instruct with other models such as LLaMA and a prior NLLB-based system. These findings highlight the promise of combining LLMs with external tools and the role of reinforcement learning in improving translation quality in low-resource language settings.

[Arxiv](https://arxiv.org/abs/2508.19481)