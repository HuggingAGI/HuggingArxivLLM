# AMQ：实现AutoML在大型语言模型混合精度仅权重量化中的应用

发布时间：2025年09月15日

`LLM应用` `基础理论`

> AMQ: Enabling AutoML for Mixed-precision Weight-Only Quantization of Large Language Models

# 摘要

> 为推动大型语言模型（LLMs）的更广泛应用，关键在于找到严格内存限制下性能最优的模型。为此，我们提出AMQ（自动化混合精度仅权重量化）框架——它通过为每层分配量化位宽，实现模型质量与内存占用的优化平衡。但组合搜索空间存在超过【数学公式】种可能配置，传统黑盒优化方法因此难以奏效。AMQ通过四项核心创新攻克了这一难题：(1) 借助先验知识修剪搜索空间，排除无前景配置；(2) 引入量化代理，避免搜索过程中高昂的格式转换成本；(3) 利用质量预测器减少评估开销；(4) 采用迭代搜索-更新策略，实现快速稳定收敛。整合这些组件后，AMQ能高效探索质量-效率空间，最终达到帕累托前沿，生成既紧凑又高性能的LLMs。相关代码可访问https://github.com/dlwns147/amq获取。

> To enable broader deployment of Large Language Models (LLMs), it is essential to identify the best-performing model under strict memory constraints. We present AMQ, Automated Mixed-Precision Weight-Only Quantization, a framework that assigns layer-wise quantization bit-widths to optimally balance model quality and memory usage. However, the combinatorial search space, with over 10^{100} possible configurations, makes conventional black-box optimization infeasible. AMQ overcomes this challenge through four key innovations:(1) search space pruning using prior knowledge to exclude unpromising configurations, (2) quantization proxy to bypass costly format conversions during search, (3) quality predictor to minimize evaluation overhead, and (4) iterative search-and-update strategy for fast and stable convergence. By integrating these components, AMQ efficiently explores the quality-efficiency landscape, reaching the Pareto frontier and yielding LLMs that are both compact and high-performing. Our code is available at https://github.com/dlwns147/amq.

[Arxiv](https://arxiv.org/abs/2509.12019)