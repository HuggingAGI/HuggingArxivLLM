# BanglishRev：一个大规模的孟加拉语 - 英语及代码混合的电商产品评论数据集

发布时间：2024年12月17日

`LLM应用` `电子商务` `情感分析`

> BanglishRev: A Large-Scale Bangla-English and Code-mixed Dataset of Product Reviews in E-Commerce

# 摘要

> 此项工作推出了 BanglishRev 数据集，这是迄今最大的电子商务产品评论数据集，涵盖孟加拉语、英语、两者的混合以及用英文字母书写的孟加拉语（Banglish）。该数据集由从针对孟加拉人群体的在线电商平台收集的 12.8 万种产品的 320 万条评级信息中整理出的 174 万条书面评论组成。每条评论都配有丰富的相关元数据，如评论者给出的评级、评论发布日期和购买日期、点赞数、不喜欢数、卖家回复、与评论相关的图片等。鉴于情感分析是评论数据集的主要用途，我们以评论评级作为积极或消极情感的指标，对二元情感分析模型展开实验，以评估 BanglishRev 中大量数据在情感分析任务中的有效性。一个 BanglishBERT 模型基于 BanglishRev 的数据进行训练，若评级大于 3，则将评论视为积极；若评级小于或等于 3，则视为消极。该模型通过与此前发布的针对混合了孟加拉语、英语和 Banglish 的电子商务评论的手动标注数据集进行测试来评估。实验模型取得了高达 94％的准确率和 0.94 的 F1 分数，彰显了该数据集在情感分析方面的效力。同时，还对数据集中的一些有趣模式和观察结果，以及该数据集可应用的未来研究方向进行了探讨和摸索。该数据集可通过 https://huggingface.co/datasets/BanglishRev/bangla-english-and-code-mixed-ecommerce-review-dataset 访问。

> This work presents the BanglishRev Dataset, the largest e-commerce product review dataset to date for reviews written in Bengali, English, a mixture of both and Banglish, Bengali words written with English alphabets. The dataset comprises of 1.74 million written reviews from 3.2 million ratings information collected from a total of 128k products being sold in online e-commerce platforms targeting the Bengali population. It includes an extensive array of related metadata for each of the reviews including the rating given by the reviewer, date the review was posted and date of purchase, number of likes, dislikes, response from the seller, images associated with the review etc. With sentiment analysis being the most prominent usage of review datasets, experimentation with a binary sentiment analysis model with the review rating serving as an indicator of positive or negative sentiment was conducted to evaluate the effectiveness of the large amount of data presented in BanglishRev for sentiment analysis tasks. A BanglishBERT model is trained on the data from BanglishRev with reviews being considered labeled positive if the rating is greater than 3 and negative if the rating is less than or equal to 3. The model is evaluated by being testing against a previously published manually annotated dataset for e-commerce reviews written in a mixture of Bangla, English and Banglish. The experimental model achieved an exceptional accuracy of 94\% and F1 score of 0.94, demonstrating the dataset's efficacy for sentiment analysis. Some of the intriguing patterns and observations seen within the dataset and future research directions where the dataset can be utilized is also discussed and explored. The dataset can be accessed through https://huggingface.co/datasets/BanglishRev/bangla-english-and-code-mixed-ecommerce-review-dataset.

[Arxiv](https://arxiv.org/abs/2412.13161)