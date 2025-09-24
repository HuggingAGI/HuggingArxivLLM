# ZERA：零初始化指令进化式优化智能体——从无指令到结构化提示词：借助基于原则的优化

发布时间：2025年09月16日

`Agent` `基础理论`

> ZERA: Zero-init Instruction Evolving Refinement Agent - From Zero Instructions to Structured Prompts via Principle-based Optimization

# 摘要

> 自动提示优化（APO）通过优化特定任务的提示词来提升大型语言模型（LLM）性能。但现有的APO方法往往存在局限：仅关注用户提示词、依赖非结构化反馈、需要大量样本和漫长迭代周期，导致成本高昂且稳定性差。为此，我们提出ZERA（零初始化指令进化优化智能体，Zero-init Instruction Evolving Refinement Agent）——一种新型框架，通过有原则、低开销的优化，实现系统与用户提示词的联合优化。ZERA基于八个可泛化标准对提示词评分（权重自动推断），并依据这些结构化评价进行修订，从而仅需少量示例和短迭代周期即可快速收敛到高质量提示词。我们在五个LLM和九个涵盖推理、摘要及代码生成任务的数据集上评估ZERA，实验结果显示其性能持续优于强基线模型；消融实验进一步揭示了各组件对高效提示词构建的贡献。相关实现（含所有提示词）已公开于https://github.com/younatics/zera-agent。

> Automatic Prompt Optimization (APO) improves large language model (LLM) performance by refining prompts for specific tasks. However, prior APO methods typically focus only on user prompts, rely on unstructured feedback, and require large sample sizes and long iteration cycles-making them costly and brittle. We propose ZERA (Zero-init Instruction Evolving Refinement Agent), a novel framework that jointly optimizes both system and user prompts through principled, low-overhead refinement. ZERA scores prompts using eight generalizable criteria with automatically inferred weights, and revises prompts based on these structured critiques. This enables fast convergence to high-quality prompts using minimal examples and short iteration cycles. We evaluate ZERA across five LLMs and nine diverse datasets spanning reasoning, summarization, and code generation tasks. Experimental results demonstrate consistent improvements over strong baselines. Further ablation studies highlight the contribution of each component to more effective prompt construction. Our implementation including all prompts is publicly available at https://github.com/younatics/zera-agent.

[Arxiv](https://arxiv.org/abs/2509.18158)