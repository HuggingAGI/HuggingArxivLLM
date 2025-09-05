# 面向具身智能体测试时自适应的世界模型植入

发布时间：2025年09月04日

`Agent` `基础理论`

> World Model Implanting for Test-time Adaptation of Embodied Agents

# 摘要

> 在具身人工智能领域，让智能体无需大量数据采集或重新训练就能稳健适应新领域，一直是个棘手难题。为此，我们提出世界模型植入框架（WorMI），它通过测试时组合技术，将大型语言模型（LLMs）的推理能力与独立训练的特定领域世界模型巧妙结合。借助世界模型的无缝植入与移除机制，具身智能体的策略得以实现并持续保持跨领域适应性。在WorMI框架中，我们采用基于原型的世界模型检索方法，通过高效的轨迹抽象表示匹配，将相关模型整合到测试时组合流程。我们还研发了世界级复合注意力机制，不仅能融合检索到的世界模型知识，还能将其中间表示与智能体策略中推理模型的表示精准对齐。这种框架设计高效融合多世界模型的领域知识，确保对未知领域的稳健适应。在VirtualHome和ALFWorld基准测试中，WorMI的表现令人瞩目——在一系列未见领域里，其零样本和少样本性能均显著优于多种基于LLM的方法。这些结果充分彰显了该框架在具身智能体场景中的可扩展落地潜力，尤其适用于那些对适应性和数据效率有高要求的实际应用。

> In embodied AI, a persistent challenge is enabling agents to robustly adapt to novel domains without requiring extensive data collection or retraining. To address this, we present a world model implanting framework (WorMI) that combines the reasoning capabilities of large language models (LLMs) with independently learned, domain-specific world models through test-time composition. By allowing seamless implantation and removal of the world models, the embodied agent's policy achieves and maintains cross-domain adaptability. In the WorMI framework, we employ a prototype-based world model retrieval approach, utilizing efficient trajectory-based abstract representation matching, to incorporate relevant models into test-time composition. We also develop a world-wise compound attention method that not only integrates the knowledge from the retrieved world models but also aligns their intermediate representations with the reasoning model's representation within the agent's policy. This framework design effectively fuses domain-specific knowledge from multiple world models, ensuring robust adaptation to unseen domains. We evaluate our WorMI on the VirtualHome and ALFWorld benchmarks, demonstrating superior zero-shot and few-shot performance compared to several LLM-based approaches across a range of unseen domains. These results highlight the frameworks potential for scalable, real-world deployment in embodied agent scenarios where adaptability and data efficiency are essential.

[Arxiv](https://arxiv.org/abs/2509.03956)