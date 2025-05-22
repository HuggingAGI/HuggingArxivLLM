# ThinkRec：基于大型语言模型的思考式推荐

发布时间：2025年05月21日

`LLM应用` `推荐系统` `电子商务`

> ThinkRec: Thinking-based recommendation via LLM

# 摘要

> 大型语言模型（LLMs）的最新进展使语义感知的推荐成为可能，通过自然语言生成技术实现更智能的推荐。然而，现有的推荐领域大型语言模型方法（LLM4Rec）大多以一种类似System 1的方式运作，主要依赖于点击历史记录中的浅层特征来匹配相似项，而非通过更深层次的行为逻辑进行推理。这种浅层次的推荐方式往往会导致表面化且有误的推荐结果。为了解决这一问题，我们提出了ThinkRec，一种基于思考的框架，将LLM4Rec从System 1转向System 2（理性系统）。在技术实现上，ThinkRec引入了一种思考激活机制，通过关键词总结增强商品元数据，并注入合成推理轨迹，引导模型形成可解释的推理链，包括分析交互历史、识别用户偏好以及基于目标商品做出决策。此外，我们还提出了一种基于实例的专家融合机制，以降低推理难度。通过根据用户的潜在特征动态分配专家模型的权重，ThinkRec能够根据个体用户调整其推理路径，从而提高推荐的准确性和个性化。在真实世界数据集上的大量实验表明，ThinkRec显著提升了推荐的准确性和可解释性。我们的实现代码可在匿名GitHub上获取：https://anonymous.4open.science/r/ThinkRec_LLM。

> Recent advances in large language models (LLMs) have enabled more semantic-aware recommendations through natural language generation. Existing LLM for recommendation (LLM4Rec) methods mostly operate in a System 1-like manner, relying on superficial features to match similar items based on click history, rather than reasoning through deeper behavioral logic. This often leads to superficial and erroneous recommendations. Motivated by this, we propose ThinkRec, a thinking-based framework that shifts LLM4Rec from System 1 to System 2 (rational system). Technically, ThinkRec introduces a thinking activation mechanism that augments item metadata with keyword summarization and injects synthetic reasoning traces, guiding the model to form interpretable reasoning chains that consist of analyzing interaction histories, identifying user preferences, and making decisions based on target items. On top of this, we propose an instance-wise expert fusion mechanism to reduce the reasoning difficulty. By dynamically assigning weights to expert models based on users' latent features, ThinkRec adapts its reasoning path to individual users, thereby enhancing precision and personalization. Extensive experiments on real-world datasets demonstrate that ThinkRec significantly improves the accuracy and interpretability of recommendations. Our implementations are available in anonymous Github: https://anonymous.4open.science/r/ThinkRec_LLM.

[Arxiv](https://arxiv.org/abs/2505.15091)