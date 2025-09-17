# 评估大型语言模型在代码翻译任务中的表现：提示语言与提示设计的影响

发布时间：2025年09月16日

`LLM应用` `工业与制造`

> Evaluating Large Language Models for Code Translation: Effects of Prompt Language and Prompt Design

# 摘要

> 大型语言模型（LLMs）在自动化源代码翻译领域展现出巨大潜力，而这一能力对软件迁移、维护及互操作性而言至关重要。然而，目前关于模型选择、提示设计及提示语言如何影响多编程语言翻译质量的对比研究仍较为匮乏。为此，本研究针对C++、Java、Python和C#间的代码翻译，对最先进的LLMs开展了系统性实证评估，并以传统方法（TransCoder）作为基线进行对比。研究采用BLEU和CodeBLEU指标，在两种提示风格（简洁指令与详细规范）及两种提示语言（英语与阿拉伯语）下，量化分析了语法保真度与结构正确性，并针对语言对进行了方向感知的评估。实验结果显示，详细提示在各模型及翻译方向上均能带来稳定提升，且英语提示的性能比阿拉伯语高出13-15%。其中，性能最优的模型在Java转C#、Python转C++等较难的语言对上实现了最高的CodeBLEU分数。评估结果显示，在所有基准测试中，各LLM的性能均优于TransCoder。这些结果不仅证实了精心设计提示与选择提示语言的重要价值，更为软件现代化及跨语言互操作性提供了实用指导。

> Large language models (LLMs) have shown promise for automated source-code translation, a capability critical to software migration, maintenance, and interoperability. Yet comparative evidence on how model choice, prompt design, and prompt language shape translation quality across multiple programming languages remains limited. This study conducts a systematic empirical assessment of state-of-the-art LLMs for code translation among C++, Java, Python, and C#, alongside a traditional baseline (TransCoder). Using BLEU and CodeBLEU, we quantify syntactic fidelity and structural correctness under two prompt styles (concise instruction and detailed specification) and two prompt languages (English and Arabic), with direction-aware evaluation across language pairs. Experiments show that detailed prompts deliver consistent gains across models and translation directions, and English prompts outperform Arabic by 13-15%. The top-performing model attains the highest CodeBLEU on challenging pairs such as Java to C# and Python to C++. Our evaluation shows that each LLM outperforms TransCoder across the benchmark. These results demonstrate the value of careful prompt engineering and prompt language choice, and provide practical guidance for software modernization and cross-language interoperability.

[Arxiv](https://arxiv.org/abs/2509.12973)