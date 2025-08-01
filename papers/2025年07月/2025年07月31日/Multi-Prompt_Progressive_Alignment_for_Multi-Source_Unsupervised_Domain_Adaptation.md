# 多提示渐进对齐的多源无监督领域适应方法

发布时间：2025年07月31日

`LLM应用

论文摘要：像CLIP这样的大型视觉语言模型凭借其强大的零样本泛化能力，已成为无监督领域适应（UDA）的理想基础。现有先进方法通常利用CLIP为目标域生成伪标签，并通过微调模型学习领域不变特征。然而，这些方法试图一次性利用所有伪标签数据对齐源域与目标域，这种做法在面对噪声大、难以分类的样本时往往力不从心，导致错误传播和特征学习效果不佳。在多源场景下，这一问题更加突出，因多个源域间存在的领域差距和噪声水平差异进一步加剧了对齐过程的不稳定性。

为了解决这一难题，我们提出了一种渐进式对齐策略，用于将CLIP适应于无标签的下游任务。我们的方法首先在目标域样本的高置信度子集上训练模型，使其能够从最可靠的数据中学习到良好的对齐表示。随着训练的深入，模型逐渐纳入更多具有挑战性的样本，引导其在不被初始标签噪声淹没的情况下完善理解。这种渐进式方法不仅有效缓解了确认偏见，还促进了更稳健的收敛，使得学习真正领域不变的特征成为可能。

我们将这种方法命名为MP²A，并在三个流行的UDA基准测试中进行了验证，包括ImageCLEF、Office-Home以及最具挑战性的DomainNet。实验结果表明，与最新的基于CLIP的多源UDA方法相比，MP²A实现了最先进的性能，充分证明了我们方法的有效性。` `计算机视觉` `无监督学习`

> Multi-Prompt Progressive Alignment for Multi-Source Unsupervised Domain Adaptation

# 摘要

> 像CLIP这样的大型视觉语言模型凭借其强大的零样本泛化能力，已成为无监督领域适应（UDA）的理想基础。现有先进方法通常利用CLIP为目标域生成伪标签，并通过微调模型学习领域不变特征。然而，这些方法试图一次性利用所有伪标签数据对齐源域与目标域，这种做法在面对噪声大、难以分类的样本时往往力不从心，导致错误传播和特征学习效果不佳。在多源场景下，这一问题更加突出，因多个源域间存在的领域差距和噪声水平差异进一步加剧了对齐过程的不稳定性。

为了解决这一难题，我们提出了一种渐进式对齐策略，用于将CLIP适应于无标签的下游任务。我们的方法首先在目标域样本的高置信度子集上训练模型，使其能够从最可靠的数据中学习到良好的对齐表示。随着训练的深入，模型逐渐纳入更多具有挑战性的样本，引导其在不被初始标签噪声淹没的情况下完善理解。这种渐进式方法不仅有效缓解了确认偏见，还促进了更稳健的收敛，使得学习真正领域不变的特征成为可能。

我们将这种方法命名为MP²A，并在三个流行的UDA基准测试中进行了验证，包括ImageCLEF、Office-Home以及最具挑战性的DomainNet。实验结果表明，与最新的基于CLIP的多源UDA方法相比，MP²A实现了最先进的性能，充分证明了我们方法的有效性。

> Large Vision-Language Models like CLIP have become a powerful foundation for Unsupervised Domain Adaptation due to their strong zero-shot generalization. State-of-the-art methods typically leverage CLIP to generate pseudo-labels for the target domain, then fine-tune the model to learn domain-invariant features. However, these methods attempt to align source and target domains using all pseudo-labeled data simultaneously. This one-shot alignment struggles with noisy, hard-to-classify samples, leading to error propagation and suboptimal feature learning. The problem is even more amplified in the multi-source scenario, where diverse domain gaps and varying noise levels across multiple source domains further destabilize the alignment process. To address this issue, in this work, we propose a progressive alignment strategy for adapting CLIP to unlabeled downstream task. Our method begins by training the model on a high-confidence subset of target samples, allowing it to first learn a well-aligned representation from the most reliable data. As training progresses, it gradually incorporates more challenging samples, guiding the model to refine its understanding without being overwhelmed by initial label noise. This progressive approach effectively mitigates confirmation bias and promotes a more robust convergence, allowing for the learning of genuinely domain-invariant features. We name our approach MP^2A and test it on three popular UDA benchmarks, namely ImageCLEF, Office-Home, and the most challenging DomainNet. Experiments showcase that MP^2A achieves state-of-the-art performance when compared with most recent CLIP-based MS-UDA approaches, demonstrating the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2507.23373)