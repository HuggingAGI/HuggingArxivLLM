# 大型语言模型在提示注入攻击下的机器翻译规模效应

发布时间：2024年03月14日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）在机器翻译任务中的应用，特别是在面对提示注入攻击（PIAs）时的表现和敏感性。论文通过分析不同大小的LLMs对PIAs的反应，并引入了新的基准数据集，探讨了LLMs在多语言环境中的非线性缩放行为。这一研究直接关联到LLMs的实际应用场景，特别是在安全性方面的考量，因此属于LLM应用分类。` `机器翻译`

> Scaling Behavior of Machine Translation with Large Language Models under Prompt Injection Attacks

# 摘要

> 大型语言模型（LLMs）因其高质量和通过自然语言指令或上下文示例指定任务的便捷性，正成为机器翻译等自然语言处理任务的首选平台。然而，其通用性也使其易受提示注入攻击（PIAs），用户可能通过嵌入特定指令操纵模型执行未授权操作。本研究针对机器翻译任务，分析了不同大小LLMs对PIAs的敏感性，并引入新基准数据集。研究发现，在特定条件下，大型模型对英语编写的注入提示更敏感，揭示了逆向缩放现象。这是首次在多语言环境中深入探讨LLMs的非线性缩放行为。

> Large Language Models (LLMs) are increasingly becoming the preferred foundation platforms for many Natural Language Processing tasks such as Machine Translation, owing to their quality often comparable to or better than task-specific models, and the simplicity of specifying the task through natural language instructions or in-context examples. Their generality, however, opens them up to subversion by end users who may embed into their requests instructions that cause the model to behave in unauthorized and possibly unsafe ways. In this work we study these Prompt Injection Attacks (PIAs) on multiple families of LLMs on a Machine Translation task, focusing on the effects of model size on the attack success rates. We introduce a new benchmark data set and we discover that on multiple language pairs and injected prompts written in English, larger models under certain conditions may become more susceptible to successful attacks, an instance of the Inverse Scaling phenomenon (McKenzie et al., 2023). To our knowledge, this is the first work to study non-trivial LLM scaling behaviour in a multi-lingual setting.

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/acc_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/acc_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/acc_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/acc_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/acc_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/acc_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/acc_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/acc_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/accuracy_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/pipeline.jpeg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/mt_examples.jpeg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../..//opt/data/Projects/HuggingArxiv/paper_images/2403.09832/bleu_ru_en.jpg)

[Arxiv](https://arxiv.org/abs/2403.09832)