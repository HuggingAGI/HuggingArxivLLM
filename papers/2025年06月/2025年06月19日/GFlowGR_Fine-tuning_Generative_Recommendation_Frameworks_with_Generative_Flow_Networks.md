# GFlowGR: 基于生成流网络的生成推荐框架微调方法

发布时间：2025年06月19日

`LLM应用` `电子商务` `推荐系统`

> GFlowGR: Fine-tuning Generative Recommendation Frameworks with Generative Flow Networks

# 摘要

> 生成推荐（GR），结合物品编码器和生成型大型语言模型（LLMs），在多个场景下表现优异。目前研究多聚焦于提升物品编码器性能或优化LLMs解码策略，但关键的微调步骤——使LLMs适应推荐数据——却鲜少被深入探索。现有方法主要依赖监督式微调（SFT）的下一个令牌预测损失，或特定推荐任务的直接偏好优化（DPO）策略，却忽视了潜在未观察正样本的探索，即曝光偏差问题。本文将GR视为多步骤生成任务，提出基于GFlowNets的微调框架（GFlowGR）。该框架整合传统推荐系统中的协作知识，构建自适应轨迹采样器和全面奖励模型。借助GFlowNets的多样化生成特性，结合采样与启发式加权技术，GFlowGR有效缓解了曝光偏差问题。在真实数据集和不同GR骨干模型上的实验证明了其卓越效果与稳定性。

> Generative recommendations (GR), which usually include item tokenizers and generative Large Language Models (LLMs), have demonstrated remarkable success across a wide range of scenarios. The majority of existing research efforts primarily concentrate on developing powerful item tokenizers or advancing LLM decoding strategies to attain superior performance. However, the critical fine-tuning step in GR frameworks, which is essential for adapting LLMs to recommendation data, remains largely unexplored. Current approaches predominantly rely on either the next-token prediction loss of supervised fine-tuning (SFT) or recommendationspecific direct preference optimization (DPO) strategies. Both methods ignore the exploration of possible positive unobserved samples, which is commonly referred to as the exposure bias problem. To mitigate this problem, this paper treats the GR as a multi-step generation task and constructs a GFlowNets-based fine-tuning framework (GFlowGR). The proposed framework integrates collaborative knowledge from traditional recommender systems to create an adaptive trajectory sampler and a comprehensive reward model. Leveraging the diverse generation property of GFlowNets, along with sampling and heuristic weighting techniques, GFlowGR emerges as a promising approach to mitigate the exposure bias problem. Extensive empirical results on two real-world datasets and with two different GR backbones highlight the effectiveness and robustness of GFlowGR.

[Arxiv](https://arxiv.org/abs/2506.16114)