# 语义缓存：提升网络负担能力

发布时间：2025年06月25日

`LLM应用` `互联网` `人工智能`

> Semantic Caching for Improving Web Affordability

# 摘要

> 随着网页内容的快速增长，网页规模不断扩大，这给互联网的可负担性带来了巨大挑战，尤其是在数据成本高昂的发展中国家。我们提出了一种基于大型语言模型（LLMs）的语义缓存方法，通过在网页内复用语义相似的图片来提升网页的可负担性。通过对50个领先的新闻和媒体网站进行分析，涵盖4264张图片和超过40,000张图片对，我们展示了显著减少数据传输的潜力，某些网站类别的图片中，高达37%的图片可以被替换。我们的概念验证架构显示，与精确缓存相比，用户可以实现约10%的字节节省。我们评估了商业和开源的多模态LLMs来评估语义可替换性。GPT-4o表现最佳，其归一化均方根误差为0.1735，加权F1得分为0.8374，而开源的LLaMA 3.1模型表现同样出色，凸显了其在大规模应用中的可行性。这种方法为用户和网站运营商都带来了好处，大幅减少了数据传输量。我们讨论了伦理问题和实际挑战，包括语义保留、用户驱动的缓存配置、隐私问题以及网站运营商可能的抵触情绪。

> The rapid growth of web content has led to increasingly large webpages, posing significant challenges for Internet affordability, especially in developing countries where data costs remain prohibitively high. We propose semantic caching using Large Language Models (LLMs) to improve web affordability by enabling reuse of semantically similar images within webpages. Analyzing 50 leading news and media websites, encompassing 4,264 images and over 40,000 image pairs, we demonstrate potential for significant data transfer reduction, with some website categories showing up to 37% of images as replaceable. Our proof-of-concept architecture shows users can achieve approximately 10% greater byte savings compared to exact caching. We evaluate both commercial and open-source multi-modal LLMs for assessing semantic replaceability. GPT-4o performs best with a low Normalized Root Mean Square Error of 0.1735 and a weighted F1 score of 0.8374, while the open-source LLaMA 3.1 model shows comparable performance, highlighting its viability for large-scale applications. This approach offers benefits for both users and website operators, substantially reducing data transmission. We discuss ethical concerns and practical challenges, including semantic preservation, user-driven cache configuration, privacy concerns, and potential resistance from website operators

[Arxiv](https://arxiv.org/abs/2506.20420)