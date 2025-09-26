# 思维融合：学会聚合专家的所思，而非仅仅他们所言

发布时间：2025年09月25日

`LLM应用` `基础理论`

> Mixture of Thoughts: Learning to Aggregate What Experts Think, Not Just What They Say

# 摘要

> 开源大型语言模型（LLMs）正日益按领域（如数学、代码、通用推理）实现专业化，这推动了能够融合各模型互补优势的系统研发。以往的多LLM方法主要分为三类：（i）将查询路由至单个或少数专家模型并独立生成结果；（ii）通过代价高昂的多轮交互聚合各模型输出；（iii）将权重融合为单一模型——但这通常要求模型架构同构。为此，我们提出思维混合（Mixture of Thoughts，MoT）——一种基于全局路由机制、实现异构专家模型潜在层协作的简洁方法。针对每个查询，轻量级路由器会筛选出top-$K$个专家模型并指定一个主专家；均匀分布的交互层将隐藏状态投影到共享潜在空间，主专家通过交叉注意力机制与活跃（选定的）同伴模型进行交互。预训练专家模型保持参数冻结；仅对路由器和轻量级交互层进行训练，并采用一种新的联合训练目标，以同时优化专家选择和专家间协作效果。在五个分布内（ID）和三个分布外（OOD）基准测试中，MoT分别比当前基于路由和聚合的最先进方法Avengers高出0.38%和2.92%。此外，MoT的性能也显著超越了最优的单个模型。MoT仅需单遍推理即可实现上述性能，运行时间与路由基线方法相当，且完全避免了迭代聚合带来的额外开销。MoT为融合异构LLM提供了一种简洁的潜在空间协作机制，为实现更广泛的多LLM协同应用迈出了实用的一步。相关代码已开源，地址为https://github.com/jacobfa/mot。

> Open-source Large Language Models (LLMs) increasingly specialize by domain (e.g., math, code, general reasoning), motivating systems that leverage complementary strengths across models. Prior multi-LLM approaches either (i) route a query to one or a few experts and generate independently, (ii) aggregate outputs from each model via costly multi-turn exchanges, or (iii) fuse weights into a single model-typically requiring architectural homogeneity. We introduce Mixture of Thoughts (MoT), a simple method for latent-level collaboration among heterogeneous experts under a global routing scheme. For each query, a lightweight router selects top-$K$ experts and designates a primary expert; uniformly placed interaction layers project hidden states into a shared latent space where the primary expert performs cross-attention over its active (selected) peers. Pre-trained experts remain frozen; only the router and the lightweight interaction layers are trained with a novel joint training objective that improves both the expert selection and inter-expert collaboration. Across five in-distribution (ID) and three out-of-distribution (OOD) benchmarks, MoT surpasses the current routing and aggregation-based state-of-the-art, Avengers, by $+0.38\%$ and $+2.92\%$, respectively. Further, MoT significantly outperforms the best-performing single model. It achieves this with single-pass inference, runtime comparable to routing baselines, and none of the overheads of iterative aggregation. MoT offers a simple latent-space mechanism for combining heterogeneous LLMs, a practical step toward broader multi-LLM collaboration. Our code is publicly available at https://github.com/jacobfa/mot.

[Arxiv](https://arxiv.org/abs/2509.21164)