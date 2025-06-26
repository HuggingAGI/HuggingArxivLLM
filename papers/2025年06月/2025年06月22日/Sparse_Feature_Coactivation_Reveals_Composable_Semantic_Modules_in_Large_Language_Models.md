# 稀疏特征共激活揭示出大型语言模型中的可组合语义模块

发布时间：2025年06月22日

`LLM理论` `国际关系` `认知科学`

> Sparse Feature Coactivation Reveals Composable Semantic Modules in Large Language Models

# 摘要

> 我们通过稀疏自编码器（SAE）特征的协同激活，在大型语言模型中识别出语义连贯、上下文一致的网络组件。聚焦于国家关系任务，我们发现去除国家和关系相关的语义组件会以可预测的方式改变模型输出，而增强这些组件则会引发反事实响应。值得注意的是，结合关系和国家组件会产生复合反事实输出。研究发现，尽管大多数国家组件源自第一层，但更抽象的关系组件则集中在后续层。此外，在关系组件内部，来自后续层的节点往往对模型输出具有更强的因果影响。总体而言，这些发现揭示了大型语言模型中知识的模块化组织方式，并为高效、有针对性的模型操作提供了新方法。

> We identify semantically coherent, context-consistent network components in large language models (LLMs) using coactivation of sparse autoencoder (SAE) features collected from just a handful of prompts. Focusing on country-relation tasks, we show that ablating semantic components for countries and relations changes model outputs in predictable ways, while amplifying these components induces counterfactual responses. Notably, composing relation and country components yields compound counterfactual outputs. We find that, whereas most country components emerge from the very first layer, the more abstract relation components are concentrated in later layers. Furthermore, within relation components themselves, nodes from later layers tend to have a stronger causal impact on model outputs. Overall, these findings suggest a modular organization of knowledge within LLMs and advance methods for efficient, targeted model manipulation.

[Arxiv](https://arxiv.org/abs/2506.18141)