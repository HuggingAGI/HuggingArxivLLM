# 框架表示假说：多令牌 LLM 的可解释性与概念引导的文本生成

发布时间：2024年12月10日

`LLM理论` `人工智能`

> Frame Representation Hypothesis: Multi-Token LLM Interpretability and Concept-Guided Text Generation

# 摘要

> 可解释性是增进对大型语言模型（LLMs）信任的关键难题，其根源在于从模型参数中提取推理的复杂性。我们提出了框架表示假说，这是一个基于线性表示假说（LRH）的理论坚实的框架，通过对多标记词建模来解释和控制LLMs。此前的研究探索了LRH以将LLM的表示与语言概念相联系，但局限于单标记分析。鉴于多数单词由多个标记构成，我们把LRH拓展到多标记词，从而能够在任何具有数千个概念的文本数据上运用。为此，我们认为单词可被理解为框架，即能更好捕捉标记与单词关系的有序向量序列。而后，概念能够表示为共享同一概念的单词框架的平均值。我们通过Top-k概念引导解码来展示这些工具，它能够直观地利用所选概念来引导文本生成。我们在Llama 3.1、Gemma 2和Phi 3系列上验证了上述想法，揭示了性别和语言偏见，暴露了有害内容，同时也展现了对其进行纠正的潜力，从而造就更安全、更透明的LLMs。代码可在https://github.com/phvv-me/frame-representation-hypothesis.git获取。

> Interpretability is a key challenge in fostering trust for Large Language Models (LLMs), which stems from the complexity of extracting reasoning from model's parameters. We present the Frame Representation Hypothesis, a theoretically robust framework grounded in the Linear Representation Hypothesis (LRH) to interpret and control LLMs by modeling multi-token words. Prior research explored LRH to connect LLM representations with linguistic concepts, but was limited to single token analysis. As most words are composed of several tokens, we extend LRH to multi-token words, thereby enabling usage on any textual data with thousands of concepts. To this end, we propose words can be interpreted as frames, ordered sequences of vectors that better capture token-word relationships. Then, concepts can be represented as the average of word frames sharing a common concept. We showcase these tools through Top-k Concept-Guided Decoding, which can intuitively steer text generation using concepts of choice. We verify said ideas on Llama 3.1, Gemma 2, and Phi 3 families, demonstrating gender and language biases, exposing harmful content, but also potential to remediate them, leading to safer and more transparent LLMs. Code is available at https://github.com/phvv-me/frame-representation-hypothesis.git

[Arxiv](https://arxiv.org/abs/2412.07334)