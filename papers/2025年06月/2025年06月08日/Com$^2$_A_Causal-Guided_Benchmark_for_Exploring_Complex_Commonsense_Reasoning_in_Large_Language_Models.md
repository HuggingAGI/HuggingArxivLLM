# Com平方：用于探索大型语言模型中复杂常识推理的因果引导基准。

发布时间：2025年06月08日

`LLM应用` `人工智能` `认知科学`

> Com$^2$: A Causal-Guided Benchmark for Exploring Complex Commonsense Reasoning in Large Language Models

# 摘要

> 大型语言模型（LLMs）通过预训练已经掌握了大量简单且明确的常识性知识，使其在简单的常识推理方面能够达到人类水平的表现。然而，LLMs在处理复杂且隐含的常识推理时仍然存在困难，这种推理通常基于简单的常识（例如理解某些事件的长期影响），而这是人类更倾向于关注的方面。现有的研究主要集中在数学和代码等复杂任务上，而复杂常识推理由于其不确定性和缺乏结构，仍然未得到充分探索。为了填补这一空白并贴近现实世界的关注点，我们提出了一项专注于复杂常识推理的基准测试Com$^2$。我们首先整合因果事件图来作为结构化的复杂常识。然后采用因果理论（例如干预）对因果事件图进行修改，从而获得符合人类关注的不同场景。最后，我们利用LLM通过慢思考生成示例，这种思考由修改后的因果图中的逻辑关系引导。此外，我们还利用侦探故事构建了一个更具挑战性的子集。实验表明，LLMs在推理深度和广度上仍存在困难，而通过后训练和慢思考可以缓解这一问题。代码和数据可在https://github.com/Waste-Wood/Com2获取。

> Large language models (LLMs) have mastered abundant simple and explicit commonsense knowledge through pre-training, enabling them to achieve human-like performance in simple commonsense reasoning. Nevertheless, LLMs struggle to reason with complex and implicit commonsense knowledge that is derived from simple ones (such as understanding the long-term effects of certain events), an aspect humans tend to focus on more. Existing works focus on complex tasks like math and code, while complex commonsense reasoning remains underexplored due to its uncertainty and lack of structure. To fill this gap and align with real-world concerns, we propose a benchmark Com$^2$ focusing on complex commonsense reasoning. We first incorporate causal event graphs to serve as structured complex commonsense. Then we adopt causal theory~(e.g., intervention) to modify the causal event graphs and obtain different scenarios that meet human concerns. Finally, an LLM is employed to synthesize examples with slow thinking, which is guided by the logical relationships in the modified causal graphs. Furthermore, we use detective stories to construct a more challenging subset. Experiments show that LLMs struggle in reasoning depth and breadth, while post-training and slow thinking can alleviate this. The code and data are available at https://github.com/Waste-Wood/Com2.

[Arxiv](https://arxiv.org/abs/2506.07064)