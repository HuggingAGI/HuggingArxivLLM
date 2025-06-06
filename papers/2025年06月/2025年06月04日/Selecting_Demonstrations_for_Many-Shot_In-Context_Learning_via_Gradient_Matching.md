# # 基于梯度匹配的多示例上下文学习示例选择方法

发布时间：2025年06月04日

`LLM理论` `模型优化`

> Selecting Demonstrations for Many-Shot In-Context Learning via Gradient Matching

# 摘要

> 上下文学习（ICL）赋能大型语言模型（LLMs）实现快速任务适应，无需微调（FT），但演示样本选择仍是关键挑战。尽管多样本ICL通过扩展演示展现出令人鼓舞的性能，现有工作中多样本演示的选择方法仍局限于随机选择。由于传统基于实例的检索方法并不适用于多样本场景，我们假设上下文学习与微调的数据需求具有相似性。为此，我们引入了一种全新的梯度匹配方法，通过将目标任务整个训练集与所选样本之间的微调梯度对齐，从而在所选样本中逼近整个训练集的学习效果。通过在相对较小的模型（如Qwen2.5-3B或Llama3-8B）上进行梯度匹配，我们的方法在4-shot到128-shot的场景下，始终优于更大规模LLMs上的随机选择方法，涵盖9个多样化数据集。例如，在Qwen2.5-72B和Llama3-70B上，我们的方法比随机选择高出4%，在5个闭源LLMs上则高出约2%。这项研究为更可靠和有效的多样本ICL解锁了潜力，为其更广泛应用铺平了道路。

> In-Context Learning (ICL) empowers Large Language Models (LLMs) for rapid task adaptation without Fine-Tuning (FT), but its reliance on demonstration selection remains a critical challenge. While many-shot ICL shows promising performance through scaled demonstrations, the selection method for many-shot demonstrations remains limited to random selection in existing work. Since the conventional instance-level retrieval is not suitable for many-shot scenarios, we hypothesize that the data requirements for in-context learning and fine-tuning are analogous. To this end, we introduce a novel gradient matching approach that selects demonstrations by aligning fine-tuning gradients between the entire training set of the target task and the selected examples, so as to approach the learning effect on the entire training set within the selected examples. Through gradient matching on relatively small models, e.g., Qwen2.5-3B or Llama3-8B, our method consistently outperforms random selection on larger LLMs from 4-shot to 128-shot scenarios across 9 diverse datasets. For instance, it surpasses random selection by 4% on Qwen2.5-72B and Llama3-70B, and by around 2% on 5 closed-source LLMs. This work unlocks more reliable and effective many-shot ICL, paving the way for its broader application.

[Arxiv](https://arxiv.org/abs/2506.04579)