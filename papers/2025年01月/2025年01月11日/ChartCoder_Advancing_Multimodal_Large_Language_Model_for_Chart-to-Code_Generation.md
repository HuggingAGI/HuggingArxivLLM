# ChartCoder: 多模态大语言模型在图表转代码生成中的新突破

发布时间：2025年01月11日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在图表理解任务中的应用，特别是如何通过将图表解析为代码来提升生成代码的可执行性和图表细节的恢复。论文提出了一个新的模型ChartCoder和一个大规模数据集Chart2Code-160k，这些都是具体的应用场景和解决方案，因此归类为LLM应用。` `数据可视化`

> ChartCoder: Advancing Multimodal Large Language Model for Chart-to-Code Generation

# 摘要

> # 多模态大型语言模型（MLLMs）在图表理解任务中表现出色。然而，用文本描述图表往往会导致信息丢失，无法全面捕捉图表中的密集信息。相比之下，将图表解析为代码则能无损地保留所有关键细节。尽管现有开源MLLMs在图表理解任务中取得了成功，但在图表到代码任务中仍面临两大挑战：（1）生成代码的可执行性差，图表细节恢复不佳；（2）缺乏大规模、多样化的训练数据。为此，我们提出了	extbf{ChartCoder}，这是首个专为图表到代码设计的MLLM，它利用代码LLMs作为语言骨干，显著提升了生成代码的可执行性。此外，我们推出了	extbf{Chart2Code-160k}，这是首个大规模、多样化的图表到代码生成数据集，并提出了	extbf{Snippet-of-Thought (SoT)}方法，将直接的图表到代码生成转化为逐步生成。实验表明，仅7B参数的ChartCoder在图表到代码基准测试中超越了现有开源MLLMs，实现了卓越的图表恢复和代码可执行性。代码将在https://github.com/thunlp/ChartCoder公开。

> Multimodal Large Language Models (MLLMs) have demonstrated remarkable capabilities in chart understanding tasks. However, interpreting charts with textual descriptions often leads to information loss, as it fails to fully capture the dense information embedded in charts. In contrast, parsing charts into code provides lossless representations that can effectively contain all critical details. Although existing open-source MLLMs have achieved success in chart understanding tasks, they still face two major challenges when applied to chart-to-code tasks.: (1) Low executability and poor restoration of chart details in the generated code and (2) Lack of large-scale and diverse training data. To address these challenges, we propose \textbf{ChartCoder}, the first dedicated chart-to-code MLLM, which leverages Code LLMs as the language backbone to enhance the executability of the generated code. Furthermore, we introduce \textbf{Chart2Code-160k}, the first large-scale and diverse dataset for chart-to-code generation, and propose the \textbf{Snippet-of-Thought (SoT)} method, which transforms direct chart-to-code generation data into step-by-step generation. Experiments demonstrate that ChartCoder, with only 7B parameters, surpasses existing open-source MLLMs on chart-to-code benchmarks, achieving superior chart restoration and code excitability. Our code will be available at https://github.com/thunlp/ChartCoder.

[Arxiv](https://arxiv.org/abs/2501.06598)