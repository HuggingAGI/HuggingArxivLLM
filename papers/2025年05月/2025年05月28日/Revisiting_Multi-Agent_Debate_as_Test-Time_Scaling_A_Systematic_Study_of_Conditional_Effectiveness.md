# 多智能体辩论再探：测试时扩展的条件效果系统性研究

发布时间：2025年05月28日

`Agent` `人工智能`

> Revisiting Multi-Agent Debate as Test-Time Scaling: A Systematic Study of Conditional Effectiveness

# 摘要

> 大型语言模型（LLM）能力的显著提升推动了多智能体系统的探索，其中辩论框架作为提升问题解决能力的途径逐渐崭露头角。这些多智能体辩论（MAD）方法中，智能体通过协作呈现、批判和精炼论点，相较于单体模型，可能带来更优的推理能力、鲁棒性和多角度的见解。尽管已有研究利用MAD方法，但与自智能体方法相比，特别是在不同条件下，MAD的有效性仍缺乏系统性的理解。本文旨在填补这一空白，将MAD概念化为一种测试时的计算扩展技术，其特点在于协作精炼和多样化探索能力。我们进行了全面的实证研究，比较了MAD与强大的自智能体测试时扩展基线在数学推理和安全相关任务上的表现。我们的研究系统地考察了任务难度、模型规模和智能体多样性对MAD性能的影响。关键发现显示，对于数学推理，MAD相比自智能体扩展仅提供有限优势，但随着问题难度增加和模型能力降低，其效果更为显著，而智能体多样性则未带来明显益处。反之，在安全任务中，MAD的协作精炼可能增加漏洞，但通过多样化智能体配置，协作精炼过程能够逐步降低攻击成功率。我们相信，我们的发现为未来开发更有效且策略性部署的MAD系统提供了关键指导。

> The remarkable growth in large language model (LLM) capabilities has spurred exploration into multi-agent systems, with debate frameworks emerging as a promising avenue for enhanced problem-solving. These multi-agent debate (MAD) approaches, where agents collaboratively present, critique, and refine arguments, potentially offer improved reasoning, robustness, and diverse perspectives over monolithic models. Despite prior studies leveraging MAD, a systematic understanding of its effectiveness compared to self-agent methods, particularly under varying conditions, remains elusive. This paper seeks to fill this gap by conceptualizing MAD as a test-time computational scaling technique, distinguished by collaborative refinement and diverse exploration capabilities. We conduct a comprehensive empirical investigation comparing MAD with strong self-agent test-time scaling baselines on mathematical reasoning and safety-related tasks. Our study systematically examines the influence of task difficulty, model scale, and agent diversity on MAD's performance. Key findings reveal that, for mathematical reasoning, MAD offers limited advantages over self-agent scaling but becomes more effective with increased problem difficulty and decreased model capability, while agent diversity shows little benefit. Conversely, for safety tasks, MAD's collaborative refinement can increase vulnerability, but incorporating diverse agent configurations facilitates a gradual reduction in attack success through the collaborative refinement process. We believe our findings provide critical guidance for the future development of more effective and strategically deployed MAD systems.

[Arxiv](https://arxiv.org/abs/2505.22960)