# OlympicArena：超级智能AI多学科认知推理能力的基准测试平台

发布时间：2024年06月18日

`LLM应用

这篇论文介绍了OlympicArena，一个大型测试平台，用于评估大型语言模型（LLMs）和大型多模态模型（LMMs）的认知推理能力。它特别关注了这些模型在解决复杂问题和科学发现中的应用，这是LLM应用领域的一个重要方面。论文通过详细的问题设计和评估方法，探讨了模型的性能和局限性，这直接关联到LLM在实际应用中的表现和改进方向。因此，将其归类为LLM应用是合适的。` `人工智能`

> OlympicArena: Benchmarking Multi-discipline Cognitive Reasoning for Superintelligent AI

# 摘要

> 随着大型语言模型（LLMs）和大型多模态模型（LMMs）的进步，人工智能（AI）的发展迅速加速，开始展现出在问题解决和科学发现（AI4Science）中曾独属于人类的认知推理能力。为了全面检验这些模型的认知推理能力，我们推出了OlympicArena，一个包含11,163个双语问题的大型测试平台，涵盖文本和图文混合模态，涉及七个领域和62个国际奥林匹克竞赛，确保无数据泄露。我们认为，奥林匹克竞赛问题的复杂性和跨学科性使其成为评估AI认知推理能力的理想选择，这对于解决科学难题和推动发现至关重要。我们不仅通过答案准确性评估了模型在各学科的表现，还从多角度进行了深入的实验和分析，探讨了模型的认知推理能力、模态适应性以及过程级评估的重要性。评估结果显示，即便是最先进的模型如GPT-4o，总体准确率也仅为39.97%，凸显了AI在复杂推理和多模态整合方面的当前局限。通过OlympicArena，我们的目标是推动AI向超级智能迈进，使其能够应对更复杂的科学挑战。同时，我们提供了一套全面的AI研究支持资源，包括基准数据集、开源标注平台、评估工具和自动提交排行榜。

> The evolution of Artificial Intelligence (AI) has been significantly accelerated by advancements in Large Language Models (LLMs) and Large Multimodal Models (LMMs), gradually showcasing potential cognitive reasoning abilities in problem-solving and scientific discovery (i.e., AI4Science) once exclusive to human intellect. To comprehensively evaluate current models' performance in cognitive reasoning abilities, we introduce OlympicArena, which includes 11,163 bilingual problems across both text-only and interleaved text-image modalities. These challenges encompass a wide range of disciplines spanning seven fields and 62 international Olympic competitions, rigorously examined for data leakage. We argue that the challenges in Olympic competition problems are ideal for evaluating AI's cognitive reasoning due to their complexity and interdisciplinary nature, which are essential for tackling complex scientific challenges and facilitating discoveries. Beyond evaluating performance across various disciplines using answer-only criteria, we conduct detailed experiments and analyses from multiple perspectives. We delve into the models' cognitive reasoning abilities, their performance across different modalities, and their outcomes in process-level evaluations, which are vital for tasks requiring complex reasoning with lengthy solutions. Our extensive evaluations reveal that even advanced models like GPT-4o only achieve a 39.97% overall accuracy, illustrating current AI limitations in complex reasoning and multimodal integration. Through the OlympicArena, we aim to advance AI towards superintelligence, equipping it to address more complex challenges in science and beyond. We also provide a comprehensive set of resources to support AI research, including a benchmark dataset, an open-source annotation platform, a detailed evaluation tool, and a leaderboard with automatic submission features.

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/logo.jpg)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/overview.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/x1.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/x2.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/x3.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/x4.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/x5.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/x6.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/x7.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/x8.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/annotation_page.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/json_example.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/x9.png)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/error_case1_fig1.jpeg)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/error_case2_fig1.jpeg)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/error_case2_fig2.jpeg)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/error_case3_fig1.jpeg)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/error_case4_fig1.jpeg)

![OlympicArena：超级智能AI多学科认知推理能力的基准测试平台](../../../paper_images/2406.12753/error_case7_fig1.png)

[Arxiv](https://arxiv.org/abs/2406.12753)