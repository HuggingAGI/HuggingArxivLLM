# 如何增强大型推理模型的安全性：实证研究

发布时间：2025年05月21日

`LLM理论` `模型安全` `推理模型`

> How Should We Enhance the Safety of Large Reasoning Models: An Empirical Study

# 摘要

> 大型推理模型（LRMs）在数学和编程等复杂推理任务中表现优异，但其推理能力的提升并不必然带来安全性能的改善，甚至可能在某些情况下导致安全性能下降。这引出了一个重要研究问题：我们如何提高LRMs的安全性？本文通过监督微调（SFT）方法，全面探讨了提升LRMs安全性的路径。我们的研究始于一个意外发现：直接从DeepSeek-R1中提取安全回答，并未显著提升模型的安全性。通过分析，我们识别出三个关键的失败模式，并证明在数据蒸馏过程中明确解决这些问题，可以带来显著的安全性能提升。进一步研究发现，冗长复杂的推理过程并非实现安全性的必要条件。有趣的是，简短的或基于模板的推理过程即可达到与复杂推理链相当的安全性能，且更容易被模型学习。这些发现促使我们对推理在保障安全性方面的作用进行更深入的反思。此外，我们在安全微调过程中发现，混入数学推理数据有助于平衡安全性和过度拒绝之间的关系。总体而言，我们希望通过这项实证研究，为提升LRMs的安全性提供一个更加全面的认识。我们在实验中使用的代码和数据已发布在https://github.com/thu-coai/LRM-Safety-Study。

> Large Reasoning Models (LRMs) have achieved remarkable success on reasoning-intensive tasks such as mathematics and programming. However, their enhanced reasoning capabilities do not necessarily translate to improved safety performance-and in some cases, may even degrade it. This raises an important research question: how can we enhance the safety of LRMs? In this paper, we present a comprehensive empirical study on how to enhance the safety of LRMs through Supervised Fine-Tuning (SFT). Our investigation begins with an unexpected observation: directly distilling safe responses from DeepSeek-R1 fails to significantly enhance safety. We analyze this phenomenon and identify three key failure patterns that contribute to it. We then demonstrate that explicitly addressing these issues during the data distillation process can lead to substantial safety improvements. Next, we explore whether a long and complex reasoning process is necessary for achieving safety. Interestingly, we find that simply using short or template-based reasoning process can attain comparable safety performance-and are significantly easier for models to learn than more intricate reasoning chains. These findings prompt a deeper reflection on the role of reasoning in ensuring safety. Finally, we find that mixing math reasoning data during safety fine-tuning is helpful to balance safety and over-refusal. Overall, we hope our empirical study could provide a more holistic picture on enhancing the safety of LRMs. The code and data used in our experiments are released in https://github.com/thu-coai/LRM-Safety-Study.

[Arxiv](https://arxiv.org/abs/2505.15404)