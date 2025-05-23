# MAPLE：多示例自适应伪标签方法在上下文学习中的应用

发布时间：2025年05月22日

`LLM理论

摘要讨论了In-Context Learning (ICL) 的方法，特别是多示例ICL，并提出了一个新的框架MAPLE来解决标注数据获取成本高的问题。这属于大型语言模型的理论和训练方法的改进，因此归类为LLM理论。` `机器学习`

> MAPLE: Many-Shot Adaptive Pseudo-Labeling for In-Context Learning

# 摘要

> In-Context Learning (ICL) 赋能大型语言模型 (LLMs) 处理多样化任务，通过整合多个输入输出示例（即演示）作为 LLMs 的输入。最近，LLMs 扩展上下文窗口的进展推动了多示例 ICL 的发展，该方法利用数百个演示，优于依赖较少示例的少样本 ICL。然而，这种方法常受限于获取大量标注数据的高成本。为应对这一挑战，我们提出 Many-Shot Adaptive Pseudo-LabEling（即 MAPLE），这是一种基于影响的多示例 ICL 新型框架，利用伪标签样本弥补标注信息的不足。首先，我们识别出一小部分具有影响力的未标注样本，并通过查询 LLMs 对其进行伪标签标注。这些伪标签样本随后被自适应地筛选并针对每个测试查询进行定制，作为输入以提升多示例 ICL 的性能，而无需显著的标注成本。在真实世界数据集上的广泛实验验证了我们框架的有效性，展示了其在有限标注数据下提升 LLM 适应性和性能的能力。


> In-Context Learning (ICL) empowers Large Language Models (LLMs) to tackle diverse tasks by incorporating multiple input-output examples, known as demonstrations, into the input of LLMs. More recently, advancements in the expanded context windows of LLMs have led to many-shot ICL, which uses hundreds of demonstrations and outperforms few-shot ICL, which relies on fewer examples. However, this approach is often hindered by the high cost of obtaining large amounts of labeled data. To address this challenge, we propose Many-Shot Adaptive Pseudo-LabEling, namely MAPLE, a novel influence-based many-shot ICL framework that utilizes pseudo-labeled samples to compensate for the lack of label information. We first identify a subset of impactful unlabeled samples and perform pseudo-labeling on them by querying LLMs. These pseudo-labeled samples are then adaptively selected and tailored to each test query as input to improve the performance of many-shot ICL, without significant labeling costs. Extensive experiments on real-world datasets demonstrate the effectiveness of our framework, showcasing its ability to enhance LLM adaptability and performance with limited labeled data.

[Arxiv](https://arxiv.org/abs/2505.16225)