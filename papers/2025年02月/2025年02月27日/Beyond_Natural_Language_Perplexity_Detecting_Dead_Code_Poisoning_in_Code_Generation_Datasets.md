# 超越自然语言困惑度：探索代码生成数据集中的死代码中毒检测

发布时间：2025年02月27日

`LLM应用` `软件工程` `网络安全`

> Beyond Natural Language Perplexity: Detecting Dead Code Poisoning in Code Generation Datasets

# 摘要

> 大型语言模型 (LLMs) 在代码任务中的广泛应用引发了对其训练数据安全性的担忧。一个关键威胁是“死代码投毒”——向训练数据中注入语法正确但功能冗余的代码，以操纵模型行为。此类攻击会导致神经代码搜索系统性能下降，产生偏颇或不安全的代码建议。现有检测方法，如基于令牌级别的困惑度分析，由于编程语言的结构和上下文特性，无法有效识别死代码。本文提出 DePA（Dead Code Perplexity Analysis），这是一种针对代码结构特性的新型行级别检测和清洗方法。DePA 通过利用代码行之间的上下文关系计算行级别困惑度，并通过将其困惑度与文件内的总体分布进行比较来识别异常行。我们在基准数据集上的实验表明，DePA 显著优于现有方法，检测 F1 分数提高了 0.14-0.19，中毒段定位精度提高了 44-65%。此外，DePA 将检测速度提高了 0.62-23 倍，使其适用于大规模数据集的清洗。总体而言，通过解决死代码投毒的独特挑战，DePA 为保障代码生成模型训练数据集的完整性提供了一个强大而高效的方法。


> The increasing adoption of large language models (LLMs) for code-related tasks has raised concerns about the security of their training datasets. One critical threat is dead code poisoning, where syntactically valid but functionally redundant code is injected into training data to manipulate model behavior. Such attacks can degrade the performance of neural code search systems, leading to biased or insecure code suggestions. Existing detection methods, such as token-level perplexity analysis, fail to effectively identify dead code due to the structural and contextual characteristics of programming languages. In this paper, we propose DePA (Dead Code Perplexity Analysis), a novel line-level detection and cleansing method tailored to the structural properties of code. DePA computes line-level perplexity by leveraging the contextual relationships between code lines and identifies anomalous lines by comparing their perplexity to the overall distribution within the file. Our experiments on benchmark datasets demonstrate that DePA significantly outperforms existing methods, achieving 0.14-0.19 improvement in detection F1-score and a 44-65% increase in poisoned segment localization precision. Furthermore, DePA enhances detection speed by 0.62-23x, making it practical for large-scale dataset cleansing. Overall, by addressing the unique challenges of dead code poisoning, DePA provides a robust and efficient solution for safeguarding the integrity of code generation model training datasets.

[Arxiv](https://arxiv.org/abs/2502.20246)