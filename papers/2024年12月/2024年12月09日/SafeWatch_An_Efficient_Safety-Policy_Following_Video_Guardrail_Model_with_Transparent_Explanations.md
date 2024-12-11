# SafeWatch：一个具备透明解释的高效安全策略遵循视频护栏模型

发布时间：2024年12月09日

`LLM应用`

> SafeWatch: An Efficient Safety-Policy Following Video Guardrail Model with Transparent Explanations

# 摘要

> 随着生成式人工智能的兴起以及高质量视频生成的迅猛发展，视频防护栏对于保障各平台的安全变得空前重要。然而，当下的视频防护栏，要么过于简化，依赖基于有限不安全类别和简单策略训练的纯分类模型，缺少详尽解释；要么用冗长的安全指南提示多模态大型语言模型（MLLM），这在防护现实世界的内容时效率低下且不实用。为了填补这一空缺，我们推出了SafeWatch，这是一款基于高效MLLM的视频防护栏模型，旨在遵循定制的安全策略，以零样本方式提供带有内容特定解释的多标签视频防护栏输出。特别要指出的是，传统基于MLLM的防护栏对所有安全策略进行自回归编码，会导致效率低和有偏差，而SafeWatch独特地并行编码每个策略块，并消除其位置偏差，使所有策略能同时受到同等重视。另外，为提升效率和准确性，SafeWatch融入了一种策略感知的视觉令牌修剪算法，它能自适应地为每个策略挑选最相关的视频令牌，摒弃嘈杂或不相关的信息。这使得防护栏更具针对性、符合策略，同时大幅降低计算开销。鉴于现有视频防护栏基准的局限性，我们提出了SafeWatch-Bench，这是一个大规模的视频防护栏基准，涵盖超过 200 万个跨越六个安全类别的视频，涉及 30 多项任务，以确保全面涵盖所有潜在的安全场景。SafeWatch 在 SafeWatch-Bench 上的表现比 SOTA 高出 28.2%，在基准测试中高出 13.6%，降低了 10%的成本，并提供了经 LLM 和人工审核验证的顶级解释。

> With the rise of generative AI and rapid growth of high-quality video generation, video guardrails have become more crucial than ever to ensure safety and security across platforms. Current video guardrails, however, are either overly simplistic, relying on pure classification models trained on simple policies with limited unsafe categories, which lack detailed explanations, or prompting multimodal large language models (MLLMs) with long safety guidelines, which are inefficient and impractical for guardrailing real-world content. To bridge this gap, we propose SafeWatch, an efficient MLLM-based video guardrail model designed to follow customized safety policies and provide multi-label video guardrail outputs with content-specific explanations in a zero-shot manner. In particular, unlike traditional MLLM-based guardrails that encode all safety policies autoregressively, causing inefficiency and bias, SafeWatch uniquely encodes each policy chunk in parallel and eliminates their position bias such that all policies are attended simultaneously with equal importance. In addition, to improve efficiency and accuracy, SafeWatch incorporates a policy-aware visual token pruning algorithm that adaptively selects the most relevant video tokens for each policy, discarding noisy or irrelevant information. This allows for more focused, policy-compliant guardrail with significantly reduced computational overhead. Considering the limitations of existing video guardrail benchmarks, we propose SafeWatch-Bench, a large-scale video guardrail benchmark comprising over 2M videos spanning six safety categories which covers over 30 tasks to ensure a comprehensive coverage of all potential safety scenarios. SafeWatch outperforms SOTA by 28.2% on SafeWatch-Bench, 13.6% on benchmarks, cuts costs by 10%, and delivers top-tier explanations validated by LLM and human reviews.

[Arxiv](https://arxiv.org/abs/2412.06878)