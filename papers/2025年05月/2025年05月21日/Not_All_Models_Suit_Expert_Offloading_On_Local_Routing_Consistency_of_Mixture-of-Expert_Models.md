# # 摘要  
最近大型语言模型 (LLMs) 的突破性进展引领了一场从机器人流程自动化 (RPA) 到智能体流程自动化 (AgPAA) 的革命性转变，这一转变通过基于 LLMs 自动化工作流编排过程实现。

发布时间：2025年05月21日

`LLM理论` `模型优化` `资源管理`

> Not All Models Suit Expert Offloading: On Local Routing Consistency of Mixture-of-Expert Models

# 摘要

> 专家混合模型 (MoE) 通过在推理过程中稀疏激活专家，实现了大型语言模型 (LLM) 的高效扩展。为了在内存受限设备上有效部署大型 MoE 模型，许多系统引入了 *专家卸载* 策略，将部分专家缓存到快速内存中，而将其他专家留在慢速内存中运行在 CPU 上或按需加载。尽管一些研究利用了专家激活的局部性，即连续的标记激活相似的专家，但这种 **局部路由一致性** 的程度在不同模型间存在差异且尚未得到充分研究。本文中，我们提出了两个指标来衡量 MoE 模型的局部路由一致性：(1) **分段路由最佳性能 (SRP)**，评估一组固定专家如何能够满足一段标记的需求；(2) **分段缓存最佳命中率 (SCH)**，衡量在给定缓存大小限制下的最优分段级缓存命中率。我们分析了 20 个具有不同规模和架构的 MoE LLM，并发现将 MoE 应用于每一层且不使用共享专家的模型具有最高的局部路由一致性。我们进一步展示了领域专用专家对路由一致性的影响大于词汇专用专家，并且大多数模型可以在缓存大小约为活跃专家的 2 倍时，在缓存有效性和效率之间取得平衡。这些发现为设计和部署内存高效的 MoE 模型铺平了道路，而不会牺牲推理速度。我们已在 https://github.com/ljcleo/moe-lrc 公布了实验复现代码。

> Mixture-of-Experts (MoE) enables efficient scaling of large language models (LLMs) with sparsely activated experts during inference. To effectively deploy large MoE models on memory-constrained devices, many systems introduce *expert offloading* that caches a subset of experts in fast memory, leaving others on slow memory to run on CPU or load on demand. While some research has exploited the locality of expert activations, where consecutive tokens activate similar experts, the degree of this **local routing consistency** varies across models and remains understudied. In this paper, we propose two metrics to measure local routing consistency of MoE models: (1) **Segment Routing Best Performance (SRP)**, which evaluates how well a fixed group of experts can cover the needs of a segment of tokens, and (2) **Segment Cache Best Hit Rate (SCH)**, which measures the optimal segment-level cache hit rate under a given cache size limit. We analyzed 20 MoE LLMs with diverse sizes and architectures and found that models that apply MoE on every layer and do not use shared experts exhibit the highest local routing consistency. We further showed that domain-specialized experts contribute more to routing consistency than vocabulary-specialized ones, and that most models can balance between cache effectiveness and efficiency with cache sizes approximately 2x the active experts. These findings pave the way for memory-efficient MoE design and deployment without compromising inference speed. We publish the code for replicating experiments at https://github.com/ljcleo/moe-lrc .

[Arxiv](https://arxiv.org/abs/2505.16056)