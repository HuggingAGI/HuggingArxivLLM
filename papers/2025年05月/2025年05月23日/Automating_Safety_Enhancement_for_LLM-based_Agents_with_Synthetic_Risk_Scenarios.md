# # 自动化方案
基于合成风险场景的LLM代理安全增强自动化方案

发布时间：2025年05月23日

`LLM应用` `人工智能` `安全技术`

> Automating Safety Enhancement for LLM-based Agents with Synthetic Risk Scenarios

# 摘要

> 基于大型语言模型（LLM）的智能体正越来越多地被部署到现实应用场景中，例如“数字助手、自主客服系统以及决策支持系统”。凭借其在多轮交互和工具增强环境中运作的能力，这些智能体在现实应用中不可或缺。然而，由于动态用户交互、外部工具使用以及潜在的意外有害行为所引发的多样且复杂的潜在风险，确保这些智能体的安全性仍是一项重大挑战。

为应对这一关键问题，我们提出了AutoSafe，这是首个通过完全自动化合成数据生成系统性提升智能体安全性的框架。具体而言，1) 我们引入了一个开放且可扩展的威胁模型OTS，该模型形式化地描述了不安全行为如何由用户指令、交互环境以及智能体动作三者相互作用而产生。这使得我们能够精准地在各类场景中建模安全风险。2) 我们开发了一条完全自动化的数据生成管道，模拟不安全的用户行为，运用自我反思推理生成安全的响应，并构建一个大规模、多样化且高质量的安全训练数据集——从而避免了危险的现实数据收集需求。

为了评估我们的框架效果，我们在合成和现实世界的安全基准测试上设计了全面的实验。实验结果表明，AutoSafe平均提升了45%的安全评分，并在现实任务中实现了28.91%的改进，验证了我们学习的安全策略的泛化能力。这些结果凸显了AutoSafe在构建更安全的基于LLM的智能体以实现现实部署方面的实用进展和可扩展性。我们的项目页面已发布在https://auto-safe.github.io/。

> Large Language Model (LLM)-based agents are increasingly deployed in real-world applications such as "digital assistants, autonomous customer service, and decision-support systems", where their ability to "interact in multi-turn, tool-augmented environments" makes them indispensable. However, ensuring the safety of these agents remains a significant challenge due to the diverse and complex risks arising from dynamic user interactions, external tool usage, and the potential for unintended harmful behaviors. To address this critical issue, we propose AutoSafe, the first framework that systematically enhances agent safety through fully automated synthetic data generation. Concretely, 1) we introduce an open and extensible threat model, OTS, which formalizes how unsafe behaviors emerge from the interplay of user instructions, interaction contexts, and agent actions. This enables precise modeling of safety risks across diverse scenarios. 2) we develop a fully automated data generation pipeline that simulates unsafe user behaviors, applies self-reflective reasoning to generate safe responses, and constructs a large-scale, diverse, and high-quality safety training dataset-eliminating the need for hazardous real-world data collection. To evaluate the effectiveness of our framework, we design comprehensive experiments on both synthetic and real-world safety benchmarks. Results demonstrate that AutoSafe boosts safety scores by 45% on average and achieves a 28.91% improvement on real-world tasks, validating the generalization ability of our learned safety strategies. These results highlight the practical advancement and scalability of AutoSafe in building safer LLM-based agents for real-world deployment. We have released the project page at https://auto-safe.github.io/.

[Arxiv](https://arxiv.org/abs/2505.17735)