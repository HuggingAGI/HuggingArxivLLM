# 专注主题，而非语言：LLMs如何跨语言解析在线移民话题

发布时间：2025年08月08日

`LLM应用` `社会科学`

> Learning the Topic, Not the Language: How LLMs Classify Online Immigration Discourse Across Languages

# 摘要

> 大型语言模型（LLMs）正在通过实现可扩展、精确的分析能力，改变社会科学领域的研究。LLMs的适应性引发了一个问题：通过在几种语言上进行微调所获得的知识，能否转移到仅在预训练阶段出现的未见过的语言？为了探讨这一点，我们在单语、双语或多语数据集上对轻量级LLaMA 3.2-3B模型进行微调，以分类来自X/Twitter的13种语言的移民相关推文，这是一个以两极化、文化特定的讨论为特点的领域。我们评估了仅进行少量语言特定微调是否能够实现跨语言主题检测，以及添加目标语言是否能够纠正预训练偏见。结果显示，经过一种或两种语言微调的LLMs，能够可靠地对未见过语言中的移民相关内容进行分类。然而，识别一条推文是支持还是反对移民，则受益于多语言微调。预训练偏见倾向于主导语言，但即使是在微调过程中对代表性不足的语言进行少量接触（仅占原始预训练标记量的【数学公式】），也能带来显著的提升。这些发现挑战了跨语言掌握需要广泛多语言训练的假设：有限的语言覆盖范围足以实现主题级别的泛化，而结构偏见可以通过轻量级干预得到纠正。通过发布4位量化的LoRA微调模型，我们提供了一个开源且可重复的替代方案，相较于OpenAI GPT-4o模型，推理速度提升了35倍，而成本仅为后者的0.00000989%。这使得研究更具扩展性和包容性。

> Large language models (LLMs) are transforming social-science research by enabling scalable, precise analysis. Their adaptability raises the question of whether knowledge acquired through fine-tuning in a few languages can transfer to unseen languages that only appeared during pre-training. To examine this, we fine-tune lightweight LLaMA 3.2-3B models on monolingual, bilingual, or multilingual data sets to classify immigration-related tweets from X/Twitter across 13 languages, a domain characterised by polarised, culturally specific discourse. We evaluate whether minimal language-specific fine-tuning enables cross-lingual topic detection and whether adding targeted languages corrects pre-training biases. Results show that LLMs fine-tuned in one or two languages can reliably classify immigration-related content in unseen languages. However, identifying whether a tweet expresses a pro- or anti-immigration stance benefits from multilingual fine-tuning. Pre-training bias favours dominant languages, but even minimal exposure to under-represented languages during fine-tuning (as little as $9.62\times10^{-11}$ of the original pre-training token volume) yields significant gains. These findings challenge the assumption that cross-lingual mastery requires extensive multilingual training: limited language coverage suffices for topic-level generalisation, and structural biases can be corrected with lightweight interventions. By releasing 4-bit-quantised, LoRA fine-tuned models, we provide an open-source, reproducible alternative to proprietary LLMs that delivers 35 times faster inference at just 0.00000989% of the dollar cost of the OpenAI GPT-4o model, enabling scalable, inclusive research.

[Arxiv](https://arxiv.org/abs/2508.06435)