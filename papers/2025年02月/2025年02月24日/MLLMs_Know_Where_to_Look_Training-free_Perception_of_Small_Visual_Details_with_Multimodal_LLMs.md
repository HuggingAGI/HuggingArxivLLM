# 多模态大语言模型懂得关注重点：无需额外训练的微小视觉细节感知

发布时间：2025年02月24日

`LLM应用` `计算机视觉` `视觉问答`

> MLLMs Know Where to Look: Training-free Perception of Small Visual Details with Multimodal LLMs

# 摘要

> 近年来，多模态大型语言模型（MLLMs）在视觉识别任务中取得了飞速进展。鉴于其可能被整合到许多关键应用中，理解它们在视觉感知方面的局限性非常重要。本研究探讨了MLLMs在回答图像相关问题时，是否能像识别大物体一样有效感知小视觉细节。我们发现，其性能对问题中视觉主体的大小极为敏感，进一步通过干预研究证实了这一影响实际上是因果关系。接下来，我们研究了MLLMs在回答视觉问题时的注意力机制，并惊人地发现，即使它们给出错误答案时，也始终知道该关注何处。基于这些发现，我们提出了一种无需训练的视觉干预方法，利用任何MLLM自身的内部知识，以注意力图和梯度图的形式，来增强其对小视觉细节的感知。我们在两个广泛使用的MLLM和七个视觉问答基准上评估了我们的方法，并证明它们在无需任何训练的情况下显著提高了MLLMs的准确性。我们的结果揭示了将MLLMs应用于涉及小细节的视觉识别任务的风险，并表明利用模型内部状态进行视觉干预是一个有前景的方向来缓解这一风险。

> Multimodal Large Language Models (MLLMs) have experienced rapid progress in visual recognition tasks in recent years. Given their potential integration into many critical applications, it is important to understand the limitations of their visual perception. In this work, we study whether MLLMs can perceive small visual details as effectively as large ones when answering questions about images. We observe that their performance is very sensitive to the size of the visual subject of the question, and further show that this effect is in fact causal by conducting an intervention study. Next, we study the attention patterns of MLLMs when answering visual questions, and intriguingly find that they consistently know where to look, even when they provide the wrong answer. Based on these findings, we then propose training-free visual intervention methods that leverage the internal knowledge of any MLLM itself, in the form of attention and gradient maps, to enhance its perception of small visual details. We evaluate our proposed methods on two widely-used MLLMs and seven visual question answering benchmarks and show that they can significantly improve MLLMs' accuracy without requiring any training. Our results elucidate the risk of applying MLLMs to visual recognition tasks concerning small details and indicate that visual intervention using the model's internal state is a promising direction to mitigate this risk.

[Arxiv](https://arxiv.org/abs/2502.17422)