# **通过大型语言模型利用参考文档进行零样本排名**

发布时间：2025年06月13日

`LLM应用` `信息检索` `文本排序`

> Leveraging Reference Documents for Zero-Shot Ranking via Large Language Models

# 摘要

> 大型语言模型（LLMs）在信息检索中的文本排序任务中表现卓越。点式排序方法虽然通过独立为文档打分提供了计算效率，但缺乏文档间的比较，往往导致相关性估计存在偏差。对式方法通过明确比较文档对来提高排序准确性，但其二次复杂度（【数学公式】）带来了巨大的计算开销。为了解决这一权衡问题，我们提出了	extbf{RefRank}，一种基于固定参考文档的简单有效的比较排序方法。

RefRank方法提示LLM将每个候选文档与一个固定的参考文档进行比较，而不是比较所有文档对。通过选择一个能够涵盖查询核心意图的参考文档，RefRank可以隐式地捕获相关性线索，从而通过这个共同的参考点实现文档间的间接比较。这将计算成本降低到线性时间（【数学公式】），同时重要的是保留了比较评估的优势。为了进一步增强鲁棒性，我们采用加权平均方案，聚合不同参考选择下的多个RefRank输出。

在多个基准数据集和不同LLM上的实验表明，RefRank显著优于点式基线方法，并且在计算成本大幅降低的情况下，性能至少可以与对式方法相媲美。

> Large Language Models (LLMs) have demonstrated exceptional performance in the task of text ranking for information retrieval. While Pointwise ranking approaches offer computational efficiency by scoring documents independently, they often yield biased relevance estimates due to the lack of inter-document comparisons. In contrast, Pairwise methods improve ranking accuracy by explicitly comparing document pairs, but suffer from substantial computational overhead with quadratic complexity ($O(n^2)$). To address this tradeoff, we propose \textbf{RefRank}, a simple and effective comparative ranking method based on a fixed reference document. Instead of comparing all document pairs, RefRank prompts the LLM to evaluate each candidate relative to a shared reference anchor. By selecting the reference anchor that encapsulates the core query intent, RefRank implicitly captures relevance cues, enabling indirect comparison between documents via this common anchor. This reduces computational cost to linear time ($O(n)$) while importantly, preserving the advantages of comparative evaluation. To further enhance robustness, we aggregate multiple RefRank outputs using a weighted averaging scheme across different reference choices. Experiments on several benchmark datasets and with various LLMs show that RefRank significantly outperforms Pointwise baselines and could achieve performance at least on par with Pairwise approaches with a significantly lower computational cost.

[Arxiv](https://arxiv.org/abs/2506.11452)