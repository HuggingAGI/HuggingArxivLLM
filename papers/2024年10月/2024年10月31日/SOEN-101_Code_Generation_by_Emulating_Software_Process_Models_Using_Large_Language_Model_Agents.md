# # SOEN-101: 利用大型语言模型代理模拟软件过程模型的代码生成方法

发布时间：2024年10月31日

`LLM应用` `软件工程` `人工智能`

> SOEN-101: Code Generation by Emulating Software Process Models Using Large Language Model Agents

# 摘要

> 软件过程模型是促进开发团队协作与沟通、解决复杂开发任务的关键。受此启发，我们提出了FlowGen——一个基于多个大型语言模型（LLM）代理的代码生成框架，能够模拟软件过程模型。通过将LLM代理分配到需求工程师、架构师、开发人员、测试人员和Scrum大师等角色中，我们模拟了FlowGenWaterfall、FlowGenTDD和FlowGenScrum三种过程模型，并组织了相应的沟通模式。这些代理通过链式思维和提示组合进行协作，并通过持续的自我完善来提升代码质量。我们使用GPT3.5作为底层LLM，并采用RawGPT、CodeT、Reflexion等基线模型，在HumanEval、HumanEval-ET、MBPP和MBPP-ET四个基准测试上评估代码生成效果。研究发现，FlowGenScrum相较于其它过程模型表现更优，在HumanEval、HumanEval-ET、MBPP和MBPP-ET上的Pass@1分别达到75.2、65.5、82.5和56.7（相较于RawGPT平均提升了15%）。与其它先进技术相比，FlowGenScrum在MBPP上的Pass@1高于CodeT，两者均优于Reflexion。值得注意的是，将CodeT与FlowGenScrum结合带来了显著改进，实现了最高的Pass@1得分。分析表明，不同开发活动对代码气味和异常处理的影响各异，其中设计和代码审查增加了异常处理并减少了代码气味。最后，FlowGen模型在GPT3.5不同版本和温度值下均保持稳定的Pass@1得分，证明了软件过程模型在提升LLM生成代码质量和稳定性方面的显著效果。

> Software process models are essential to facilitate collaboration and communication among software teams to solve complex development tasks. Inspired by these software engineering practices, we present FlowGen - a code generation framework that emulates software process models based on multiple Large Language Model (LLM) agents. We emulate three process models, FlowGenWaterfall, FlowGenTDD, and FlowGenScrum, by assigning LLM agents to embody roles (i.e., requirement engineer, architect, developer, tester, and scrum master) that correspond to everyday development activities and organize their communication patterns. The agents work collaboratively using chain-of-thought and prompt composition with continuous self-refinement to improve the code quality. We use GPT3.5 as our underlying LLM and several baselines (RawGPT, CodeT, Reflexion) to evaluate code generation on four benchmarks: HumanEval, HumanEval-ET, MBPP, and MBPP-ET. Our findings show that FlowGenScrum excels compared to other process models, achieving a Pass@1 of 75.2, 65.5, 82.5, and 56.7 in HumanEval, HumanEval-ET, MBPP, and MBPP-ET, respectively (an average of 15% improvement over RawGPT). Compared with other state-of-the-art techniques, FlowGenScrum achieves a higher Pass@1 in MBPP compared to CodeT, with both outperforming Reflexion. Notably, integrating CodeT into FlowGenScrum resulted in statistically significant improvements, achieving the highest Pass@1 scores. Our analysis also reveals that the development activities impacted code smell and exception handling differently, with design and code review adding more exception handling and reducing code smells. Finally, FlowGen models maintain stable Pass@1 scores across GPT3.5 versions and temperature values, highlighting the effectiveness of software process models in enhancing the quality and stability of LLM-generated code.

[Arxiv](https://arxiv.org/abs/2403.15852)