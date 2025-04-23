# 时尚-RAG：多模态时尚图像编辑的检索增强生成方法

发布时间：2025年04月18日

`RAG` `图像生成`

> Fashion-RAG: Multimodal Fashion Image Editing via Retrieval-Augmented Generation

# 摘要

> 近年来，随着电子商务和虚拟应用的蓬勃发展，时尚行业越来越多地借助人工智能技术提升客户体验。其中，虚拟试穿和多模态时尚图像编辑——利用文本、服装草图和身体姿势等多种输入形式——已成为研究的热点。扩散模型作为一种生成任务的领先方法，提供了更高质量和多样性的图像生成。然而，现有的虚拟试穿方法大多依赖于特定的服装输入，这在实际场景中往往不切实际，因为用户可能仅提供文本描述。为了解决这一限制，本研究提出了时尚检索增强生成（Fashion-RAG），这是一种基于用户文本偏好定制时尚商品的新方法。我们的方法通过检索与输入描述匹配的多件服装，并整合这些服装的属性，生成个性化图像。为此，我们采用了文本反转技术，将检索到的服装图像投影到Stable Diffusion文本编码器的文本嵌入空间中，从而实现检索元素与生成过程的无缝融合。在Dress Code数据集上的实验结果表明，Fashion-RAG在定性和定量评估中均优于现有方法，能够有效捕捉到检索服装的精细视觉细节。据我们所知，这是首个专门针对多模态时尚图像编辑的检索增强生成方法。


> In recent years, the fashion industry has increasingly adopted AI technologies to enhance customer experience, driven by the proliferation of e-commerce platforms and virtual applications. Among the various tasks, virtual try-on and multimodal fashion image editing -- which utilizes diverse input modalities such as text, garment sketches, and body poses -- have become a key area of research. Diffusion models have emerged as a leading approach for such generative tasks, offering superior image quality and diversity. However, most existing virtual try-on methods rely on having a specific garment input, which is often impractical in real-world scenarios where users may only provide textual specifications. To address this limitation, in this work we introduce Fashion Retrieval-Augmented Generation (Fashion-RAG), a novel method that enables the customization of fashion items based on user preferences provided in textual form. Our approach retrieves multiple garments that match the input specifications and generates a personalized image by incorporating attributes from the retrieved items. To achieve this, we employ textual inversion techniques, where retrieved garment images are projected into the textual embedding space of the Stable Diffusion text encoder, allowing seamless integration of retrieved elements into the generative process. Experimental results on the Dress Code dataset demonstrate that Fashion-RAG outperforms existing methods both qualitatively and quantitatively, effectively capturing fine-grained visual details from retrieved garments. To the best of our knowledge, this is the first work to introduce a retrieval-augmented generation approach specifically tailored for multimodal fashion image editing.

[Arxiv](https://arxiv.org/abs/2504.14011)