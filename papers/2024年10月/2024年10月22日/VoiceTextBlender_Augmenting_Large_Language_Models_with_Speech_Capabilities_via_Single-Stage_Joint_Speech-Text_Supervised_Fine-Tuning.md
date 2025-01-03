# VoiceTextBlender：通过单阶段联合语音-文本监督微调，为大型语言模型赋予语音能力

发布时间：2024年10月22日

`LLM应用

理由：这篇论文主要讨论了如何通过增强大型语言模型（LLMs）的语音能力来推动SpeechLMs的发展，并提出了具体的优化方法（如低秩适应LoRA和联合语音-文本SFT）。这些内容属于LLM在实际应用中的改进和优化，因此分类为LLM应用。` `语音处理`

> VoiceTextBlender: Augmenting Large Language Models with Speech Capabilities via Single-Stage Joint Speech-Text Supervised Fine-Tuning

# 摘要

> 近期研究通过增强LLMs的语音能力，推动了SpeechLMs的发展。早期SpeechLMs专注于单轮语音问答（QA），用户输入包括语音上下文和文本问题。最新研究将其扩展至多轮对话，尽管通常需要复杂、多阶段的监督微调（SFT）和多样化数据。SpeechLMs的另一大挑战是灾难性遗忘——即针对语音任务优化的模型在纯文本任务上性能显著下降。为解决这些问题，我们提出了一种基于LLM骨干低秩适应（LoRA）的单阶段联合语音-文本SFT方法。我们的联合SFT将纯文本SFT数据与三种语音相关数据结合：语音识别与翻译、语音QA及混合模态SFT。与之前7B或13B参数的SpeechLMs相比，我们的3B模型在各种语音基准测试中表现卓越，同时保留了纯文本任务的能力。此外，我们的模型还展现出处理多轮、混合模态输入等新任务的新兴能力。

> Recent studies have augmented large language models (LLMs) with speech capabilities, leading to the development of speech language models (SpeechLMs). Earlier SpeechLMs focused on single-turn speech-based question answering (QA), where user input comprised a speech context and a text question. More recent studies have extended this to multi-turn conversations, though they often require complex, multi-stage supervised fine-tuning (SFT) with diverse data. Another critical challenge with SpeechLMs is catastrophic forgetting-where models optimized for speech tasks suffer significant degradation in text-only performance. To mitigate these issues, we propose a novel single-stage joint speech-text SFT approach on the low-rank adaptation (LoRA) of the LLM backbone. Our joint SFT combines text-only SFT data with three types of speech-related data: speech recognition and translation, speech-based QA, and mixed-modal SFT. Compared to previous SpeechLMs with 7B or 13B parameters, our 3B model demonstrates superior performance across various speech benchmarks while preserving the original capabilities on text-only tasks. Furthermore, our model shows emergent abilities of effectively handling previously unseen prompts and tasks, including multi-turn, mixed-modal inputs.

[Arxiv](https://arxiv.org/abs/2410.17485)