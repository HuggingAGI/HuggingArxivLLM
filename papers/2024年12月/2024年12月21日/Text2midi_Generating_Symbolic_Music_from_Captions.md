# Text2midi：由标题生成符号音乐

发布时间：2024年12月21日

`LLM应用` `多模态生成`

> Text2midi: Generating Symbolic Music from Captions

# 摘要

> 本文介绍了 text2midi 这一能从文本描述生成 MIDI 文件的端到端模型。趁着多模态生成方法越来越受欢迎的势头，text2midi 充分借助了丰富的文本数据以及大型语言模型（LLMs）的成功。我们的端到端系统借助 LLMs 的能力，以 MIDI 文件的形式生成符号音乐。具体而言，我们用预训练的 LLM 编码器处理说明文字，然后让自回归变压器解码器以此为条件生成能精准反映所给描述的 MIDI 序列。这种直观且对用户友好的方法，让用户能通过文本提示生成音乐片段，大大简化了音乐创作流程。我们开展了全面的实证评估，涵盖了自动化和人工研究，结果显示我们的模型生成的 MIDI 文件质量上乘，确实能通过可能包含和弦、调式和节奏等音乐理论术语的文本说明进行控制。我们在演示页面（https://github.com/AMAAI-Lab/Text2midi）发布了代码和音乐样本，供用户与 text2midi 进行互动。

> This paper introduces text2midi, an end-to-end model to generate MIDI files from textual descriptions. Leveraging the growing popularity of multimodal generative approaches, text2midi capitalizes on the extensive availability of textual data and the success of large language models (LLMs). Our end-to-end system harnesses the power of LLMs to generate symbolic music in the form of MIDI files. Specifically, we utilize a pretrained LLM encoder to process captions, which then condition an autoregressive transformer decoder to produce MIDI sequences that accurately reflect the provided descriptions. This intuitive and user-friendly method significantly streamlines the music creation process by allowing users to generate music pieces using text prompts. We conduct comprehensive empirical evaluations, incorporating both automated and human studies, that show our model generates MIDI files of high quality that are indeed controllable by text captions that may include music theory terms such as chords, keys, and tempo. We release the code and music samples on our demo page (https://github.com/AMAAI-Lab/Text2midi) for users to interact with text2midi.

[Arxiv](https://arxiv.org/abs/2412.16526)