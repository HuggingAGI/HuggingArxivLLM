# Transformer 副驾驶：通过错误日志精调大语言模型

发布时间：2025年05月22日

`LLM理论` `推荐系统`

> Transformer Copilot: Learning from The Mistake Log in LLM Fine-tuning

# 摘要

> 大型语言模型通常通过监督微调来适应特定领域的下游任务。然而，标准微调仅关注通过最小化生成损失来优化模型参数。我们更进一步，提出了一种基于模型自身学习信号的改进方法，这与人类学习者通过反思过去错误来提升未来表现的方式相类似。我们引入了“错误日志”（Mistake Log）的概念，用以系统性地追踪模型在微调过程中的学习行为和重复错误。将原始的基于Transformer的模型称为“飞行员”（Pilot），我们设计了一个“副飞行员”（Copilot）模型，通过调整飞行员的推理结果来优化其推理性能。我们将整体飞行员-副飞行员框架命名为Transformer Copilot，它具有以下三个创新点：(i)一种新型的副飞行员模型设计，(ii)一种联合训练范式，其中副飞行员与飞行员一同持续从不断更新的错误日志中学习，以及(iii)一种融合推理范式，其中副飞行员通过调整飞行员的 logits 来提升生成效果。我们从理论和实证两个角度对这一新型学习框架进行了深入分析。在涵盖常识推理、算术和推荐任务的12个基准测试中，实验结果表明，Transformer Copilot 在性能上一致提升了34.5%，同时仅给飞行员模型带来了轻微的计算开销，并展现出强大的可扩展性和迁移能力。

> Large language models are typically adapted to downstream tasks through supervised fine-tuning on domain-specific data. While standard fine-tuning focuses on minimizing generation loss to optimize model parameters, we take a deeper step by retaining and leveraging the model's own learning signals, analogous to how human learners reflect on past mistakes to improve future performance. We first introduce the concept of Mistake Log to systematically track the model's learning behavior and recurring errors throughout fine-tuning. Treating the original transformer-based model as the Pilot, we correspondingly design a Copilot model to refine the Pilot's inference performance via logits rectification. We name the overall Pilot-Copilot framework the Transformer Copilot, which introduces (i) a novel Copilot model design, (ii) a joint training paradigm where the Copilot continuously learns from the evolving Mistake Log alongside the Pilot, and (iii) a fused inference paradigm where the Copilot rectifies the Pilot's logits for enhanced generation. We provide both theoretical and empirical analyses on our new learning framework. Experiments on 12 benchmarks spanning commonsense, arithmetic, and recommendation tasks demonstrate that Transformer Copilot consistently improves performance by up to 34.5%, while introducing marginal computational overhead to Pilot models and exhibiting strong scalability and transferability.

[Arxiv](https://arxiv.org/abs/2505.16270)