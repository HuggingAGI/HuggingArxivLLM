# M$^3$oralBench：专为 LVLMs 设立的多模态道德基准

发布时间：2024年12月30日

`LLM应用` `医疗保健`

> M$^3$oralBench: A MultiModal Moral Benchmark for LVLMs

# 摘要

> 最近，大型基础模型，像大型语言模型（LLMs）和大型视觉语言模型（LVLMs），已成为法律、金融、医疗保健等关键领域不可或缺的工具。随着这些模型日益融入我们的日常生活，进行道德评估很有必要，以保证其输出符合人类价值观，不超出道德界限。此前的工作主要聚焦于LLMs，提出的道德数据集和基准仅限于文本模式。但鉴于LVLMs的迅速发展，多模态道德评估方法仍缺失。为填补这一空缺，我们推出了M$^3$oralBench，这是首个针对LVLMs的多模态道德基准。M$^3$oralBench拓展了道德基础小插曲（MFVs）中的日常道德场景，并运用文本到图像扩散模型SD3.0生成相应的场景图像。它针对道德基础理论（MFT）的六个道德基础展开道德评估，涵盖道德判断、道德分类和道德回应等任务，为多模态道德理解和推理方面的模型性能提供了全面测评。对10个热门的开源和闭源LVLMs开展的大量实验表明，M$^3$oralBench是一个颇具挑战性的基准，暴露出当前模型中明显的道德局限性。我们的基准可公开获取。

> Recently, large foundation models, including large language models (LLMs) and large vision-language models (LVLMs), have become essential tools in critical fields such as law, finance, and healthcare. As these models increasingly integrate into our daily life, it is necessary to conduct moral evaluation to ensure that their outputs align with human values and remain within moral boundaries. Previous works primarily focus on LLMs, proposing moral datasets and benchmarks limited to text modality. However, given the rapid development of LVLMs, there is still a lack of multimodal moral evaluation methods. To bridge this gap, we introduce M$^3$oralBench, the first MultiModal Moral Benchmark for LVLMs. M$^3$oralBench expands the everyday moral scenarios in Moral Foundations Vignettes (MFVs) and employs the text-to-image diffusion model, SD3.0, to create corresponding scenario images. It conducts moral evaluation across six moral foundations of Moral Foundations Theory (MFT) and encompasses tasks in moral judgement, moral classification, and moral response, providing a comprehensive assessment of model performance in multimodal moral understanding and reasoning. Extensive experiments on 10 popular open-source and closed-source LVLMs demonstrate that M$^3$oralBench is a challenging benchmark, exposing notable moral limitations in current models. Our benchmark is publicly available.

[Arxiv](https://arxiv.org/abs/2412.20718)