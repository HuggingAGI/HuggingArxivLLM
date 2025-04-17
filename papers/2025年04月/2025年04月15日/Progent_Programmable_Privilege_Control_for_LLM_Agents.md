# Progent：大型语言模型代理的可编程权限控制方案

发布时间：2025年04月15日

`Agent` `人工智能`

> Progent: Programmable Privilege Control for LLM Agents

# 摘要

> LLM代理：一种新兴的人工智能系统形式，以大型语言模型（LLMs）为核心，通过多样化工具完成用户任务。尽管潜力巨大，但其安全风险不容忽视——在与外部交互时，可能遭遇恶意指令，触发危险操作。解决这一问题的关键在于实施最小权限原则：仅放行必要操作，拦截无关行为。然而，这一目标的实现面临诸多挑战，需兼顾各类代理场景，同时确保安全与实用并重。

    我们推出了Progent——首个专为LLM代理设计的权限控制机制。其核心亮点在于采用领域特定语言，灵活定义代理执行过程中的权限策略。这些策略对工具调用进行精准限制，明确何时放行，并在必要时提供备用方案。这使得开发者和用户能够为具体场景量身定制策略，并以确定性方式执行，从而确保安全性。凭借模块化设计，Progent无需改动代理内部结构，仅需少量代码调整，大大提升了实用性和推广潜力。我们还借助LLMs实现策略自动化编写，根据用户查询生成策略，并动态优化以增强安全与实用。经过全面测试，Progent在AgentDojo、ASB和AgentPoison三大场景中均展现出卓越的安全性与实用性。深入分析表明，其核心组件表现优异，自动化策略生成机制在应对自适应攻击时亦展现出强大韧性。

> LLM agents are an emerging form of AI systems where large language models (LLMs) serve as the central component, utilizing a diverse set of tools to complete user-assigned tasks. Despite their great potential, LLM agents pose significant security risks. When interacting with the external world, they may encounter malicious commands from attackers, leading to the execution of dangerous actions. A promising way to address this is by enforcing the principle of least privilege: allowing only essential actions for task completion while blocking unnecessary ones. However, achieving this is challenging, as it requires covering diverse agent scenarios while preserving both security and utility.
  We introduce Progent, the first privilege control mechanism for LLM agents. At its core is a domain-specific language for flexibly expressing privilege control policies applied during agent execution. These policies provide fine-grained constraints over tool calls, deciding when tool calls are permissible and specifying fallbacks if they are not. This enables agent developers and users to craft suitable policies for their specific use cases and enforce them deterministically to guarantee security. Thanks to its modular design, integrating Progent does not alter agent internals and requires only minimal changes to agent implementation, enhancing its practicality and potential for widespread adoption. To automate policy writing, we leverage LLMs to generate policies based on user queries, which are then updated dynamically for improved security and utility. Our extensive evaluation shows that it enables strong security while preserving high utility across three distinct scenarios or benchmarks: AgentDojo, ASB, and AgentPoison. Furthermore, we perform an in-depth analysis, showcasing the effectiveness of its core components and the resilience of its automated policy generation against adaptive attacks.

[Arxiv](https://arxiv.org/abs/2504.11703)