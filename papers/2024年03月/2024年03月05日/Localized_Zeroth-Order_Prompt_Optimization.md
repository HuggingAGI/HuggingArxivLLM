# 针对局部化的零阶提示优化技术，该方法利用零阶优化策略对模型的提示进行微调，特别是在特定任务或领域中，以提升模型的表现和适应性。

发布时间：2024年03月05日

`LLM理论`

> Localized Zeroth-Order Prompt Optimization

# 摘要

> LLMs在处理自然语言上的强大能力激发了人们对如何运用黑盒LLMs的研究热情，进而催生了一系列基于提示的方法。然而，当前多数方法过于侧重于全局最优的寻求，却在特定任务上不尽人意，这促使我们反思是否有必要在提示优化中始终坚持找寻全局最优解。经过对提示优化的全面实证探究，我们得到两大关键发现：首先，相较于罕见的全局最优，局部最优解往往普遍存在且表现出色，它们在追求高效提示优化时更具价值（洞察 I）；其次，输入域的选择，既关乎提示生成也涉及其表达方式，会直接影响到能否识别出优秀的局部最优解（洞察 II）。基于这两点洞察，我们创新性地提出了名为“局部零阶提示优化”（ZOPO）的新算法，它巧妙地将基于神经张量核推导出的高斯过程融入标准零阶优化框架中，以期在提示优化过程中更高效地定位并锁定表现卓越的局部最优解。令人瞩目的是，ZOPO在优化性能和查询效率两方面均超过了现有的基准方法，这一结论已在大量的实验中得到了验证。

> The efficacy of large language models (LLMs) in understanding and generating natural language has aroused a wide interest in developing prompt-based methods to harness the power of black-box LLMs. Existing methodologies usually prioritize a global optimization for finding the global optimum, which however will perform poorly in certain tasks. This thus motivates us to re-think the necessity of finding a global optimum in prompt optimization. To answer this, we conduct a thorough empirical study on prompt optimization and draw two major insights. Contrasting with the rarity of global optimum, local optima are usually prevalent and well-performed, which can be more worthwhile for efficient prompt optimization (Insight I). The choice of the input domain, covering both the generation and the representation of prompts, affects the identification of well-performing local optima (Insight II). Inspired by these insights, we propose a novel algorithm, namely localized zeroth-order prompt optimization (ZOPO), which incorporates a Neural Tangent Kernel-based derived Gaussian process into standard zeroth-order optimization for an efficient search of well-performing local optima in prompt optimization. Remarkably, ZOPO outperforms existing baselines in terms of both the optimization performance and the query efficiency, which we demonstrate through extensive experiments.

[Arxiv](https://arxiv.org/abs/2403.02993)