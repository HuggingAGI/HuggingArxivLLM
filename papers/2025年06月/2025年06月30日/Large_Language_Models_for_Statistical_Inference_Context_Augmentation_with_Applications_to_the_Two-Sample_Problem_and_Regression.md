# # 大型语言模型在统计推断中的应用：上下文增强技术及其在双样本问题与回归分析中的应用

发布时间：2025年06月30日

`LLM应用` `统计推断` `文本分析`

> Large Language Models for Statistical Inference: Context Augmentation with Applications to the Two-Sample Problem and Regression

# 摘要

> 我们提出了上下文增强（context augmentation），这是一种利用大型语言模型（LLMs）生成与观察到的字符串相关联的上下文的数据增强方法，旨在促进有效的频率学派推断。这些生成的上下文重新引入了不确定性，整合了辅助信息，并促进了可解释性。例如，在双样本检验中，我们比较了字符串在自身组与另一组上下文中对数概率的差异。我们在合成数据上展示了该方法的t统计量表现出预期的空假设行为，同时保持了检验力，并通过重复实验表明该方法具有强大的解释性。接下来，我们引入了基于文本的回归分析。在预测变量字符串周围生成的上下文被视为预测变量与结果字符串之间的中介变量。通过使用负对照，我们区分了预测中的语义和句法维度。对现实世界对话数据的分析展示了与心理语言学框架一致的行为。在理论上，我们提供了识别条件，推导了影响函数分解，并展示了通过反复交叉拟合一个关键统计量可以获得更高阶的效率。我们还推导了估计误差、上下文数量和交叉拟合次数之间的界限。综合来看，上下文增强提供了一种将LLMs与传统统计实践相结合的能力。

> We introduce context augmentation, a data-augmentation approach that uses large language models (LLMs) to generate contexts around observed strings as a means of facilitating valid frequentist inference. These generated contexts serve to reintroduce uncertainty, incorporate auxiliary information, and facilitate interpretability. For example, in the two-sample test, we compare the log-probability of strings under contexts from its own versus the other group. We show on synthetic data that the method's t-statistics exhibit the expected null behaviour while maintaining power and, through a replication, that the method is powerful and interpretable. We next introduce text-on-text regression. Contexts generated around the predictor string are treated as mediating variables between the predictor and outcome strings. Using negative controls, we then distinguish between semantic and syntactic dimensions of prediction. Analysis of real-world dialogic data illustrates behaviour predicted from a psycholinguistic framework. Theoretically, we provide identification conditions, derive an influence-function decomposition, and show that repeated cross-fitting of a pivotal statistic yields higher-order efficiency. We derive bounds linking estimation error, context count, and number of cross-fits. Taken together, context augmentation offers the ability to connect LLMs with longstanding statistical practice.

[Arxiv](https://arxiv.org/abs/2506.23862)