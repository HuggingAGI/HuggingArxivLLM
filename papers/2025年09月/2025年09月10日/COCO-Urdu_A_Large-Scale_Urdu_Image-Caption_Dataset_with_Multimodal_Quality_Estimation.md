# COCO-Urdu：含多模态质量评估的大规模乌尔都语图像-标题数据集

发布时间：2025年09月10日

`其他` `基础理论`

> COCO-Urdu: A Large-Scale Urdu Image-Caption Dataset with Multimodal Quality Estimation

# 摘要

> 乌尔都语使用者超2.5亿，却在多模态与视觉-语言研究领域严重缺乏关注。大规模高质量数据集的缺失，不仅限制了乌尔都语智能系统的开发，还加剧了主要基于高资源语言训练的多语言视觉-语言模型中的偏见。为填补这一空白，我们构建了COCO-Urdu——一个源自MS COCO的大规模图像-标题数据集，包含59,000张图像和319,000条乌尔都语标题，通过分层抽样选取以保留原始数据分布。标题通过SeamlessM4T v2翻译，并借助混合多模态质量评估框架验证——该框架整合了COMET-Kiwi（用于翻译质量）、基于CLIP的相似度（用于视觉关联）以及带反向翻译的BERTScore（用于语义一致性）；低评分标题则通过开源大型语言模型进行迭代优化。我们进一步在BLEU、SacreBLEU和chrF指标上对COCO-Urdu进行基准测试，结果表现稳定且优异。据我们所知，COCO-Urdu是目前最大的公开乌尔都语图像标题数据集。我们发布该数据集及质量评估流程，旨在减少多模态研究中的语言偏见，为构建包容性视觉-语言系统奠定基础。

> Urdu, spoken by over 250 million people, remains critically under-served in multimodal and vision-language research. The absence of large-scale, high-quality datasets has limited the development of Urdu-capable systems and reinforced biases in multilingual vision-language models trained primarily on high-resource languages. To address this gap, we present COCO-Urdu, a large-scale image-caption dataset derived from MS COCO, containing 59,000 images and 319,000 Urdu captions selected through stratified sampling to preserve the original distribution. Captions were translated using SeamlessM4T v2 and validated with a hybrid multimodal quality estimation framework that integrates COMET-Kiwi for translation quality, CLIP-based similarity for visual grounding, and BERTScore with back-translation for semantic consistency; low-scoring captions were iteratively refined using open-source large language models. We further benchmark COCO-Urdu on BLEU, SacreBLEU, and chrF, reporting consistently strong results. To the best of our knowledge, COCO-Urdu is the largest publicly available Urdu captioning dataset. By releasing both the dataset and the quality estimation pipeline, we aim to reduce language bias in multimodal research and establish a foundation for inclusive vision-language systems.

[Arxiv](https://arxiv.org/abs/2509.09014)