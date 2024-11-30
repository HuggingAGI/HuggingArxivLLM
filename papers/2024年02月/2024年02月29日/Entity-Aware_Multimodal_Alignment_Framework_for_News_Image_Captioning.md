# 我们提出了一种针对新闻图片描述任务的“实体感知多模态对齐框架”，该框架旨在更好地整合和利用图文信息，以提升新闻图片自动描述的质量与准确性。

发布时间：2024年02月29日

`LLM应用`

> Entity-Aware Multimodal Alignment Framework for News Image Captioning

# 摘要

> 新闻图片captioning任务要求模型在新闻图片及相关新闻文本的基础上产出更丰富的描述，而多模态大型语言模型在此领域虽发展迅猛，但我们在实验中发现，常规MLLMs在零样本场景下生成实体信息的表现不佳。即使经过针对新闻图片captioning数据集的微调，其处理实体信息的能力仍较为有限。因此，为提升模型对多模态实体信息的处理能力，我们创新设计了两项多模态实体感知对齐任务，并构建了一套对齐框架，以优化模型并生成高质量的新闻图片标题。最终，我们的方法在GoodNews和NYTimes800k数据集上取得了显著突破，CIDEr得分分别从72.33提升至86.29、从70.83提升至85.61，超越了以往的最优水平。

> News image captioning task is a variant of image captioning task which requires model to generate a more informative caption with news image and the associated news article. Multimodal Large Language models have developed rapidly in recent years and is promising in news image captioning task. However, according to our experiments, common MLLMs are not good at generating the entities in zero-shot setting. Their abilities to deal with the entities information are still limited after simply fine-tuned on news image captioning dataset. To obtain a more powerful model to handle the multimodal entity information, we design two multimodal entity-aware alignment tasks and an alignment framework to align the model and generate the news image captions. Our method achieves better results than previous state-of-the-art models in CIDEr score (72.33 -> 86.29) on GoodNews dataset and (70.83 -> 85.61) on NYTimes800k dataset.

[Arxiv](https://arxiv.org/abs/2402.19404)