# 面向基于LLM的社会模拟的人群对齐角色生成

发布时间：2025年09月12日

`LLM应用` `基础理论`

> Population-Aligned Persona Generation for LLM-based Social Simulation

# 摘要

> 大型语言模型（LLMs）的最新进展，以空前的规模和保真度实现了类人社会模拟，为计算社会科学带来新机遇。然而，核心挑战在于如何构建能真实反映现实人群多样性与分布特征的角色集。现有多数基于LLM的社会模拟研究，多侧重于智能体框架与模拟环境设计，却常忽略角色生成的复杂性及非代表性角色集潜藏的偏差。为此，本文提出系统化框架，用于合成高质量、与人群特征对齐的角色集，以支持LLM驱动的社会模拟。该方法首先利用LLM从长期社交媒体数据中生成叙事角色，随后通过严格质量评估筛选低保真度档案；接着借助重要性抽样，使角色集与参考心理测量分布（如大五人格特质）实现全局对齐；为适配特定场景，进一步引入任务模块将全局对齐角色集调整为目标亚群版本。实验验证表明，该方法显著降低群体层面偏差，可为各类研究与政策应用提供准确且灵活的社会模拟支持。

> Recent advances in large language models (LLMs) have enabled human-like social simulations at unprecedented scale and fidelity, offering new opportunities for computational social science. A key challenge, however, is the construction of persona sets that authentically represent the diversity and distribution of real-world populations. Most existing LLM-based social simulation studies focus primarily on designing agentic frameworks and simulation environments, often overlooking the complexities of persona generation and the potential biases introduced by unrepresentative persona sets. In this paper, we propose a systematic framework for synthesizing high-quality, population-aligned persona sets for LLM-driven social simulation. Our approach begins by leveraging LLMs to generate narrative personas from long-term social media data, followed by rigorous quality assessment to filter out low-fidelity profiles. We then apply importance sampling to achieve global alignment with reference psychometric distributions, such as the Big Five personality traits. To address the needs of specific simulation contexts, we further introduce a task-specific module that adapts the globally aligned persona set to targeted subpopulations. Extensive experiments demonstrate that our method significantly reduces population-level bias and enables accurate, flexible social simulation for a wide range of research and policy applications.

[Arxiv](https://arxiv.org/abs/2509.10127)