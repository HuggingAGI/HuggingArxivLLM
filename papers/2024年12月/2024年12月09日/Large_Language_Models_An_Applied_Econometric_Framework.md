# 大型语言模型：一种应用计量经济学框架

发布时间：2024年12月09日

`LLM应用` `经济学` `计量经济学`

> Large Language Models: An Applied Econometric Framework

# 摘要

> 大型语言模型（LLMs）在经济学研究中被用于进行预测、标注文本、模拟人类反应、生成假设，甚至为没有相关数据的时间和地点创造数据。尽管这些应用颇具创新性，但它们是否有效呢？何时我们能抛开 LLM 的内部运作机制，单纯依赖其输出呢？为此，我们构建了一个计量经济学框架来解答此问题。我们的框架区分了两类实证任务。在一种情况下，将 LLM 的输出用于预测问题（包括假设生成）是有效的，即 LLM 的训练数据集与研究人员的样本之间不存在“泄漏”。将 LLM 的输出用于估计问题，以自动测量某些经济概念（通过某些文本或来自人类受试者表达），则需要一个额外的假设：LLM 的输出必须与它们所替代的黄金标准测量结果一样好。否则，估计可能会有偏差，即便 LLM 的输出高度准确但并非完全准确。我们记录了这些条件被违背的程度，以及在金融和政治经济的示例应用中对研究结果的影响。我们还为实证研究人员提供了指导。确保没有训练泄漏的唯一方法是使用具有记录训练数据和公布权重的开源 LLM。处理 LLM 测量误差的唯一方法是收集验证数据并对误差结构进行建模。一个必然的结论是，如果对于候选的 LLM 应用无法满足这些条件，我们强烈建议：不要使用。

> Large language models (LLMs) are being used in economics research to form predictions, label text, simulate human responses, generate hypotheses, and even produce data for times and places where such data don't exist. While these uses are creative, are they valid? When can we abstract away from the inner workings of an LLM and simply rely on their outputs? We develop an econometric framework to answer this question. Our framework distinguishes between two types of empirical tasks. Using LLM outputs for prediction problems (including hypothesis generation) is valid under one condition: no "leakage" between the LLM's training dataset and the researcher's sample. Using LLM outputs for estimation problems to automate the measurement of some economic concept (expressed by some text or from human subjects) requires an additional assumption: LLM outputs must be as good as the gold standard measurements they replace. Otherwise estimates can be biased, even if LLM outputs are highly accurate but not perfectly so. We document the extent to which these conditions are violated and the implications for research findings in illustrative applications to finance and political economy. We also provide guidance to empirical researchers. The only way to ensure no training leakage is to use open-source LLMs with documented training data and published weights. The only way to deal with LLM measurement error is to collect validation data and model the error structure. A corollary is that if such conditions can't be met for a candidate LLM application, our strong advice is: don't.

[Arxiv](https://arxiv.org/abs/2412.07031)