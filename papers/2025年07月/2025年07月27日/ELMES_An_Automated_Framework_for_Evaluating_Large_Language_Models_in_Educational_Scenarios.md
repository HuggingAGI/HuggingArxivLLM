# ELMES：专为教育场景设计的大型语言模型自动化评估框架

发布时间：2025年07月27日

`LLM应用`

> ELMES: An Automated Framework for Evaluating Large Language Models in Educational Scenarios

# 摘要

> 大型语言模型（LLMs）的出现为教育领域带来了变革性的机遇，生成了众多新颖的应用场景。然而，重大挑战依然存在：不同教育场景下的评估指标差异显著，而许多新兴场景缺乏合适的评估指标。当前的基准测试主要衡量通用智能，而非教育能力。为了解决这一差距，我们引入了ELMES，这是一个专为教育场景中评估LLMs设计的开源自动化评估框架。

ELMES具有模块化架构，研究人员可以通过简单的配置文件创建动态的多智能体对话，从而实现灵活的场景设计，而无需深厚的编程专业知识。该框架集成了一个混合评估引擎，通过将LLM作为裁判的方法，客观量化传统上主观的教育指标。

我们在四个关键教育场景中对最先进的LLMs进行了系统性基准测试：知识点讲解、引导式问题解决教学、跨学科课程计划生成以及情境化问题生成，采用了与教育专家合作开发的细粒度指标。我们的结果显示了不同模型在能力分布上的显著差异，揭示了它们在特定上下文中的优势和局限性。

ELMES为教育工作者和研究人员提供了一个易于使用的评估框架，显著降低了其在多样化教育应用中的适应障碍，同时推动了LLMs在教育实践中的实际应用。该框架在\emph{https://github.com/sii-research/elmes.git}公开可用。

> The emergence of Large Language Models (LLMs) presents transformative opportunities for education, generating numerous novel application scenarios. However, significant challenges remain: evaluation metrics vary substantially across different educational scenarios, while many emerging scenarios lack appropriate assessment metrics. Current benchmarks predominantly measure general intelligence rather than pedagogical capabilities. To address this gap, we introduce ELMES, an open-source automated evaluation framework specifically designed for assessing LLMs in educational settings. ELMES features a modular architecture that enables researchers to create dynamic, multi-agent dialogues through simple configuration files, facilitating flexible scenario design without requiring extensive programming expertise. The framework incorporates a hybrid evaluation engine that objectively quantifies traditionally subjective pedagogical metrics using an LLM-as-a-Judge methodology. We conduct systematic benchmarking of state-of-the-art LLMs across four critical educational scenarios: Knowledge Point Explanation, Guided Problem-Solving Teaching, Interdisciplinary Lesson Plan Generation, and Contextualized Question Generation, employing fine-grained metrics developed in collaboration with education specialists. Our results demonstrate distinct capability distributions among models, revealing context-specific strengths and limitations. ELMES provides educators and researchers with an accessible evaluation framework that significantly reduces adaptation barriers for diverse educational applications while advancing the practical implementation of LLMs in pedagogy. The framework is publicly available at \emph{https://github.com/sii-research/elmes.git}.

[Arxiv](https://arxiv.org/abs/2507.22947)