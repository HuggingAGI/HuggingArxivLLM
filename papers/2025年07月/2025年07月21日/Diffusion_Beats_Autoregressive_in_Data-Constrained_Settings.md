# 扩散模型在数据受限的场景下优于自回归模型

发布时间：2025年07月21日

`LLM理论

摘要主要探讨了扩散式语言模型与自回归模型在数据受限情况下的性能对比，分析了扩散模型的优势及其背后的理论原因，属于LLM的理论研究。` `人工智能` `语言模型`

> Diffusion Beats Autoregressive in Data-Constrained Settings

# 摘要

> 自回归（AR）模型长期主导着大型语言模型领域，推动了各类任务的进展。最近，扩散式语言模型作为一种有前途的替代方案崭露头角，但它们相较于AR模型的优势仍待进一步探索。

本文系统研究了在数据受限的训练场景下——即训练过程中需要反复使用有限数据——发现当计算资源充足但数据稀缺时，扩散模型显著优于AR模型。扩散模型能更好地利用重复数据，实现更低的验证损失和更优的下游性能。

我们将其优势解释为隐式数据增强：与AR模型固定的左到右分解方式不同，遮罩扩散模型使模型接触到了更多样化的token顺序和预测任务。我们发现了扩散模型的新扩展规律，并推导出了一个闭合形式的临界计算阈值表达式，该阈值标志着扩散模型开始超越AR模型的性能。

这些结果表明，当数据而非计算成为瓶颈时，扩散模型为标准的AR范式提供了一个极具吸引力的替代方案。我们的代码可在以下链接获取：https://diffusion-scaling.github.io。


> Autoregressive (AR) models have long dominated the landscape of large language models, driving progress across a wide range of tasks. Recently, diffusion-based language models have emerged as a promising alternative, though their advantages over AR models remain underexplored. In this paper, we systematically study masked diffusion models in data-constrained settings-where training involves repeated passes over limited data-and find that they significantly outperform AR models when compute is abundant but data is scarce. Diffusion models make better use of repeated data, achieving lower validation loss and superior downstream performance. We interpret this advantage as implicit data augmentation: masked diffusion exposes the model to a diverse distribution of token orderings and prediction tasks, unlike AR's fixed left-to-right factorization. We find new scaling laws for diffusion models and derive a closed-form expression for the critical compute threshold at which diffusion begins to outperform AR. These results suggest that when data, not compute, is the bottleneck, diffusion models offer a compelling alternative to the standard AR paradigm. Our code is available at: https://diffusion-scaling.github.io.

[Arxiv](https://arxiv.org/abs/2507.15857)