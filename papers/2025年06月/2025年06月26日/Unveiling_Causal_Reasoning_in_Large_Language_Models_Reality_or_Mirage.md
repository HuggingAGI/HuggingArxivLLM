# 解密大型语言模型的因果推理能力：真实存在还是虚幻泡影？

发布时间：2025年06月26日

`LLM理论` `人工智能` `问答系统`

> Unveiling Causal Reasoning in Large Language Models: Reality or Mirage?

# 摘要

> 因果推理能力是推动大型语言模型（LLMs）迈向强人工智能的关键。尽管LLMs在理解因果关系和生成符合因果规律的回应方面表现出色，但它们是否能像人类一样进行真正的因果推理仍存疑。现有证据表明，LLMs仅能进行浅层（一级）因果推理，这主要得益于其参数中嵌入的因果知识，但缺乏真正类人（二级）因果推理的能力。为支持这一观点，我们从方法上深入分析了基于transformer的LLMs的自回归机制，发现其本质上不具备因果性。在实证方面，我们推出了全新因果问答基准测试CausalProbe-2024，其语料库对研究对象几乎全新且未接触过。相比以往基准，LLMs在CausalProbe-2024上表现显著下滑，印证了它们主要进行一级因果推理的事实。为突破这一局限，我们从人类推理通常借助常识和目标这一特点中获得启发，提出了G^2-Reasoner方法，将常识和目标导向提示融入LLMs的因果推理过程。实验结果表明，G^2-Reasoner显著提升了LLMs的因果推理能力，尤其在全新和反事实情境下表现突出。这项研究为LLMs向真正因果推理迈进开辟了新路径，超越一级推理，向着二级推理迈出重要一步。

> Causal reasoning capability is critical in advancing large language models (LLMs) toward strong artificial intelligence. While versatile LLMs appear to have demonstrated capabilities in understanding contextual causality and providing responses that obey the laws of causality, it remains unclear whether they perform genuine causal reasoning akin to humans. However, current evidence indicates the contrary. Specifically, LLMs are only capable of performing shallow (level-1) causal reasoning, primarily attributed to the causal knowledge embedded in their parameters, but they lack the capacity for genuine human-like (level-2) causal reasoning. To support this hypothesis, methodologically, we delve into the autoregression mechanism of transformer-based LLMs, revealing that it is not inherently causal. Empirically, we introduce a new causal Q&A benchmark called CausalProbe-2024, whose corpora are fresh and nearly unseen for the studied LLMs. The LLMs exhibit a significant performance drop on CausalProbe-2024 compared to earlier benchmarks, indicating the fact that they primarily engage in level-1 causal reasoning. To bridge the gap towards level-2 causal reasoning, we draw inspiration from the fact that human reasoning is usually facilitated by general knowledge and intended goals. We propose G^2-Reasoner, a method that incorporates general knowledge and goal-oriented prompts into LLMs' causal reasoning processes. Experiments demonstrate that G^2-Reasoner significantly enhances LLMs' causal reasoning capability, particularly in fresh and counterfactual contexts. This work sheds light on a new path for LLMs to advance towards genuine causal reasoning, going beyond level-1 and making strides towards level-2.

[Arxiv](https://arxiv.org/abs/2506.21215)