# 基于 VisionLLM 的多模态融合网络用于声门癌的早期检测

发布时间：2024年12月23日

`LLM应用` `癌症检测`

> VisionLLM-based Multimodal Fusion Network for Glottic Carcinoma Early Detection

# 摘要

> 声门癌的早期检测对改善患者预后意义重大，因其能及时干预，保住发声功能，还能大幅降低肿瘤进展和转移的风险。但声门癌与声带发育不良在形态上颇为相似，致使检测准确率欠佳。为应对此问题，我们提出了一种基于视觉大语言模型（VisionLLM-based）的声门癌检测多模态融合网络，即 MMGC-Net。通过整合图像和文本模态，多模态模型能够获取互补信息，进而做出更准确、更可靠的预测。在本文中，我们从中山大学附属第一医院收集了一个名为 SYSU1H 的私人真实声门癌数据集，包含 5799 个图像 - 文本对。我们借助图像编码器和额外的 Q-Former 提取视觉嵌入，并用大型语言模型 Meta AI（Llama3）获取文本嵌入。随后，这些模态通过喉部特征融合块加以整合，实现图像和文本特征的全面融合，从而提升声门癌的识别性能。在 SYSU1H 数据集上开展的大量实验表明，MMGC-Net 能够达到顶尖水平，优于以往的多模态模型。

> The early detection of glottic carcinoma is critical for improving patient outcomes, as it enables timely intervention, preserves vocal function, and significantly reduces the risk of tumor progression and metastasis. However, the similarity in morphology between glottic carcinoma and vocal cord dysplasia results in suboptimal detection accuracy. To address this issue, we propose a vision large language model-based (VisionLLM-based) multimodal fusion network for glottic carcinoma detection, known as MMGC-Net. By integrating image and text modalities, multimodal models can capture complementary information, leading to more accurate and robust predictions. In this paper, we collect a private real glottic carcinoma dataset named SYSU1H from the First Affiliated Hospital of Sun Yat-sen University, with 5,799 image-text pairs. We leverage an image encoder and additional Q-Former to extract vision embeddings and the Large Language Model Meta AI (Llama3) to obtain text embeddings. These modalities are then integrated through a laryngeal feature fusion block, enabling a comprehensive integration of image and text features, thereby improving the glottic carcinoma identification performance. Extensive experiments on the SYSU1H dataset demonstrate that MMGC-Net can achieve state-of-the-art performance, which is superior to previous multimodal models.

[Arxiv](https://arxiv.org/abs/2412.18124)