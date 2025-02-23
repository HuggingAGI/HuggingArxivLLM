# 微调大型语言模型中的跨语言迁移：基于中间层表示对齐

发布时间：2025年02月20日

`LLM应用

摘要分析：论文探讨了大规模语言模型在跨语言任务中的应用挑战，并提出了一种中间层对齐的方法，显著提升了跨语言迁移效果，属于LLM应用的研究。` `机器翻译`

> Middle-Layer Representation Alignment for Cross-Lingual Transfer in Fine-Tuned LLMs

# 摘要

> 大规模语言模型通过微调在特定任务中表现卓越，但要实现跨语言的广泛应用，仍面临诸多挑战。由于不同语言间LLM性能差异及微调数据的匮乏，跨语言迁移效果受限。通过对超过1,000种语言对的分析，我们发现中间层在跨语言对齐方面潜力最大。基于此，我们提出了一种结合任务训练的中间层对齐方法。实验结果显示，该方法在槽填充、机器翻译和结构化文本生成任务中显著提升了跨语言迁移效果，尤其对资源较少的语言效果显著。该方法对对齐语言选择具有鲁棒性，并能推广到未参与对齐的语言。此外，我们发现单独训练的对齐模块可与现有任务模块无缝结合，无需完全重新训练即可增强跨语言能力。我们的代码已开源（https://github.com/dannigt/mid-align）。

> While large language models demonstrate remarkable capabilities at task-specific applications through fine-tuning, extending these benefits across diverse languages is essential for broad accessibility. However, effective cross-lingual transfer is hindered by LLM performance gaps across languages and the scarcity of fine-tuning data in many languages. Through analysis of LLM internal representations from over 1,000+ language pairs, we discover that middle layers exhibit the strongest potential for cross-lingual alignment. Building on this finding, we propose a middle-layer alignment objective integrated into task-specific training. Our experiments on slot filling, machine translation, and structured text generation show consistent improvements in cross-lingual transfer, especially to lower-resource languages. The method is robust to the choice of alignment languages and generalizes to languages unseen during alignment. Furthermore, we show that separately trained alignment modules can be merged with existing task-specific modules, improving cross-lingual capabilities without full re-training. Our code is publicly available (https://github.com/dannigt/mid-align).

[Arxiv](https://arxiv.org/abs/2502.14830)