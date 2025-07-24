# 解析消费者偏好，基于注意力的语言模型

发布时间：2025年07月23日

`LLM应用` `电子商务`

> Decoding Consumer Preferences Using Attention-Based Language Models

# 摘要

> 本文提出了一种基于注意力机制的语言模型的新需求估计方法。通过两阶段训练流程，我们利用该模型分析了美国大型在线拍卖市场上二手车的自然语言描述。该方法能够对结构模型中的需求原变量进行半非参数估计，这些变量代表了每条车辆 listings 的私人估值和市场规模。首先，我们微调语言模型，使其能够通过自然语言车辆描述来编码目标拍卖结果。其次，将训练好的语言模型编码映射到结构模型的参数空间中。通过保留的拍卖数据子样本验证了模型在训练市场空间中进行反事实分析的能力，其中包括一组独特的“零样本”实例。

> This paper proposes a new demand estimation method using attention-based language models. An encoder-only language model is trained in a two-stage process to analyze the natural language descriptions of used cars from a large US-based online auction marketplace. The approach enables semi-nonparametrically estimation for the demand primitives of a structural model representing the private valuations and market size for each vehicle listing. In the first stage, the language model is fine-tuned to encode the target auction outcomes using the natural language vehicle descriptions. In the second stage, the trained language model's encodings are projected into the parameter space of the structural model. The model's capability to conduct counterfactual analyses within the trained market space is validated using a subsample of withheld auction data, which includes a set of unique "zero shot" instances.

[Arxiv](https://arxiv.org/abs/2507.17564)