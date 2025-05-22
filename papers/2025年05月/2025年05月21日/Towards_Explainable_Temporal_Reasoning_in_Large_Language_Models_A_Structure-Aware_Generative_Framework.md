# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月21日

`LLM应用` `时间推理` `知识图谱`

> Towards Explainable Temporal Reasoning in Large Language Models: A Structure-Aware Generative Framework

# 摘要

> 大型语言模型（LLMs）在时间推理领域虽潜力无限，但现有研究多专注于性能提升，往往忽视了推理过程的可解释性。为解决这一问题，我们构建了一个涵盖多种时间粒度的全面基准测试，旨在系统性评估LLMs在可解释时间推理方面的能力。研究发现，仅依赖文本信息时，LLMs难以提供令人信服的解释。为此，我们提出了GETER——一种全新的结构感知生成框架，通过整合图结构与文本实现可解释的时间推理。具体来说，我们首先基于时间知识图谱开发了一个时间编码器，用于捕获查询的结构信息。随后，我们设计了一个结构-文本前缀适配器，将图结构特征映射到文本嵌入空间。最后，LLMs通过将软图令牌与指令微调提示令牌无缝结合生成解释文本。实验结果表明，GETER不仅达到了当前最优性能，还展现了其有效性以及强大的泛化能力。我们的数据集和代码已在GitHub上开源，地址为https://github.com/carryTatum/GETER。

> While large language models (LLMs) show great potential in temporal reasoning, most existing work focuses heavily on enhancing performance, often neglecting the explainable reasoning processes underlying the results. To address this gap, we introduce a comprehensive benchmark covering a wide range of temporal granularities, designed to systematically evaluate LLMs' capabilities in explainable temporal reasoning. Furthermore, our findings reveal that LLMs struggle to deliver convincing explanations when relying solely on textual information. To address challenge, we propose GETER, a novel structure-aware generative framework that integrates Graph structures with text for Explainable TEmporal Reasoning. Specifically, we first leverage temporal knowledge graphs to develop a temporal encoder that captures structural information for the query. Subsequently, we introduce a structure-text prefix adapter to map graph structure features into the text embedding space. Finally, LLMs generate explanation text by seamlessly integrating the soft graph token with instruction-tuning prompt tokens. Experimental results indicate that GETER achieves state-of-the-art performance while also demonstrating its effectiveness as well as strong generalization capabilities. Our dataset and code are available at https://github.com/carryTatum/GETER.

[Arxiv](https://arxiv.org/abs/2505.15245)