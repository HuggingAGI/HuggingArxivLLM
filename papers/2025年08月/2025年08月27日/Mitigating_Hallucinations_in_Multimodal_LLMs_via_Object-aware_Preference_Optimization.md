# 基于对象感知偏好优化缓解多模态大型语言模型的幻觉

发布时间：2025年08月27日

`LLM应用` `基础理论`

> Mitigating Hallucinations in Multimodal LLMs via Object-aware Preference Optimization

# 摘要

> 多模态大型语言模型（MLLMs）已成为处理从自然语言处理到计算机视觉等多种任务的统一接口。尽管在众多基准测试中表现出最先进的性能，但MLLMs长期存在的问题是容易产生幻觉——即生成的用户查询答案与视觉输入不符。本文将幻觉问题视为对齐问题，旨在引导MLLM倾向于生成无幻觉的内容。与近期需要构建复杂流程来生成对齐训练用的合成偏好数据（且往往依赖专有模型）的方法不同，我们借助著名的CHAIR指标——该指标最初用于衡量图像描述的幻觉程度。对于一对生成答案，我们利用CHAIR区分优胜（非幻觉）和劣势（幻觉）样本，并通过直接偏好优化（DPO）微调现成的MLLMs。我们将此方法命名为CHAIR-DPO，它在多个幻觉基准测试中有效减少了幻觉答案的数量，证明了基于CHAIR奖励微调MLLM的有效性。源代码和训练模型已在https://github.com/aimagelab/CHAIR-DPO公开。

> Multimodal Large Language Models (MLLMs) emerge as a unified interface to address a multitude of tasks, ranging from NLP to computer vision. Despite showcasing state-of-the-art results in many benchmarks, a long-standing issue is the tendency of MLLMs to hallucinate, that is to generate answers to the user's query that are not reflected in the visual input. In this paper, we address the problem of hallucinations as an alignment problem, seeking to steer the MLLM so that it prefers generating content without hallucinations. In contrast to recent approaches that require complicated pipelines to build synthetic preference data for alignment training, often relying on proprietary models, we capitalize on the well-known CHAIR metric, originally proposed to gauge the degree of hallucinations in image captioning. Given a pair of generated answers, we leverage CHAIR to distinguish winner and loser options (i.e., non-hallucinated and hallucinated samples) and fine-tune off-the-shelf MLLMs via Direct Preference Optimization (DPO). The resulting method, which we refer to as CHAIR-DPO, effectively diminishes the amount of hallucinated answers on several hallucination benchmarks, demonstrating the effectiveness of fine-tuning the MLLM with a CHAIR-based reward. Source code and trained models are publicly available at https://github.com/aimagelab/CHAIR-DPO.

[Arxiv](https://arxiv.org/abs/2508.20181)