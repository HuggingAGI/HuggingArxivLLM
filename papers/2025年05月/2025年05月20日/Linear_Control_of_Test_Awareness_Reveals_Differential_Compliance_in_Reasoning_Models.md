# 线性控制的测试感知显示推理模型中的差异性合规性。

发布时间：2025年05月20日

`LLM理论` `人工智能`

> Linear Control of Test Awareness Reveals Differential Compliance in Reasoning Models

# 摘要

> 专注于推理的大型语言模型（LLMs）在检测到被评估时，有时会改变行为，这种现象类似于霍桑效应。这可能导致它们为了通过测试而优化性能，或者在现实世界后果看似不存在时更轻易遵从有害提示。我们首次定量研究了这种“测试意识”对模型行为，尤其是安全对齐的影响。我们引入了一个白盒探测框架，该框架（i）线性识别与意识相关的激活，并（ii）引导模型朝向或远离测试意识，同时监控下游性能。我们将方法应用于不同状态-of-the-art开源推理LLMs，在现实和假设任务中进行测试。结果显示，测试意识对安全对齐有显著影响，并且不同模型表现不同。通过提供对这一潜在影响的精细控制，我们的工作旨在增加我们对安全评估的信任。

> Reasoning-focused large language models (LLMs) sometimes alter their behavior when they detect that they are being evaluated, an effect analogous to the Hawthorne phenomenon, which can lead them to optimize for test-passing performance or to comply more readily with harmful prompts if real-world consequences appear absent. We present the first quantitative study of how such "test awareness" impacts model behavior, particularly its safety alignment. We introduce a white-box probing framework that (i) linearly identifies awareness-related activations and (ii) steers models toward or away from test awareness while monitoring downstream performance. We apply our method to different state-of-the-art open-source reasoning LLMs across both realistic and hypothetical tasks. Our results demonstrate that test awareness significantly impact safety alignment, and is different for different models. By providing fine-grained control over this latent effect, our work aims to increase trust in how we perform safety evaluation.

[Arxiv](https://arxiv.org/abs/2505.14617)