# <翻译失败>

发布时间：2025年05月28日

`LLM理论` `语言模型`

> Stochastic Chameleons: Irrelevant Context Hallucinations Reveal Class-Based (Mis)Generalization in LLMs

# 摘要

> 大型语言模型（LLMs）在NLP基准测试中取得了广泛应用的成功，但人们也担忧它们主要扮演着随机鹦鹉的角色，往往错误地复现与预训练期间所见相似的文本。然而，这些错误的本质是什么？它们是否具有某种规律性？在本研究中，我们聚焦于无关上下文幻觉现象，即模型将误导性的上下文线索融入预测中。通过行为分析，我们揭示了这些错误源于一种结构化却有缺陷的机制——我们称之为基于类的（错误）泛化。模型会将抽象类线索与从查询或上下文中提取的特征相结合，从而生成答案。进一步，在Llama-3、Mistral和Pythia模型上进行的机制可解释性实验，涵盖了39种事实检索关系类型，揭示了这种行为体现在模型的内部计算中：(i) 抽象类表示在较低层被构建，随后在高层被细化为具体答案；(ii) 特征选择受两个相互竞争的回路控制——一个优先考虑基于查询的直接推理，另一个则结合上下文线索——这两个回路的相对影响决定了最终输出。我们的研究为随机鹦鹉论提供了更细致入微的视角：通过形式化训练，LLMs可以利用抽象实现泛化，尽管这种泛化基于上下文线索，存在不可靠性——我们称之为随机变色龙。

> The widespread success of large language models (LLMs) on NLP benchmarks has been accompanied by concerns that LLMs function primarily as stochastic parrots that reproduce texts similar to what they saw during pre-training, often erroneously. But what is the nature of their errors, and do these errors exhibit any regularities? In this work, we examine irrelevant context hallucinations, in which models integrate misleading contextual cues into their predictions. Through behavioral analysis, we show that these errors result from a structured yet flawed mechanism that we term class-based (mis)generalization, in which models combine abstract class cues with features extracted from the query or context to derive answers. Furthermore, mechanistic interpretability experiments on Llama-3, Mistral, and Pythia across 39 factual recall relation types reveal that this behavior is reflected in the model's internal computations: (i) abstract class representations are constructed in lower layers before being refined into specific answers in higher layers, (ii) feature selection is governed by two competing circuits -- one prioritizing direct query-based reasoning, the other incorporating contextual cues -- whose relative influences determine the final output. Our findings provide a more nuanced perspective on the stochastic parrot argument: through form-based training, LLMs can exhibit generalization leveraging abstractions, albeit in unreliable ways based on contextual cues -- what we term stochastic chameleons.

[Arxiv](https://arxiv.org/abs/2505.22630)