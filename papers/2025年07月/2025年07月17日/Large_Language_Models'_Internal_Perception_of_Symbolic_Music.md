# 大型语言模型如何感知符号音乐

发布时间：2025年07月17日

`LLM应用` `音乐生成`

> Large Language Models' Internal Perception of Symbolic Music

# 摘要

> 大型语言模型（LLMs）在处理自然语言中的文本关系方面表现出色，并且在扩展到编码或数学等其他符号领域方面也显示出潜力。然而，它们在隐式建模符号音乐方面的程度仍然研究不足。本文通过从描述音乐流派和风格组合的文本提示生成符号音乐数据，研究了LLMs如何表示音乐概念，并通过识别和生成任务评估其效用。我们生成了一个LLM生成的MIDI文件数据集，无需依赖显式的音乐训练。然后，我们完全基于这个LLM生成的MIDI数据集训练神经网络，并进行流派和风格分类以及旋律补全，将其性能与现有模型进行基准测试。我们的结果显示，LLMs可以从文本中推断出基本的音乐结构和时间关系，既突显了它们隐式编码音乐模式的潜力，也揭示了由于缺乏显式音乐上下文而产生的局限性，从而阐明了它们在符号音乐生成方面的能力。

> Large language models (LLMs) excel at modeling relationships between strings in natural language and have shown promise in extending to other symbolic domains like coding or mathematics. However, the extent to which they implicitly model symbolic music remains underexplored. This paper investigates how LLMs represent musical concepts by generating symbolic music data from textual prompts describing combinations of genres and styles, and evaluating their utility through recognition and generation tasks. We produce a dataset of LLM-generated MIDI files without relying on explicit musical training. We then train neural networks entirely on this LLM-generated MIDI dataset and perform genre and style classification as well as melody completion, benchmarking their performance against established models. Our results demonstrate that LLMs can infer rudimentary musical structures and temporal relationships from text, highlighting both their potential to implicitly encode musical patterns and their limitations due to a lack of explicit musical context, shedding light on their generative capabilities for symbolic music.

[Arxiv](https://arxiv.org/abs/2507.12808)