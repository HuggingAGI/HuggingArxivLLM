# # 自动化检测黑盒 LLM 中的预训练文本

发布时间：2025年06月24日

`LLM应用` `法律合规`

> Automated Detection of Pre-training Text in Black-box LLMs

# 摘要

> 检测给定文本是否为大型语言模型（LLMs）预训练数据的成员，对于保障数据隐私和版权保护至关重要。现有方法大多依赖于LLM的隐藏信息（如模型参数或词元概率），因此在黑箱环境中效果不佳。尽管针对黑箱环境提出了一些方法，但它们依赖于大量人工努力，例如设计复杂的提问或指令。为了解决这些问题，我们提出了VeilProbe，这是首个无需人工干预、在黑箱环境中自动检测LLMs预训练文本的框架。

VeilProbe利用序列到序列映射模型，推断输入文本与LLM生成的对应输出后缀之间的潜在映射特征。然后通过关键词元扰动获得更具区分度的成员特征。此外，考虑到实际场景中真实训练文本样本有限的问题，引入了基于原型的成员分类器以缓解过拟合问题。在三个广泛使用的数据集上的大量评估表明，我们的框架在黑箱环境中有效且性能优越。

> Detecting whether a given text is a member of the pre-training data of Large Language Models (LLMs) is crucial for ensuring data privacy and copyright protection. Most existing methods rely on the LLM's hidden information (e.g., model parameters or token probabilities), making them ineffective in the black-box setting, where only input and output texts are accessible. Although some methods have been proposed for the black-box setting, they rely on massive manual efforts such as designing complicated questions or instructions. To address these issues, we propose VeilProbe, the first framework for automatically detecting LLMs' pre-training texts in a black-box setting without human intervention. VeilProbe utilizes a sequence-to-sequence mapping model to infer the latent mapping feature between the input text and the corresponding output suffix generated by the LLM. Then it performs the key token perturbations to obtain more distinguishable membership features. Additionally, considering real-world scenarios where the ground-truth training text samples are limited, a prototype-based membership classifier is introduced to alleviate the overfitting issue. Extensive evaluations on three widely used datasets demonstrate that our framework is effective and superior in the black-box setting.

[Arxiv](https://arxiv.org/abs/2506.19399)