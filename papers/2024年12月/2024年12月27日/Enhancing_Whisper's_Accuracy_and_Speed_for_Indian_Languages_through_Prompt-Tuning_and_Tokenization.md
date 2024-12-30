# 通过提示调整与标记化来提升 Whisper 处理印度语言的准确性和速度

发布时间：2024年12月27日

`LLM应用` `语音识别` `印度语言`

> Enhancing Whisper's Accuracy and Speed for Indian Languages through Prompt-Tuning and Tokenization

# 摘要

> 自动语音识别近来因 Whisper 等大型基础模型而有了重大进展。然而，这些模型在低资源语言（比如印度语言）中常常表现欠佳。本文探索了两种新颖的方法来提升 Whisper 在印度语言中的多语言语音识别性能。其一，我们提议采用带有语言家族信息的提示调整，这能增强 Whisper 在语言相似语言中的准确性。其二，我们引入了一种新型标记器，减少了生成的标记数量，进而加快了 Whisper 的推理速度。我们大量的实验表明，标记器大幅缩短了推理时间，而提示调整提高了包括小、中、大等各种 Whisper 模型规模的准确性。总之，这些技术在最优 WER 和推理速度之间达成了平衡。

> Automatic speech recognition has recently seen a significant advancement with large foundational models such as Whisper. However, these models often struggle to perform well in low-resource languages, such as Indian languages. This paper explores two novel approaches to enhance Whisper's multilingual speech recognition performance in Indian languages. First, we propose prompt-tuning with language family information, which enhances Whisper's accuracy in linguistically similar languages. Second, we introduce a novel tokenizer that reduces the number of generated tokens, thereby accelerating Whisper's inference speed. Our extensive experiments demonstrate that the tokenizer significantly reduces inference time, while prompt-tuning enhances accuracy across various Whisper model sizes, including Small, Medium, and Large. Together, these techniques achieve a balance between optimal WER and inference speed.

[Arxiv](https://arxiv.org/abs/2412.19785)