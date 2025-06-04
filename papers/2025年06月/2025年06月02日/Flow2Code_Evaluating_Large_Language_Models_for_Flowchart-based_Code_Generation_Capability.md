# Flow2Code: 评估大型语言模型在流程图代码生成方面的表现

发布时间：2025年06月02日

`LLM应用` `代码生成` `软件工程`

> Flow2Code: Evaluating Large Language Models for Flowchart-based Code Generation Capability

# 摘要

> 大型语言模型（LLMs）在代码生成领域展现出巨大潜力，但现有研究往往忽略了基于流程图的代码生成这一重要方向。为此，我们提出了Flow2Code——一个全新的基准测试，专注于评估基于流程图的代码生成能力。我们的数据集覆盖了15种编程语言，包含5,622段代码，每段代码都与16,866张不同类型的流程图配对，包括代码流程图、UML图和伪代码图三种类型。通过对13种多模态LLMs的全面测试，我们发现目前的LLMs在根据流程图生成代码方面仍有较大提升空间。值得注意的是，实验结果表明监督微调技术对模型性能的提升起到了关键作用。我们的代码和数据集已开源，地址为https://github.com/hml-github/Flow2Code。

> While large language models (LLMs) show promise in code generation, existing benchmarks neglect the flowchart-based code generation. To promote further research on flowchart-based code generation, this work presents Flow2Code, a novel benchmark for flowchart-based code generation evaluation. The evaluation dataset spans 15 programming languages and includes 5,622 code segments paired with 16,866 flowcharts of three types: code, UML, and pseudocode. Extensive experiments with 13 multimodal LLMs reveal that current LLMs can not generate code based on flowcharts perfectly. Besides, experiment results show that the supervised fine-tuning technique contributes greatly to the models' performance. We publicly release our code and datasets at https://github.com/hml-github/Flow2Code.

[Arxiv](https://arxiv.org/abs/2506.02073)