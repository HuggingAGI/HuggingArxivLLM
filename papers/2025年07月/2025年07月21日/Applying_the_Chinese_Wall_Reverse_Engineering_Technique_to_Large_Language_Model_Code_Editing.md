# 将中文墙逆向工程应用于大型语言模型代码编辑

发布时间：2025年07月21日

`LLM应用` `软件开发`

> Applying the Chinese Wall Reverse Engineering Technique to Large Language Model Code Editing

# 摘要

> 代码大型语言模型（Code LLM）在编程环境中越来越受欢迎。尽管它们在编程环境中有广泛的应用，但顶级 LLM 的训练数据集仍然没有公开，这引发了人们对潜在版权违规的担忧。一些模型，如 Pleias 和 Comma，特别注重数据整理和许可证，但受限于有限的训练数据，这些模型缺乏竞争力，仅作为概念验证存在。为了提高这些模型的实用性，我们提出了一种“中国墙”技术的应用，这一灵感源自同名的逆向工程技术——即使用一个高质量的模型为较弱的模型生成详细的指令。这样一来，一个较弱但符合伦理的模型也可以执行复杂的任务，否则这些任务只能由更强大的模型来完成。在我们的评估中，我们发现这种技术使 Comma v0.1 1T 在 CanItEdit 基准测试中的性能提升了超过 66%，而 Starcoder2 Instruct 的性能也提高了大约 20%，相较于仅在基准测试中运行相同模型的情况。然而，由于缺乏不受版权限制的公共领域内容训练模型，该技术在当今的实际应用可能会受到限制。

> Large language models for code (Code LLM) are increasingly utilized in programming environments. Despite their utility, the training datasets for top LLM remain undisclosed, raising concerns about potential copyright violations. Some models, such as Pleias and Comma put emphasis on data curation and licenses, however, with limited training data these models are not competitive and only serve as proof of concepts. To improve the utility of these models, we propose an application of the "Chinese Wall" technique, inspired by the reverse engineering technique of the same name -- a high quality model is used to generate detailed instructions for a weaker model. By doing so, a weaker but ethically aligned model may be used to perform complicated tasks that, otherwise, can only be completed by more powerful models. In our evaluation, we've found that this technique improves Comma v0.1 1T's performance in CanItEdit benchmark by over 66%, and Starcoder2 Instruct by roughly 20% compared to when running the same model on the benchmark alone. The practical application of this technique today, however, may be limited due to the lack of models trained on public domain content without copyright restrictions.

[Arxiv](https://arxiv.org/abs/2507.15599)