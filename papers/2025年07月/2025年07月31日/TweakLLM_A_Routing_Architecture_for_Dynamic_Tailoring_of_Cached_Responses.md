# TweakLLM：为动态定制缓存响应设计的路由架构

发布时间：2025年07月31日

`LLM应用` `云计算` `人工智能`

> TweakLLM: A Routing Architecture for Dynamic Tailoring of Cached Responses

# 摘要

> 每天处理数百万个查询的大型语言模型（LLMs），其高效响应缓存成为降低费用和延迟的有力优化手段。然而，由于聊天机器人交互的个性化特性和语义相似性搜索的准确性有限，使用这种方法保持与用户查询的相关性变得困难。为了解决这一问题，我们提出了TweakLLM，这是一种新颖的路由架构，利用轻量级LLM动态调整缓存响应以适应传入提示。通过全面的评估，包括并排比较的用户研究、满意度投票，以及多智能体LLM辩论，我们证明TweakLLM在保持与前沿模型相当的响应质量的同时，显著提高了缓存效果。我们在真实世界数据集上的实验结果凸显了TweakLLM作为可扩展且资源高效的缓存解决方案，适用于高吞吐量的LLM部署，同时不会影响用户体验。

> Large Language Models (LLMs) process millions of queries daily, making efficient response caching a compelling optimization for reducing cost and latency. However, preserving relevance to user queries using this approach proves difficult due to the personalized nature of chatbot interactions and the limited accuracy of semantic similarity search. To address this, we present TweakLLM, a novel routing architecture that employs a lightweight LLM to dynamically adapt cached responses to incoming prompts. Through comprehensive evaluation, including user studies with side-by-side comparisons, satisfaction voting, as well as multi-agent LLM debates, we demonstrate that TweakLLM maintains response quality comparable to frontier models while significantly improving cache effectiveness. Our results across real-world datasets highlight TweakLLM as a scalable, resource-efficient caching solution for high-volume LLM deployments without compromising user experience.

[Arxiv](https://arxiv.org/abs/2507.23674)