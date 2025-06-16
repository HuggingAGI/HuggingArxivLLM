# # KokushiMD-10：评估大型语言模型在十个日本国家医疗执照考试中的基准测试

发布时间：2025年06月08日

`LLM应用

摘要中提到的论文讨论了大型语言模型在医学领域的应用，特别是评估它们在多模态和多语言环境下的表现。研究者构建了一个新的基准测试 KokushiMD-10，用于评估现有模型在医疗推理中的能力，并通过实验展示了当前模型的不足。这属于应用层面的研究，因为它是在特定领域（医学）中应用LLMs，并评估其效果。` `医学AI`

> KokushiMD-10: Benchmark for Evaluating Large Language Models on Ten Japanese National Healthcare Licensing Examinations

# 摘要

> # 摘要
近期，大型语言模型（LLMs）在医学执照考试中展现了显著表现。然而，对于各类医疗角色，尤其是在高风险临床场景中的全面评估，仍是一项挑战。现有的基准测试通常基于文本，以英语为中心，并主要关注药物领域，这限制了它们评估更广泛医疗知识和多模态推理的能力。

为了解决这些局限性，我们引入了 KokushiMD-10，这是首个基于十种日本国家医疗执照考试构建的多模态基准。该基准涵盖了多个领域，包括医学、牙科、护理、药学和相关健康职业。它包含超过 11588 个真实考试问题，融入了临床图像和专家注释的推理，以评估文本和视觉推理能力。

我们对包括 GPT-4o、Claude 3.5 和 Gemini 在内的 30 多个最先进的 LLM 进行了基准测试，涵盖文本和图像两种设置。尽管取得了令人鼓舞的结果，但没有一个模型能够在所有领域一致地达到及格线，突显了医学 AI 领域持续存在的挑战。

KokushiMD-10 为评估和推进以推理为中心的多语言和多模态临床任务中的医学 AI 提供了一个全面且语言基础的资源。


> Recent advances in large language models (LLMs) have demonstrated notable performance in medical licensing exams. However, comprehensive evaluation of LLMs across various healthcare roles, particularly in high-stakes clinical scenarios, remains a challenge. Existing benchmarks are typically text-based, English-centric, and focus primarily on medicines, which limits their ability to assess broader healthcare knowledge and multimodal reasoning. To address these gaps, we introduce KokushiMD-10, the first multimodal benchmark constructed from ten Japanese national healthcare licensing exams. This benchmark spans multiple fields, including Medicine, Dentistry, Nursing, Pharmacy, and allied health professions. It contains over 11588 real exam questions, incorporating clinical images and expert-annotated rationales to evaluate both textual and visual reasoning. We benchmark over 30 state-of-the-art LLMs, including GPT-4o, Claude 3.5, and Gemini, across both text and image-based settings. Despite promising results, no model consistently meets passing thresholds across domains, highlighting the ongoing challenges in medical AI. KokushiMD-10 provides a comprehensive and linguistically grounded resource for evaluating and advancing reasoning-centric medical AI across multilingual and multimodal clinical tasks.

[Arxiv](https://arxiv.org/abs/2506.11114)