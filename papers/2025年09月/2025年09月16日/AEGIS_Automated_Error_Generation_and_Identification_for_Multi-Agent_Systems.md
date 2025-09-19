# AEGIS：多智能体系统的自动化错误生成与识别

发布时间：2025年09月16日

`Agent` `基础理论`

> AEGIS: Automated Error Generation and Identification for Multi-Agent Systems

# 摘要

> 随着多智能体系统（MAS）日益自主化和复杂化，理解其错误模式对保障系统可靠性与安全性至关重要。然而，该领域研究因缺乏大规模、多样化且带有精确真实错误标签的数据集而严重受阻。为突破这一瓶颈，我们提出	extbf{AEGIS}——一个面向多智能体系统的	extbf{自}动	extbf{错}误	extbf{生}成与	extbf{识}别（Automated Error Generation and Identification for Multi-Agent Systems）新型框架。通过系统性地向初始成功轨迹中注入可控可追溯错误，我们构建了丰富的真实故障数据集。这一过程借助基于大型语言模型（LLM）的上下文感知自适应操纵器实现，该操纵器能执行提示注入、响应损坏等复杂攻击，以诱发特定预定义错误模式。我们通过探索错误识别任务的三种学习范式（监督微调、强化学习、对比学习）验证了数据集的价值。综合实验表明，基于AEGIS数据训练的模型在所有三种范式中均实现显著提升。值得关注的是，我们的多个微调模型性能媲美甚至超越规模大一个数量级的专有系统，这证明我们的自动化数据生成框架是开发更稳健、可解释的多智能体系统的关键资源。项目网站详见https://kfq20.github.io/AEGIS-Website。

> As Multi-Agent Systems (MAS) become increasingly autonomous and complex, understanding their error modes is critical for ensuring their reliability and safety. However, research in this area has been severely hampered by the lack of large-scale, diverse datasets with precise, ground-truth error labels. To address this bottleneck, we introduce \textbf{AEGIS}, a novel framework for \textbf{A}utomated \textbf{E}rror \textbf{G}eneration and \textbf{I}dentification for Multi-Agent \textbf{S}ystems. By systematically injecting controllable and traceable errors into initially successful trajectories, we create a rich dataset of realistic failures. This is achieved using a context-aware, LLM-based adaptive manipulator that performs sophisticated attacks like prompt injection and response corruption to induce specific, predefined error modes. We demonstrate the value of our dataset by exploring three distinct learning paradigms for the error identification task: Supervised Fine-Tuning, Reinforcement Learning, and Contrastive Learning. Our comprehensive experiments show that models trained on AEGIS data achieve substantial improvements across all three learning paradigms. Notably, several of our fine-tuned models demonstrate performance competitive with or superior to proprietary systems an order of magnitude larger, validating our automated data generation framework as a crucial resource for developing more robust and interpretable multi-agent systems. Our project website is available at https://kfq20.github.io/AEGIS-Website.

[Arxiv](https://arxiv.org/abs/2509.14295)