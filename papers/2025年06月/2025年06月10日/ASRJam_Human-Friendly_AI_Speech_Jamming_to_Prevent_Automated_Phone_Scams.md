# ASRJam：以人为本的AI语音干扰，防范自动电话诈骗

发布时间：2025年06月10日

`LLM应用` `网络安全`

> ASRJam: Human-Friendly AI Speech Jamming to Prevent Automated Phone Scams

# 摘要

> 大型语言模型（LLMs）与文本转语音（TTS）和自动语音识别（ASR）相结合，正越来越多地被用于自动化语音钓鱼（vishing）诈骗。这些系统不仅可扩展，而且极具说服力，构成了重大的安全威胁。我们发现，诈骗流程中ASR转录环节是最薄弱的环节，并提出了ASRJam，一个主动防御框架。通过向受害者音频中注入对抗性扰动，ASRJam能够有效干扰攻击者的ASR，从而打破诈骗的反馈循环，而不会影响人类通话者的正常沟通。尽管先前的对抗性音频技术通常令人不快且不适合实时使用，我们还提出了EchoGuard，一种新型干扰器。EchoGuard利用对ASR破坏性但对人类可接受的自然失真（如混响和回声），在不损害人类听觉体验的同时有效干扰ASR。为了全面评估EchoGuard的有效性和实用性，我们进行了39人的用户研究，将其与三种最先进的攻击进行了对比测试。研究结果显示，EchoGuard在整体效用方面表现最佳，实现了ASR干扰效果与人类听觉体验的最佳平衡。

> Large Language Models (LLMs), combined with Text-to-Speech (TTS) and Automatic Speech Recognition (ASR), are increasingly used to automate voice phishing (vishing) scams. These systems are scalable and convincing, posing a significant security threat. We identify the ASR transcription step as the most vulnerable link in the scam pipeline and introduce ASRJam, a proactive defence framework that injects adversarial perturbations into the victim's audio to disrupt the attacker's ASR. This breaks the scam's feedback loop without affecting human callers, who can still understand the conversation. While prior adversarial audio techniques are often unpleasant and impractical for real-time use, we also propose EchoGuard, a novel jammer that leverages natural distortions, such as reverberation and echo, that are disruptive to ASR but tolerable to humans. To evaluate EchoGuard's effectiveness and usability, we conducted a 39-person user study comparing it with three state-of-the-art attacks. Results show that EchoGuard achieved the highest overall utility, offering the best combination of ASR disruption and human listening experience.

[Arxiv](https://arxiv.org/abs/2506.11125)