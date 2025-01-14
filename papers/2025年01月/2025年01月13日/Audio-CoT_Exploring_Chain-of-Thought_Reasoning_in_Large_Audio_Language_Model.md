# Audio-CoT: 大型音频语言模型中的思维链推理探索

发布时间：2025年01月13日

`LLM应用

**理由**：该论文主要探讨了如何将思维链（CoT）推理引入大型音频-语言模型（LALMs），以提升其在听觉模态中的推理能力。这属于对现有大型语言模型（LLM）的应用和扩展，特别是在音频和语言结合的领域。因此，将其分类为“LLM应用”是合适的。` `音频处理` `语音识别`

> Audio-CoT: Exploring Chain-of-Thought Reasoning in Large Audio Language Model

# 摘要

> 大型音频-语言模型（LALMs）在语音识别和音频字幕生成等任务中表现出色，但其在解决复杂问题中的推理能力仍有待探索。本研究首次将思维链（CoT）推理引入LALMs，以提升其在听觉模态中的推理能力。我们评估了多种CoT方法，分析了它们在声音、音乐和语音领域的信息提取与推理任务中的表现。结果显示，CoT方法在简单和中等难度任务上表现优异，但在复杂任务中，推理链可能导致模型混淆，而非提升准确性。此外，推理路径长度与准确性呈正相关，表明扩展推理在高级指令跟随和推理中的潜力。本研究不仅揭示了CoT在增强LALM推理能力方面的潜力，还指出了关键限制，并为未来研究指明了方向。

> Large Audio-Language Models (LALMs) have demonstrated remarkable performance in tasks involving audio perception and understanding, such as speech recognition and audio captioning. However, their reasoning capabilities - critical for solving complex real-world problems - remain underexplored. In this work, we conduct the first exploration into integrating Chain-of-Thought (CoT) reasoning into LALMs to enhance their reasoning ability across auditory modalities. We evaluate representative CoT methods, analyzing their performance in both information extraction and reasoning tasks across sound, music, and speech domains. Our findings reveal that CoT methods significantly improve performance on easy and medium tasks but encounter challenges with hard tasks, where reasoning chains can confuse the model rather than improve accuracy. Additionally, we identify a positive correlation between reasoning path length and accuracy, demonstrating the potential of scaling inference for advanced instruction-following and reasoning. This study not only highlights the promise of CoT in enhancing LALM reasoning capabilities but also identifies key limitations and provides actionable directions for future research.

[Arxiv](https://arxiv.org/abs/2501.07246)