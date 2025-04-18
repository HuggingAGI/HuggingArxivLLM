# 通过部分感知监督来为 LVLMs 抵御视觉攻击

发布时间：2024年12月17日

`LLM应用` `计算机视觉` `模型防御`

> Defending LVLMs Against Vision Attacks through Partial-Perception Supervision

# 摘要

> 近期研究对大型视觉语言模型（LVLMs）易受恶意注入或干扰输入图像影响这一脆弱性深表担忧，此类图像可能误导其响应。现有的防御方法显示，这类视觉攻击对图像修改（尤其是裁剪）颇为敏感，将修改后图像的响应进行多数投票作为校正响应。然而，这些修改常导致部分图像出现且语义扭曲，降低了投票后干净图像的响应质量。我们并非直接用部分图像的响应来投票，而是研究用其监督 LVLM 对原始图像的响应。我们提出了一种名为 DPS（通过部分感知监督进行防御）的无训练黑盒方法。在此方法中，利用仅感知部分图像的模型生成的响应来提示模型。借助 DPS，模型受攻击时能依据对部分图像的理解调整响应，同时自信地维持对干净输入的原始响应。我们的发现表明，弱模型能够监督强模型：面对受攻击的输入，强模型信心降低，并依据弱模型的部分理解调整响应，有效抵御攻击。对于干净输入，它自信地保持原始响应。实证实验表明，我们的方法优于基线，在三个流行模型的六个数据集中，平均攻击成功率降低了 76.3%。

> Recent studies have raised significant concerns regarding the vulnerability of Large Vision Language Models (LVLMs) to maliciously injected or perturbed input images, which can mislead their responses. Existing defense methods show that such vision attacks are sensitive to image modifications especially cropping, using majority voting across responses of modified images as corrected responses. However, these modifications often result in partial images and distort the semantics, which reduces response quality on clean images after voting. Instead of directly using responses from partial images for voting, we investigate using them to supervise the LVLM's responses to the original images. We propose a black-box, training-free method called DPS (Defense through Partial-Perception Supervision). In this approach, the model is prompted using the responses generated by a model that perceives only a partial image. With DPS, the model can adjust its response based on partial image understanding when under attack, while confidently maintaining its original response for clean input. Our findings show that the weak model can supervise the strong model: when faced with an attacked input, the strong model becomes less confident and adjusts its response based on the weak model's partial understanding, effectively defending against the attack. With clean input, it confidently maintains its original response. Empirical experiments show our method outperforms the baseline, cutting the average attack success rate by 76.3% across six datasets on three popular models.

[Arxiv](https://arxiv.org/abs/2412.12722)