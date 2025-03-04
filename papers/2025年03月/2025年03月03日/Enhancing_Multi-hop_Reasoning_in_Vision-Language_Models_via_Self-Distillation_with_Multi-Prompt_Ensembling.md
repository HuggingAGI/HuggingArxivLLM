# 基于多提示集成的自蒸馏方法提升视觉-语言模型的多跳推理能力

发布时间：2025年03月03日

`LLM应用` `多模态` `计算机视觉`

> Enhancing Multi-hop Reasoning in Vision-Language Models via Self-Distillation with Multi-Prompt Ensembling

# 摘要

> 多模态大型语言模型与大型语言模型齐头并进，取得了快速发展。然而，尽管语言模型能有效利用思维链提示进行零样本或少样本学习，但多模态LLMs由于模态差距和任务复杂性，类似提示策略效果较弱。为应对这一挑战，我们探索了两种提示方法：一种是将多模态输入分析与回答生成分离的双查询方法，另一种是结合多种提示变体的集成提示方法，以得出最终答案。尽管这些方法在不进行微调的情况下增强了模型的推理能力，但显著增加了推理开销。因此，基于这两种提示技术，我们提出了一种自蒸馏框架，使模型无需标注数据即可自我改进。我们的自蒸馏框架从集成双查询提示收集的推理轨迹中学习表示干预模块，以隐含表示形式呈现。这些轻量级干预模块与冻结的原模型并行运行，从而在保持计算效率的同时显著提升模型能力。我们在五个广泛使用的VQA基准测试上评估了我们的方法，证明了其在复杂任务中进行多跳推理的有效性。

> Multi-modal large language models have seen rapid advancement alongside large language models. However, while language models can effectively leverage chain-of-thought prompting for zero or few-shot learning, similar prompting strategies are less effective for multi-modal LLMs due to modality gaps and task complexity. To address this challenge, we explore two prompting approaches: a dual-query method that separates multi-modal input analysis and answer generation into two prompting steps, and an ensemble prompting method that combines multiple prompt variations to arrive at the final answer. Although these approaches enhance the model's reasoning capabilities without fine-tuning, they introduce significant inference overhead. Therefore, building on top of these two prompting techniques, we propose a self-distillation framework such that the model can improve itself without any annotated data. Our self-distillation framework learns representation intervention modules from the reasoning traces collected from ensembled dual-query prompts, in the form of hidden representations. The lightweight intervention modules operate in parallel with the frozen original model, which makes it possible to maintain computational efficiency while significantly improving model capability. We evaluate our method on five widely-used VQA benchmarks, demonstrating its effectiveness in performing multi-hop reasoning for complex tasks.

[Arxiv](https://arxiv.org/abs/2503.01754)