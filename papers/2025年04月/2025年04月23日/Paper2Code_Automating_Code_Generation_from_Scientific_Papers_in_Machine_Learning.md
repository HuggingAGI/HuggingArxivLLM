# Paper2Code：从机器学习领域的科学论文中自动化生成代码

发布时间：2025年04月23日

`LLM应用` `软件工程`

> Paper2Code: Automating Code Generation from Scientific Papers in Machine Learning

# 摘要

> 尽管机器学习研究发展迅猛，但代码实现往往难以获取，这严重阻碍了研究的复现与扩展。近期大型语言模型（LLMs）在理解科学文档和生成高质量代码方面表现出色，为此我们提出了PaperCoder——一个多智能体LLM框架，能够将机器学习论文转化为功能代码仓库。

PaperCoder运行于三个核心阶段：规划、分析与生成。在规划阶段，它构建高层次路线图、设计系统架构（附带图示）、识别文件依赖并生成配置文件；分析阶段专注于解析实现细节；生成阶段则产出模块化、依赖感知的代码。每个阶段都通过一组专门设计的智能体来实现，这些智能体能够在整个流程中有效协作。

我们基于模型评估和人工评估（特别是原始论文作者的评估）来评估PaperCoder的表现，若可用，以作者发布的仓库作为基准。实验结果表明，PaperCoder能够有效生成高质量、忠实于原论文的代码实现。此外，在近期发布的PaperBench基准测试中，它也表现优异，远超强劲的基线模型。

> Despite the rapid growth of machine learning research, corresponding code implementations are often unavailable, making it slow and labor-intensive for researchers to reproduce results and build upon prior work. In the meantime, recent Large Language Models (LLMs) excel at understanding scientific documents and generating high-quality code. Inspired by this, we introduce PaperCoder, a multi-agent LLM framework that transforms machine learning papers into functional code repositories. PaperCoder operates in three stages: planning, where it constructs a high-level roadmap, designs the system architecture with diagrams, identifies file dependencies, and generates configuration files; analysis, which focuses on interpreting implementation-specific details; and generation, where modular, dependency-aware code is produced. Moreover, each phase is instantiated through a set of specialized agents designed to collaborate effectively across the pipeline. We then evaluate PaperCoder on generating code implementations from machine learning papers based on both model-based and human evaluations, specifically from the original paper authors, with author-released repositories as ground truth if available. Our results demonstrate the effectiveness of PaperCoder in creating high-quality, faithful implementations. Furthermore, it consistently shows strengths in the recently released PaperBench benchmark, surpassing strong baselines by substantial margins.

[Arxiv](https://arxiv.org/abs/2504.17192)