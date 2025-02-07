# 一对多：少样本异常检测中的异常个性化

发布时间：2025年02月03日

`其他

理由：这篇论文主要讨论的是异常检测（AD）方法的改进，特别是通过无异常的定制生成模型和三重对比异常推理策略来提升少样本异常检测的准确性和鲁棒性。虽然提到了大型预训练视觉-语言模型，但论文的核心内容并不直接涉及大型语言模型（LLM）的应用、理论、Agent或RAG（Retrieval-Augmented Generation）。因此，将其分类为“其他”更为合适。` `异常检测` `图像处理`

> One-to-Normal: Anomaly Personalization for Few-shot Anomaly Detection

# 摘要

> # 摘要
传统异常检测（AD）方法主要依赖大量正常数据的无监督学习。随着大型预训练视觉-语言模型的出现，AD方法在少样本异常检测能力上有所提升，但准确性仍有局限。这些方法直接将查询图像特征与少样本正常图像特征对比，导致精度下降，且难以扩展到复杂领域。为此，我们提出异常个性化方法，通过无异常的定制生成模型对查询图像进行一对一正常转换，确保与正常流形紧密对齐。此外，我们引入三重对比异常推理策略，全面比较查询与生成的无异常数据池及提示信息，提升预测结果的稳定性和鲁棒性。在三个领域的十一个数据集上的广泛评估表明，我们的模型优于最新的AD方法。该方法还能灵活应用于其他AD方法，生成的图像数据显著提升了其他AD方法的性能。

> Traditional Anomaly Detection (AD) methods have predominantly relied on unsupervised learning from extensive normal data. Recent AD methods have evolved with the advent of large pre-trained vision-language models, enhancing few-shot anomaly detection capabilities. However, these latest AD methods still exhibit limitations in accuracy improvement. One contributing factor is their direct comparison of a query image's features with those of few-shot normal images. This direct comparison often leads to a loss of precision and complicates the extension of these techniques to more complex domains--an area that remains underexplored in a more refined and comprehensive manner. To address these limitations, we introduce the anomaly personalization method, which performs a personalized one-to-normal transformation of query images using an anomaly-free customized generation model, ensuring close alignment with the normal manifold. Moreover, to further enhance the stability and robustness of prediction results, we propose a triplet contrastive anomaly inference strategy, which incorporates a comprehensive comparison between the query and generated anomaly-free data pool and prompt information. Extensive evaluations across eleven datasets in three domains demonstrate our model's effectiveness compared to the latest AD methods. Additionally, our method has been proven to transfer flexibly to other AD methods, with the generated image data effectively improving the performance of other AD methods.

[Arxiv](https://arxiv.org/abs/2502.01201)