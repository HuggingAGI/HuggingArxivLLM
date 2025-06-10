# # 标题
解析语言切换：基于大语言模型的复杂语言切换与资源匮乏语言的UD标注

发布时间：2025年06月08日

`LLM应用` `多语言处理`

> Parsing the Switch: LLM-Based UD Annotation for Complex Code-Switched and Low-Resource Languages

# 摘要

> 语言混用对句法分析提出了复杂挑战，特别是在标注数据稀缺的低资源语言环境中。尽管 recent work 探索了大语言模型（LLMs）在序列级标注中的应用，但很少有方法系统性地研究这些模型在语言混用语境下对句法结构的捕捉能力。此外，现有基于单语树库训练的解析器常常无法很好地推广到多语言和混合语言输入。为了解决这一差距，我们引入了 BiLingua Parser，这是一个基于 LLM 的注释流水线，旨在为语言混用文本生成通用依赖（UD）注释。首先，我们为西班牙语-英语和西班牙语-瓜拉尼语数据开发了一个基于提示的框架，结合了少量样本 LLM 提示和专家评审。其次，我们发布了两个标注数据集，包括首个西班牙语-瓜拉尼语 UD 解析语料库。第三，我们对跨语言对和交际语境中的切换点进行了详细句法分析。实验结果表明，经过专家修订后，BiLingua Parser 的 LAS 达到 95.29%，显著优于先前的基线和多语言解析器。这些结果表明，当经过精心指导时，LLMs 可以作为在低资源语言混用环境中构建句法资源的实用工具。数据和源代码可在 https://github.com/N3mika/ParsingProject 获取。


> Code-switching presents a complex challenge for syntactic analysis, especially in low-resource language settings where annotated data is scarce. While recent work has explored the use of large language models (LLMs) for sequence-level tagging, few approaches systematically investigate how well these models capture syntactic structure in code-switched contexts. Moreover, existing parsers trained on monolingual treebanks often fail to generalize to multilingual and mixed-language input. To address this gap, we introduce the BiLingua Parser, an LLM-based annotation pipeline designed to produce Universal Dependencies (UD) annotations for code-switched text. First, we develop a prompt-based framework for Spanish-English and Spanish-Guaraní data, combining few-shot LLM prompting with expert review. Second, we release two annotated datasets, including the first Spanish-Guaraní UD-parsed corpus. Third, we conduct a detailed syntactic analysis of switch points across language pairs and communicative contexts. Experimental results show that BiLingua Parser achieves up to 95.29% LAS after expert revision, significantly outperforming prior baselines and multilingual parsers. These results show that LLMs, when carefully guided, can serve as practical tools for bootstrapping syntactic resources in under-resourced, code-switched environments. Data and source code are available at https://github.com/N3mika/ParsingProject

[Arxiv](https://arxiv.org/abs/2506.07274)