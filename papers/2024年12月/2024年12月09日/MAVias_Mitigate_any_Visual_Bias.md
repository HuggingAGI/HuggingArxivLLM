# MAVias：消除任何视觉偏差

发布时间：2024年12月09日

`LLM应用` `计算机视觉` `人工智能`

> MAVias: Mitigate any Visual Bias

# 摘要

> 减轻计算机视觉模型中的偏差，是走向人工智能模型可信性的关键一步。现有的偏差缓解方法多聚焦于少量预定义的偏差，这限制了它们在存在多种可能未知偏差的视觉数据集中的应用。为应对此限制，我们推出了 MAVias，这是一种借助基础模型来发现视觉属性与目标类别间虚假关联的开放集偏差缓解手段。MAVias 先是通过基础图像标记模型用自然语言捕捉各类视觉特征，接着利用大型语言模型选取定义目标类别的那些视觉特征，由此得出一组语言编码的潜在视觉偏差。随后，我们把这组潜在偏差转化为视觉语言嵌入，并引入一种处理中的偏差缓解方法，防止模型编码与之相关的信息。我们在 CelebA、Waterbirds、ImageNet 和 UrbanCars 等多种数据集上的实验表明，MAVias 能有效检测和缓解视觉识别任务中的各类偏差，表现优于当下的先进水平。

> Mitigating biases in computer vision models is an essential step towards the trustworthiness of artificial intelligence models. Existing bias mitigation methods focus on a small set of predefined biases, limiting their applicability in visual datasets where multiple, possibly unknown biases exist. To address this limitation, we introduce MAVias, an open-set bias mitigation approach leveraging foundation models to discover spurious associations between visual attributes and target classes. MAVias first captures a wide variety of visual features in natural language via a foundation image tagging model, and then leverages a large language model to select those visual features defining the target class, resulting in a set of language-coded potential visual biases. We then translate this set of potential biases into vision-language embeddings and introduce an in-processing bias mitigation approach to prevent the model from encoding information related to them. Our experiments on diverse datasets, including CelebA, Waterbirds, ImageNet, and UrbanCars, show that MAVias effectively detects and mitigates a wide range of biases in visual recognition tasks outperforming current state-of-the-art.

[Arxiv](https://arxiv.org/abs/2412.06632)