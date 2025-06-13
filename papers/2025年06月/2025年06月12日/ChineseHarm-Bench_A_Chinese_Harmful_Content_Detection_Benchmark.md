# 中文有害内容检测基准（ChineseHarm-Bench）：首个专注于中文有害内容检测的基准数据集。

发布时间：2025年06月12日

`LLM应用` `内容安全` `有害内容检测`

> ChineseHarm-Bench: A Chinese Harmful Content Detection Benchmark

# 摘要

> 大型语言模型（LLMs）在自动有害内容检测领域的应用不断扩展，不仅帮助审核人员快速识别违规内容，还显著提升了内容审核的整体效率和精准度。然而，现有有害内容检测资源主要面向英语内容，中文数据集则相对匮乏且覆盖范围有限。为此，我们推出了一个全面、专业标注的中文有害内容检测基准，涵盖六大代表性类别，完全基于真实数据构建而成。我们的标注流程还衍生出一个知识规则库，为大型语言模型提供显性的专家知识，助力中文有害内容检测。此外，我们提出了一种知识增强的基线方法，巧妙结合人工标注的知识规则与大型语言模型中的隐性知识，使中小型规模的模型也能达到与顶尖大型语言模型相媲美的检测效果。相关代码和数据已开源，详情请访问https://github.com/zjunlp/ChineseHarm-bench。

> Large language models (LLMs) have been increasingly applied to automated harmful content detection tasks, assisting moderators in identifying policy violations and improving the overall efficiency and accuracy of content review. However, existing resources for harmful content detection are predominantly focused on English, with Chinese datasets remaining scarce and often limited in scope. We present a comprehensive, professionally annotated benchmark for Chinese content harm detection, which covers six representative categories and is constructed entirely from real-world data. Our annotation process further yields a knowledge rule base that provides explicit expert knowledge to assist LLMs in Chinese harmful content detection. In addition, we propose a knowledge-augmented baseline that integrates both human-annotated knowledge rules and implicit knowledge from large language models, enabling smaller models to achieve performance comparable to state-of-the-art LLMs. Code and data are available at https://github.com/zjunlp/ChineseHarm-bench.

[Arxiv](https://arxiv.org/abs/2506.10960)