# ConspEmoLLM-v2：一款稳健且稳定的模型，旨在检测情感转化的阴谋论

发布时间：2025年05月20日

`LLM应用` `信息检测`

> ConspEmoLLM-v2: A robust and stable model to detect sentiment-transformed conspiracy theories

# 摘要

> 大型语言模型（LLMs）在带来诸多优势的同时，也可能引发危害，例如自动生成包括阴谋论在内的错误信息。更令人担忧的是，LLMs 还能通过改变文本特征（如将阴谋论中的负面情绪转化为更积极的语气）来“伪装”阴谋论。尽管已有研究提出了多种自动检测阴谋论的方法，但这些方法通常依赖于人工编写的文本进行训练，而这些文本的特征可能与 LLM 生成的文本大相径庭。此外，包括先前提出的 ConspEmoLLM 在内的多个阴谋论检测模型，严重依赖于人类编写阴谋内容中的典型情感特征。因此，经过伪装的内容可能能够逃避检测。为了解决这些问题，我们开发了增强版的 ConDID 阴谋论检测数据集——ConDID-v2。该数据集在人类编写的阴谋推文中补充了由 LLM 重写的版本，以降低原文的负面情绪。我们通过结合人工和 LLM 基于评估验证了重写推文的质量。随后，我们利用 ConDID-v2 训练了 ConspEmoLLM 的增强版——ConspEmoLLM-v2。实验结果表明，ConspEmoLLM-v2 在 ConDID 中的原始人类编写内容上保持或超越了 ConspEmoLLM 的性能，并且在应用于 ConDID-v2 中情绪转化的推文时，显著优于 ConspEmoLLM 以及其他多个基线模型。该项目将在 https://github.com/lzw108/ConspEmoLLM 上开放。

> Despite the many benefits of large language models (LLMs), they can also cause harm, e.g., through automatic generation of misinformation, including conspiracy theories. Moreover, LLMs can also ''disguise'' conspiracy theories by altering characteristic textual features, e.g., by transforming their typically strong negative emotions into a more positive tone. Although several studies have proposed automated conspiracy theory detection methods, they are usually trained using human-authored text, whose features can vary from LLM-generated text. Furthermore, several conspiracy detection models, including the previously proposed ConspEmoLLM, rely heavily on the typical emotional features of human-authored conspiracy content. As such, intentionally disguised content may evade detection. To combat such issues, we firstly developed an augmented version of the ConDID conspiracy detection dataset, ConDID-v2, which supplements human-authored conspiracy tweets with versions rewritten by an LLM to reduce the negativity of their original sentiment. The quality of the rewritten tweets was verified by combining human and LLM-based assessment. We subsequently used ConDID-v2 to train ConspEmoLLM-v2, an enhanced version of ConspEmoLLM. Experimental results demonstrate that ConspEmoLLM-v2 retains or exceeds the performance of ConspEmoLLM on the original human-authored content in ConDID, and considerably outperforms both ConspEmoLLM and several other baselines when applied to sentiment-transformed tweets in ConDID-v2. The project will be available at https://github.com/lzw108/ConspEmoLLM.

[Arxiv](https://arxiv.org/abs/2505.14917)