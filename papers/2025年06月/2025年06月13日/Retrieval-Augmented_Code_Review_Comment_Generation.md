# # 检索增强的代码审查注释生成

发布时间：2025年06月13日

`RAG` `软件开发` `代码审查`

> Retrieval-Augmented Code Review Comment Generation

# 摘要

> 自动化代码审查注释生成（RCG）旨在通过自动生成自然语言反馈来协助开发者处理代码更改。现有方法主要分为两类：基于生成的方法，使用预训练语言模型；以及基于信息检索（IR）的方法，从过去的类似示例中重用注释。基于生成的方法通过在大型代码-自然语言语料库上进行特定于代码的预训练来学习代码与自然语言之间的语义关系，但由于其概率性质，它们常常难以生成低频但语义重要的标记。相比之下，基于IR的方法通过从现有示例中复制来擅长恢复这些罕见标记，但在适应新的代码上下文方面缺乏灵活性——例如，当输入代码包含检索数据库中未找到的标识符或结构时。为了弥合基于生成和基于IR方法之间的差距，本研究提出了一种基于检索增强生成（RAG）的RCG方法，通过基于检索到的代码审查示例对预训练语言模型进行条件化。通过提供相关示例，展示类似代码是如何被之前审查的，模型能够更好地生成准确的审查注释。我们在Tufano等人的基准测试上的评估表明，基于RAG的RCG在生成和IR基线之间取得了更好的性能。与基于生成的RCG相比，它在精确匹配方面提高了+1.67%，在BLEU分数方面提高了+4.25%。它还改善了低频真实标记的生成，提高了高达24.01%。我们还发现，随着检索到的示例数量增加，性能也得到了提升。

> Automated code review comment generation (RCG) aims to assist developers by automatically producing natural language feedback for code changes. Existing approaches are primarily either generation-based, using pretrained language models, or information retrieval-based (IR), reusing comments from similar past examples. While generation-based methods leverage code-specific pretraining on large code-natural language corpora to learn semantic relationships between code and natural language, they often struggle to generate low-frequency but semantically important tokens due to their probabilistic nature. In contrast, IR-based methods excel at recovering such rare tokens by copying from existing examples but lack flexibility in adapting to new code contexts-for example, when input code contains identifiers or structures not found in the retrieval database. To bridge the gap between generation-based and IR-based methods, this work proposes to leverage retrieval-augmented generation (RAG) for RCG by conditioning pretrained language models on retrieved code-review exemplars. By providing relevant examples that illustrate how similar code has been previously reviewed, the model is better guided to generate accurate review comments. Our evaluation on the Tufano et al. benchmark shows that RAG-based RCG outperforms both generation-based and IR-based RCG. It achieves up to +1.67% higher exact match and +4.25% higher BLEU scores compared to generation-based RCG. It also improves the generation of low-frequency ground-truth tokens by up to 24.01%. We additionally find that performance improves as the number of retrieved exemplars increases.

[Arxiv](https://arxiv.org/abs/2506.11591)