# RETROcode：通过代码数据库改进自然语言到代码的生成能力

发布时间：2025年04月08日

`LLM应用` `软件开发` `数据处理`

> RETROcode: Leveraging a Code Database for Improved Natural Language to Code Generation

# 摘要

> 随着文本和代码资源的不断扩展，大规模预训练模型在代码生成任务中展现出了令人瞩目的潜力，通常采用基于问题描述与程序配对的监督微调方法。然而，单纯通过增大模型规模和数据量来提升性能，不仅会增加计算需求，还可能引发过拟合的风险。为了解决这些挑战，我们提出了RETROcode——这是对RETRO架构\cite{RETRO}在序列到序列模型中的一种创新性适应，采用大型代码数据库作为辅助扩展方法。与简单地扩大模型和数据集规模不同，RETROcode能够通过整合庞大的代码数据库进行预测，从而显著提升模型的效率。研究结果表明，RETROcode不仅在测试集上超越了类似规模的传统架构，而且在训练数据集小得多的情况下，其性能也接近规模大得多的Codex模型。

> As text and code resources have expanded, large-scale pre-trained models have shown promising capabilities in code generation tasks, typically employing supervised fine-tuning with problem statement-program pairs. However, increasing model size and data volume for performance gains also raises computational demands and risks of overfitting. Addressing these challenges, we present RETROcode, a novel adaptation of the RETRO architecture \cite{RETRO} for sequence-to-sequence models, utilizing a large code database as an auxiliary scaling method. This approach, diverging from simply enlarging model and dataset sizes, allows RETROcode to leverage a vast code database for prediction, enhancing the model's efficiency by integrating extensive memory. Our findings indicate that RETROcode not only outperforms similar-sized traditional architectures on test sets but also approaches the effectiveness of the much larger Codex model, despite being trained from scratch on a substantially smaller dataset.

[Arxiv](https://arxiv.org/abs/2504.05759)