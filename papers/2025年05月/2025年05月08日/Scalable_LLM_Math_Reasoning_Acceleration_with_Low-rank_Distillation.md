# 利用低秩蒸馏实现大型语言模型数学推理的可扩展加速。

发布时间：2025年05月08日

`LLM应用

摘要分析：该论文专注于优化大型语言模型（LLM）在数学推理中的性能，提出了一种蒸馏方法Caprese，以提高推理效率和减少计算资源需求。这属于LLM的应用层面优化，因此归类为LLM应用。` `数学推理` `生成式AI`

> Scalable LLM Math Reasoning Acceleration with Low-rank Distillation

# 摘要

> 大型语言模型（LLM）在数学推理时由于推理过程较长，需要大量计算资源和时间。虽然现有高效推理方法在语言任务上表现出色，但它们往往严重损害数学性能。本文提出了一种名为Caprese的低成本蒸馏方法，专注于前馈块，旨在恢复高效推理部署后丢失的能力。通过仅增加约1%的额外参数和20K合成训练样本，在不改变原始权重的情况下，Caprese能够恢复绝大多数甚至全部的数学推理能力，同时不影响指令型LLM的语言任务性能。此外，Caprese大幅减少了活跃参数数量（为Gemma 2 9B和Llama 3.1 8B分别减少约20亿），并能无缝集成到现有模型层中，降低生成延迟（使用Qwen 2.5 14B生成2048个token时延迟降低超11%），同时鼓励生成更简洁的响应。

> Due to long generations, large language model (LLM) math reasoning demands significant computational resources and time. While many existing efficient inference methods have been developed with excellent performance preservation on language tasks, they often severely degrade math performance. In this paper, we propose Caprese, a low-cost distillation method to recover lost capabilities from deploying efficient inference methods, focused primarily in feedforward blocks. With original weights unperturbed, roughly 1% of additional parameters, and only 20K synthetic training samples, we are able to recover much if not all of the math capabilities lost from efficient inference for thinking LLMs and without harm to language tasks for instruct LLMs. Moreover, Caprese slashes the number of active parameters (~2B cut for Gemma 2 9B and Llama 3.1 8B) and integrates cleanly into existing model layers to reduce latency (>11% reduction to generate 2048 tokens with Qwen 2.5 14B) while encouraging response brevity.

[Arxiv](https://arxiv.org/abs/2505.07861)