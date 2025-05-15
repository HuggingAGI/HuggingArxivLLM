# WorldView-Bench：一套评测大型语言模型全球文化视角的基准

发布时间：2025年05月14日

`LLM应用` `全球文化包容性` `文化多样性`

> WorldView-Bench: A Benchmark for Evaluating Global Cultural Perspectives in Large Language Models

# 摘要

> 大型语言模型（LLMs）的训练和对齐主要强化了以西方为中心的知识论和社会文化规范，导致文化趋同现象，限制了其反映全球文明多样性的能力。现有基准测试框架未能充分捕捉这种偏见，因为它们依赖 rigid, closed-form assessments，忽视了文化包容性的复杂性。为此，我们提出了 WorldView-Bench，一个通过分析 LLMs 对不同世界观的容纳能力来评估其全球文化包容性（GCI）的基准。我们的方法基于 Senturk 等人提出的 Multiplex Worldview 理论，该理论区分了 Uniplex 模型（强化文化趋同）和 Multiplex 模型（整合多元视角）。WorldView-Bench 通过自由形式的生成评估而非传统分类基准来衡量文化极化，即对替代观点的排斥。我们通过两种干预策略实现应用多重视角：（1）上下文嵌入式多重视角 LLMs，其中系统提示嵌入多重视角原则；（2）多智能体系统（MAS）嵌入式多重视角 LLMs，其中代表不同文化视角的多个 LLM 代理协作生成响应。结果显示，与基线相比，采用 MAS 嵌入式多重视角 LLMs 使视角分布得分（PDS）的熵从 13% 提升至 94%，同时情感转向正面（67.7%），文化平衡性得到显著增强。这些发现凸显了多重视角感知 AI 评估在缓解 LLMs 文化偏见方面的潜力，为构建更具包容性和伦理对齐的 AI 系统铺平了道路。

> Large Language Models (LLMs) are predominantly trained and aligned in ways that reinforce Western-centric epistemologies and socio-cultural norms, leading to cultural homogenization and limiting their ability to reflect global civilizational plurality. Existing benchmarking frameworks fail to adequately capture this bias, as they rely on rigid, closed-form assessments that overlook the complexity of cultural inclusivity. To address this, we introduce WorldView-Bench, a benchmark designed to evaluate Global Cultural Inclusivity (GCI) in LLMs by analyzing their ability to accommodate diverse worldviews. Our approach is grounded in the Multiplex Worldview proposed by Senturk et al., which distinguishes between Uniplex models, reinforcing cultural homogenization, and Multiplex models, which integrate diverse perspectives. WorldView-Bench measures Cultural Polarization, the exclusion of alternative perspectives, through free-form generative evaluation rather than conventional categorical benchmarks. We implement applied multiplexity through two intervention strategies: (1) Contextually-Implemented Multiplex LLMs, where system prompts embed multiplexity principles, and (2) Multi-Agent System (MAS)-Implemented Multiplex LLMs, where multiple LLM agents representing distinct cultural perspectives collaboratively generate responses. Our results demonstrate a significant increase in Perspectives Distribution Score (PDS) entropy from 13% at baseline to 94% with MAS-Implemented Multiplex LLMs, alongside a shift toward positive sentiment (67.7%) and enhanced cultural balance. These findings highlight the potential of multiplex-aware AI evaluation in mitigating cultural bias in LLMs, paving the way for more inclusive and ethically aligned AI systems.

[Arxiv](https://arxiv.org/abs/2505.09595)