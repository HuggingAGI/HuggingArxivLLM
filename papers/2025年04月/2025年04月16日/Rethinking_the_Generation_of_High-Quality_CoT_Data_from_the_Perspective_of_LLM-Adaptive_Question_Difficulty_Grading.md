# # 从LLM自适应问题难度分级的视角，重新思考如何生成高质量的CoT数据

发布时间：2025年04月16日

`LLM应用` `人工智能`

> Rethinking the Generation of High-Quality CoT Data from the Perspective of LLM-Adaptive Question Difficulty Grading

# 摘要

> 最近，DeepSeek-R1 (671B) (DeepSeek-AI 等人，2025) 在复杂任务中展现了其出色的推理能力，并公开了其方法论。这为激发小型大语言模型的推理能力提供了高质量的思维链 (CoT) 数据支持。为了生成适用于不同大语言模型 (LLM) 的高质量 CoT 数据，我们提出了一种高效方法，能够根据 LLM 的适应性调整问题难度，从而生成高质量的 CoT 数据。首先，我们根据 LLM 本身的推理能力对问题难度进行分级，并构建一个 LLM 适应性问题数据库。其次，我们根据问题难度分布对问题数据库进行采样，然后使用 DeepSeek-R1 (671B) 生成对应难度的高质量 CoT 数据及正确答案。得益于这种 LLM 适应性难度分级的 CoT 数据构建方法，我们显著降低了数据生成成本，并提升了模型监督微调 (SFT) 的效率。最后，我们在复杂数学竞赛和代码生成任务领域验证了所提方法的有效性和通用性。值得注意的是，仅使用 2k 高质量数学 CoT 数据，我们的 ZMath-32B 在数学推理任务中超越了 DeepSeek-Distill-32B。同样地，仅使用 2k 高质量代码 CoT 数据，我们的 ZCode-32B 在代码推理任务中也超越了 DeepSeek-Distill-32B。

> Recently, DeepSeek-R1 (671B) (DeepSeek-AIet al., 2025) has demonstrated its excellent reasoning ability in complex tasks and has publiclyshared its methodology. This provides potentially high-quality chain-of-thought (CoT) data for stimulating the reasoning abilities of small-sized large language models (LLMs). To generate high-quality CoT data for different LLMs, we seek an efficient method for generating high-quality CoT data with LLM-Adaptive questiondifficulty levels. First, we grade the difficulty of the questions according to the reasoning ability of the LLMs themselves and construct a LLM-Adaptive question database. Second, we sample the problem database based on a distribution of difficulty levels of the questions and then use DeepSeek-R1 (671B) (DeepSeek-AI et al., 2025) to generate the corresponding high-quality CoT data with correct answers. Thanks to the construction of CoT data with LLM-Adaptive difficulty levels, we have significantly reduced the cost of data generation and enhanced the efficiency of model supervised fine-tuning (SFT). Finally, we have validated the effectiveness and generalizability of the proposed method in the fields of complex mathematical competitions and code generation tasks. Notably, with only 2k high-quality mathematical CoT data, our ZMath-32B surpasses DeepSeek-Distill-32B in math reasoning task. Similarly, with only 2k high-quality code CoT data, our ZCode-32B surpasses DeepSeek-Distill-32B in code reasoning tasks.

[Arxiv](https://arxiv.org/abs/2504.11919)