# # 高效且有效的代码摘要

发布时间：2025年02月05日

`LLM应用` `软件工程` `代码摘要`

> Resource-Efficient & Effective Code Summarization

# 摘要

> 代码语言模型（CLMs）在修复错误、代码生成和代码文档编写等软件工程任务中表现出色。这种进步得益于GPT-4等大型模型的扩展，参数规模从数百万到数万亿。然而，随着模型规模的扩大，可持续性问题也随之浮现，因为它们需要大量资源，凸显了高效且环保的解决方案的必要性。GreenAI技术，如QLoRA（量化低秩适配），为应对大型模型的可持续性提供了有前景的解决方案，因为它支持资源高效的模型微调。此前的研究表明，QLoRA在代码生成等涉及自然语言输入和代码输出（NL-to-Code）的任务中非常有效。然而，尚未有研究探索其在方向相反的代码摘要任务中的应用，导致我们对QLoRA在代码到自然语言（Code-to-NL）任务中表现的理解存在空白。为填补这一空白，我们研究了QLoRA在代码摘要（一个典型的Code-to-NL任务）中的应用潜力。我们的研究评估了CodeLlama和DeepSeek-Coder两种CLMs在Python和Java上的表现，要求模型为代码方法生成描述。结果表明，QLoRA能够实现CLMs在代码摘要任务上的高效微调，与之前的研究一致。

> Code Language Models (CLMs) have demonstrated high effectiveness in automating software engineering tasks such as bug fixing, code generation, and code documentation. This progress has been driven by the scaling of large models, ranging from millions to trillions of parameters (e.g., GPT-4). However, as models grow in scale, sustainability concerns emerge, as they are extremely resource-intensive, highlighting the need for efficient, environmentally conscious solutions. GreenAI techniques, such as QLoRA (Quantized Low-Rank Adaptation), offer a promising path for dealing with large models' sustainability as they enable resource-efficient model fine-tuning. Previous research has shown the effectiveness of QLoRA in code-related tasks, particularly those involving natural language inputs and code as the target output (NL-to-Code), such as code generation. However, no studies have explored its application to tasks that are fundamentally similar to NL-to-Code (natural language to code) but operate in the opposite direction, such as code summarization. This leaves a gap in understanding how well QLoRA can generalize to Code-to-NL tasks, which are equally important for supporting developers in understanding and maintaining code. To address this gap, we investigate the extent to which QLoRA's capabilities in NL-to-Code tasks can be leveraged and transferred to code summarization, one representative Code-to-NL task. Our study evaluates two state-of-the-art CLMs (CodeLlama and DeepSeek-Coder) across two programming languages: Python and Java. Our research tasked models with generating descriptions for Python and Java code methods. The results align with prior findings on QLoRA for source code generation, showing that QLoRA enables efficient fine-tuning of CLMs for code summarization.

[Arxiv](https://arxiv.org/abs/2502.03617)