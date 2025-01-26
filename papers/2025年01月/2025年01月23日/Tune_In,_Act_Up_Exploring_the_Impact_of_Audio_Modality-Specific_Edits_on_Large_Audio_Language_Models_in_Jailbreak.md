# Tune In, Act Up: 音频模态特定编辑对大型音频语言模型越狱影响的探索

发布时间：2025年01月23日

`LLM应用

**理由**：这篇论文主要探讨了多模态大型语言模型（特别是大型音频语言模型，LALMs）在音频编辑下的安全性和鲁棒性。研究聚焦于如何通过音频编辑影响模型的推理过程，并提出了相应的工具和数据集来评估模型的性能。这属于对大型语言模型在实际应用中的安全性和性能的研究，因此归类为LLM应用。` `音频处理`

> Tune In, Act Up: Exploring the Impact of Audio Modality-Specific Edits on Large Audio Language Models in Jailbreak

# 摘要

> 大型语言模型（LLMs）在多种自然语言处理任务中展现了卓越的零-shot性能。通过集成多模态编码器，LLMs的能力得以扩展，从而催生了能够处理视觉、音频和文本的多模态大型语言模型。然而，这些能力也带来了严重的安全隐患，因为这些模型可能被操纵，通过越狱生成有害或不适当的内容。尽管已有大量研究探讨了特定模态输入编辑对文本型LLMs和大型视觉语言模型在越狱中的影响，但音频特定编辑对大型音频语言模型（LALMs）的影响仍鲜有研究。为此，本文通过探究音频特定编辑如何影响LALMs在越狱中的推理，填补了这一研究空白。我们推出了音频编辑工具箱（AET），支持音调调整、词语强调和噪声注入等音频模态编辑，并构建了编辑音频数据集（EADs），作为全面的音频越狱基准。此外，我们对当前最先进的LALMs进行了广泛评估，以测试它们在不同音频编辑下的鲁棒性。这项研究为未来探索LALMs安全中的音频模态交互奠定了基础。

> Large Language Models (LLMs) demonstrate remarkable zero-shot performance across various natural language processing tasks. The integration of multimodal encoders extends their capabilities, enabling the development of Multimodal Large Language Models that process vision, audio, and text. However, these capabilities also raise significant security concerns, as these models can be manipulated to generate harmful or inappropriate content through jailbreak. While extensive research explores the impact of modality-specific input edits on text-based LLMs and Large Vision-Language Models in jailbreak, the effects of audio-specific edits on Large Audio-Language Models (LALMs) remain underexplored. Hence, this paper addresses this gap by investigating how audio-specific edits influence LALMs inference regarding jailbreak. We introduce the Audio Editing Toolbox (AET), which enables audio-modality edits such as tone adjustment, word emphasis, and noise injection, and the Edited Audio Datasets (EADs), a comprehensive audio jailbreak benchmark. We also conduct extensive evaluations of state-of-the-art LALMs to assess their robustness under different audio edits. This work lays the groundwork for future explorations on audio-modality interactions in LALMs security.

[Arxiv](https://arxiv.org/abs/2501.13772)