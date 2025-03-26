# 多模态大模型真的懂焊接吗？

发布时间：2025年03月18日

`LLM应用

摘要讨论了多模态大型语言模型在焊接等工业应用中的实际表现，评估了模型在不同背景下的能力，并提出了一种提示策略以提升性能。这些内容属于模型的实际应用和改进，因此归类为LLM应用。` `工业制造` `工业自动化`

> Do Multimodal Large Language Models Understand Welding?

# 摘要

> 本文研究了多模态大型语言模型（MLLMs）在焊接等熟练生产工作中的应用表现。通过一个由领域专家标注的真实世界与在线焊接图像数据集，我们评估了当前两种最先进的MLLMs在RV & Marine、航空航天和农业三个背景下的焊缝质量评估能力。尽管两种模型在在线图像上的表现更优，这可能源于其先前的学习或记忆，但它们在未见过的真实世界焊接图像上也表现不俗。此外，我们提出了一种名为WeldPrompt的提示策略，该策略结合链式思维生成与上下文学习，旨在减少幻觉并提升推理能力。实验结果显示，WeldPrompt在某些背景下显著提升了模型的召回率，但在其他场景下表现仍不稳定。这些发现不仅揭示了MLLMs在高风险技术领域中的潜力与局限，也为未来研究指明了方向，即通过模型微调、领域专用数据和更精细的提示策略来提升模型可靠性。这项研究为多模态学习在工业应用中的深入探索开辟了新的研究路径。

> This paper examines the performance of Multimodal LLMs (MLLMs) in skilled production work, with a focus on welding. Using a novel data set of real-world and online weld images, annotated by a domain expert, we evaluate the performance of two state-of-the-art MLLMs in assessing weld acceptability across three contexts: RV \& Marine, Aeronautical, and Farming. While both models perform better on online images, likely due to prior exposure or memorization, they also perform relatively well on unseen, real-world weld images. Additionally, we introduce WeldPrompt, a prompting strategy that combines Chain-of-Thought generation with in-context learning to mitigate hallucinations and improve reasoning. WeldPrompt improves model recall in certain contexts but exhibits inconsistent performance across others. These results underscore the limitations and potentials of MLLMs in high-stakes technical domains and highlight the importance of fine-tuning, domain-specific data, and more sophisticated prompting strategies to improve model reliability. The study opens avenues for further research into multimodal learning in industry applications.

[Arxiv](https://arxiv.org/abs/2503.16537)