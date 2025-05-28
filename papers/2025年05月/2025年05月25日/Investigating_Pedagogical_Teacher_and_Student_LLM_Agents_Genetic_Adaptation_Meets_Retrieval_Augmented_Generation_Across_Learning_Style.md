# # 研究教育型教师与学生LLM智能体：遗传适应与检索增强生成跨学习风格的结合

发布时间：2025年05月25日

`LLM应用

摘要讨论了大型语言模型在教育模拟中的应用，特别是通过学生代理和教师代理的互动，以及使用Persona-RAG模块来提升个性化教学。尽管提到了RAG模块，但研究的核心在于LLM在教育领域的应用，因此归类为LLM应用。` `自适应学习`

> Investigating Pedagogical Teacher and Student LLM Agents: Genetic Adaptation Meets Retrieval Augmented Generation Across Learning Style

# 摘要

> 在教育领域，适应学生多样化的认知和行为特征进行教学是一大持续性挑战。尽管大型语言模型（LLMs）在模拟复杂教学环境方面展现出潜力，但现有模拟框架仍存在两大局限：一是将学生简化为静态的知识档案，二是缺乏机制模拟教师根据学生反馈调整策略的过程。为解决这些问题，我们提出了一种创新的模拟框架，整合了基于LLM的异质学生代理与一个自我优化的教师代理。教师代理的教学策略通过遗传算法动态演变，使其能够根据多样学习者的整体表现发现和优化有效的教学策略。此外，我们推出了Persona-RAG，一个检索增强生成模块，使学生代理能够检索与其学习风格相匹配的知识。Persona-RAG在保持标准RAG基线的检索准确性的同时，提升了个性化水平，这对模拟现实教育场景至关重要。通过大量实验，我们展示了我们的框架在与不同学生群体互动时如何支持不同且可解释的教学模式的出现。我们的结果凸显了LLM驱动的模拟在促进自适应教学实践方面的潜力，并为在受控、数据驱动的环境中培训人类教育者提供了一个测试平台。

> Effective teaching requires adapting instructional strategies to accommodate the diverse cognitive and behavioral profiles of students, a persistent challenge in education and teacher training. While Large Language Models (LLMs) offer promise as tools to simulate such complex pedagogical environments, current simulation frameworks are limited in two key respects: (1) they often reduce students to static knowledge profiles, and (2) they lack adaptive mechanisms for modeling teachers who evolve their strategies in response to student feedback. To address these gaps, \textbf{we introduce a novel simulation framework that integrates LLM-based heterogeneous student agents with a self-optimizing teacher agent}. The teacher agent's pedagogical policy is dynamically evolved using a genetic algorithm, allowing it to discover and refine effective teaching strategies based on the aggregate performance of diverse learners. In addition, \textbf{we propose Persona-RAG}, a Retrieval Augmented Generation module that enables student agents to retrieve knowledge tailored to their individual learning styles. Persona-RAG preserves the retrieval accuracy of standard RAG baselines while enhancing personalization, an essential factor in modeling realistic educational scenarios. Through extensive experiments, we demonstrate how our framework supports the emergence of distinct and interpretable teaching patterns when interacting with varied student populations. Our results highlight the potential of LLM-driven simulations to inform adaptive teaching practices and provide a testbed for training human educators in controlled, data-driven environments.

[Arxiv](https://arxiv.org/abs/2505.19173)