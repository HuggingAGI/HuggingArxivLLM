# 通过基于内部事实的对比解码，缓解大型视觉-语言模型中的幻觉问题

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论了大型视觉语言模型（LVLMs）在处理多模态任务时面临的物体幻觉问题，并提出了一种新的方法——基于内部事实的对比解码（IFCD）来抑制幻觉。虽然论文涉及视觉和语言模态的融合，但其核心关注点是通过调整模型内部表示来优化模型输出，减少幻觉。这属于对大型语言模型（LLM）在实际应用中的改进和优化，因此归类为LLM应用。` `计算机视觉`

> Mitigating Hallucinations in Large Vision-Language Models with Internal Fact-based Contrastive Decoding

# 摘要

> # 摘要
大型视觉语言模型（LVLMs）融合了视觉与语言模态，在多模态任务中表现卓越。然而，LVLMs仍面临物体幻觉问题的困扰。以往的研究多通过监督微调（SFT）或引入外部知识来应对，但这些方法成本高昂。为此，我们提出了一种模型无关的新方法——基于内部事实的对比解码（IFCD），通过利用LVLMs自身的幻觉，在推理过程中有效抑制幻觉。IFCD基于实验发现：对LVLMs内部表示的调整会加剧语言偏差导致的幻觉。通过对比扰动分布，IFCD校准模型输出，剔除幻觉logits。实验证明，IFCD显著减少了物体级和属性级幻觉，并在POPE和MME物体幻觉子集上分别提升了9%和8%的准确率。

> Large Visual Language Models (LVLMs) integrate visual and linguistic modalities, exhibiting exceptional performance across various multimodal tasks. Nevertheless, LVLMs remain vulnerable to the issue of object hallucinations. Previous efforts to mitigate this issue focus on supervised fine-tuning (SFT) or incorporating external knowledge, both of which entail significant costs related to training and the acquisition of external data. To address these challenges, we propose a novel model-agnostic approach termed Internal Fact-based Contrastive Decoding (IFCD), designed to mitigate and suppress hallucinations during the inference process of LVLMs by exploiting the LVLMs' own hallucinations. IFCD is grounded in experimental observations that alterations to the LVLMs' internal representations tend to amplify hallucinations caused by language bias. By contrasting disturbed distribution, IFCD calibrates the LVLMs' output and effectively removes the hallucinatory logits from the final predictions. Experimental results validate that IFCD significantly alleviates both object-level and attribute-level hallucinations while achieving an average 9% accuracy improvement on POPE and 8% accuracy improvement on MME object hallucinations subset compared with direct decoding, respectively.

[Arxiv](https://arxiv.org/abs/2502.01056)