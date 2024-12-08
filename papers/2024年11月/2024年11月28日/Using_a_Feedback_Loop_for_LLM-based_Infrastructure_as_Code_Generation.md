# 利用基于 LLM 的基础设施即代码生成的反馈环

发布时间：2024年11月28日

`Agent` `软件开发` `基础设施管理`

> Using a Feedback Loop for LLM-based Infrastructure as Code Generation

# 摘要

> 使用大型语言模型（LLMs）生成代码有助于提升软件开发人员在编码任务中的效率，然而对于围绕代码的软件开发人员的任务尚未产生显著影响。特别是，基础设施管理这一挑战仍是未解之谜。我们探究了 LLM 代理运用基础设施即代码（IaC）范式构建基础设施的能力。我们尤其研究了使用反馈回路，其能返回生成的 IaC 中的错误和警告，以便 LLM 代理改进代码。我们发现，对于该回路的每次迭代，其有效性呈指数下降，直至在某一点趋于平稳并失效。

> Code generation with Large Language Models (LLMs) has helped to increase software developer productivity in coding tasks, but has yet to have significant impact on the tasks of software developers that surround this code. In particular, the challenge of infrastructure management remains an open question. We investigate the ability of an LLM agent to construct infrastructure using the Infrastructure as Code (IaC) paradigm. We particularly investigate the use of a feedback loop that returns errors and warnings on the generated IaC to allow the LLM agent to improve the code. We find that, for each iteration of the loop, its effectiveness decreases exponentially until it plateaus at a certain point and becomes ineffective.

[Arxiv](https://arxiv.org/abs/2411.19043)