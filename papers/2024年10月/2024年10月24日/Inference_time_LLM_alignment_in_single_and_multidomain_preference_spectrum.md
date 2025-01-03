# 单域与多域偏好谱中的推理时间 LLM 对齐

发布时间：2024年10月24日

`LLM应用

理由：这篇论文提出了一种推理时模型对齐方法，通过学习偏好维度的编码表示（对齐向量，AV）来动态调整大型语言模型（LLM）的行为。这种方法旨在解决现有对齐方法的资源密集和耗时问题，并在医疗、法律和金融等专业领域中展示了其实际应用潜力。论文的核心在于如何在实际应用中更高效地调整和控制LLM的输出，因此属于LLM应用的范畴。`

> Inference time LLM alignment in single and multidomain preference spectrum

# 摘要

> # 摘要
对齐大型语言模型（LLM）以应对主观性和细微偏好，需要足够的灵活性和控制，但这一过程往往资源密集且耗时。现有的训练时对齐方法在调整时需完全重新训练，而推理时方法则通常需在每一步推理中访问奖励模型。为解决这些限制，我们提出了一种推理时模型对齐方法，通过学习偏好维度的编码表示——	extit{对齐向量}（AV），实现动态调整模型行为。AV通过从对齐模型中减去基础模型计算得出，类似于模型编辑，使得在推理过程中通过简单线性操作即可调整模型行为。尽管偏好维度可涵盖多种粒度，本文重点展示了医疗、法律和金融三个专业领域中的逐步响应水平，凸显了其实际应用潜力。这一新范式在推理中引入了可调节的偏好旋钮，用户可据此定制LLM输出，同时推理成本较提示工程方法降低一半。此外，我们发现AV在同一模型的不同微调阶段间可转移，展现了其灵活性。AV还支持多领域、多样化偏好的快速对齐，速度比重新训练方法快12倍。

> Aligning Large Language Models (LLM) to address subjectivity and nuanced preference levels requires adequate flexibility and control, which can be a resource-intensive and time-consuming procedure. Existing training-time alignment methods require full re-training when a change is needed and inference-time ones typically require access to the reward model at each inference step. To address these limitations, we introduce inference-time model alignment method that learns encoded representations of preference dimensions, called \textit{Alignment Vectors} (AV). These representations are computed by subtraction of the base model from the aligned model as in model editing enabling dynamically adjusting the model behavior during inference through simple linear operations. Even though the preference dimensions can span various granularity levels, here we focus on three gradual response levels across three specialized domains: medical, legal, and financial, exemplifying its practical potential. This new alignment paradigm introduces adjustable preference knobs during inference, allowing users to tailor their LLM outputs while reducing the inference cost by half compared to the prompt engineering approach. Additionally, we find that AVs are transferable across different fine-tuning stages of the same model, demonstrating their flexibility. AVs also facilitate multidomain, diverse preference alignment, making the process 12x faster than the retraining approach.

[Arxiv](https://arxiv.org/abs/2410.19206)