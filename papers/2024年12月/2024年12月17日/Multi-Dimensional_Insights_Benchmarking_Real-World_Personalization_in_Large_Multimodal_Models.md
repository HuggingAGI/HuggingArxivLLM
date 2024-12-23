# 多维度洞察：为大型多模态模型中的现实世界个性化设定基准

发布时间：2024年12月17日

`LLM应用` `多模态模型` `评估基准`

> Multi-Dimensional Insights: Benchmarking Real-World Personalization in Large Multimodal Models

# 摘要

> 在迅速发展的大型多模态模型（LMMs）领域，各种具备出色能力的模型纷纷涌现。然而，现有的基准无法全面、客观且准确地评估 LMMs 在现实场景中是否契合人类的多元需求。为填补这一空缺，我们推出了多维洞察（MDI）基准，其中包含超过 500 张涵盖人类生活六种常见场景的图像。尤为值得一提的是，MDI 基准相较现有评估具有两大显著优势：（1）每张图像都配有两类问题：简单问题用于评估模型对图像的理解，复杂问题用于衡量模型超越基础内容进行分析和推理的能力。（2）考虑到不同年龄组的人在面对相同场景时有着不同的需求和视角，我们的基准将问题划分为三个年龄类别：年轻人、中年人、老年人。如此设计能够对 LMMs 满足不同年龄组偏好和需求的能力进行细致评估。凭借 MDI 基准，像 GPT-4o 这样的强大模型在与年龄相关的任务上实现了 79％的准确率，这表明现有的 LMMs 在应对现实应用方面仍有很大的提升空间。展望未来，我们预期 MDI 基准将为 LMMs 中的现实世界个性化对齐开辟新的道路。MDI 基准数据和评估代码可在 https://mdi-benchmark.github.io/ 获得。

> The rapidly developing field of large multimodal models (LMMs) has led to the emergence of diverse models with remarkable capabilities. However, existing benchmarks fail to comprehensively, objectively and accurately evaluate whether LMMs align with the diverse needs of humans in real-world scenarios. To bridge this gap, we propose the Multi-Dimensional Insights (MDI) benchmark, which includes over 500 images covering six common scenarios of human life. Notably, the MDI-Benchmark offers two significant advantages over existing evaluations: (1) Each image is accompanied by two types of questions: simple questions to assess the model's understanding of the image, and complex questions to evaluate the model's ability to analyze and reason beyond basic content. (2) Recognizing that people of different age groups have varying needs and perspectives when faced with the same scenario, our benchmark stratifies questions into three age categories: young people, middle-aged people, and older people. This design allows for a detailed assessment of LMMs' capabilities in meeting the preferences and needs of different age groups. With MDI-Benchmark, the strong model like GPT-4o achieve 79% accuracy on age-related tasks, indicating that existing LMMs still have considerable room for improvement in addressing real-world applications. Looking ahead, we anticipate that the MDI-Benchmark will open new pathways for aligning real-world personalization in LMMs. The MDI-Benchmark data and evaluation code are available at https://mdi-benchmark.github.io/

[Arxiv](https://arxiv.org/abs/2412.12606)