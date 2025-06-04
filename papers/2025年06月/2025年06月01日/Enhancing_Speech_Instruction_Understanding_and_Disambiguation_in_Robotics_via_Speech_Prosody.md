# 利用语音韵律提升机器人语音指令的理解与歧义消除能力

发布时间：2025年06月01日

`Agent` `机器人` `语音识别`

> Enhancing Speech Instruction Understanding and Disambiguation in Robotics via Speech Prosody

# 摘要

> 要实现高效的人机协作，机器人必须能够准确理解并执行口语指令。传统方法依赖语音识别将语音转录为文本，但往往忽略了有助于澄清意图的语调线索。我们提出了一种创新方法，直接利用语音语调来推断并解析指令意图。通过上下文学习，将预测的意图整合到大语言模型中，以澄清并选择合适的任务计划。此外，我们还推出了首个用于机器人领域的模糊语音数据集，旨在推动语音澄清研究的发展。我们的方法在识别单次 utterance 中的引用意图方面达到了 95.79% 的准确率，并以 71.96% 的准确率确定了模糊指令的预期任务计划，这表明它有潜力显著提升人机交流的效果。

> Enabling robots to accurately interpret and execute spoken language instructions is essential for effective human-robot collaboration. Traditional methods rely on speech recognition to transcribe speech into text, often discarding crucial prosodic cues needed for disambiguating intent. We propose a novel approach that directly leverages speech prosody to infer and resolve instruction intent. Predicted intents are integrated into large language models via in-context learning to disambiguate and select appropriate task plans. Additionally, we present the first ambiguous speech dataset for robotics, designed to advance research in speech disambiguation. Our method achieves 95.79% accuracy in detecting referent intents within an utterance and determines the intended task plan of ambiguous instructions with 71.96% accuracy, demonstrating its potential to significantly improve human-robot communication.

[Arxiv](https://arxiv.org/abs/2506.02057)