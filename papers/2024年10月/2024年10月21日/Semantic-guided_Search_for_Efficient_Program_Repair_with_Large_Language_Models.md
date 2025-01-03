# 语义引导的搜索助力基于大型语言模型的高效程序修复

发布时间：2024年10月21日

`LLM应用

理由：这篇论文主要讨论了如何通过改进LLM（大型语言模型）的技术来解决内存消耗和修复效率的问题，特别是在自动程序修复（APR）领域的应用。论文提出了FLAMES技术，通过语义引导的补丁生成来提升修复效果和内存效率。这属于LLM在实际应用中的优化和改进，因此归类为LLM应用。` `软件工程` `程序修复`

> Semantic-guided Search for Efficient Program Repair with Large Language Models

# 摘要

> 本文首先指出，即使是小型LLM（1B-7B参数）的beam size增加也会导致GPU资源消耗激增，使得基于LLM的APR因内存过载而崩溃的概率高达80%。常见的减少内存消耗的方法包括：（1）量化LLM模型，即将高精度权重转换为低精度；（2）顺序化beam search，即依次处理每个beam后再合并输出。然而，理论和实验均表明这些方法效果有限。为此，我们提出了FLAMES，一种基于LLM的APR技术，通过语义引导的补丁生成提升修复效果和内存效率。与传统beam search不同，FLAMES采用贪婪解码，结合语义引导的最佳优先搜索算法，高效寻找潜在修复方案。在每个解码步骤中，FLAMES利用测试验证的语义反馈（如通过和失败的测试用例数量）选择最有希望的token进行进一步探索。在Defects4J和HumanEval-Java数据集上的实验表明，FLAMES不仅将内存消耗降低了83%，还显著加快了修复速度。值得注意的是，FLAMES成功修复了Defects4J和HumanEval-Java数据集中的133和103个bug，分别比现有最优技术多修复了10和11个bug，展现了其高效性和优越性。

> In this paper, we first show that increases in beam size of even just small-sized LLM (1B-7B parameters) require an extensive GPU resource consumption, leading to up to 80% of recurring crashes due to memory overloads in LLM-based APR. Seemingly simple solutions to reduce memory consumption are (1) to quantize LLM models, i.e., converting the weights of a LLM from high-precision values to lower-precision ones. and (2) to make beam search sequential, i.e., forwarding each beam through the model sequentially and then concatenate them back into a single model output. However, we show that these approaches still do not work via both theoretical analysis and experiments. To address this, we introduce FLAMES, a novel LLM-based APR technique that employs semantic-guided patch generation to enhance repair effectiveness and memory efficiency. Unlike conventional methods that rely on beam search, FLAMES utilizes greedy decoding to enhance memory efficiency while steering the search to more potentially good repair candidates via a semantic-guided best-first search algorithm. At each decoding step, FLAMES uses semantic feedback from test validation such as the number of passing and failing test cases to select the most promising token to explore further. Our empirical evaluation on the Defects4J and HumanEval-Java datasets shows that FLAMES not only substantially reduces memory consumption by up to 83% compared to conventional LLM-based APR, but also accelerates the repair process. Remarkably, FLAMES successfully generated 133 and 103 correct fixes for 333 and 163 bugs in the Defects4J and HumanEval-Java datasets, respectively. This suggests that FLAMES is not only more efficient but also outperforms state-of-the-art techniques, fixing at least 10 and 11 more bugs than SOTA baselines in the Defects4J and HumanEval-Java datasets, respectively.

[Arxiv](https://arxiv.org/abs/2410.16655)