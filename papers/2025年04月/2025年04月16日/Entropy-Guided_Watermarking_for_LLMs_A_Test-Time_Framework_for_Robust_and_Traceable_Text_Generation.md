# 熵引导的大型语言模型水印技术：测试时稳健可追溯文本生成框架

发布时间：2025年04月16日

`LLM应用

摘要中讨论了在大型语言模型中引入水印方案以增强内容可追溯性和安全性，属于应用层面的改进。` `内容安全`

> Entropy-Guided Watermarking for LLMs: A Test-Time Framework for Robust and Traceable Text Generation

# 摘要

> 大型语言模型（LLMs）的快速发展加剧了人们对内容可追溯性和潜在滥用的担忧。现有的针对采样文本的水印方案常常在保持文本质量和确保对各种攻击的鲁棒检测之间面临权衡。为了解决这些问题，我们提出了一种新型水印方案，通过引入累积水印熵阈值来提升检测率和文本质量。我们的方法与现有采样函数兼容并具有更好的通用性，从而增强了适应性。在多个LLMs上的实验结果表明，我们的方案显著优于现有方法，在广泛使用的数据集（如MATH和GSM8K）上实现了80%以上的提升，同时保持了高检测准确性。

> The rapid development of Large Language Models (LLMs) has intensified concerns about content traceability and potential misuse. Existing watermarking schemes for sampled text often face trade-offs between maintaining text quality and ensuring robust detection against various attacks. To address these issues, we propose a novel watermarking scheme that improves both detectability and text quality by introducing a cumulative watermark entropy threshold. Our approach is compatible with and generalizes existing sampling functions, enhancing adaptability. Experimental results across multiple LLMs show that our scheme significantly outperforms existing methods, achieving over 80\% improvements on widely-used datasets, e.g., MATH and GSM8K, while maintaining high detection accuracy.

[Arxiv](https://arxiv.org/abs/2504.12108)