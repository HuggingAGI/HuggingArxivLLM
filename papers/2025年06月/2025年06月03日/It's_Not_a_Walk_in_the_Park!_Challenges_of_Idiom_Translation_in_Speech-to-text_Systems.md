# 这不是件轻松的事！语音转文字系统中的习语翻译难题

发布时间：2025年06月03日

`LLM应用` `机器翻译`

> It's Not a Walk in the Park! Challenges of Idiom Translation in Speech-to-text Systems

# 摘要

> 习语是由一组词语组成的表达，其比喻意义无法通过单独理解每个词语得出。尽管现代机器翻译系统取得了显著进步，但习语的翻译仍然是一个重大挑战，尤其是对于语音到文本系统而言，相关研究更是明显不足。本文系统性地对比了习语翻译与传统新闻翻译在文本到文本机器翻译（MT）和语音到文本翻译（SLT）系统中的表现，涵盖两个语言对（德语到英语，俄语到英语）。我们比较了最先进的端到端SLT系统（SeamlessM4T SLT-to-text，Whisper Large v3）与MT系统（SeamlessM4T SLT-to-text，No Language Left Behind）、大型语言模型（DeepSeek，LLaMA）以及级联替代方案。研究发现，SLT系统在处理习语数据时表现明显下降，甚至在更高层次上也往往退化为字面翻译，而MT系统和大型语言模型则在习语处理方面表现更好。这些发现强调了针对习语的特定策略和改进SLT架构内部表示的需求。

> Idioms are defined as a group of words with a figurative meaning not deducible from their individual components. Although modern machine translation systems have made remarkable progress, translating idioms remains a major challenge, especially for speech-to-text systems, where research on this topic is notably sparse. In this paper, we systematically evaluate idiom translation as compared to conventional news translation in both text-to-text machine translation (MT) and speech-to-text translation (SLT) systems across two language pairs (German to English, Russian to English). We compare state-of-the-art end-to-end SLT systems (SeamlessM4T SLT-to-text, Whisper Large v3) with MT systems (SeamlessM4T SLT-to-text, No Language Left Behind), Large Language Models (DeepSeek, LLaMA) and cascaded alternatives. Our results reveal that SLT systems experience a pronounced performance drop on idiomatic data, often reverting to literal translations even in higher layers, whereas MT systems and Large Language Models demonstrate better handling of idioms. These findings underscore the need for idiom-specific strategies and improved internal representations in SLT architectures.

[Arxiv](https://arxiv.org/abs/2506.02995)