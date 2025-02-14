# # **SB-Bench：大型多模态模型的刻板印象偏见基准测试**

发布时间：2025年02月12日

`LLM应用` `AI公平性` `社会责任`

> SB-Bench: Stereotype Bias Benchmark for Large Multimodal Models

# 摘要

> 大型多模态模型中的刻板印象偏见延续了对社会有害的偏见，削弱了AI应用的公平性。随着LMMs影响力增强，解决刻板印象、有害生成和现实场景中的模糊假设偏见成为当务之急。然而，现有评估数据集缺乏多样性和依赖合成图像，导致现实视觉环境下偏见评估存在空白。为解决此问题，我们推出刻板印象偏见基准（SB-bench），这是迄今最全面的框架，通过非合成图像评估涵盖九个类别的刻板印象偏见。SB-bench通过精心策划的视觉情景评估LMMs，挑战其对视觉刻板印象的准确推理能力。它提供了一个强大的评估框架，包含现实视觉样本、图像变体和多项选择题格式。通过基于视觉的查询分离视觉和文本偏见，SB-bench能够精确评估模型在不同难度水平上的推理能力。通过对开源和闭源LMMs的严格测试，SB-bench为评估LMMs在关键社会维度上的刻板印象偏见提供系统化方法。这一基准测试是迈向促进AI公平性、减少偏见的重要一步，为构建公平和社会责任的LMMs奠定基础。我们的代码和数据集已公开发布。

> Stereotype biases in Large Multimodal Models (LMMs) perpetuate harmful societal prejudices, undermining the fairness and equity of AI applications. As LMMs grow increasingly influential, addressing and mitigating inherent biases related to stereotypes, harmful generations, and ambiguous assumptions in real-world scenarios has become essential. However, existing datasets evaluating stereotype biases in LMMs often lack diversity and rely on synthetic images, leaving a gap in bias evaluation for real-world visual contexts. To address this, we introduce the Stereotype Bias Benchmark (SB-bench), the most comprehensive framework to date for assessing stereotype biases across nine diverse categories with non-synthetic images. SB-bench rigorously evaluates LMMs through carefully curated, visually grounded scenarios, challenging them to reason accurately about visual stereotypes. It offers a robust evaluation framework featuring real-world visual samples, image variations, and multiple-choice question formats. By introducing visually grounded queries that isolate visual biases from textual ones, SB-bench enables a precise and nuanced assessment of a model's reasoning capabilities across varying levels of difficulty. Through rigorous testing of state-of-the-art open-source and closed-source LMMs, SB-bench provides a systematic approach to assessing stereotype biases in LMMs across key social dimensions. This benchmark represents a significant step toward fostering fairness in AI systems and reducing harmful biases, laying the groundwork for more equitable and socially responsible LMMs. Our code and dataset are publicly available.

[Arxiv](https://arxiv.org/abs/2502.08779)