# QAVA：与查询无关的视觉攻击方法，针对大型视觉-语言模型

发布时间：2025年04月15日

`LLM应用

这篇论文探讨了针对大型视觉语言模型（LVLMs）的对抗攻击方法，特别是无查询视觉攻击（QAVA），属于模型应用层面的研究，因此归类为LLM应用。` `计算机视觉` `网络安全`

> QAVA: Query-Agnostic Visual Attack to Large Vision-Language Models

# 摘要

> 在视觉问答（VQA）等多模态任务中，针对特定图像和问题的对抗攻击会让大型视觉语言模型（LVLMs）出错。然而，同一张图片可能对应多个问题，LVLMs在面对被特定问题攻击的对抗图像时，仍可能正确回答其他问题。为此，我们提出了无查询视觉攻击（QAVA），旨在生成稳健的对抗示例，让模型对任何未指定的问题都给出错误答案。与传统专注于特定图像和问题的对抗攻击相比，QAVA在问题未知时大幅提升了攻击效果，其表现可与针对已知问题的攻击相媲美。这项研究扩展了LVLMs在实际应用中视觉对抗攻击的范围，揭示了此前被忽视的漏洞，特别是在视觉对抗威胁方面。代码已开源，地址为https://github.com/btzyd/qava。

> In typical multimodal tasks, such as Visual Question Answering (VQA), adversarial attacks targeting a specific image and question can lead large vision-language models (LVLMs) to provide incorrect answers. However, it is common for a single image to be associated with multiple questions, and LVLMs may still answer other questions correctly even for an adversarial image attacked by a specific question. To address this, we introduce the query-agnostic visual attack (QAVA), which aims to create robust adversarial examples that generate incorrect responses to unspecified and unknown questions. Compared to traditional adversarial attacks focused on specific images and questions, QAVA significantly enhances the effectiveness and efficiency of attacks on images when the question is unknown, achieving performance comparable to attacks on known target questions. Our research broadens the scope of visual adversarial attacks on LVLMs in practical settings, uncovering previously overlooked vulnerabilities, particularly in the context of visual adversarial threats. The code is available at https://github.com/btzyd/qava.

[Arxiv](https://arxiv.org/abs/2504.11038)