# IRT-Router：基于项目反应理论的有效且可解释的多LLM路由方案

发布时间：2025年06月01日

`LLM应用` `模型优化`

> IRT-Router: Effective and Interpretable Multi-LLM Routing via Item Response Theory

# 摘要

> 大型语言模型（LLMs）在各类自然语言任务中表现优异，但在选择最适合的LLM来响应用户查询时，需在性能与成本之间找到平衡。强大的模型固然效果更好，但成本也更高，而较小的模型则更经济但能力有限。为解决这一难题，我们提出了IRT-Router——一个基于心理测量学中的项目反应理论（IRT）的多LLM路由框架。它通过建模LLM能力与查询属性的关系，不仅实现精准预测，还提供可解释的见解，如模型能力和查询难度。此外，我们还设计了一种基于语义相似性的在线预热技术，进一步提升了IRT-Router的泛化能力。在20个LLM和12个数据集上的实验显示，IRT-Router在效果和可解释性上优于多数基线方法。其在冷启动场景中的出色表现也验证了其在实际应用中的可靠性和实用性。代码已开源，地址为https://github.com/Mercidaiha/IRT-Router。

> Large language models (LLMs) have demonstrated exceptional performance across a wide range of natural language tasks. However, selecting the optimal LLM to respond to a user query often necessitates a delicate balance between performance and cost. While powerful models deliver better results, they come at a high cost, whereas smaller models are more cost-effective but less capable. To address this trade-off, we propose IRT-Router, a multi-LLM routing framework that efficiently routes user queries to the most suitable LLM. Inspired by Item Response Theory (IRT), a psychological measurement methodology, IRT-Router explicitly models the relationship between LLM capabilities and user query attributes. This not only enables accurate prediction of response performance but also provides interpretable insights, such as LLM abilities and query difficulty. Additionally, we design an online query warm-up technique based on semantic similarity, further enhancing the online generalization capability of IRT-Router. Extensive experiments on 20 LLMs and 12 datasets demonstrate that IRT-Router outperforms most baseline methods in terms of effectiveness and interpretability. Its superior performance in cold-start scenarios further confirms the reliability and practicality of IRT-Router in real-world applications. Code is available at https://github.com/Mercidaiha/IRT-Router.

[Arxiv](https://arxiv.org/abs/2506.01048)