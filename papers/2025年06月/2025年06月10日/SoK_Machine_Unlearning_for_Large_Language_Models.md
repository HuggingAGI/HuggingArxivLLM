# # 大型语言模型的机器遗忘机制研究现状

发布时间：2025年06月10日

`LLM理论` `机器学习` `数据隐私`

> SoK: Machine Unlearning for Large Language Models

# 摘要

> 大型语言模型 (LLM) 的遗忘机制已成为机器学习领域的热门课题，其目标是消除特定训练数据或知识的影响，同时避免从头重新训练模型。目前，研究者提出了多种技术手段，包括梯度上升、模型编辑和重新引导隐藏表示等方法。然而，现有综述往往基于技术特性对这些方法进行分类，这种分类方式忽视了一个更根本的维度：遗忘的内在意图——是真正去除内部知识，还是仅仅抑制其行为表现。在本文中，我们基于这一意图导向的视角，提出了一种新的分类体系。在此基础上，我们做出了三项关键贡献：首先，我们重新审视了近期研究，发现许多去除方法在功能上可能更像抑制行为，并探讨了真正去除是否必要或可行；其次，我们调研了现有的评估策略，识别了当前指标和基准的局限性，并提出了开发更可靠且与意图相符的评估方法的方向；最后，我们强调了一些实际挑战，如可扩展性和对序列化遗忘的支持，这些挑战目前阻碍了遗忘方法的更广泛应用。总的来说，这项工作为理解和推进生成式 AI 中的遗忘机制提供了一个全面的框架，旨在支持未来的研究，并为数据删除和隐私保护的政策决策提供指导。

> Large language model (LLM) unlearning has become a critical topic in machine learning, aiming to eliminate the influence of specific training data or knowledge without retraining the model from scratch. A variety of techniques have been proposed, including Gradient Ascent, model editing, and re-steering hidden representations. While existing surveys often organize these methods by their technical characteristics, such classifications tend to overlook a more fundamental dimension: the underlying intention of unlearning--whether it seeks to truly remove internal knowledge or merely suppress its behavioral effects. In this SoK paper, we propose a new taxonomy based on this intention-oriented perspective. Building on this taxonomy, we make three key contributions. First, we revisit recent findings suggesting that many removal methods may functionally behave like suppression, and explore whether true removal is necessary or achievable. Second, we survey existing evaluation strategies, identify limitations in current metrics and benchmarks, and suggest directions for developing more reliable and intention-aligned evaluations. Third, we highlight practical challenges--such as scalability and support for sequential unlearning--that currently hinder the broader deployment of unlearning methods. In summary, this work offers a comprehensive framework for understanding and advancing unlearning in generative AI, aiming to support future research and guide policy decisions around data removal and privacy.

[Arxiv](https://arxiv.org/abs/2506.09227)