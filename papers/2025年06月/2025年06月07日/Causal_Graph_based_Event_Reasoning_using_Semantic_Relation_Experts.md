# 基于因果图的事件推理：语义关系专家助力

发布时间：2025年06月07日

`LLM应用` `事件预测` `因果推理`

> Causal Graph based Event Reasoning using Semantic Relation Experts

# 摘要

> 理解场景中事件之间的因果联系对于有效建模和推理事件至关重要。然而，事件推理仍然是一个困难的挑战，尽管最近取得了进展，大型语言模型（LLMs）仍然难以准确识别事件之间的因果关系。这种困难导致在事件预测和时间线理解等更深层次的推理任务中表现不佳。为了解决这一挑战，我们研究了生成因果事件图（例如，A 使 B 成为可能）作为并行机制，以帮助 LLMs 在推理过程中显式表示因果关系。本文评估了如何生成正确的图以及图如何辅助推理。我们提出了一种协作的因果图生成方法，其中我们使用 LLMs 模拟专注于特定语义关系的专家。这些专家进行多轮讨论，然后由最终专家整合讨论结果。接下来，为了展示因果图的实用性，我们将其应用于多个下游应用程序，并引入了一个新的可解释事件预测任务，该任务要求在解释中包含因果事件链。这些解释比基线生成的更具信息量和连贯性。最后，我们的整体方法无需在任何下游任务上进行微调，就在预测和下一个事件预测任务上都取得了与现有最先进模型相媲美的结果。

> Understanding how events in a scenario causally connect with each other is important for effectively modeling and reasoning about events. But event reasoning remains a difficult challenge, and despite recent advances, Large Language Models (LLMs) still struggle to accurately identify causal connections between events. This struggle leads to poor performance on deeper reasoning tasks like event forecasting and timeline understanding. To address this challenge, we investigate the generation of causal event graphs (e.g., A enables B) as a parallel mechanism to help LLMs explicitly represent causality during inference. This paper evaluates both how to generate correct graphs as well as how graphs can assist reasoning. We propose a collaborative approach to causal graph generation where we use LLMs to simulate experts that focus on specific semantic relations. The experts engage in multiple rounds of discussions which are then consolidated by a final expert. Then, to demonstrate the utility of causal graphs, we use them on multiple downstream applications, and also introduce a new explainable event prediction task that requires a causal chain of events in the explanation. These explanations are more informative and coherent than baseline generations. Finally, our overall approach not finetuned on any downstream task, achieves competitive results with state-of-the-art models on both forecasting and next event prediction tasks.

[Arxiv](https://arxiv.org/abs/2506.06910)