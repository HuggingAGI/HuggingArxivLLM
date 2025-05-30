# 阿拉伯语AI指纹：大规模语言模型文本的风格分析与检测

发布时间：2025年05月29日

`LLM应用` `信息检测`

> The Arabic AI Fingerprint: Stylometric Analysis and Detection of Large Language Models Text

# 摘要

> 大型语言模型（LLMs）在生成类人文本方面展现出前所未有的能力，这对教育、社交媒体和学术界等关键领域构成了重大的信息完整性挑战。这些模型能够发起复杂的虚假信息活动，破坏医疗指导，并促进有针对性的宣传。这种挑战在资源较少的语言（如阿拉伯语）中尤为严峻。本文对阿拉伯语机器生成文本进行了全面研究，探讨了多种生成策略（仅基于标题的生成、内容感知生成和文本润色）在学术和社会媒体领域中不同模型架构（ALLaM、Jais、Llama 和 GPT-4）上的表现。我们的文体学分析揭示了在这些不同背景下区分人写与机器生成阿拉伯语文本的独特语言模式。尽管LLMs具备类人特性，我们证明它们在阿拉伯语输出中会产生可检测的特征，且这些特征在不同语境下表现出显著的领域特定差异。基于这些发现，我们开发了基于BERT的检测模型，在正式语境下实现了卓越性能（最高达99.9%的F1分数），并在不同模型架构上保持了强大的精确度。我们的跨领域分析证实了先前文献中报告的泛化挑战。据我们所知，这项研究是迄今为止对阿拉伯语机器生成文本最全面的调查，独特地结合了多种提示生成方法、多样化的模型架构以及跨不同文本领域的深入文体学分析，为开发稳健、语言学知识丰富的检测系统奠定了基础，这对于维护阿拉伯语环境中的信息完整性至关重要。

> Large Language Models (LLMs) have achieved unprecedented capabilities in generating human-like text, posing subtle yet significant challenges for information integrity across critical domains, including education, social media, and academia, enabling sophisticated misinformation campaigns, compromising healthcare guidance, and facilitating targeted propaganda. This challenge becomes severe, particularly in under-explored and low-resource languages like Arabic. This paper presents a comprehensive investigation of Arabic machine-generated text, examining multiple generation strategies (generation from the title only, content-aware generation, and text refinement) across diverse model architectures (ALLaM, Jais, Llama, and GPT-4) in academic, and social media domains. Our stylometric analysis reveals distinctive linguistic patterns differentiating human-written from machine-generated Arabic text across these varied contexts. Despite their human-like qualities, we demonstrate that LLMs produce detectable signatures in their Arabic outputs, with domain-specific characteristics that vary significantly between different contexts. Based on these insights, we developed BERT-based detection models that achieved exceptional performance in formal contexts (up to 99.9\% F1-score) with strong precision across model architectures. Our cross-domain analysis confirms generalization challenges previously reported in the literature. To the best of our knowledge, this work represents the most comprehensive investigation of Arabic machine-generated text to date, uniquely combining multiple prompt generation methods, diverse model architectures, and in-depth stylometric analysis across varied textual domains, establishing a foundation for developing robust, linguistically-informed detection systems essential for preserving information integrity in Arabic-language contexts.

[Arxiv](https://arxiv.org/abs/2505.23276)