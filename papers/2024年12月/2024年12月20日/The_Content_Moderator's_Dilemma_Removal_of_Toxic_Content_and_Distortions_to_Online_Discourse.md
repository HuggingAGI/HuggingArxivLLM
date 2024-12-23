# 《内容审核员的两难困境：有毒内容的清除与在线话语的变形》

发布时间：2024年12月20日

`LLM应用` `社交媒体` `内容审核`

> The Content Moderator's Dilemma: Removal of Toxic Content and Distortions to Online Discourse

# 摘要

> 关于如何在社交媒体上整治有害言论以及内容审核对在线话语的影响，一直存在争议。我们提出并验证了一种借助计算语言学中的文本嵌入来衡量在线话语中因内容审核导致的扭曲的方法。我们在包含 500 万条美国政治推文的代表性数据集中测试了该测量方法，发现删除有害推文会使在线内容产生扭曲。这一发现于不同的嵌入模型、毒性指标和样本中均保持一致。关键在于，我们证明了内容审核引发的扭曲并非由有害语言造成。相反，我们指出，作为副作用，内容审核改变了嵌入空间的均值和方差，扭曲了在线内容的主题构成。最后，我们提出一种内容审核的替代方案，利用生成式大型语言模型改写有害推文，以保留其有价值的内容，而非将其完全删除。我们证明，这种改写策略在降低毒性的同时，最大程度地减少了在线内容的扭曲。

> There is an ongoing debate about how to moderate toxic speech on social media and how content moderation affects online discourse. We propose and validate a methodology for measuring the content-moderation-induced distortions in online discourse using text embeddings from computational linguistics. We test our measure on a representative dataset of 5 million US political Tweets and find that removing toxic Tweets distorts online content. This finding is consistent across different embedding models, toxicity metrics, and samples. Importantly, we demonstrate that content-moderation-induced distortions are not caused by the toxic language. Instead, we show that, as a side effect, content moderation shifts the mean and variance of the embedding space, distorting the topic composition of online content. Finally, we propose an alternative approach to content moderation that uses generative Large Language Models to rephrase toxic Tweets to preserve their salvageable content rather than removing them entirely. We demonstrate that this rephrasing strategy reduces toxicity while minimizing distortions in online content.

[Arxiv](https://arxiv.org/abs/2412.16114)