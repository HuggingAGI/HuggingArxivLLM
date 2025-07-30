# # MultiAIGCD: 全面覆盖多语言、模型、提示与场景的AI生成代码检测数据集

发布时间：2025年07月29日

`LLM应用` `软件开发`

> MultiAIGCD: A Comprehensive dataset for AI Generated Code Detection Covering Multiple Languages, Models,Prompts, and Scenarios

# 摘要

> 大型语言模型（LLMs）的快速发展使其在代码生成领域发挥越来越重要的作用。虽然这为软件开发带来了便利，但也引发了教育和招聘等领域的担忧。为了维护学术诚信并确保招聘公平，开发可靠的AI生成代码检测系统势在必行。本研究推出了MultiAIGCD——一个用于检测Python、Java和Go语言AI生成代码的数据集。我们基于CodeNet数据集的问题定义和人工编写的代码，使用六种不同的LLMs和三种不同的提示，生成了Java、Python和Go语言的多个代码样本。这一生成过程主要围绕三个关键场景展开：(i) 根据问题描述生成代码，(ii) 修复人类编写代码中的运行时错误，(iii) 纠正错误输出。MultiAIGCD数据集总计包含121,271个AI生成代码片段和32,148个人工编写代码片段。我们还对三个最先进的AI生成代码检测模型进行了基准测试，并评估了它们在跨模型和跨语言等多种场景下的性能表现。为支持该领域的进一步研究，我们公开分享了数据集和代码。

> As large language models (LLMs) rapidly advance, their role in code generation has expanded significantly. While this offers streamlined development, it also creates concerns in areas like education and job interviews. Consequently, developing robust systems to detect AI-generated code is imperative to maintain academic integrity and ensure fairness in hiring processes. In this study, we introduce MultiAIGCD, a dataset for AI-generated code detection for Python, Java, and Go. From the CodeNet dataset's problem definitions and human-authored codes, we generate several code samples in Java, Python, and Go with six different LLMs and three different prompts. This generation process covered three key usage scenarios: (i) generating code from problem descriptions, (ii) fixing runtime errors in human-written code, and (iii) correcting incorrect outputs. Overall, MultiAIGCD consists of 121,271 AI-generated and 32,148 human-written code snippets. We also benchmark three state-of-the-art AI-generated code detection models and assess their performance in various test scenarios such as cross-model and cross-language. We share our dataset and codes to support research in this field.

[Arxiv](https://arxiv.org/abs/2507.21693)