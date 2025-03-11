# VLRMBench：面向视觉-语言奖励模型的全面且具挑战性基准测试

发布时间：2025年03月10日

`LLM应用

论文摘要：大型视觉语言模型（LVLMs）在多模态任务中表现出色，但推理过程中的偏见有时会导致错误。近期，奖励模型（RMs）在推理中变得至关重要。具体来说，过程RMs评估推理步骤，结果RMs评估推理结果，而 critique RMs分析推理过程的错误并进行修正。然而，现有的视觉语言奖励模型（VLRMs）基准测试通常仅评估单一能力（如区分答案），限制了全面评估和领域发展。为此，我们提出了一项全面且具挑战性的基准测试——VLRMBench，包含12,634个问题。该基准基于三种 dataset，涵盖数学推理、幻觉理解及多图像理解。我们在三大类别中设计了12个任务，重点评估VLRMs在过程理解、结果判断和 critique 生成方面的能力。实验表明，VLRMBench对现有模型提出了严峻挑战。例如，在`预测未来`任务中，GPT-4o的准确率仅为76.0%。我们还进行了全面分析，为VLRMs的未来发展提供了重要见解。VLRMBench有望成为推动VLRMs发展的重要基准。代码和数据集可在GitHub获取。

LLM应用` `视觉语言模型` `基准测试`

> VLRMBench: A Comprehensive and Challenging Benchmark for Vision-Language Reward Models

# 摘要

> 大型视觉语言模型（LVLMs）在多模态任务中表现出色，但推理过程中的偏见有时会导致错误。近期，奖励模型（RMs）在推理中变得至关重要。具体来说，过程RMs评估推理步骤，结果RMs评估推理结果，而 critique RMs分析推理过程的错误并进行修正。然而，现有的视觉语言奖励模型（VLRMs）基准测试通常仅评估单一能力（如区分答案），限制了全面评估和领域发展。为此，我们提出了一项全面且具挑战性的基准测试——VLRMBench，包含12,634个问题。该基准基于三种 dataset，涵盖数学推理、幻觉理解及多图像理解。我们在三大类别中设计了12个任务，重点评估VLRMs在过程理解、结果判断和 critique 生成方面的能力。实验表明，VLRMBench对现有模型提出了严峻挑战。例如，在`预测未来`任务中，GPT-4o的准确率仅为76.0%。我们还进行了全面分析，为VLRMs的未来发展提供了重要见解。VLRMBench有望成为推动VLRMs发展的重要基准。代码和数据集可在GitHub获取。

> Although large visual-language models (LVLMs) have demonstrated strong performance in multimodal tasks, errors may occasionally arise due to biases during the reasoning process. Recently, reward models (RMs) have become increasingly pivotal in the reasoning process. Specifically, process RMs evaluate each reasoning step, outcome RMs focus on the assessment of reasoning results, and critique RMs perform error analysis on the entire reasoning process, followed by corrections. However, existing benchmarks for vision-language RMs (VLRMs) typically assess only a single aspect of their capabilities (e.g., distinguishing between two answers), thus limiting the all-round evaluation and restricting the development of RMs in the visual-language domain. To address this gap, we propose a comprehensive and challenging benchmark, dubbed as VLRMBench, encompassing 12,634 questions. VLRMBench is constructed based on three distinct types of datasets, covering mathematical reasoning, hallucination understanding, and multi-image understanding. We design 12 tasks across three major categories, focusing on evaluating VLRMs in the aspects of process understanding, outcome judgment, and critique generation. Extensive experiments are conducted on 21 open-source models and 5 advanced closed-source models, highlighting the challenges posed by VLRMBench. For instance, in the `Forecasting Future', a binary classification task, the advanced GPT-4o achieves only a 76.0% accuracy. Additionally, we perform comprehensive analytical studies, offering valuable insights for the future development of VLRMs. We anticipate that VLRMBench will serve as a pivotal benchmark in advancing VLRMs. Code and datasets will be available at https://github.com/JCruan519/VLRMBench.

[Arxiv](https://arxiv.org/abs/2503.07478)