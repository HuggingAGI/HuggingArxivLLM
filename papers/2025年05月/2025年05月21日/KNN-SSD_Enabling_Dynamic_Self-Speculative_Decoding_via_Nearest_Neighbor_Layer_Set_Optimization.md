# KNN-SSD：通过最近邻层集优化实现动态自推测解码

发布时间：2025年05月21日

`LLM应用` `大型语言模型` `领域适应`

> KNN-SSD: Enabling Dynamic Self-Speculative Decoding via Nearest Neighbor Layer Set Optimization

# 摘要

> Speculative Decoding（SD）作为一种高效加速大型语言模型（LLMs）推理的范式，备受青睐，同时保持了生成质量。其核心在于：通过高效利用紧凑模型并行起草多个令牌，随后借助目标LLM进行验证。值得注意的是，自我推测解码（Self-Speculative Decoding）创新性地提出跳过特定层构建草稿模型，完全避免了额外参数或训练的需求。然而，我们在研究中发现，跳层起草方法在面对领域偏移时表现出显著的敏感性，导致加速性能大幅下滑。为了解决这一问题，我们提出了KNN-SSD算法，该算法巧妙地运用K-近邻（KNN）搜索技术，实现不同跳层与多样化领域输入的精准匹配。经过在多种模型和多项任务上的测试，结果表明，KNN-SSD的应用可使LLM推理速度提升1.3至1.6倍，显著提升了该范式的领域适应能力。

> Speculative Decoding (SD) has emerged as a widely used paradigm to accelerate the inference of large language models (LLMs) without compromising generation quality. It works by efficiently drafting multiple tokens using a compact model and then verifying them in parallel using the target LLM. Notably, Self-Speculative Decoding proposes skipping certain layers to construct the draft model, which eliminates the need for additional parameters or training. Despite its strengths, we observe in this work that drafting with layer skipping exhibits significant sensitivity to domain shifts, leading to a substantial drop in acceleration performance. To enhance the domain generalizability of this paradigm, we introduce KNN-SSD, an algorithm that leverages K-Nearest Neighbor (KNN) search to match different skipped layers with various domain inputs. We evaluated our algorithm in various models and multiple tasks, observing that its application leads to 1.3x-1.6x speedup in LLM inference.

[Arxiv](https://arxiv.org/abs/2505.16162)