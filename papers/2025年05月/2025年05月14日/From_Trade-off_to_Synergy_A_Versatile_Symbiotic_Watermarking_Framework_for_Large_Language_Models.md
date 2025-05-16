# 从权衡到协同：一种通用的共生水印框架，专为大型语言模型设计

发布时间：2025年05月14日

`LLM应用

摘要讨论了大型语言模型（LLMs）生成文本的滥用问题，并提出了一种水印技术来解决这一问题。水印技术属于LLM的应用层面，因为它涉及如何在实际应用中防止滥用。因此，这篇论文应归类为LLM应用。` `数字版权管理` `信息安全`

> From Trade-off to Synergy: A Versatile Symbiotic Watermarking Framework for Large Language Models

# 摘要

> 大型语言模型 (LLMs) 的兴起引发了对 AI 生成文本滥用的广泛关注，水印技术成为解决这一问题的有力工具。目前主流的 LLM 水印方案主要分为两类：基于 logits 的和基于采样的。然而，现有方案在鲁棒性、文本质量和安全性之间存在权衡。为了解决这一问题，我们整合了基于 logits 和基于采样的方案，结合它们各自的优点，以实现协同效应。在本文中，我们提出了一种灵活的共生水印框架，包含三种策略：串行、并行和混合。混合框架通过利用令牌熵和语义熵自适应地嵌入水印，优化了可检测性、鲁棒性、文本质量和安全性之间的平衡。此外，我们通过在各种数据集和模型上的全面实验验证了我们的方法。实验结果表明，我们的方法优于现有的基线，并达到了最先进的 (SOTA) 性能。我们相信，这一框架为多样化的水印范式提供了新颖的见解。我们的代码可在 \href{https://github.com/redwyd/SymMark}{https://github.com/redwyd/SymMark} 获取。

> The rise of Large Language Models (LLMs) has heightened concerns about the misuse of AI-generated text, making watermarking a promising solution. Mainstream watermarking schemes for LLMs fall into two categories: logits-based and sampling-based. However, current schemes entail trade-offs among robustness, text quality, and security. To mitigate this, we integrate logits-based and sampling-based schemes, harnessing their respective strengths to achieve synergy. In this paper, we propose a versatile symbiotic watermarking framework with three strategies: serial, parallel, and hybrid. The hybrid framework adaptively embeds watermarks using token entropy and semantic entropy, optimizing the balance between detectability, robustness, text quality, and security. Furthermore, we validate our approach through comprehensive experiments on various datasets and models. Experimental results indicate that our method outperforms existing baselines and achieves state-of-the-art (SOTA) performance. We believe this framework provides novel insights into diverse watermarking paradigms. Our code is available at \href{https://github.com/redwyd/SymMark}{https://github.com/redwyd/SymMark}.

[Arxiv](https://arxiv.org/abs/2505.09924)