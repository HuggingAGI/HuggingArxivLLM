# # 低复杂度语义数据包聚合：利用前瞻搜索优化令牌通信

发布时间：2025年06月24日

`LLM应用` `生成式AI`

> Low-Complexity Semantic Packet Aggregation for Token Communication via Lookahead Search

# 摘要

> Token是生成式AI（GenAI）和大型语言模型（LLMs）的基本处理单元，而Token通信（TC）是实现远程AI生成内容（AIGC）和无线LLM应用的关键所在。与传统比特不同，Token的语义依赖于其上下文环境，这种依赖性使得TC在面对信道中断时尤为脆弱，单个Token的丢失可能导致原始消息语义的严重扭曲。为此，本文专注于优化Token分组策略，旨在最大化中断信道下原始与接收Token消息间的平均相似度（ATS）。由于Token间的强依赖性，这一问题具有组合复杂性，其复杂度随消息长度呈指数级增长。为应对这一挑战，我们提出了一种名为语义包聚合（SemPA-Look）的创新框架，该框架基于两大核心理念。首先，引入残差语义分数（RSS）作为消息级ATS的Token级代理，确保即使部分Token包丢失，仍能实现稳健的语义保留。其次，SemPA-Look采用前瞻搜索启发的算法，在固定深度下无放回地采样包内Token候选，同时在固定宽度下有放回地采样包间Token候选，从而实现线性复杂度。实验结果表明，在MS-COCO数据集（带文本描述的图像）上的远程AIGC任务中，SemPA-Look在ATS和LPIPS评分上达到了与穷举搜索相当的高水平，同时将计算复杂度降低了多达40倍。与遗传算法（GA）等其他线性复杂度算法相比，SemPA-Look的复杂度降低了10倍，充分证明了其在远程AIGC和其他Token通信应用中的实际价值。

> Tokens are fundamental processing units of generative AI (GenAI) and large language models (LLMs), and token communication (TC) is essential for enabling remote AI-generate content (AIGC) and wireless LLM applications. Unlike traditional bits, each of which is independently treated, the semantics of each token depends on its surrounding context tokens. This inter-token dependency makes TC vulnerable to outage channels, where the loss of a single token can significantly distort the original message semantics. Motivated by this, this paper focuses on optimizing token packetization to maximize the average token similarity (ATS) between the original and received token messages under outage channels. Due to inter-token dependency, this token grouping problem is combinatorial, with complexity growing exponentially with message length. To address this, we propose a novel framework of semantic packet aggregation with lookahead search (SemPA-Look), built on two core ideas. First, it introduces the residual semantic score (RSS) as a token-level surrogate for the message-level ATS, allowing robust semantic preservation even when a certain token packet is lost. Second, instead of full search, SemPA-Look applies a lookahead search-inspired algorithm that samples intra-packet token candidates without replacement (fixed depth), conditioned on inter-packet token candidates sampled with replacement (fixed width), thereby achieving linear complexity. Experiments on a remote AIGC task with the MS-COCO dataset (text captioned images) demonstrate that SemPA-Look achieves high ATS and LPIPS scores comparable to exhaustive search, while reducing computational complexity by up to 40$\times$. Compared to other linear-complexity algorithms such as the genetic algorithm (GA), SemPA-Look achieves 10$\times$ lower complexity, demonstrating its practicality for remote AIGC and other TC applications.

[Arxiv](https://arxiv.org/abs/2506.19451)