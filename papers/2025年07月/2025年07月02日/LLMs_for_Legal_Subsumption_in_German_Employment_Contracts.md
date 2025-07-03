# # 大型语言模型在德国雇佣合同法律适用中的研究

发布时间：2025年07月02日

`LLM应用

摘要讨论了大型语言模型在法律领域的应用，具体是评估德国民事合同条款的合法性。研究扩展了数据集，并探讨了LLMs在不同法律背景下的表现，属于实际应用场景。`

> LLMs for Legal Subsumption in German Employment Contracts

# 摘要

> 法律工作因其文本密集和资源消耗大的特点，为NLP研究带来了独特的挑战和机遇。尽管数据驱动的方法推动了该领域的发展，但其缺乏可解释性和可信度限制了其在动态法律环境中的应用。为了解决这些问题，我们与法律专家合作扩展了现有数据集，并探索了大型语言模型（LLMs）和上下文学习在评估德国民事合同条款合法性方面的应用。我们的研究评估了不同LLMs在三种法律背景变体下对条款分类为“有效”、“不公平”或“无效”的能力：无法律背景、完整的法律文本和法院判决，以及这些文本的精简版本（称为考试大纲）。结果显示，完整的法律文本适度提升了性能，而考试大纲显著提高了无效条款的召回率和加权F1-Score，达到了80%。尽管取得了这些进展，但使用完整法律文本的LLMs表现仍远低于人类律师的水平。我们贡献了一个扩展的数据集，其中包括考试大纲、参考法律来源和相应的标注，以及我们的代码和所有日志文件。我们的研究结果突显了LLMs在协助律师进行合同合法性审查的潜力，同时也强调了所呈现方法的局限性。

> Legal work, characterized by its text-heavy and resource-intensive nature, presents unique challenges and opportunities for NLP research. While data-driven approaches have advanced the field, their lack of interpretability and trustworthiness limits their applicability in dynamic legal environments. To address these issues, we collaborated with legal experts to extend an existing dataset and explored the use of Large Language Models (LLMs) and in-context learning to evaluate the legality of clauses in German employment contracts. Our work evaluates the ability of different LLMs to classify clauses as "valid," "unfair," or "void" under three legal context variants: no legal context, full-text sources of laws and court rulings, and distilled versions of these (referred to as examination guidelines). Results show that full-text sources moderately improve performance, while examination guidelines significantly enhance recall for void clauses and weighted F1-Score, reaching 80\%. Despite these advancements, LLMs' performance when using full-text sources remains substantially below that of human lawyers. We contribute an extended dataset, including examination guidelines, referenced legal sources, and corresponding annotations, alongside our code and all log files. Our findings highlight the potential of LLMs to assist lawyers in contract legality review while also underscoring the limitations of the methods presented.

[Arxiv](https://arxiv.org/abs/2507.01734)