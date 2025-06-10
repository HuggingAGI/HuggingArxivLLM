# 基于排名的均匀性测试：审查黑盒LLM API

发布时间：2025年06月07日

`LLM应用` `网络安全` `人工智能`

> Auditing Black-Box LLM APIs with a Rank-Based Uniformity Test

# 摘要

> 随着API访问成为大型语言模型（LLMs）的主要交互接口，用户通常与提供有限模型部署透明度的黑箱系统进行交互。为了降低成本或恶意改变模型行为，API提供商可能会悄然提供量化或微调后的变体，这可能会降低性能并危及安全性。检测此类替换颇具挑战性，因为用户无法访问模型权重，且在大多数情况下甚至无法获取输出logits。为解决这一问题，我们提出了一种基于排序的均匀性测试，可以验证黑箱LLM与本地部署的真实模型在行为上是否一致。我们的方法具有高准确性、查询高效性，并避免可检测的查询模式，使其能够抵御那些在检测到测试尝试时重定向或混合响应的对抗性提供商。我们通过多样化的威胁场景评估了该方法，包括量化、有害微调、越狱提示和完整模型替换，结果表明，在受限的查询预算下，该方法始终在统计效力上优于先前的方法。

> As API access becomes a primary interface to large language models (LLMs), users often interact with black-box systems that offer little transparency into the deployed model. To reduce costs or maliciously alter model behaviors, API providers may discreetly serve quantized or fine-tuned variants, which can degrade performance and compromise safety. Detecting such substitutions is difficult, as users lack access to model weights and, in most cases, even output logits. To tackle this problem, we propose a rank-based uniformity test that can verify the behavioral equality of a black-box LLM to a locally deployed authentic model. Our method is accurate, query-efficient, and avoids detectable query patterns, making it robust to adversarial providers that reroute or mix responses upon the detection of testing attempts. We evaluate the approach across diverse threat scenarios, including quantization, harmful fine-tuning, jailbreak prompts, and full model substitution, showing that it consistently achieves superior statistical power over prior methods under constrained query budgets.

[Arxiv](https://arxiv.org/abs/2506.06975)