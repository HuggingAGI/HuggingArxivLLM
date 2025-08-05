# <翻译失败>

发布时间：2025年08月04日

`LLM理论` `语音技术`

> I Have No Mouth, and I Must Rhyme: Uncovering Internal Phonetic Representations in LLaMA 3.2

# 摘要

> 大型语言模型擅长语音任务（如押韵），无需显式语音或听觉基础。本研究探讨了erb|Llama-3.2-1B-Instruct|如何表示基于标记的语音信息。研究发现，Llama采用了丰富的内部音素模型来完成语音任务，并在潜在空间中形成了高级音素组织结构。我们还发现了一个在押韵任务中起关键作用的“音素移动头”。通过可视化这个头的输出空间，我们发现Llama学习的元音模型与人类标准国际音标元音图谱相似，尽管它从未接受过直接监督来完成这一任务。

> Large language models demonstrate proficiency on phonetic tasks, such as rhyming, without explicit phonetic or auditory grounding. In this work, we investigate how \verb|Llama-3.2-1B-Instruct| represents token-level phonetic information. Our results suggest that Llama uses a rich internal model of phonemes to complete phonetic tasks. We provide evidence for high-level organization of phoneme representations in its latent space. In doing so, we also identify a ``phoneme mover head" which promotes phonetic information during rhyming tasks. We visualize the output space of this head and find that, while notable differences exist, Llama learns a model of vowels similar to the standard IPA vowel chart for humans, despite receiving no direct supervision to do so.

[Arxiv](https://arxiv.org/abs/2508.02527)