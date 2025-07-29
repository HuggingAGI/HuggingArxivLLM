# AI驱动生成古英语：面向低资源语言的框架

发布时间：2025年07月26日

`LLM应用` `语言保护` `文化复兴`

> AI-Driven Generation of Old English: A Framework for Low-Resource Languages

# 摘要

> 保护古代语言对于理解人类的文化和语言遗产至关重要，然而古英语资源匮乏，难以让现代自然语言处理技术发挥作用。我们提出了一种可扩展的框架，利用先进的大型语言模型生成高质量的古英语文本，填补这一空白。我们的方法结合了参数高效的微调技术（Low-Rank Adaptation，LoRA）、通过反向翻译进行数据增强，以及一个双代理管道，分别负责内容生成（用现代英语）和翻译（转为古英语）。通过自动化指标（如BLEU、METEOR和CHRF）评估，我们的模型在英语到古英语翻译任务中表现优异，BLEU分数从26提升至65以上。专家人工评估也证实了生成文本在语法准确性和风格忠实性方面表现优异。除了扩充古英语语料库外，我们的方法还为复兴其他濒危语言提供了一个实用的蓝图，有效结合了AI创新与文化保护的目标。

> Preserving ancient languages is essential for understanding humanity's cultural and linguistic heritage, yet Old English remains critically under-resourced, limiting its accessibility to modern natural language processing (NLP) techniques. We present a scalable framework that uses advanced large language models (LLMs) to generate high-quality Old English texts, addressing this gap. Our approach combines parameter-efficient fine-tuning (Low-Rank Adaptation, LoRA), data augmentation via backtranslation, and a dual-agent pipeline that separates the tasks of content generation (in English) and translation (into Old English). Evaluation with automated metrics (BLEU, METEOR, and CHRF) shows significant improvements over baseline models, with BLEU scores increasing from 26 to over 65 for English-to-Old English translation. Expert human assessment also confirms high grammatical accuracy and stylistic fidelity in the generated texts. Beyond expanding the Old English corpus, our method offers a practical blueprint for revitalizing other endangered languages, effectively uniting AI innovation with the goals of cultural preservation.

[Arxiv](https://arxiv.org/abs/2507.20111)