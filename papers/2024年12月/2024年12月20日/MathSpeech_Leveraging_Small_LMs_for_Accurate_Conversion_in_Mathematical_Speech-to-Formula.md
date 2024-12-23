# MathSpeech：借助小型语言模型实现数学语音到公式的精准转换

发布时间：2024年12月20日

`LLM应用`

> MathSpeech: Leveraging Small LMs for Accurate Conversion in Mathematical Speech-to-Formula

# 摘要

> 在诸如数学讲座或研究报告等各类学术和专业场景中，常常需要口头表述数学表达式。然而，在没有视觉辅助的情况下朗读数学表达式，会极大地阻碍理解，尤其对于听力障碍者或因语言障碍依赖字幕的人而言。比如，当演讲者朗读欧拉公式时，当前的自动语音识别（ASR）模型往往会生成冗长且易出错的文本描述（如，e 的 i x 次幂等于 x 的余弦加上 i $	extit{side}$ of x），而非简洁的 $\LaTeX{}$ 格式（即，$ e^{ix} = \cos(x) + i\sin(x) $），这不利于清晰的理解与交流。为解决此问题，我们推出了 MathSpeech，这是一个创新的管道，它将 ASR 模型与小型语言模型（sLMs）相结合，以纠正数学表达式中的错误，并将口头表述准确转化为结构化的 $\LaTeX{}$ 表示。通过对从讲座录音中获取的新数据集进行评估，MathSpeech 展现出了与领先的商业大型语言模型（LLMs）相媲美的 $\LaTeX{}$ 生成能力，同时借助了仅 120M 参数的微调小型语言模型。具体来说，在 $\LaTeX{}$ 翻译的 CER、BLEU 和 ROUGE 分数方面，MathSpeech 表现出比 GPT-4o 更为出色的能力。我们发现 CER 从 0.390 降至 0.298，并且 ROUGE/BLEU 分数高于 GPT-4o。

> In various academic and professional settings, such as mathematics lectures or research presentations, it is often necessary to convey mathematical expressions orally. However, reading mathematical expressions aloud without accompanying visuals can significantly hinder comprehension, especially for those who are hearing-impaired or rely on subtitles due to language barriers. For instance, when a presenter reads Euler's Formula, current Automatic Speech Recognition (ASR) models often produce a verbose and error-prone textual description (e.g., e to the power of i x equals cosine of x plus i $\textit{side}$ of x), instead of the concise $\LaTeX{}$ format (i.e., $ e^{ix} = \cos(x) + i\sin(x) $), which hampers clear understanding and communication. To address this issue, we introduce MathSpeech, a novel pipeline that integrates ASR models with small Language Models (sLMs) to correct errors in mathematical expressions and accurately convert spoken expressions into structured $\LaTeX{}$ representations. Evaluated on a new dataset derived from lecture recordings, MathSpeech demonstrates $\LaTeX{}$ generation capabilities comparable to leading commercial Large Language Models (LLMs), while leveraging fine-tuned small language models of only 120M parameters. Specifically, in terms of CER, BLEU, and ROUGE scores for $\LaTeX{}$ translation, MathSpeech demonstrated significantly superior capabilities compared to GPT-4o. We observed a decrease in CER from 0.390 to 0.298, and higher ROUGE/BLEU scores compared to GPT-4o.

[Arxiv](https://arxiv.org/abs/2412.15655)