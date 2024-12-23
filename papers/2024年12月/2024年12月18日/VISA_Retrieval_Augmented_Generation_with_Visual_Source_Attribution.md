# VISA：带有视觉源归因的检索增强式生成

发布时间：2024年12月18日

`RAG` `检索增强生成`

> VISA: Retrieval Augmented Generation with Visual Source Attribution

# 摘要

> 生成时具备来源归属对于提升检索增强生成（RAG）系统的可验证性至关重要。然而，RAG 现有的方法主要是把生成的内容与文档级别的参考相链接，这使得用户难以在众多内容丰富的检索文档中找到证据。为应对此挑战，我们提出了带有视觉来源归属的检索增强生成（VISA）这一新方法，它将答案生成与视觉来源归属相结合。借助大型视觉语言模型（VLMs），VISA 能识别证据，并在检索文档的截图中用边框突出显示支持生成答案的准确区域。为评估其有效性，我们精心打造了两个数据集：基于爬取的维基百科网页截图的 Wiki-VISA，以及源自 PubLayNet 并针对医疗领域定制的 Paper-VISA。实验结果表明 VISA 在文档原始外观上进行视觉来源归属的有效性，同时也凸显了有待改进的挑战。代码、数据和模型检查点将会发布。

> Generation with source attribution is important for enhancing the verifiability of retrieval-augmented generation (RAG) systems. However, existing approaches in RAG primarily link generated content to document-level references, making it challenging for users to locate evidence among multiple content-rich retrieved documents. To address this challenge, we propose Retrieval-Augmented Generation with Visual Source Attribution (VISA), a novel approach that combines answer generation with visual source attribution. Leveraging large vision-language models (VLMs), VISA identifies the evidence and highlights the exact regions that support the generated answers with bounding boxes in the retrieved document screenshots. To evaluate its effectiveness, we curated two datasets: Wiki-VISA, based on crawled Wikipedia webpage screenshots, and Paper-VISA, derived from PubLayNet and tailored to the medical domain. Experimental results demonstrate the effectiveness of VISA for visual source attribution on documents' original look, as well as highlighting the challenges for improvement. Code, data, and model checkpoints will be released.

[Arxiv](https://arxiv.org/abs/2412.14457)