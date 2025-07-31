# IFEvalCode：实现可控代码生成

发布时间：2025年07月30日

`LLM应用

理由：这篇论文探讨了代码大型语言模型在受控代码生成中的应用，提出了一种新的生成方法，并引入了新的多语言基准进行评估，属于LLM的应用层面。` `软件开发`

> IFEvalCode: Controlled Code Generation

# 摘要

> 代码大型语言模型（Code LLMs）在将自然语言转化为功能代码方面取得了显著进展，但现实应用中往往需要更严格地满足编码风格、行数和结构等详细要求。为此，本文提出了一种基于前向和后向约束生成的方法，旨在提升代码LLMs在受控代码生成中的指令遵循能力，使其输出更贴近人类定义的规范。此外，我们还推出了包含1.6K测试样本的多语言基准IFEvalCode，覆盖Python、Java、JavaScript、TypeScript、Shell、C++和C#七种语言，每样本均提供中英文双语查询。与现有基准不同，IFEvalCode将评估细分为正确性（Corr.）和指令遵循（Instr.）两个维度，从而实现更细致的模型能力评估。实验结果显示，闭源模型在可控代码生成方面优于开源模型，且模型在生成正确代码与精确遵循指令之间存在显著差距。

> Code large language models (Code LLMs) have made significant progress in code generation by translating natural language descriptions into functional code; however, real-world applications often demand stricter adherence to detailed requirements such as coding style, line count, and structural constraints, beyond mere correctness. To address this, the paper introduces forward and backward constraints generation to improve the instruction-following capabilities of Code LLMs in controlled code generation, ensuring outputs align more closely with human-defined guidelines. The authors further present IFEvalCode, a multilingual benchmark comprising 1.6K test samples across seven programming languages (Python, Java, JavaScript, TypeScript, Shell, C++, and C#), with each sample featuring both Chinese and English queries. Unlike existing benchmarks, IFEvalCode decouples evaluation into two metrics: correctness (Corr.) and instruction-following (Instr.), enabling a more nuanced assessment. Experiments on over 40 LLMs reveal that closed-source models outperform open-source ones in controllable code generation and highlight a significant gap between the models' ability to generate correct code versus code that precisely follows instructions.

[Arxiv](https://arxiv.org/abs/2507.22462)