# Select2Reason：面向长链推理的高效指令微调数据选择

发布时间：2025年05月22日

`LLM应用` `人工智能`

> Select2Reason: Efficient Instruction-Tuning Data Selection for Long-CoT Reasoning

# 摘要

> 激活预训练大型语言模型中长链式推理能力的实用方法，是通过监督微调在由强大型推理模型（如DeepSeek-R1）合成的指令数据集上进行训练，这为强化学习提供了一种更具成本效益的替代方案。然而，包含超过10万样本的大规模指令集会导致显著的训练开销，而针对自动长链式推理指令选择的有效策略仍然未被探索。在此研究中，我们提出了Select2Reason，这是一个用于长链式推理的新型高效指令微调数据选择框架。从重新思考行为（如自我修正和回溯）的出现角度出发，我们探讨了可能决定长链式推理指令质量的常见指标。Select2Reason通过一个量化器来评估问题难度，并通过加权方案结合基于推理轨迹长度的启发式方法，对数据进行排序，以优先选择高价值示例。在OpenR1-Math-220k数据集上的实证结果表明，仅对Select2Reason选择的10%数据进行微调，即可在三个竞赛级别和六个综合性数学基准测试中，使LLM的性能达到或超越全数据微调和开源基线OpenR1-Qwen-7B的表现。进一步的实验凸显了Select2Reason在数据规模上的可扩展性、推理过程中的效率，以及其以极低成本适应其他指令池的灵活性。

> A practical approach to activate long chain-of-thoughts reasoning ability in pre-trained large language models is to perform supervised fine-tuning on instruction datasets synthesized by strong Large Reasoning Models such as DeepSeek-R1, offering a cost-effective alternative to reinforcement learning. However, large-scale instruction sets with more than 100k samples incur significant training overhead, while effective strategies for automatic long-CoT instruction selection still remain unexplored. In this work, we propose Select2Reason, a novel and efficient instruction-tuning data selection framework for long-CoT reasoning. From the perspective of emergence of rethinking behaviors like self-correction and backtracking, we investigate common metrics that may determine the quality of long-CoT reasoning instructions. Select2Reason leverages a quantifier to estimate difficulty of question and jointly incorporates a reasoning trace length-based heuristic through a weighted scheme for ranking to prioritize high-utility examples. Empirical results on OpenR1-Math-220k demonstrate that fine-tuning LLM on only 10% of the data selected by Select2Reason achieves performance competitive with or superior to full-data tuning and open-source baseline OpenR1-Qwen-7B across three competition-level and six comprehensive mathematical benchmarks. Further experiments highlight the scalability in varying data size, efficiency during inference, and its adaptability to other instruction pools with minimal cost.

[Arxiv](https://arxiv.org/abs/2505.17266)