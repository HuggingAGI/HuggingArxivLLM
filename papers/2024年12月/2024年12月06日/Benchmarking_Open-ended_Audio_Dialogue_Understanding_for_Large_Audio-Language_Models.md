# 对大型音频语言模型的开放式音频对话理解进行基准测试

发布时间：2024年12月06日

`LLM应用` `语言模型`

> Benchmarking Open-ended Audio Dialogue Understanding for Large Audio-Language Models

# 摘要

> 大型音频语言模型（LALMs）已开启音频对话功能，音频对话即 LALMs 与人类之间的口语直接交流。像 GPT-4o 这样的最新进展，让 LALMs 能与人类进行来回的音频对话。这一进步不仅彰显了 LALMs 的潜力，还拓展了其在众多由音频对话支撑的实际场景中的应用范围。然而，尽管有这些进展，目前仍缺少一个全面的基准来衡量 LALMs 在开放式音频对话理解方面的表现。为填补这一空白，我们提出了音频对话理解基准（ADU-Bench），它由 4 个基准数据集构成。其在 3 种常见场景、12 项技能、9 种多语言以及 4 类歧义处理方面，对 LALMs 的开放式音频对话能力进行评估。值得一提的是，我们率先提出对音频对话中歧义处理的评估，这些歧义表达了在句子相同字面意义之外的不同意图，比如不同语调的“真的！？”。总之，ADU-Bench 涵盖了超过 20,000 个开放式音频对话，用于评估 LALMs。通过对 13 个 LALMs 开展的大量实验，我们的分析表明，现有 LALMs 的音频对话理解能力仍有很大的提升余地。特别是在数学符号和公式、理解人类行为（如角色扮演）、理解多种语言以及处理来自不同语音元素（如语调、停顿位置和同音词）的音频对话歧义等方面存在难题。

> Large Audio-Language Models (LALMs) have unclocked audio dialogue capabilities, where audio dialogues are a direct exchange of spoken language between LALMs and humans. Recent advances, such as GPT-4o, have enabled LALMs in back-and-forth audio dialogues with humans. This progression not only underscores the potential of LALMs but also broadens their applicability across a wide range of practical scenarios supported by audio dialogues. However, given these advancements, a comprehensive benchmark to evaluate the performance of LALMs in the open-ended audio dialogue understanding remains absent currently. To address this gap, we propose an Audio Dialogue Understanding Benchmark (ADU-Bench), which consists of 4 benchmark datasets. They assess the open-ended audio dialogue ability for LALMs in 3 general scenarios, 12 skills, 9 multilingual languages, and 4 categories of ambiguity handling. Notably, we firstly propose the evaluation of ambiguity handling in audio dialogues that expresses different intentions beyond the same literal meaning of sentences, e.g., "Really!?" with different intonations. In summary, ADU-Bench includes over 20,000 open-ended audio dialogues for the assessment of LALMs. Through extensive experiments conducted on 13 LALMs, our analysis reveals that there is still considerable room for improvement in the audio dialogue understanding abilities of existing LALMs. In particular, they struggle with mathematical symbols and formulas, understanding human behavior such as roleplay, comprehending multiple languages, and handling audio dialogue ambiguities from different phonetic elements, such as intonations, pause positions, and homophones.

[Arxiv](https://arxiv.org/abs/2412.05167)