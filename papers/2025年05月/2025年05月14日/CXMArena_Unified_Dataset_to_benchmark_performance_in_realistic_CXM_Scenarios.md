# CXMArena：用于在现实 CXM 场景中评估性能表现的统一数据集

发布时间：2025年05月14日

`LLM应用

摘要讨论了大型语言模型在客户体验管理中的应用，特别是客服中心的运营，并提出了一个新的基准数据集CXMArena来评估AI在这些场景中的表现。这属于LLM的应用领域，因此归类为LLM应用。` `客户体验管理` `知识库`

> CXMArena: Unified Dataset to benchmark performance in realistic CXM Scenarios

# 摘要

> 大型语言模型 (LLMs) 在客户体验管理 (CXM) 领域，尤其是在客服中心运营中，蕴含巨大潜力。然而，由于数据稀缺（源于隐私担忧）和现有基准的局限性，评估其在复杂运营环境中的实际效用面临挑战。现有基准往往缺乏现实感，未能整合深度知识库 (KB)、真实世界的噪声，或超越对话流利性的关键运营任务。为填补这一空白，我们推出 CXMArena，这是一个专为在运营 CXM 场景中评估 AI 设计的新型大规模合成基准数据集。

鉴于客服中心功能的多样性，我们开发了一个可扩展的 LLM 驱动管道，模拟构建数据集基础的品牌 CXM 实体，例如包含产品规格、问题分类和客服中心对话的知识文章。这些实体因受控噪声注入（由领域专家指导）和严格的自动化验证而紧密贴合现实世界分布。在此基础上，我们发布了 CXMArena，它为五个关键运营任务提供了专门的基准：知识库精炼、意图预测、客服质量合规、文章搜索，以及集成工具的多轮 RAG。

我们的基线实验凸显了该基准的难度：即使最先进的嵌入和生成模型在文章搜索中也仅达到 68% 的准确率，而标准嵌入方法在知识库精炼中的 F1 分数仅为 0.3，凸显了当前模型在复杂管道和解决方案上的重大挑战，超越了传统技术的需求。

> Large Language Models (LLMs) hold immense potential for revolutionizing Customer Experience Management (CXM), particularly in contact center operations. However, evaluating their practical utility in complex operational environments is hindered by data scarcity (due to privacy concerns) and the limitations of current benchmarks. Existing benchmarks often lack realism, failing to incorporate deep knowledge base (KB) integration, real-world noise, or critical operational tasks beyond conversational fluency. To bridge this gap, we introduce CXMArena, a novel, large-scale synthetic benchmark dataset specifically designed for evaluating AI in operational CXM contexts. Given the diversity in possible contact center features, we have developed a scalable LLM-powered pipeline that simulates the brand's CXM entities that form the foundation of our datasets-such as knowledge articles including product specifications, issue taxonomies, and contact center conversations. The entities closely represent real-world distribution because of controlled noise injection (informed by domain experts) and rigorous automated validation. Building on this, we release CXMArena, which provides dedicated benchmarks targeting five important operational tasks: Knowledge Base Refinement, Intent Prediction, Agent Quality Adherence, Article Search, and Multi-turn RAG with Integrated Tools. Our baseline experiments underscore the benchmark's difficulty: even state of the art embedding and generation models achieve only 68% accuracy on article search, while standard embedding methods yield a low F1 score of 0.3 for knowledge base refinement, highlighting significant challenges for current models necessitating complex pipelines and solutions over conventional techniques.

[Arxiv](https://arxiv.org/abs/2505.09436)