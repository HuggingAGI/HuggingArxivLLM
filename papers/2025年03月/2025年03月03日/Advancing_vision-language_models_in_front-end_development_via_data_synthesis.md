# 借助数据合成，提升前端开发中的视觉语言模型

发布时间：2025年03月03日

`LLM应用

理由：论文探讨了如何利用视觉语言模型（VLMs）生成前端开发代码，属于大型语言模型的应用场景。` `前端开发` `视觉语言模型`

> Advancing vision-language models in front-end development via data synthesis

# 摘要

> 现代前端开发，尤其是在利用 React 和 Vue 等框架的独特功能时，面临诸多挑战，包括管理模块化架构、实现数据与视觉输出的同步渲染，以及将可复用组件适应多样场景。这些复杂性使得大视觉语言模型 (VLMs) 难以直接从设计图像生成准确且功能正常的代码。为此，我们提出了一种反思型能动工作流，通过合成高质量的图像-文本数据捕捉前端开发的多样化特征。该工作流能够从真实项目中自动化提取自包含的代码片段、渲染对应的视觉输出，并生成详细描述，将设计元素与功能代码联系起来。为了进一步扩展合成的范围和实用性，我们引入了三种数据合成策略：基于演进的合成，支持可扩展且多样的数据集扩展；基于瀑布模型的合成，生成符合系统需求的逻辑连贯代码；以及基于增量开发的合成，逐步增加人工编写组件的复杂性。我们构建了一个大型视觉语言模型 Flame，使用合成数据集进行训练，并通过【数学公式】指标验证其在生成 React 代码方面的有效性。实验结果表明，经过训练以在代码生成前解释图像的 VLM 可能实现更好的性能。

> Modern front-end (FE) development, especially when leveraging the unique features of frameworks like React and Vue, presents distinctive challenges. These include managing modular architectures, ensuring synchronization between data and visual outputs for declarative rendering, and adapting reusable components to various scenarios. Such complexities make it particularly difficult for state-of-the-art large vision-language models (VLMs) to generate accurate and functional code directly from design images. To address these challenges, we propose a reflective agentic workflow that synthesizes high-quality image-text data to capture the diverse characteristics of FE development. This workflow automates the extraction of self-contained\footnote{A \textbf{self-contained} code snippet is one that encapsulates all necessary logic, styling, and dependencies, ensuring it functions independently without requiring external imports or context.} code snippets from real-world projects, renders the corresponding visual outputs, and generates detailed descriptions that link design elements to functional code. To further expand the scope and utility of the synthesis, we introduce three data synthesis strategies: Evolution-based synthesis, which enables scalable and diverse dataset expansion; Waterfall-Model-based synthesis, which generates logically coherent code derived from system requirements; and Additive Development synthesis, which iteratively increases the complexity of human-authored components. We build a large vision-language model, Flame, trained on the synthesized datasets and demonstrate its effectiveness in generating React code via the $\text{pass}@k$ metric. Our results suggest that a code VLM trained to interpret images before code generation may achieve better performance.

[Arxiv](https://arxiv.org/abs/2503.01619)