# ExeCoder：为大型语言模型赋能，通过可执行性表示提升代码翻译能力

发布时间：2025年01月30日

`LLM应用

理由：这篇论文主要讨论了如何利用预训练的大型语言模型（LLMs）进行代码翻译，并提出了一个名为ExeCoder的专门用于代码翻译的LLM。论文的核心在于通过引入可执行性表示来提升LLMs在代码翻译中的表现，这属于LLM在实际应用中的改进和优化，因此应归类为LLM应用。` `软件开发` `代码翻译`

> ExeCoder: Empowering Large Language Models with Executability Representation for Code Translation

# 摘要

> # 摘要
代码翻译在软件开发和维护中至关重要，研究人员近期开始探索使用预训练的大型语言模型（LLMs）进行代码翻译。然而，现有LLMs在预训练时仅关注代码的上下文语义，忽略了与代码执行状态紧密相关的可执行性信息，导致代码的可执行性无法保证，自动化翻译的可靠性也大打折扣。为此，我们提出了ExeCoder，一个专为代码翻译设计的LLM，通过引入功能语义、语法结构和变量依赖等可执行性表示，显著提升了LLMs的代码翻译能力。为了验证ExeCoder的效果，我们手动优化了广泛使用的基准测试TransCoder-test，推出了专为LLMs设计的TransCoder-test-X。评估结果显示，ExeCoder在代码翻译中表现卓越，在两个关键指标上分别领先现有开源LLMs 10.88%至38.78%和27.44%至42.97%，甚至超越了知名的闭源LLM GPT-4o。网站: https://execoder4trans.github.io/

> Code translation is a crucial activity in the software development and maintenance process, and researchers have recently begun to focus on using pre-trained large language models (LLMs) for code translation. However, existing LLMs only learn the contextual semantics of code during pre-training, neglecting executability information closely related to the execution state of the code, which results in unguaranteed code executability and unreliable automated code translation. To address this issue, we propose ExeCoder, an LLM specifically designed for code translation, aimed at utilizing executability representations such as functional semantics, syntax structures, and variable dependencies to enhance the capabilities of LLMs in code translation. To evaluate the effectiveness of ExeCoder, we manually enhanced the widely used benchmark TransCoder-test, resulting in a benchmark called TransCoder-test-X that serves LLMs. Evaluation of TransCoder-test-X indicates that ExeCoder achieves state-of-the-art performance in code translation, surpassing existing open-source code LLMs by over 10.88% to 38.78% and over 27.44% to 42.97% on two metrics, and even outperforms the renowned closed-source LLM GPT-4o. Website: https://execoder4trans.github.io/

[Arxiv](https://arxiv.org/abs/2501.18460)