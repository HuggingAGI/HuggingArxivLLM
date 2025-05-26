# PreMoe: 在受限内存环境下，通过专家剪枝和检索优化 MoEs

发布时间：2025年05月23日

`LLM理论` `模型优化` `模型部署`

> PreMoe: Lightening MoEs on Constrained Memory by Expert Pruning and Retrieval

# 摘要

> 专家混合模型 (MoE) 架构使大型语言模型 (LLMs) 能够扩展到巨大的参数数量，而不会导致计算成本成比例增加。然而，大型 MoE 模型的显著内存需求阻碍了它们在各种计算环境中的部署，从云服务器到消费级设备。本研究首先展示了在 MoE 层中，专家激活模式展现出显著的任务特异性专业化的特征。基于此，我们提出了一种名为 PreMoe 的创新框架，旨在实现在内存受限环境中高效部署大规模 MoE 模型的目标。PreMoe 包含两个核心组件：概率化专家剪枝 (PEP) 和任务自适应专家检索 (TAER)。PEP 引入了一种全新的指标——任务条件化预期选择分数 (TCESS)，该指标由路由器的 logits 推导而来，用于量化特定任务下专家的重要性，从而识别出一组关键的最小专家集合。TAER 则利用这些任务特定的专家重要性配置文件进行高效推理。它预先计算并存储了适用于多种任务的紧凑专家模式。当接收到用户查询时，TAER 迅速识别出最相关的预存任务模式，并仅加载对当前任务至关重要的少量专家子集来重建模型。这种方法在所有部署场景下都极大地减少了内存占用。DeepSeek-R1 671B 在剪枝到 8/128 配置（50% 专家减少）时在 MATH500 上保持了 97.2% 的准确率，即使在激进的 8/32 剪枝（87.5% 专家减少）下仍能达到 72.0%。Pangu-Ultra-MoE 718B 在 8/128 剪枝下实现了 97.15% 的 MATH500 准确率和 81.3% 的 AIME24 准确率，而即使采用更为激进的 4/64 剪枝（内存占用 390GB），其在 MATH500 上仍保持 96.95% 的准确率。我们公开发布了我们的代码，可在 https://github.com/JarvisPei/PreMoe 获取。


> Mixture-of-experts (MoE) architectures enable scaling large language models (LLMs) to vast parameter counts without a proportional rise in computational costs. However, the significant memory demands of large MoE models hinder their deployment across various computational environments, from cloud servers to consumer devices. This study first demonstrates pronounced task-specific specialization in expert activation patterns within MoE layers. Building on this, we introduce PreMoe, a novel framework that enables efficient deployment of massive MoE models in memory-constrained environments. PreMoe features two main components: probabilistic expert pruning (PEP) and task-adaptive expert retrieval (TAER). PEP employs a new metric, the task-conditioned expected selection score (TCESS), derived from router logits to quantify expert importance for specific tasks, thereby identifying a minimal set of critical experts. TAER leverages these task-specific expert importance profiles for efficient inference. It pre-computes and stores compact expert patterns for diverse tasks. When a user query is received, TAER rapidly identifies the most relevant stored task pattern and reconstructs the model by loading only the small subset of experts crucial for that task. This approach dramatically reduces the memory footprint across all deployment scenarios. DeepSeek-R1 671B maintains 97.2\% accuracy on MATH500 when pruned to 8/128 configuration (50\% expert reduction), and still achieves 72.0\% with aggressive 8/32 pruning (87.5\% expert reduction). Pangu-Ultra-MoE 718B achieves 97.15\% on MATH500 and 81.3\% on AIME24 with 8/128 pruning, while even more aggressive pruning to 4/64 (390GB memory) preserves 96.95\% accuracy on MATH500. We make our code publicly available at https://github.com/JarvisPei/PreMoe.

[Arxiv](https://arxiv.org/abs/2505.17639)