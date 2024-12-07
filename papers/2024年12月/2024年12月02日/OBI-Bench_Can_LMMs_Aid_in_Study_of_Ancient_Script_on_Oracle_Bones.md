# OBI-Bench：大型语言模型（LMMs）能否有助于对甲骨文上古代文字的研究？

发布时间：2024年12月02日

`LLM应用` `甲骨文研究` `古代语言研究`

> OBI-Bench: Can LMMs Aid in Study of Ancient Script on Oracle Bones?

# 摘要

> 我们推出了 OBI-Bench 这一综合性基准，旨在对大型多模态模型（LMMs）在整个甲骨文处理任务中的表现进行系统性评估，这些任务需要专家级的领域知识和审慎的认知能力。OBI-Bench 涵盖了 5523 个精心收集的、来源多样的图像，涉及五个关键领域的问题：识别、拼接、分类、检索和解密。这些图像涵盖了几个世纪的考古成果以及一线学者多年的研究，包含了从挖掘到合成的多阶段字体形态，如原始甲骨文、墨拓、甲骨碎片、裁剪的单个字符和手写字符。和现有的基准不同，OBI-Bench 专注于结合甲骨文特定知识的高级视觉感知与推理，让 LMMs 挑战类似于专家所面临的任务。对 6 个专有 LMMs 以及 17 个开源 LMMs 的评估凸显了 OBI-Bench 所带来的重大挑战和需求。即便最新版的 GPT-4o、Gemini 1.5 Pro 和 Qwen-VL-Max，在某些细粒度感知任务中仍远逊于普通人类。不过，它们在解密任务中的表现与未受训的人类相当，展现出在提供新的解读视角和产生创造性猜测方面的出色能力。我们期望 OBI-Bench 能助力社区开发针对古代语言研究的特定领域多模态基础模型，深入挖掘并增强 LMMs 这些尚未开发的潜力。

> We introduce OBI-Bench, a holistic benchmark crafted to systematically evaluate large multi-modal models (LMMs) on whole-process oracle bone inscriptions (OBI) processing tasks demanding expert-level domain knowledge and deliberate cognition. OBI-Bench includes 5,523 meticulously collected diverse-sourced images, covering five key domain problems: recognition, rejoining, classification, retrieval, and deciphering. These images span centuries of archaeological findings and years of research by front-line scholars, comprising multi-stage font appearances from excavation to synthesis, such as original oracle bone, inked rubbings, oracle bone fragments, cropped single character, and handprinted character. Unlike existing benchmarks, OBI-Bench focuses on advanced visual perception and reasoning with OBI-specific knowledge, challenging LMMs to perform tasks akin to those faced by experts. The evaluation of 6 proprietary LMMs as well as 17 open-source LMMs highlights the substantial challenges and demands posed by OBI-Bench. Even the latest versions of GPT-4o, Gemini 1.5 Pro, and Qwen-VL-Max are still far from public-level humans in some fine-grained perception tasks. However, they perform at a level comparable to untrained humans in deciphering task, indicating remarkable capabilities in offering new interpretative perspectives and generating creative guesses. We hope OBI-Bench can facilitate the community to develop domain-specific multi-modal foundation models towards ancient language research and delve deeper to discover and enhance these untapped potentials of LMMs.

[Arxiv](https://arxiv.org/abs/2412.01175)