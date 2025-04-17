# # 提升网络代理的显式回滚机制
为网络代理注入显式回滚机制，提升性能

发布时间：2025年04月16日

`Agent` `网络代理` `网络导航`

> Enhancing Web Agents with Explicit Rollback Mechanisms

# 摘要

> 得益于大型语言模型的突破性进展，网络代理的能力得到了显著提升。然而，面对复杂多变的网络环境，现有方法仍需更强大的规划与搜索能力。以往研究通常采用的贪婪单向搜索策略，在遇到错误状态时往往难以自洽恢复。本研究通过为网络代理引入显式的回滚机制，使其能够返回导航轨迹中的先前状态。这一机制赋予模型对搜索过程的直接控制权，从而形成了一种高效且有效的网络导航方法。我们在两个实时网络导航基准测试中进行了实验，分别采用零样本和微调设置。实验结果充分验证了我们提出方法的有效性。

> With recent advancements in large language models, web agents have been greatly improved. However, dealing with complex and dynamic web environments requires more advanced planning and search abilities. Previous studies usually adopt a greedy one-way search strategy, which may struggle to recover from erroneous states. In this work, we enhance web agents with an explicit rollback mechanism, enabling the agent to revert back to a previous state in its navigation trajectory. This mechanism gives the model the flexibility to directly control the search process, leading to an effective and efficient web navigation method. We conduct experiments on two live web navigation benchmarks with zero-shot and fine-tuning settings. The results demonstrate the effectiveness of our proposed approach.

[Arxiv](https://arxiv.org/abs/2504.11788)