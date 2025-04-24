# 逆向翻译中的诗意意图悖论——大型语言模型中文翻译质量评估

发布时间：2025年04月22日

`LLM应用` `机器翻译` `翻译技术`

> The Paradox of Poetic Intent in Back-Translation: Evaluating the Quality of Large Language Models in Chinese Translation

# 摘要

> 大型语言模型（LLMs）的快速发展重塑了机器翻译的格局，但在中英翻译中仍面临诗意意图、文化遗产和专业术语处理的挑战。本研究构建了一个包含中文科学术语、历史翻译悖论和文学隐喻的多样化语料库。通过反向翻译结合Friedman测试的评估系统（BT-Fried），我们对六种主流LLMs（如GPT-4.5、DeepSeek V3）和三种传统翻译工具的BLEU、CHRF、TER以及语义相似度等指标进行了评估。主要发现包括：(1) 科学摘要通常受益于反向翻译，而传统工具在语言差异较大的文本上表现优于LLMs；(2) LLMs在保留文化和文学特征方面存在困难，体现了"诗意意图的悖论"；(3) 部分模型表现出"逐字反向翻译"的现象，反映了记忆行为的涌现；(4) 提出了一种基于Jieba分词和n-gram加权的新BLEU变体。本研究为中文NLP性能的实证评估提供了贡献，并加深了对AI介导翻译中文化忠实性的理解。

> The rapid advancement of large language models (LLMs) has reshaped the landscape of machine translation, yet challenges persist in preserving poetic intent, cultural heritage, and handling specialized terminology in Chinese-English translation. This study constructs a diverse corpus encompassing Chinese scientific terminology, historical translation paradoxes, and literary metaphors. Utilizing a back-translation and Friedman test-based evaluation system (BT-Fried), we evaluate BLEU, CHRF, TER, and semantic similarity metrics across six major LLMs (e.g., GPT-4.5, DeepSeek V3) and three traditional translation tools. Key findings include: (1) Scientific abstracts often benefit from back-translation, while traditional tools outperform LLMs in linguistically distinct texts; (2) LLMs struggle with cultural and literary retention, exemplifying the "paradox of poetic intent"; (3) Some models exhibit "verbatim back-translation", reflecting emergent memory behavior; (4) A novel BLEU variant using Jieba segmentation and n-gram weighting is proposed. The study contributes to the empirical evaluation of Chinese NLP performance and advances understanding of cultural fidelity in AI-mediated translation.

[Arxiv](https://arxiv.org/abs/2504.16286)