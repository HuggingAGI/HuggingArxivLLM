# 先分组后扩展：动态专家混合多语言语言模型

发布时间：2025年06月14日

`LLM理论

论文摘要：多语言大语言模型（LLMs）面临一个根本性挑战——多语言诅咒现象。由于模型容量有限以及不同语言之间的负迁移，多语言之间的竞争导致模型性能下降。针对这一问题，我们提出了一种创新方法：通过动态分组和扩展多语言LLM的参数，同时促进相似语言之间的正迁移。具体而言，模型首先在单语语料库上进行微调，以确定每层的参数偏差并量化语言间的相似性。对于偏差较大的层，我们将其扩展为专家混合层，从而减少语言间的竞争，每个专家模块专注于一组相似语言。实验结果表明，该方法在18到128种语言的测试中，显著减少了语言间的负迁移，同时在更少的参数下提升了多语言性能。这种基于专家的语言组专业化不仅有利于新语言的适应，还能减少对已有跨语言知识的推理需求。

LLM理论` `跨语言处理`

> Group then Scale: Dynamic Mixture-of-Experts Multilingual Language Model

# 摘要

> 多语言大语言模型（LLMs）面临一个根本性挑战——多语言诅咒现象。由于模型容量有限以及不同语言之间的负迁移，多语言之间的竞争导致模型性能下降。针对这一问题，我们提出了一种创新方法：通过动态分组和扩展多语言LLM的参数，同时促进相似语言之间的正迁移。具体而言，模型首先在单语语料库上进行微调，以确定每层的参数偏差并量化语言间的相似性。对于偏差较大的层，我们将其扩展为专家混合层，从而减少语言间的竞争，每个专家模块专注于一组相似语言。实验结果表明，该方法在18到128种语言的测试中，显著减少了语言间的负迁移，同时在更少的参数下提升了多语言性能。这种基于专家的语言组专业化不仅有利于新语言的适应，还能减少对已有跨语言知识的推理需求。

> The curse of multilinguality phenomenon is a fundamental problem of multilingual Large Language Models (LLMs), where the competition between massive languages results in inferior performance. It mainly comes from limited capacity and negative transfer between dissimilar languages. To address this issue, we propose a method to dynamically group and scale up the parameters of multilingual LLM while boosting positive transfer among similar languages. Specifically, the model is first tuned on monolingual corpus to determine the parameter deviation in each layer and quantify the similarity between languages. Layers with more deviations are extended to mixture-of-experts layers to reduce competition between languages, where one expert module serves one group of similar languages. Experimental results on 18 to 128 languages show that our method reduces the negative transfer between languages and significantly boosts multilingual performance with fewer parameters. Such language group specialization on experts benefits the new language adaptation and reduces the inference on the previous multilingual knowledge learned.

[Arxiv](https://arxiv.org/abs/2506.12388)