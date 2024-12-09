# Diff4Steer：用于具有语义引导的生成音乐检索的可控扩散先验

发布时间：2024年12月05日

`LLM应用` `检索系统`

> Diff4Steer: Steerable Diffusion Prior for Generative Music Retrieval with Semantic Guidance

# 摘要

> 现代音乐检索系统往往依赖于用户偏好的固定表征，这限制了其捕捉用户多样且不确定的检索需求的能力。为突破这一局限，我们推出了 Diff4Steer 这一新颖的生成式检索框架，它运用轻量级扩散模型，从用户查询中合成多样的种子嵌入，这些嵌入代表着音乐探索的潜在方向。和将用户查询映射到嵌入空间单个点的确定性方法不同，Diff4Steer 为检索的目标模态（音频）提供了统计先验，有力地捕捉到用户偏好的不确定性和多面性。而且，Diff4Steer 能够由图像或文本输入来引导，结合最近邻搜索实现更灵活且可控的音乐发现。我们的框架在检索和排名指标上优于确定性回归方法和基于 LLM 的生成式检索基线，彰显了其在捕捉用户偏好方面的成效，带来了更多样且相关的推荐。收听示例可在 tinyurl.com/diff4steer 获取。

> Modern music retrieval systems often rely on fixed representations of user preferences, limiting their ability to capture users' diverse and uncertain retrieval needs. To address this limitation, we introduce Diff4Steer, a novel generative retrieval framework that employs lightweight diffusion models to synthesize diverse seed embeddings from user queries that represent potential directions for music exploration. Unlike deterministic methods that map user query to a single point in embedding space, Diff4Steer provides a statistical prior on the target modality (audio) for retrieval, effectively capturing the uncertainty and multi-faceted nature of user preferences. Furthermore, Diff4Steer can be steered by image or text inputs, enabling more flexible and controllable music discovery combined with nearest neighbor search. Our framework outperforms deterministic regression methods and LLM-based generative retrieval baseline in terms of retrieval and ranking metrics, demonstrating its effectiveness in capturing user preferences, leading to more diverse and relevant recommendations. Listening examples are available at tinyurl.com/diff4steer.

[Arxiv](https://arxiv.org/abs/2412.04746)