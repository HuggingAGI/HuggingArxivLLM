# 元学习在提示微调大语言模型中的冷启动个性化研究

发布时间：2025年07月22日

`LLM应用

摘要中讨论了将大型语言模型（LLM）应用于推荐系统，特别是在冷启动场景下的优化。论文提出了一种元学习框架，用于参数高效的提示微调，以提升推荐系统的个性化和实时性能。这些应用在金融系统中的实时风险配置文件中得到了验证，属于LLM的实际应用。因此，分类为LLM应用。` `推荐系统`

> Meta-Learning for Cold-Start Personalization in Prompt-Tuned LLMs

# 摘要

> 基于大型语言模型（LLM）的生成式、可解释且灵活的推荐系统虽然潜力巨大，但在冷启动用户场景（即几乎没有或完全没有交互历史）下表现不佳。现有的监督微调和协同过滤解决方案主要关注密集的用户-项目交互，维护和更新成本高昂。本文提出了一种元学习框架，用于执行参数高效的提示微调，从而在冷启动时快速有效地个性化基于LLM的推荐系统。模型通过将每个用户视为任务，利用一阶（Reptile）和二阶（MAML）优化学习软提示嵌入。这些可学习的向量作为输入令牌的增强，代表用户行为的先验知识，是可微分的控制变量。通过 episodic 采样、内循环适应和外循环泛化，提示在元优化过程中得到优化。在 MovieLens-1M、Amazon Reviews 和 Recbole 数据集上，我们的自适应模型在 NDCG@10、HR@10 和 MRR 等指标上超越了强大的基线模型，并且可以在实时（即低于 300 毫秒）在消费级 GPU 上运行。这种可扩展的解决方案还支持零历史记录的个性化，其 275 毫秒的适应速度通过缩短检测延迟和提高支付网络稳定性，成功实现了金融系统的实时风险配置文件。至关重要的是，275 毫秒的适应能力可以为金融机构实现实时风险配置文件，与传统的合规检查相比，显著减少了系统性脆弱性检测的延迟。通过防止支付网络（如 Fedwire）中的传染，该框架增强了国家金融基础设施的弹性。

> Generative, explainable, and flexible recommender systems, derived using Large Language Models (LLM) are promising and poorly adapted to the cold-start user situation, where there is little to no history of interaction. The current solutions i.e. supervised fine-tuning and collaborative filtering are dense-user-item focused and would be expensive to maintain and update. This paper introduces a meta-learning framework, that can be used to perform parameter-efficient prompt-tuning, to effectively personalize LLM-based recommender systems quickly at cold-start. The model learns soft prompt embeddings with first-order (Reptile) and second-order (MAML) optimization by treating each of the users as the tasks. As augmentations to the input tokens, these learnable vectors are the differentiable control variables that represent user behavioral priors. The prompts are meta-optimized through episodic sampling, inner-loop adaptation, and outer-loop generalization. On MovieLens-1M, Amazon Reviews, and Recbole, we can see that our adaptive model outperforms strong baselines in NDCG@10, HR@10, and MRR, and it runs in real-time (i.e., below 300 ms) on consumer GPUs. Zero-history personalization is also supported by this scalable solution, and its 275 ms rate of adaptation allows successful real-time risk profiling of financial systems by shortening detection latency and improving payment network stability. Crucially, the 275 ms adaptation capability can enable real-time risk profiling for financial institutions, reducing systemic vulnerability detection latency significantly versus traditional compliance checks. By preventing contagion in payment networks (e.g., Fedwire), the framework strengthens national financial infrastructure resilience.

[Arxiv](https://arxiv.org/abs/2507.16672)