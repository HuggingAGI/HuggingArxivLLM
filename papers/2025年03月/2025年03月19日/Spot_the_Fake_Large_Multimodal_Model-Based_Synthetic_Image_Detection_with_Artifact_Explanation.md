# Spot the Fake：基于大模型的合成图像检测与伪影解释

发布时间：2025年03月19日

`LLM应用` `图像处理` `计算机视觉`

> Spot the Fake: Large Multimodal Model-Based Synthetic Image Detection with Artifact Explanation

# 摘要

> 随着人工智能生成内容（AIGC）技术的迅猛发展，合成图像在日常生活中越来越普遍，这为真实性评估和检测带来了新的挑战。尽管现有方法在评估图像真实性和定位伪造方面具有有效性，但这些方法通常缺乏人类可解释性，并未能完全应对合成数据日益增长的复杂性。为了解决这些挑战，我们引入了FakeVLM，这是一个专门针对通用合成图像和深度伪造检测任务设计的大型多模态模型。FakeVLM不仅在区分真实与虚假图像方面表现出色，还能够提供清晰、自然语言描述的图像伪迹解释，从而增强了可解释性。此外，我们还推出了FakeClue，这是一个包含超过100,000张图像的综合数据集，涵盖七个类别，并以自然语言标注了细粒度的伪迹线索。FakeVLM的表现可与专家模型相媲美，同时无需额外的分类器，使其成为合成数据检测的 robust 解决方案。在多个数据集上的广泛评估证实了FakeVLM在真实性和伪迹解释任务中的优越性，为合成图像检测树立了新的基准。数据集和代码将在以下链接中发布：https://github.com/opendatalab/FakeVLM。

> With the rapid advancement of Artificial Intelligence Generated Content (AIGC) technologies, synthetic images have become increasingly prevalent in everyday life, posing new challenges for authenticity assessment and detection. Despite the effectiveness of existing methods in evaluating image authenticity and locating forgeries, these approaches often lack human interpretability and do not fully address the growing complexity of synthetic data. To tackle these challenges, we introduce FakeVLM, a specialized large multimodal model designed for both general synthetic image and DeepFake detection tasks. FakeVLM not only excels in distinguishing real from fake images but also provides clear, natural language explanations for image artifacts, enhancing interpretability. Additionally, we present FakeClue, a comprehensive dataset containing over 100,000 images across seven categories, annotated with fine-grained artifact clues in natural language. FakeVLM demonstrates performance comparable to expert models while eliminating the need for additional classifiers, making it a robust solution for synthetic data detection. Extensive evaluations across multiple datasets confirm the superiority of FakeVLM in both authenticity classification and artifact explanation tasks, setting a new benchmark for synthetic image detection. The dataset and code will be released in: https://github.com/opendatalab/FakeVLM.

[Arxiv](https://arxiv.org/abs/2503.14905)