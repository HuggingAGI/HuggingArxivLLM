# MELT：迈向利用大型语言模型内置知识实现多模态情感数据自动标注

发布时间：2025年05月30日

`LLM应用` `语音处理` `人工智能`

> MELT: Towards Automated Multimodal Emotion Data Annotation by Leveraging LLM Embedded Knowledge

# 摘要

> 尽管语音情感识别 (SER) 在深度学习领域取得了显著进展，但标注仍然是一个重大挑战。人工标注不仅成本高昂，且容易出现不一致：标注者偏好各异，可能缺乏必要上下文知识，导致标签多样且不准确。与此同时，大型语言模型 (LLMs) 已成为标注文本数据的可扩展替代方案。然而，LLMs 在无需人工监督下进行情感语音数据标注的潜力尚未得到充分研究。为解决这些问题，我们应用 GPT-4o 对从情景喜剧《老友记》收集的多模态数据集进行标注，仅使用文本提示作为输入。通过精心设计的结构化文本提示，我们的方法充分利用了 GPT-4o 在训练过程中积累的知识，展示了其在无需直接访问多模态输入的情况下生成准确且上下文相关的标注的能力。因此，我们提出了完全由 GPT-4o 标注的多模态情感数据集 MELT。通过微调四个自监督学习 (SSL) 主干网络并在情感数据集上评估语音情感识别性能，我们证明了 MELT 的有效性。此外，我们的主观实验结果表明，在语音情感识别任务上有一致的性能提升。

> Although speech emotion recognition (SER) has advanced significantly with deep learning, annotation remains a major hurdle. Human annotation is not only costly but also subject to inconsistencies annotators often have different preferences and may lack the necessary contextual knowledge, which can lead to varied and inaccurate labels. Meanwhile, Large Language Models (LLMs) have emerged as a scalable alternative for annotating text data. However, the potential of LLMs to perform emotional speech data annotation without human supervision has yet to be thoroughly investigated. To address these problems, we apply GPT-4o to annotate a multimodal dataset collected from the sitcom Friends, using only textual cues as inputs. By crafting structured text prompts, our methodology capitalizes on the knowledge GPT-4o has accumulated during its training, showcasing that it can generate accurate and contextually relevant annotations without direct access to multimodal inputs. Therefore, we propose MELT, a multimodal emotion dataset fully annotated by GPT-4o. We demonstrate the effectiveness of MELT by fine-tuning four self-supervised learning (SSL) backbones and assessing speech emotion recognition performance across emotion datasets. Additionally, our subjective experiments\' results demonstrate a consistence performance improvement on SER.

[Arxiv](https://arxiv.org/abs/2505.24493)