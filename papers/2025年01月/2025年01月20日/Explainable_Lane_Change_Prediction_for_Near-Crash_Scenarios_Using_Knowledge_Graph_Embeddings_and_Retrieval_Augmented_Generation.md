# 基于知识图谱嵌入与检索增强生成的可解释车道变换预测，助力近碰撞场景分析

发布时间：2025年01月20日

`LLM应用

理由：该论文主要讨论了利用语言上下文信息预测变道行为，并结合RAG技术为预测结果提供清晰自然的语言解释。这涉及到将大型语言模型（LLM）应用于自动驾驶领域，以提升模型的可解释性和透明度。因此，该论文应归类为LLM应用。` `自动驾驶` `交通安全`

> Explainable Lane Change Prediction for Near-Crash Scenarios Using Knowledge Graph Embeddings and Retrieval Augmented Generation

# 摘要

> 变道操作，尤其是突然或危险情况下的变道，是交通事故的主要诱因之一。然而，现有研究多集中于预测安全变道，且事故数据集通常仅依赖图像，缺乏全面的感官数据。本研究利用CRASH数据集（专为危险变道收集）和HighD数据集（用于安全变道），结合KG和贝叶斯推理，通过语言上下文信息预测变道行为，提升模型的可解释性和透明度。模型在预测危险变道时，提前四秒的f1分数高达91.5%，安全变道的f1分数则为90.0%。我们通过在CARLA模拟器中集成模型，验证其在危险变道场景中的有效性，成功预测了突发变道，为自动驾驶车辆争取了更多反应时间。此外，我们利用RAG技术为预测结果提供清晰自然的语言解释，进一步增强了模型的可解释性。

> Lane-changing maneuvers, particularly those executed abruptly or in risky situations, are a significant cause of road traffic accidents. However, current research mainly focuses on predicting safe lane changes. Furthermore, existing accident datasets are often based on images only and lack comprehensive sensory data. In this work, we focus on predicting risky lane changes using the CRASH dataset (our own collected dataset specifically for risky lane changes), and safe lane changes (using the HighD dataset). Then, we leverage KG and Bayesian inference to predict these maneuvers using linguistic contextual information, enhancing the model's interpretability and transparency. The model achieved a 91.5% f1-score with anticipation time extending to four seconds for risky lane changes, and a 90.0% f1-score for predicting safe lane changes with the same anticipation time. We validate our model by integrating it into a vehicle within the CARLA simulator in scenarios that involve risky lane changes. The model managed to anticipate sudden lane changes, thus providing automated vehicles with further time to plan and execute appropriate safe reactions. Finally, to enhance the explainability of our model, we utilize RAG to provide clear and natural language explanations for the given prediction.

[Arxiv](https://arxiv.org/abs/2501.11560)