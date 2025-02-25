# # Emoti-Attack：零扰动对抗攻击：通过表情符号序列对NLP系统进行零扰动攻击

发布时间：2025年02月24日

`LLM理论

理由：这篇论文探讨了大型语言模型在对抗攻击中的脆弱性，并提出了一种新的攻击方法Emoji-Attack，属于模型安全性和理论分析的范畴。` `信息安全`

> Emoti-Attack: Zero-Perturbation Adversarial Attacks on NLP Systems via Emoji Sequences

# 摘要

> 深度神经网络（DNN）在自然语言处理（NLP）领域大放异彩，催生了像ChatGPT这样广为人知的应用。然而，这些模型易受对抗攻击的弱点仍是亟待解决的难题。与图像等连续域不同，文本的离散性使得任何微小的改动都可能被人类轻易察觉。这种离散性也给传统优化技术的应用带来了障碍，因为文本是非可微的。此前的研究主要集中在字符级、单词级、句子级和多级对抗攻击方法上，但这些方法都因效率低下或易于察觉而难以令人满意。
    本研究提出了一种全新的对抗攻击方法——Emoji-Attack，该方法巧妙利用emoji操控来制造细微却有效的扰动。与传统的字符级和单词级策略不同，Emoji-Attack将emoji作为独立的攻击层面，从而在不显著改变文本的情况下实现更不易察觉的修改。这一创新方法在以往研究中鲜有探索，通常emoji插入被视为字符级攻击的延伸。实验结果表明，Emoji-Attack在大模型和小模型上均展现出强大的攻击效果，成为提升NLP系统对抗鲁棒性的有力技术。

> Deep neural networks (DNNs) have achieved remarkable success in the field of natural language processing (NLP), leading to widely recognized applications such as ChatGPT. However, the vulnerability of these models to adversarial attacks remains a significant concern. Unlike continuous domains like images, text exists in a discrete space, making even minor alterations at the sentence, word, or character level easily perceptible to humans. This inherent discreteness also complicates the use of conventional optimization techniques, as text is non-differentiable. Previous research on adversarial attacks in text has focused on character-level, word-level, sentence-level, and multi-level approaches, all of which suffer from inefficiency or perceptibility issues due to the need for multiple queries or significant semantic shifts.
  In this work, we introduce a novel adversarial attack method, Emoji-Attack, which leverages the manipulation of emojis to create subtle, yet effective, perturbations. Unlike character- and word-level strategies, Emoji-Attack targets emojis as a distinct layer of attack, resulting in less noticeable changes with minimal disruption to the text. This approach has been largely unexplored in previous research, which typically focuses on emoji insertion as an extension of character-level attacks. Our experiments demonstrate that Emoji-Attack achieves strong attack performance on both large and small models, making it a promising technique for enhancing adversarial robustness in NLP systems.

[Arxiv](https://arxiv.org/abs/2502.17392)