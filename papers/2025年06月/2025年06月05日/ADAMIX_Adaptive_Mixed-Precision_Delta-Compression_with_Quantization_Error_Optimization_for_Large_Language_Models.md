# ADAMIX：面向大规模语言模型的自适应混合精度增量压缩，基于量化误差优化

发布时间：2025年06月05日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的delta压缩方法，提出了一种新的自适应混合精度压缩框架ADAMIX。它涉及模型优化和压缩策略的理论研究，属于LLM理论范畴。` `大型语言模型` `模型压缩`

> ADAMIX: Adaptive Mixed-Precision Delta-Compression with Quantization Error Optimization for Large Language Models

# 摘要

> 大型语言模型（LLMs）在跨领域知识密集型和复杂推理任务中表现卓越。特别是在多租户服务等场景下，大量基于同一基础模型微调的LLMs被部署以满足用户的多样化需求。近期研究探索了通过量化和压缩定制LLM与其基础模型间delta参数的delta压缩方法。然而，现有方法或在高压缩比下效果欠佳，或依赖经验比特分配方案。本研究提出ADAMIX，一种有效的自适应混合精度delta压缩框架。我们通过数学推导量化误差，支持混合精度压缩策略，并将最优混合精度比特分配方案建模为0/1整数线性规划问题的解。该策略在满足预设压缩比的前提下，最小化量化误差。实验结果表明，ADAMIX在多个模型和基准测试中显著超越现有最佳基线。特别是在AIME2024和GQA任务中，当ΔW的范数较大且基础模型能力不足时，ADAMIX分别以7B模型超越Delta-CoMe基线22.3%和6.1%。

> Large language models (LLMs) achieve impressive performance on various knowledge-intensive and complex reasoning tasks in different domains. In certain scenarios like multi-tenant serving, a large number of LLMs finetuned from the same base model are deployed to meet complex requirements for users. Recent works explore delta-compression approaches to quantize and compress the delta parameters between the customized LLM and the corresponding base model. However, existing works either exhibit unsatisfactory performance at high compression ratios or depend on empirical bit allocation schemes. In this work, we propose ADAMIX, an effective adaptive mixed-precision delta-compression framework. We provide a mathematical derivation of quantization error to motivate our mixed-precision compression strategy and formulate the optimal mixed-precision bit allocation scheme as the solution to a 0/1 integer linear programming problem. Our derived bit allocation strategy minimizes the quantization error while adhering to a predefined compression ratio requirement. Experimental results on various models and benchmarks demonstrate that our approach surpasses the best baseline by a considerable margin. On tasks like AIME2024 and GQA, where the norm of $Δ\mathbf{W}$ is large and the base model lacks sufficient ability, ADAMIX outperforms the best baseline Delta-CoMe by 22.3% and 6.1% with 7B models, respectively.

[Arxiv](https://arxiv.org/abs/2506.11087)