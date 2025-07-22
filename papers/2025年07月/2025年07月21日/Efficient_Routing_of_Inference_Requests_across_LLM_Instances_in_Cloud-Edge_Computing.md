# # 云边计算环境中 LLM 实例间推理请求的高效路由优化

发布时间：2025年07月21日

`LLM应用` `云计算` `分布式计算`

> Efficient Routing of Inference Requests across LLM Instances in Cloud-Edge Computing

# 摘要

> 大型语言模型（LLM）推理服务需求的激增，加剧了计算资源的压力，带来了延迟和成本的双重挑战。本文提出了一种基于非支配排序遗传算法II（NSGA-II）的创新路由算法，用于在云边计算环境中智能分配异构LLM实例的推理请求。该算法以多目标优化为核心，兼顾响应质量、响应速度和推理成本，灵活应对请求异质性（如不同复杂度和提示长度）以及节点多样性（如边缘与云资源）。这种自适应路由算法在动态工作负载下实现了性能的最优化。我们通过一个测试床进行了全面的基准测试，采用了包括斯坦福问答数据集（SQuAD）、大部分基础Python问题（MBPP）、HELLA情境与对抗生成（HellaSwag）以及小学数学8K（GSM8K）在内的多样化数据集。实验结果表明，相较于基准方法，我们的解决方案在响应时间和成本方面分别提升了95.2%和34.9%。这些结果充分验证了该算法在可扩展LLM部署中的显著有效性。

> The rising demand for Large Language Model (LLM) inference services has intensified pressure on computational resources, resulting in latency and cost challenges. This paper introduces a novel routing algorithm based on the Non-dominated Sorting Genetic Algorithm II (NSGA-II) to distribute inference requests across heterogeneous LLM instances in a cloud-edge computing environment. Formulated as a multi-objective optimization problem, the algorithm balances response quality, response time, and inference cost, adapting to request heterogeneity (e.g., varying complexity and prompt lengths) and node diversity (e.g., edge vs. cloud resources). This adaptive routing algorithm optimizes performance under dynamic workloads. We benchmark the approach using a testbed with datasets including Stanford Question Answering Dataset (SQuAD), Mostly Basic Python Problems (MBPP), Hella Situations With Adversarial Generations (HellaSwag), and Grade School Math 8K (GSM8K). Experimental results show our solution, compared to the baselines, achieves up to 95.2% and 34.9% improvements in terms of response time and cost, respectively. These findings validate the algorithm's effectiveness for scalable LLM deployments.

[Arxiv](https://arxiv.org/abs/2507.15553)