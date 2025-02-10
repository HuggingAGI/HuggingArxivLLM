# # **CodeSCM: 因果分析驱动的多模态代码生成方法**

发布时间：2025年02月07日

`LLM理论

摘要中提到的研究使用结构因果模型（SCM）来分析大型语言模型（LLMs）驱动的多模态代码生成，并通过干预测量不同提示模态的因果效应。这属于对LLM内部机制的理论分析，因此归类为LLM理论。` `软件工程` `代码生成`

> CodeSCM: Causal Analysis for Multi-Modal Code Generation

# 摘要

> 本文提出了一种名为CodeSCM的结构因果模型（SCM），用于分析大型语言模型（LLMs）驱动的多模态代码生成。通过在CodeSCM中进行干预，我们测量了不同提示模态（包括自然语言、代码和输入输出示例）对模型的因果效应。CodeSCM通过引入潜在中介变量，分离了多模态代码生成提示中的代码和自然语言语义。借助因果中介分析的原理，我们量化了直接效应，揭示了模型的虚假倾向。研究发现，除了自然语言指令外，输入输出示例对代码生成的影响同样显著。

> In this paper, we propose CodeSCM, a Structural Causal Model (SCM) for analyzing multi-modal code generation using large language models (LLMs). By applying interventions to CodeSCM, we measure the causal effects of different prompt modalities, such as natural language, code, and input-output examples, on the model. CodeSCM introduces latent mediator variables to separate the code and natural language semantics of a multi-modal code generation prompt. Using the principles of Causal Mediation Analysis on these mediators we quantify direct effects representing the model's spurious leanings. We find that, in addition to natural language instructions, input-output examples significantly influence code generation.

[Arxiv](https://arxiv.org/abs/2502.05150)