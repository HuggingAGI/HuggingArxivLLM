# 代码语言模型记住了多少？微调前后数据提取攻击的深入探究

发布时间：2025年01月29日

`LLM理论

理由：这篇论文主要研究了代码语言模型在预训练和微调过程中数据可提取性的问题，探讨了模型对训练数据的记忆和泄露风险。这涉及到大型语言模型（LLM）的理论基础，特别是模型训练过程中数据的记忆和遗忘机制。因此，将其归类为LLM理论更为合适。` `信息安全` `代码分析`

> How Much Do Code Language Models Remember? An Investigation on Data Extraction Attacks before and after Fine-tuning

# 摘要

> # 摘要
代码语言模型虽然广受欢迎，但通常是在未经处理的互联网源代码上训练的。研究表明，预训练模型可能记住训练数据，并通过数据提取攻击泄露信息。由于模型规模庞大，只有少数实体能负担预训练。然而，微调资源需求较少，且对专门数据效果显著，因此被广泛使用。这些微调数据集可能包含敏感或专有信息。本研究攻击了预训练和微调的代码语言模型，探究数据可提取性。我们开发了自定义基准，评估预训练和微调样本对提取攻击的脆弱性。结果显示，StarCoder2-15B中54.9%的预训练数据可被提取，微调后降至23.5%，表明微调降低了预训练数据的可提取性。然而，与大型模型相比，微调小型模型增加了其对微调数据提取攻击的脆弱性，可能导致更严重后果。我们还手动分析了2000个微调前后的可提取样本，发现数据载体和许可信息最易被记住，而后者在微调后最易被遗忘。

> Code language models, while widely popular, are often trained on unsanitized source code gathered from across the Internet. Previous work revealed that pre-trained models can remember the content of their training data and regurgitate them through data extraction attacks. Due to the large size of current models, only a few entities have the resources for pre-training such models. However, fine-tuning requires fewer resources and is increasingly used by both small and large entities for its effectiveness on specialized data. Such small curated data for fine-tuning might contain sensitive information or proprietary assets. In this study, we attack both pre-trained and fine-tuned code language models to investigate the extent of data extractability. We first develop a custom benchmark to assess the vulnerability of both pre-training and fine-tuning samples to extraction attacks. Our findings reveal that 54.9% of extractable pre-training data could be retrieved from StarCoder2-15B, whereas this number decreased to 23.5% after fine-tuning. This indicates that fine-tuning reduces the extractability of pre-training data. However, compared to larger models, fine-tuning smaller models increases their vulnerability to data extraction attacks on fine-tuning data. Given the potential sensitivity of fine-tuning data, this can lead to more severe consequences. Lastly, we also manually analyzed 2000 extractable samples before and after fine-tuning. We also found that data carriers and licensing information are the most likely data categories to be memorized from pre-trained and fine-tuned models, while the latter is the most likely to be forgotten after fine-tuning.

[Arxiv](https://arxiv.org/abs/2501.17501)