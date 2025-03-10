# WritingBench：面向生成式写作的综合性基准测试

发布时间：2025年03月07日

`LLM应用`

> WritingBench: A Comprehensive Benchmark for Generative Writing

# 摘要

> 大型语言模型（LLMs）的最新进展显著提升了文本生成能力，但评估其在生成性写作中的表现仍是难题。现有基准主要关注通用文本生成或特定写作任务，未能全面涵盖高质量书面内容的多样化需求。为解决这一问题，我们推出了WritingBench，一个全面评估LLMs的基准测试，涵盖6个核心写作领域和100个子领域，包括创意、说服性、信息性和技术性写作。我们还提出了一种基于查询的评估框架，使LLMs能够动态生成特定实例的评估标准。该框架结合了经过微调的评判模型，用于标准感知评分，能够在风格、格式和长度方面进行评估。该框架的有效性通过其数据整理能力得到验证，使7B参数模型能够达到当前最优（SOTA）性能。我们开源了该基准测试、评估工具和模块化框架组件，以推动LLMs在写作领域的开发。

> Recent advancements in large language models (LLMs) have significantly enhanced text generation capabilities, yet evaluating their performance in generative writing remains a challenge. Existing benchmarks primarily focus on generic text generation or limited in writing tasks, failing to capture the diverse requirements of high-quality written contents across various domains. To bridge this gap, we present WritingBench, a comprehensive benchmark designed to evaluate LLMs across 6 core writing domains and 100 subdomains, encompassing creative, persuasive, informative, and technical writing. We further propose a query-dependent evaluation framework that empowers LLMs to dynamically generate instance-specific assessment criteria. This framework is complemented by a fine-tuned critic model for criteria-aware scoring, enabling evaluations in style, format and length. The framework's validity is further demonstrated by its data curation capability, which enables 7B-parameter models to approach state-of-the-art (SOTA) performance. We open-source the benchmark, along with evaluation tools and modular framework components, to advance the development of LLMs in writing.

[Arxiv](https://arxiv.org/abs/2503.05244)