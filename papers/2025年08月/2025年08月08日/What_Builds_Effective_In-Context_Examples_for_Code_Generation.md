# 什么构建有效的上下文示例用于代码生成？

发布时间：2025年08月08日

`LLM理论` `软件工程` `代码生成`

> What Builds Effective In-Context Examples for Code Generation?

# 摘要

> 上下文学习（ICL）通过在提示中加入代码示例，使大型语言模型（LLMs）能够从演示中学习，从而成为提升代码生成能力的有力工具。尽管基于代码示例的ICL方法效果显著，但具体是哪些代码特征（如变量命名风格、代码格式、解决方案见解）对ICL的效果起关键作用，目前尚不明确。本文通过控制变量的消融实验，系统研究了不同代码特征对ICL的影响。研究发现，变量和函数的恰当命名对代码生成至关重要，命名缺失会导致性能下降30个百分点。此外，我们发现LLMs更重视语义有意义的变量名称，而非格式规范，并且在变量命名的详细程度上存在语言偏好。进一步研究发现，尽管当前模型能有效利用直接信息，但从相似代码中提取可推广的解决方案见解仍具挑战性。这些发现为优化代码生成中的ICL系统提供了重要启示，并揭示了基于反思学习在代码生成中的核心难题。

> In-Context Learning (ICL) has emerged as a promising solution to enhance the code generation capabilities of Large Language Models (LLMs), which incorporates code examples inside the prompt to let LLMs learn from demonstrations. However, despite the substantial effectiveness of the code example-based ICL approach, the specific features (e.g., identifier naming styles, code formatting, solution insight) within the ICL-provided code examples that significantly contribute to the ICL's effectiveness remain unclear. This paper systematically investigates the impact of various code features on ICL with code examples through controlled ablation studies. Our findings reveal that the appropriate naming of variables and functions is crucial for effective code generation, with their elimination leading to performance decreases of up to 30 percentage points. We further demonstrate that LLMs prioritize semantically meaningful identifier names over formatting conventions, with language-specific preferences regarding identifier verbosity. Additionally, our investigation into ICL's potential for enhancing reflection and inference capabilities reveals that current LLMs struggle to extract generalizable problem-solving insights from similar code solutions, despite being capable of utilizing direct information effectively. These findings are expected to provide valuable insights for optimizing ICL systems in code generation applications and highlight fundamental challenges in reflection-based learning for code generation tasks.

[Arxiv](https://arxiv.org/abs/2508.06414)