# "别这么做！": 基于大型语言模型的约束生成引导具身系统

发布时间：2025年06月04日

`LLM应用` `机器人` `自动化`

> "Don't Do That!": Guiding Embodied Systems through Large Language Model-based Constraint Generation

# 摘要

> 大型语言模型（LLMs）的最新进展激发了对一种新型机器人导航技术的广泛关注。该技术能够将自然语言中涉及复杂空间、数学和条件约束的信息整合到规划问题中。这些约束虽然可以是非正式的，但通常非常复杂，因此很难将其转化为可用于规划算法的正式描述。本文中，我们提出了STPR框架，它利用LLMs将约束（以“不要做什么”的指令形式表达）转化为可执行的Python函数。STPR框架借助LLMs强大的编码能力，将问题描述从语言形式转化为结构化、透明化的代码，从而绕过了复杂的推理过程，避免了潜在的幻觉问题。我们证明，这些由LLM生成的函数能够准确描述复杂的数学约束，并将其与传统搜索算法结合应用于点云表示。在模拟的Gazebo环境中进行的实验表明，STPR框架在多种约束和场景下均能确保完全合规，同时运行时间较短。我们还验证了STPR框架可以与小型、专注于代码的LLMs配合使用，使其能够以较低的推理成本应用于各种紧凑型模型。

> Recent advancements in large language models (LLMs) have spurred interest in robotic navigation that incorporates complex spatial, mathematical, and conditional constraints from natural language into the planning problem. Such constraints can be informal yet highly complex, making it challenging to translate into a formal description that can be passed on to a planning algorithm. In this paper, we propose STPR, a constraint generation framework that uses LLMs to translate constraints (expressed as instructions on ``what not to do'') into executable Python functions. STPR leverages the LLM's strong coding capabilities to shift the problem description from language into structured and transparent code, thus circumventing complex reasoning and avoiding potential hallucinations. We show that these LLM-generated functions accurately describe even complex mathematical constraints, and apply them to point cloud representations with traditional search algorithms. Experiments in a simulated Gazebo environment show that STPR ensures full compliance across several constraints and scenarios, while having short runtimes. We also verify that STPR can be used with smaller, code-specific LLMs, making it applicable to a wide range of compact models at low inference cost.

[Arxiv](https://arxiv.org/abs/2506.04500)