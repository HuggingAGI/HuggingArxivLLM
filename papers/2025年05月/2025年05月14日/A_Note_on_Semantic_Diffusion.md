# # 语义扩散探索：一些初步思考

发布时间：2025年05月14日

`LLM应用` `生成模型`

> A Note on Semantic Diffusion

# 摘要

> 本文深入探讨了语义扩散作为大型语言模型（LLMs）在设计应用中的补充工具。传统LLMs和扩散模型无法诱导出收敛的迭代改进过程：每次调用扩散机制都会生成新的随机循环，导致连续输出彼此无关，无法保证收敛到理想设计。本文提出的"LLM + 语义扩散"混合框架通过强制执行近似收敛的搜索过程解决了这一限制，正式解决了局部设计改进的问题。

> This paper provides an in-depth examination of the concept of semantic diffusion as a complementary instrument to large language models (LLMs) for design applications. Conventional LLMs and diffusion models fail to induce a convergent, iterative refinement process: each invocation of the diffusion mechanism spawns a new stochastic cycle, so successive outputs do not relate to prior ones and convergence toward a desired design is not guaranteed. The proposed hybrid framework - "LLM + semantic diffusion" - resolves this limitation by enforcing an approximately convergent search procedure, thereby formally addressing the problem of localized design refinement.

[Arxiv](https://arxiv.org/abs/2505.09283)