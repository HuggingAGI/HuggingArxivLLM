# Self-ReS：大型视觉-语言模型的自我反思机制，助力长视频理解

发布时间：2025年03月26日

`LLM应用` `视频处理`

> Self-ReS: Self-Reflection in Large Vision-Language Models for Long Video Understanding

# 摘要

> 大型视觉-语言模型 (LVLMs) 在短视频任务（如视频问答）中表现出色，但在长视频理解方面面临挑战。传统线性帧采样策略未能捕捉视频数据中关键事件的非线性分布，导致在长上下文中引入冗余信息，在短上下文中可能遗漏关键事件。为解决这一问题，我们提出了 SelfReS，这是一种基于用户提示动态选择关键视频片段的非线性时空自反思采样方法。与传统方法不同，SelfReS 利用 LVLMs 本身固有的稀疏注意力图定义反思令牌，无需额外训练或外部模块即可实现相关令牌的选择。实验表明，SelfReS 可无缝集成到强大 LVLMs 中，显著提升长视频任务的准确性，同时在相同 GPU 内存预算下将推理速度提升高达 46%。

> Large Vision-Language Models (LVLMs) demonstrate remarkable performance in short-video tasks such as video question answering, but struggle in long-video understanding. The linear frame sampling strategy, conventionally used by LVLMs, fails to account for the non-linear distribution of key events in video data, often introducing redundant or irrelevant information in longer contexts while risking the omission of critical events in shorter ones. To address this, we propose SelfReS, a non-linear spatiotemporal self-reflective sampling method that dynamically selects key video fragments based on user prompts. Unlike prior approaches, SelfReS leverages the inherently sparse attention maps of LVLMs to define reflection tokens, enabling relevance-aware token selection without requiring additional training or external modules. Experiments demonstrate that SelfReS can be seamlessly integrated into strong base LVLMs, improving long-video task accuracy and achieving up to 46% faster inference speed within the same GPU memory budget.

[Arxiv](https://arxiv.org/abs/2503.20362)