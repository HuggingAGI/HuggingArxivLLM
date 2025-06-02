# Mind the Quote: 留心引用，为大型语言模型赋能引用感知对话的即插即用模块

发布时间：2025年05月30日

`LLM应用` `对话系统`

> Mind the Quote: Enabling Quotation-Aware Dialogue in LLMs via Plug-and-Play Modules

# 摘要

> 人机对话常需引用先前文本，例如“用我刚才标出的公式验证一下”，但当今大型语言模型（LLMs）缺乏明确的机制来定位并利用这些文本片段。我们将其形式化为基于跨度的条件生成，将每一轮对话分解为对话历史、一组基于令牌偏移的引用跨度以及意图表达。基于这一抽象概念，我们引入了一个以引用为中心的数据管道，能够自动合成特定任务的对话，通过多阶段一致性检查验证答案的正确性，并生成异质训练语料库和首个涵盖五种代表性场景的基准测试。为满足基准测试的零开销和参数高效性要求，我们提出了一种轻量级的训练方法QuAda，该方法在每个注意力头后附加两个瓶颈投影，动态放大或抑制推理时对引用跨度的注意力，同时保持提示不变，并更新不到2.8%的主干权重。跨模型的实验表明，QuAda适用于所有场景，并能推广到未见过的主题，为引用感知对话提供了一种有效且即插即用的解决方案。

> Human-AI conversation frequently relies on quoting earlier text-"check it with the formula I just highlighted"-yet today's large language models (LLMs) lack an explicit mechanism for locating and exploiting such spans. We formalise the challenge as span-conditioned generation, decomposing each turn into the dialogue history, a set of token-offset quotation spans, and an intent utterance. Building on this abstraction, we introduce a quotation-centric data pipeline that automatically synthesises task-specific dialogues, verifies answer correctness through multi-stage consistency checks, and yields both a heterogeneous training corpus and the first benchmark covering five representative scenarios. To meet the benchmark's zero-overhead and parameter-efficiency requirements, we propose QuAda, a lightweight training-based method that attaches two bottleneck projections to every attention head, dynamically amplifying or suppressing attention to quoted spans at inference time while leaving the prompt unchanged and updating < 2.8% of backbone weights. Experiments across models show that QuAda is suitable for all scenarios and generalises to unseen topics, offering an effective, plug-and-play solution for quotation-aware dialogue.

[Arxiv](https://arxiv.org/abs/2505.24292)