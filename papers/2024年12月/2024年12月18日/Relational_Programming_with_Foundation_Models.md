# 基于基础模型的关系编程

发布时间：2024年12月18日

`LLM应用` `人工智能` `基础模型编程`

> Relational Programming with Foundation Models

# 摘要

> 基础模型在实现多样化的人工智能应用方面潜力巨大。这些模型虽强大但存在不足，这促使了一系列机制的产生，以增强其诸如上下文学习、信息检索和代码解读等能力。我们提出了 Vieira 这一声明式框架，将这些机制统一于基础模型编程的通用解决方案中。Vieira 遵循概率关系范式，把基础模型视作具有关系输入和输出的无状态函数。它支持神经符号应用，能使此类模型与逻辑程序无缝结合，还支持复杂的多模态应用，可简化不同子模型的组合。我们通过为 Scallop 编译器扩展一个支持基础模型作为插件的外部接口来实现 Vieira。我们为包括 GPT、CLIP 和 SAM 在内的 12 个基础模型开发了插件。我们在 9 个涵盖语言、视觉、结构化和向量数据库的具有挑战性的任务上对 Vieira 进行了评估。评估结果显示，Vieira 中的程序简洁，能够整合现代基础模型，且具有与竞争基线相当甚至更优的准确性。

> Foundation models have vast potential to enable diverse AI applications. The powerful yet incomplete nature of these models has spurred a wide range of mechanisms to augment them with capabilities such as in-context learning, information retrieval, and code interpreting. We propose Vieira, a declarative framework that unifies these mechanisms in a general solution for programming with foundation models. Vieira follows a probabilistic relational paradigm and treats foundation models as stateless functions with relational inputs and outputs. It supports neuro-symbolic applications by enabling the seamless combination of such models with logic programs, as well as complex, multi-modal applications by streamlining the composition of diverse sub-models. We implement Vieira by extending the Scallop compiler with a foreign interface that supports foundation models as plugins. We implement plugins for 12 foundation models including GPT, CLIP, and SAM. We evaluate Vieira on 9 challenging tasks that span language, vision, and structured and vector databases. Our evaluation shows that programs in Vieira are concise, can incorporate modern foundation models, and have comparable or better accuracy than competitive baselines.

[Arxiv](https://arxiv.org/abs/2412.14515)