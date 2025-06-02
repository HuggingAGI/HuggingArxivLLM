# HardTests：为LLM编程生成高质量测试用例

发布时间：2025年05月29日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）生成高质量的测试用例，用于验证和评估LLM生成的代码。具体来说，它提出了一种名为HARDTESTGEN的流水线，用于合成测试用例，并展示了这种方法在提高评估准确性和召回率方面的有效性。这一应用属于将LLMs应用于实际问题解决的范畴，因此归类为LLM应用。` `编程竞赛` `软件工程`

> HardTests: Synthesizing High-Quality Test Cases for LLM Coding

# 摘要

> 验证器在LLM推理中发挥着关键作用，被强化学习等后训练技术所依赖。然而，对于复杂的编码问题，获得可靠的验证器非常困难，因为一个伪装良好的错误解决方案可能只有通过精心设计的人工编写的边界测试用例才能被检测到，而这些测试用例难以合成。为了解决这一问题，我们提出了HARDTESTGEN，一个利用LLMs进行高质量测试合成的流水线。通过这一流水线，我们整理了一个全面的编程竞赛数据集HARDTESTS，包含47,000个问题和合成的高质量测试用例。与现有测试相比，HARDTESTGEN生成的测试在评估LLM生成代码时，精确度提高了11.3个百分点，召回率提高了17.5个百分点。对于更难的问题，精确度的提升可以高达40个百分点。HARDTESTS也被证明在模型训练中更为有效，通过下游代码生成性能进行衡量。我们将在https://leililab.github.io/HardTests/开源我们的数据集和合成流水线。

> Verifiers play a crucial role in large language model (LLM) reasoning, needed by post-training techniques such as reinforcement learning. However, reliable verifiers are hard to get for difficult coding problems, because a well-disguised wrong solution may only be detected by carefully human-written edge cases that are difficult to synthesize. To address this issue, we propose HARDTESTGEN, a pipeline for high-quality test synthesis using LLMs. With this pipeline, we curate a comprehensive competitive programming dataset HARDTESTS with 47k problems and synthetic high-quality tests. Compared with existing tests, HARDTESTGEN tests demonstrate precision that is 11.3 percentage points higher and recall that is 17.5 percentage points higher when evaluating LLM-generated code. For harder problems, the improvement in precision can be as large as 40 points. HARDTESTS also proves to be more effective for model training, measured by downstream code generation performance. We will open-source our dataset and synthesis pipeline at https://leililab.github.io/HardTests/.

[Arxiv](https://arxiv.org/abs/2505.24098)