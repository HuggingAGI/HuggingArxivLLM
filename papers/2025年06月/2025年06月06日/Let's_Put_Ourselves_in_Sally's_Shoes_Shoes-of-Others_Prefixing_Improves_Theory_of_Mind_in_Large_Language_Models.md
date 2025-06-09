# 站在Sally的角度思考：换位思考前缀提升大型语言模型的视角理论

发布时间：2025年06月06日

`LLM理论

摘要中提到的论文探讨了如何通过推理时的方法提升大型语言模型（LLMs）的心智理论（ToM）能力。心智理论是指理解他人心理状态的能力，这对社交互动至关重要。论文提出了一种新的方法，称为“设身处地”（SoO）前缀，通过在输出的开头添加特定的提示语，帮助模型更好地理解他人的观点。这种方法属于对模型能力的理论改进，因此归类为LLM理论。` `人工智能`

> Let's Put Ourselves in Sally's Shoes: Shoes-of-Others Prefixing Improves Theory of Mind in Large Language Models

# 摘要

> 最新研究表明，大型语言模型（LLMs）的心智理论（ToM）尚未达到人类水平。由于在ToM数据集上微调LLMs通常会损害其泛化能力，已有研究提出了多种推理时方法来增强LLMs的ToM能力。然而，现有的ToM推理时方法大多专门针对涉及世界状态变化的上下文进行信念推理。在本研究中，我们提出了一种新的ToM推理时方法——“设身处地”（SoO）前缀。该方法对上下文的假设较少，适用于更广泛的场景。SoO前缀只需在LLM输出的开头添加“让我们站在A的角度思考”，其中A代表目标角色的姓名。我们在两个基准测试中评估了SoO前缀，这些基准测试分别评估了对话和叙述场景下（不涉及世界状态变化）的ToM能力，发现SoO前缀在五个类别的心智状态中均显著提升了ToM表现。我们的分析表明，SoO前缀能够激发更忠实的思考，从而提升ToM性能。

> Recent studies have shown that Theory of Mind (ToM) in large language models (LLMs) has not reached human-level performance yet. Since fine-tuning LLMs on ToM datasets often degrades their generalization, several inference-time methods have been proposed to enhance ToM in LLMs. However, existing inference-time methods for ToM are specialized for inferring beliefs from contexts involving changes in the world state. In this study, we present a new inference-time method for ToM, Shoes-of-Others (SoO) prefixing, which makes fewer assumptions about contexts and is applicable to broader scenarios. SoO prefixing simply specifies the beginning of LLM outputs with ``Let's put ourselves in A's shoes.'', where A denotes the target character's name. We evaluate SoO prefixing on two benchmarks that assess ToM in conversational and narrative contexts without changes in the world state and find that it consistently improves ToM across five categories of mental states. Our analysis suggests that SoO prefixing elicits faithful thoughts, thereby improving the ToM performance.

[Arxiv](https://arxiv.org/abs/2506.05970)