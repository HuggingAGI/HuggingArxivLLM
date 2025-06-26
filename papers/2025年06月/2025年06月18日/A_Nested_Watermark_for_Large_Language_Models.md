# 大型语言模型的嵌入式水印

发布时间：2025年06月18日

`LLM应用` `信息安全` `内容安全`

> A Nested Watermark for Large Language Models

# 摘要

> 大型语言模型 (LLMs) 的快速发展引发了对其潜在滥用的担忧，尤其是在生成虚假新闻和误导信息方面。为应对这些风险，针对自回归语言模型的水印技术作为一种检测 LLM 生成文本的手段应运而生。现有方法通常通过根据单一密钥选择的标记组增加标记概率来嵌入水印。然而，这种方法存在一个关键缺陷：如果密钥泄露，就无法追踪文本的来源或确定作者身份。为克服这一漏洞，我们提出了一种新颖的嵌套水印方案，该方案使用两个独立密钥将两个不同的水印嵌入到生成文本中。这种设计即使其中一个密钥被泄露，仍能可靠地识别作者身份。实验结果表明，我们的方法在保持生成文本流畅性和整体质量的同时，实现了对两个水印的高检测准确率。

> The rapid advancement of large language models (LLMs) has raised concerns regarding their potential misuse, particularly in generating fake news and misinformation. To address these risks, watermarking techniques for autoregressive language models have emerged as a promising means for detecting LLM-generated text. Existing methods typically embed a watermark by increasing the probabilities of tokens within a group selected according to a single secret key. However, this approach suffers from a critical limitation: if the key is leaked, it becomes impossible to trace the text's provenance or attribute authorship. To overcome this vulnerability, we propose a novel nested watermarking scheme that embeds two distinct watermarks into the generated text using two independent keys. This design enables reliable authorship identification even in the event that one key is compromised. Experimental results demonstrate that our method achieves high detection accuracy for both watermarks while maintaining the fluency and overall quality of the generated text.

[Arxiv](https://arxiv.org/abs/2506.17308)