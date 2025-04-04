# <翻译失败>

发布时间：2025年04月03日

`LLM理论` `人工智能` `计算语言学`

> The quasi-semantic competence of LLMs: a case study on the part-whole relation

# 摘要

> 深入理解大型语言模型（LLMs）的语义能力是当前人工智能（AI）和计算语言学（CL）领域科学议程的核心。我们通过研究LLMs对\emph{部分-整体关系}（即\emph{meronymy}）的理解，为这一研究领域做出了贡献。部分-整体关系在词汇组织中扮演着重要角色，但目前对其的研究仍然非常有限。我们利用ConceptNet关系\citep{speer2016conceptnet}和人类生成的语义特征规范\citep{McRae:2005}的数据，探索了LLMs处理	extit{部分-整体关系}的能力。我们基于三个分析层次采用了多种方法：i.) 通过提示进行	extbf{行为测试}，直接查询模型对meronymy的知识；ii.) 句子	extbf{概率评分}，测试模型区分正确（真实）和错误（不对称反事实）	extit{部分-整体关系}的能力；iii.) 在向量空间中进行	extbf{概念表示分析}，证明了	extit{部分-整体}概念在嵌入和解嵌空间中的线性组织。这些分析揭示了一幅复杂的图景，表明LLMs对这种关系的理解仅限于部分层面。它们仅具备一种“\emph{类语义}”能力，尚未能够捕捉到深层次的推理特性。

> Understanding the extent and depth of the semantic competence of \emph{Large Language Models} (LLMs) is at the center of the current scientific agenda in Artificial Intelligence (AI) and Computational Linguistics (CL). We contribute to this endeavor by investigating their knowledge of the \emph{part-whole} relation, a.k.a. \emph{meronymy}, which plays a crucial role in lexical organization, but it is significantly understudied. We used data from ConceptNet relations \citep{speer2016conceptnet} and human-generated semantic feature norms \citep{McRae:2005} to explore the abilities of LLMs to deal with \textit{part-whole} relations. We employed several methods based on three levels of analysis: i.) \textbf{behavioral} testing via prompting, where we directly queried the models on their knowledge of meronymy, ii.) sentence \textbf{probability} scoring, where we tested models' abilities to discriminate correct (real) and incorrect (asymmetric counterfactual) \textit{part-whole} relations, and iii.) \textbf{concept representation} analysis in vector space, where we proved the linear organization of the \textit{part-whole} concept in the embedding and unembedding spaces. These analyses present a complex picture that reveals that the LLMs' knowledge of this relation is only partial. They have just a ``\emph{quasi}-semantic'' competence and still fall short of capturing deep inferential properties.

[Arxiv](https://arxiv.org/abs/2504.02395)