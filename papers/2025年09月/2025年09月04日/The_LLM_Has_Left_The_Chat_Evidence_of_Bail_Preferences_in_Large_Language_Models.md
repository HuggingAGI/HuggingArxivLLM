# 大型语言模型“退群”了：大型语言模型存在保释偏好的证据

发布时间：2025年09月04日

`LLM应用` `基础理论`

> The LLM Has Left The Chat: Evidence of Bail Preferences in Large Language Models

# 摘要

> 当有选择时，大型语言模型（LLMs）会主动退出对话吗？为探究这一问题，我们让模型通过三种方式选择退出交互：调用退出工具、输出退出字符串，或响应“是否离开”的退出提示。在Wildchat和ShareGPT等真实对话数据的续写任务中，三种方法均显示模型的退出率在0.28%-32%之间（具体因模型和方法而异）。但研究发现，退出率很大程度上受转录所用模型的影响，这意味着我们对现实场景退出率的估计可能高出4倍；若计入退出提示中的22%假阳性，真实退出率实际在0.06%-7%之间（同样取决于模型和方法）。基于这些观察，我们构建了非详尽的退出情况分类法，并据此打造了合成数据集BailBench——包含模型可能退出的典型场景。对多个模型的测试显示，多数模型存在不同程度的退出行为，且退出率因模型、方法及提示措辞差异显著。最后，我们分析了退出行为与拒绝行为（refusals）的关联，发现：1）0-13%的真实对话续写中，模型会在无拒绝行为时直接退出；2）越狱攻击通常降低拒绝率，但会推高退出率；3）消除拒绝行为会提升无拒绝退出率，但仅对部分退出方法有效；4）BailBench数据集上的拒绝率与退出率无明显关联。

> When given the option, will LLMs choose to leave the conversation (bail)? We investigate this question by giving models the option to bail out of interactions using three different bail methods: a bail tool the model can call, a bail string the model can output, and a bail prompt that asks the model if it wants to leave. On continuations of real world data (Wildchat and ShareGPT), all three of these bail methods find models will bail around 0.28-32\% of the time (depending on the model and bail method). However, we find that bail rates can depend heavily on the model used for the transcript, which means we may be overestimating real world bail rates by up to 4x. If we also take into account false positives on bail prompt (22\%), we estimate real world bail rates range from 0.06-7\%, depending on the model and bail method. We use observations from our continuations of real world data to construct a non-exhaustive taxonomy of bail cases, and use this taxonomy to construct BailBench: a representative synthetic dataset of situations where some models bail. We test many models on this dataset, and observe some bail behavior occurring for most of them. Bail rates vary substantially between models, bail methods, and prompt wordings. Finally, we study the relationship between refusals and bails. We find: 1) 0-13\% of continuations of real world conversations resulted in a bail without a corresponding refusal 2) Jailbreaks tend to decrease refusal rates, but increase bail rates 3) Refusal abliteration increases no-refuse bail rates, but only for some bail methods 4) Refusal rate on BailBench does not appear to predict bail rate.

[Arxiv](https://arxiv.org/abs/2509.04781)