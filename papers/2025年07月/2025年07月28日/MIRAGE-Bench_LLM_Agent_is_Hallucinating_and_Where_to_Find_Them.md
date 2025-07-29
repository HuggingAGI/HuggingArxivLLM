# MIRAGE-Bench：LLM智能体出现幻觉，如何发现这些智能体

发布时间：2025年07月28日

`Agent` `人工智能` `智能系统`

> MIRAGE-Bench: LLM Agent is Hallucinating and Where to Find Them

# 摘要

> 幻觉为大型语言模型（LLM）代理带来了关键风险，通常表现为由于认知背景中的伪造或误解信息而产生的幻觉动作。尽管 recent studies 已经揭示了这些失败案例，但现有的评估仍然分散且缺乏系统性的测试环境。本文中，我们介绍了 MIRAGE-Bench——用于衡量风险环境中智能体幻觉的基准——这是首个统一的基准框架，用于在交互式 LLM 智能体场景中引发和评估幻觉。我们首先引入了一个三部分的分类法来应对智能体幻觉：与 (i) 任务指令、(ii) 执行历史或 (iii) 环境观察不符的动作。为了进行分析，我们首先通过对现有智能体基准进行系统性审查来揭示此类失败案例，然后采用快照策略，以确定性且可重复的方式隔离决策点，从而合成测试用例。为了评估幻觉行为，我们采用了一种细粒度级别的 LLM 作为评判者的范式，并设计了具有风险意识的提示，从而能够在不枚举完整动作空间的情况下进行可扩展且高保真的智能体动作评估。MIRAGE-Bench 为 LLM 智能体的失败模式提供了可操作的见解，并为在交互式环境中系统性地缓解幻觉奠定了基础。


> Hallucinations pose critical risks for large language model (LLM)-based agents, often manifesting as hallucinative actions resulting from fabricated or misinterpreted information within the cognitive context. While recent studies have exposed such failures, existing evaluations remain fragmented and lack a principled testbed. In this paper, we present MIRAGE-Bench--Measuring Illusions in Risky AGEnt settings--the first unified benchmark for eliciting and evaluating hallucinations in interactive LLM-agent scenarios. We begin by introducing a three-part taxonomy to address agentic hallucinations: actions that are unfaithful to (i) task instructions, (ii) execution history, or (iii) environment observations. To analyze, we first elicit such failures by performing a systematic audit of existing agent benchmarks, then synthesize test cases using a snapshot strategy that isolates decision points in deterministic and reproducible manners. To evaluate hallucination behaviors, we adopt a fine-grained-level LLM-as-a-Judge paradigm with tailored risk-aware prompts, enabling scalable, high-fidelity assessment of agent actions without enumerating full action spaces. MIRAGE-Bench provides actionable insights on failure modes of LLM agents and lays the groundwork for principled progress in mitigating hallucinations in interactive environments.

[Arxiv](https://arxiv.org/abs/2507.21017)