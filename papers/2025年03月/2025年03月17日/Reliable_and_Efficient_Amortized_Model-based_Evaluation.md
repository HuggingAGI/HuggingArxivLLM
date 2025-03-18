# # 基于模型的 amortized 评估：可靠且高效

发布时间：2025年03月17日

`LLM应用` `人工智能`

> Reliable and Efficient Amortized Model-based Evaluation

# 摘要

> 在语言模型的开发和部署阶段进行全面评估至关重要。这些模型不仅具备数学推理、法律支持、医疗诊断等多种功能，同时也伴随种族偏见、毒性内容、虚假信息等安全风险。跨多种基准测试的平均分数为我们提供了一个实践指导信号，帮助我们更好地应用这些语言模型。然而，目前全面评估的成本较高，原因在于需要处理大量基准测试问题，使得频繁评估难以实现。一种流行的降本尝试是计算基准测试子集的平均分数，但这种方法通常无法准确衡量语言模型的性能，因为平均分数往往与基准测试子集问题的难度相关。项目反应理论 (IRT) 通过严格控制问题难度，提供了一个可靠的测量方法。然而，问题难度的估算成本较高。我们训练了一个能够根据问题内容预测其难度的模型，从而以较低的成本实现可靠的测量。此外，我们利用这一难度预测器，通过训练一个可以根据难度级别生成问题的生成器，进一步提高评估效率。这个生成器在自适应测试中至关重要，它可以根据当前对大语言模型性能的评估，自适应地选择具有信息量的问题，而不是随机选择基准测试问题。在 22 个常见自然语言基准测试和 172 个语言模型上的实验表明，与当前常见做法相比，该方法更具可靠性和效率。

> Comprehensive evaluations of language models (LM) during both development and deployment phases are necessary because these models possess numerous capabilities (e.g., mathematical reasoning, legal support, or medical diagnostic) as well as safety risks (e.g., racial bias, toxicity, or misinformation). The average score across a wide range of benchmarks provides a signal that helps guide the use of these LMs in practice. Currently, holistic evaluations are costly due to the large volume of benchmark questions, making frequent evaluations impractical. A popular attempt to lower the cost is to compute the average score on a subset of the benchmark. This approach, unfortunately, often renders an unreliable measure of LM performance because the average score is often confounded with the difficulty of the questions in the benchmark subset. Item response theory (IRT) was designed to address this challenge, providing a reliable measurement by careful controlling for question difficulty. Unfortunately, question difficulty is expensive to estimate. Facing this challenge, we train a model that predicts question difficulty from its content, enabling a reliable measurement at a fraction of the cost. In addition, we leverage this difficulty predictor to further improve the evaluation efficiency through training a question generator given a difficulty level. This question generator is essential in adaptive testing, where, instead of using a random subset of the benchmark questions, informative questions are adaptively chosen based on the current estimation of LLM performance. Experiments on 22 common natural language benchmarks and 172 LMs show that this approach is more reliable and efficient compared to current common practice.

[Arxiv](https://arxiv.org/abs/2503.13335)