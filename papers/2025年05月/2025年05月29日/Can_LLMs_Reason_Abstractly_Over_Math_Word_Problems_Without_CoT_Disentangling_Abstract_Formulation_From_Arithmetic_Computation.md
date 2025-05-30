# # 摘要  
大型语言模型 (LLMs) 的最新进展推动了从机器人流程自动化到智能体流程自动化的革命性范式转变，这一转变是通过基于 LLMs 自动化工作流编排过程实现的。

发布时间：2025年05月29日

`LLM理论` `数学推理` `模型评估`

> Can LLMs Reason Abstractly Over Math Word Problems Without CoT? Disentangling Abstract Formulation From Arithmetic Computation

# 摘要

> 基于最终答案的评估指标常用于评估大型语言模型（LLMs）在数学题上的表现，通常被视为推理能力的代理指标。然而，这类指标混淆了两种不同的子技能：抽象建模（通过表达式捕捉数学关系）和算术计算（执行计算）。通过对GSM8K和SVAMP进行分离式评估，我们发现，Llama-3和Qwen2.5（1B-32B）在没有CoT的情况下，最终答案的准确性几乎完全受限于算术计算步骤，而非抽象建模步骤。与普遍观念相反，我们发现CoT主要有助于计算，对抽象建模的影响有限。从机制上讲，我们展示了即使在没有推理步骤的单次前向传递中，这两种技能也是通过“先抽象后计算”的机制结合在一起的：模型首先捕捉问题的抽象，然后进行计算。因果补丁验证了这些抽象是存在的、可转移的、可组合的，并且在计算之前就已经形成。这些行为和机制上的发现强调了分离式评估的必要性，以便准确评估LLM的推理能力，并指导未来的改进。

> Final-answer-based metrics are commonly used for evaluating large language models (LLMs) on math word problems, often taken as proxies for reasoning ability. However, such metrics conflate two distinct sub-skills: abstract formulation (capturing mathematical relationships using expressions) and arithmetic computation (executing the calculations). Through a disentangled evaluation on GSM8K and SVAMP, we find that the final-answer accuracy of Llama-3 and Qwen2.5 (1B-32B) without CoT is overwhelmingly bottlenecked by the arithmetic computation step and not by the abstract formulation step. Contrary to the common belief, we show that CoT primarily aids in computation, with limited impact on abstract formulation. Mechanistically, we show that these two skills are composed conjunctively even in a single forward pass without any reasoning steps via an abstract-then-compute mechanism: models first capture problem abstractions, then handle computation. Causal patching confirms these abstractions are present, transferable, composable, and precede computation. These behavioural and mechanistic findings highlight the need for disentangled evaluation to accurately assess LLM reasoning and to guide future improvements.

[Arxiv](https://arxiv.org/abs/2505.23701)