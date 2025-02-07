# 低成本且全面的非文本输入模糊测试：基于LLM的输入生成器

发布时间：2025年01月31日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）在非文本输入上进行语法感知模糊测试，并提出了一个名为G2FUZZ的新方法。该方法结合了LLMs驱动的全局搜索和传统模糊测试工具的局部搜索，以提高代码覆盖率和漏洞发现能力。虽然论文涉及LLMs的应用，但重点在于如何利用LLMs来增强模糊测试的效果，而不是探讨LLMs的理论或构建智能体（Agent）。因此，将其分类为“LLM应用”是合适的。` `软件测试` `模糊测试`

> Low-Cost and Comprehensive Non-textual Input Fuzzing with LLM-Synthesized Input Generators

# 摘要

> 现代软件常处理高度复杂的语法输入。大型语言模型（LLMs）的最新进展显示，它们能生成符合特定语法的高质量自然语言文本和代码。然而，LLMs在生成非文本输出（如图像、视频和PDF文件）方面能力有限或成本过高，这限制了它们在语法感知模糊测试中的应用。
    我们提出了一种新方法，使LLMs能在非文本输入上进行语法感知模糊测试。我们利用LLMs合成并变异输入生成器，这些生成器以Python脚本形式生成符合特定语法的数据。随后，传统模糊测试工具（如AFL++）对这些非文本数据进行进一步变异，以有效探索软件输入空间。我们的方法G2FUZZ结合了LLMs驱动的全局搜索和工业级模糊测试工具驱动的局部搜索，具有两大优势：（1）LLMs擅长合成和变异输入生成器，能跳出局部最优，与基于变异的模糊测试工具协同工作；（2）LLMs仅在必要时调用，大幅降低了使用成本。我们在TIFF图像、MP4音频和PDF文件等多种输入格式上评估了G2FUZZ。结果显示，在UNIFUZZ、FuzzBench和MAGMA三个平台上，G2FUZZ在代码覆盖率和漏洞发现方面优于AFL++、Fuzztruction和FormatFuzzer等SOTA工具。

> Modern software often accepts inputs with highly complex grammars. Recent advances in large language models (LLMs) have shown that they can be used to synthesize high-quality natural language text and code that conforms to the grammar of a given input format. Nevertheless, LLMs are often incapable or too costly to generate non-textual outputs, such as images, videos, and PDF files. This limitation hinders the application of LLMs in grammar-aware fuzzing.
  We present a novel approach to enabling grammar-aware fuzzing over non-textual inputs. We employ LLMs to synthesize and also mutate input generators, in the form of Python scripts, that generate data conforming to the grammar of a given input format. Then, non-textual data yielded by the input generators are further mutated by traditional fuzzers (AFL++) to explore the software input space effectively. Our approach, namely G2FUZZ, features a hybrid strategy that combines a holistic search driven by LLMs and a local search driven by industrial quality fuzzers. Two key advantages are: (1) LLMs are good at synthesizing and mutating input generators and enabling jumping out of local optima, thus achieving a synergistic effect when combined with mutation-based fuzzers; (2) LLMs are less frequently invoked unless really needed, thus significantly reducing the cost of LLM usage. We have evaluated G2FUZZ on a variety of input formats, including TIFF images, MP4 audios, and PDF files. The results show that G2FUZZ outperforms SOTA tools such as AFL++, Fuzztruction, and FormatFuzzer in terms of code coverage and bug finding across most programs tested on three platforms: UNIFUZZ, FuzzBench, and MAGMA.

[Arxiv](https://arxiv.org/abs/2501.19282)