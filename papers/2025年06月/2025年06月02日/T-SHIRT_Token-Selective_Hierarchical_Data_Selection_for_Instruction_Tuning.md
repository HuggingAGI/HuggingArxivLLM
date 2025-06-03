# T-SHIRT：令牌选择式分层数据选择在指令微调中的应用

发布时间：2025年06月02日

`LLM应用` `数据科学`

> T-SHIRT: Token-Selective Hierarchical Data Selection for Instruction Tuning

# 摘要

> 指令微调是大型语言模型（LLMs）有效理解和执行用户指令的关键。为了提升训练效率并减少数据冗余，近期研究采用基于LLM的评分函数（如指令遵循难度（IFD））来筛选高质量的指令微调数据，仅保留得分高于阈值的样本。尽管这些方法通常能训练出性能匹敌甚至超越全量数据训练模型的模型，但我们发现其存在两个关键局限：(i) 它们仅从样本层面评估质量，忽略了token层面的信息量；(ii) 它们忽视了评分方法的鲁棒性，往往因表层词汇特征而选择某个样本，而非其真实质量。  
在本研究中，我们提出了用于指令微调的Token-Selective HIeRarchical Data Selection（T-SHIRT）方法，这是一个全新的数据筛选框架。它引入了一种新的评分方法，仅在质量评估中纳入具有信息量的token，同时促进选择稳健可靠的样本，其邻近样本也表现出高质量且局部不一致较少。  
我们证明，使用T-SHIRT方法筛选后的精简数据集（仅为原始数据集的5%）进行指令微调的模型，在八个基准测试中平均比使用完整大规模数据集训练的模型高出5.48分。在各种LLMs和训练集规模下，我们的方法始终超越现有最先进的数据筛选技术，同时保持成本效益和高效性。例如，通过使用GPT-2进行评分计算，我们能够在单个GPU上用40分钟处理包含52,000个样本的数据集。

> Instruction tuning is essential for Large Language Models (LLMs) to effectively follow user instructions. To improve training efficiency and reduce data redundancy, recent works use LLM-based scoring functions, e.g., Instruction-Following Difficulty (IFD), to select high-quality instruction-tuning data with scores above a threshold. While these data selection methods often lead to models that can match or even exceed the performance of models trained on the full datasets, we identify two key limitations: (i) they assess quality at the sample level, ignoring token-level informativeness; and (ii) they overlook the robustness of the scoring method, often selecting a sample due to superficial lexical features instead of its true quality. In this work, we propose Token-Selective HIeRarchical Data Selection for Instruction Tuning (T-SHIRT), a novel data selection framework that introduces a new scoring method to include only informative tokens in quality evaluation and also promotes robust and reliable samples whose neighbors also show high quality with less local inconsistencies. We demonstrate that models instruction-tuned on a curated dataset (only 5% of the original size) using T-SHIRT can outperform those trained on the entire large-scale dataset by up to 5.48 points on average across eight benchmarks. Across various LLMs and training set scales, our method consistently surpasses existing state-of-the-art data selection techniques, while also remaining both cost-effective and highly efficient. For instance, by using GPT-2 for score computation, we are able to process a dataset of 52k samples using 40 minutes on a single GPU.

[Arxiv](https://arxiv.org/abs/2506.01317)