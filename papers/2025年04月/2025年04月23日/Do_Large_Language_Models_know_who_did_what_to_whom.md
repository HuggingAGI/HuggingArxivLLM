# 大型语言模型能否准确区分谁做了什么给谁？

发布时间：2025年04月23日

`LLM理论` `语言学`

> Do Large Language Models know who did what to whom?

# 摘要

> 大型语言模型（LLMs）常被批评为无法真正理解语言。但许多批评都集中在与语言处理在人类中截然不同的认知能力上。我们转而研究一种与语言紧密相关的理解能力：推断句子中“谁对谁做了什么”（即主语和宾语角色）。LLMs的核心训练目标——词预测——是否让它们的句子表示能够捕捉到这些角色关系？在两项实验中，我们分析了四个LLMs的句子表示。与人类的相似性判断不同，在LLMs中，句子对的整体表示相似性反映了句法相似性，但并未体现主语和宾语的指派是否一致或颠倒。此外，我们几乎没有发现任何隐藏单元子集能提供主语和宾语角色信息的证据。然而，某些注意力头能够稳健地捕捉到这些角色关系，且与句法无关。因此，LLMs能够提取主语和宾语角色，但与人类相比，这些信息对其表示的影响较为微弱。

> Large Language Models (LLMs) are commonly criticized for not understanding language. However, many critiques focus on cognitive abilities that, in humans, are distinct from language processing. Here, we instead study a kind of understanding tightly linked to language: inferring who did what to whom (thematic roles) in a sentence. Does the central training objective of LLMs-word prediction-result in sentence representations that capture thematic roles? In two experiments, we characterized sentence representations in four LLMs. In contrast to human similarity judgments, in LLMs the overall representational similarity of sentence pairs reflected syntactic similarity but not whether their agent and patient assignments were identical vs. reversed. Furthermore, we found little evidence that thematic role information was available in any subset of hidden units. However, some attention heads robustly captured thematic roles, independently of syntax. Therefore, LLMs can extract thematic roles but, relative to humans, this information influences their representations more weakly.

[Arxiv](https://arxiv.org/abs/2504.16884)