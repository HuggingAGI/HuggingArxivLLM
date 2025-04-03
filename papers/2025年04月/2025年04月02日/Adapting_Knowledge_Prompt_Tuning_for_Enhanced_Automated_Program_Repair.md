# # 优化知识提示调整，提升自动程序修复效果

发布时间：2025年04月02日

`LLM应用` `软件工程` `人工智能`

> Adapting Knowledge Prompt Tuning for Enhanced Automated Program Repair

# 摘要

> 自动程序修复（APR）旨在通过生成修复补丁提升软件可靠性。近期研究通过微调预训练大型语言模型（如CodeT5）改进了APR技术。然而，在数据稀缺场景下，微调效果会减弱，而数据稀缺在实际应用中很常见。为解决这一问题，本文提出了一种基于提示调优的增强型APR方法，并通过全面研究评估其在数据稀缺场景下的有效性。我们使用了三种不同规模的LLM和跨越四种编程语言的六个多样化数据集进行实验。提示调优通过添加额外的提示令牌重写输入，并在小数据集上微调模型和提示。这些令牌提供特定任务的知识，可以提升模型在APR中的表现，尤其是在数据稀缺场景下至关重要。此外，领域知识在许多代码智能任务中被证明至关重要，但现有研究未能在APR的提示调优过程中利用领域知识。为填补这一空白，我们引入了知识提示调优，这是一种结合六种不同类型的代码或与漏洞相关的领域知识来增强APR的提示调优方法。据我们所知，我们的工作是首次适应并评估提示调优以及代码或漏洞相关领域知识在APR中的有效性，特别是在数据稀缺设置下。实验结果表明，知识提示调优在各种实验设置下普遍优于微调，在数据稀缺场景下比微调平均提升了87.33%。

> Automated Program Repair (APR) aims to enhance software reliability by automatically generating bug-fixing patches. Recent work has improved the state-of-the-art of APR by fine-tuning pre-trained large language models (LLMs), such as CodeT5, for APR. However, the effectiveness of fine-tuning becomes weakened in data scarcity scenarios, and data scarcity can be a common issue in practice, limiting fine-tuning performance. To alleviate this limitation, this paper adapts prompt tuning for enhanced APR and conducts a comprehensive study to evaluate its effectiveness in data scarcity scenarios, using three LLMs of different sizes and six diverse datasets across four programming languages. Prompt tuning rewrites the input to a model by adding extra prompt tokens and tunes both the model and the prompts on a small dataset. These tokens provide task-specific knowledge that can improve the model for APR, which is especially critical in data scarcity scenarios. Moreover, domain knowledge has proven crucial in many code intelligence tasks, but existing studies fail to leverage domain knowledge during the prompt tuning for APR. To close this gap, we introduce knowledge prompt tuning, an approach that adapts prompt tuning with six distinct types of code- or bug-related domain knowledge for APR. Our work, to the best of our knowledge, is the first to adapt and evaluate prompt tuning and the effectiveness of code- or bug-related domain knowledge for APR, particularly under data scarcity settings. Our evaluation results demonstrate that prompt tuning with knowledge generally outperforms fine-tuning under various experimental settings, achieving an average improvement of 87.33% over fine-tuning in data scarcity scenarios.

[Arxiv](https://arxiv.org/abs/2504.01523)