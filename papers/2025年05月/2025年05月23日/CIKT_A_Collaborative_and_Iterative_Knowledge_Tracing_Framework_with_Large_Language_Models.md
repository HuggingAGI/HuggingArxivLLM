# 协作迭代知识追踪框架 C I K T：基于大型语言模型的深度学习框架。

发布时间：2025年05月23日

`LLM应用` `人工智能`

> CIKT: A Collaborative and Iterative Knowledge Tracing Framework with Large Language Models

# 摘要

> 知识追踪（KT）旨在建模学生随时间的学习状态并预测其未来表现。然而，传统KT方法在可解释性、可扩展性和对复杂知识依赖的有效建模方面常常面临挑战。虽然大型语言模型（LLMs）为KT提供了新的途径，但它们的直接应用往往难以生成结构化、可解释的学生表示，并缺乏对持续、任务特定优化的机制。为了解决这些问题，我们提出了协作迭代知识追踪（CIKT），一个利用LLMs增强预测准确性和可解释性的框架。CIKT采用双组件架构：分析师从学生历史响应中生成动态、可解释的用户档案，而预测器利用这些档案预测未来表现。CIKT的核心是一个协同优化循环。在这个循环中，分析师根据预测器的预测准确性进行迭代优化，预测器则基于生成的档案进行条件预测，随后预测器利用这些增强的档案进行重新训练。在多个教育数据集上的评估表明，CIKT在预测准确性方面表现出显著提升，通过其动态更新的用户档案增强了可解释性，并展示了更好的可扩展性。我们的工作为推进知识追踪系统提供了一个强大且可解释的解决方案，有效弥合了预测性能与模型透明性之间的差距。

> Knowledge Tracing (KT) aims to model a student's learning state over time and predict their future performance. However, traditional KT methods often face challenges in explainability, scalability, and effective modeling of complex knowledge dependencies. While Large Language Models (LLMs) present new avenues for KT, their direct application often struggles with generating structured, explainable student representations and lacks mechanisms for continuous, task-specific refinement. To address these gaps, we propose Collaborative Iterative Knowledge Tracing (CIKT), a framework that harnesses LLMs to enhance both prediction accuracy and explainability. CIKT employs a dual-component architecture: an Analyst generates dynamic, explainable user profiles from student historical responses, and a Predictor utilizes these profiles to forecast future performance. The core of CIKT is a synergistic optimization loop. In this loop, the Analyst is iteratively refined based on the predictive accuracy of the Predictor, which conditions on the generated profiles, and the Predictor is subsequently retrained using these enhanced profiles. Evaluated on multiple educational datasets, CIKT demonstrates significant improvements in prediction accuracy, offers enhanced explainability through its dynamically updated user profiles, and exhibits improved scalability. Our work presents a robust and explainable solution for advancing knowledge tracing systems, effectively bridging the gap between predictive performance and model transparency.

[Arxiv](https://arxiv.org/abs/2505.17705)