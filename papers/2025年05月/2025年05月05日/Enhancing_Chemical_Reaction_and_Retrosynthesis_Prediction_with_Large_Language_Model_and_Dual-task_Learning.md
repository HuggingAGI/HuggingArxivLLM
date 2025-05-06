# 提升化学反应与逆向合成预测：结合大型语言模型与双任务学习

发布时间：2025年05月05日

`LLM应用` `药物设计`

> Enhancing Chemical Reaction and Retrosynthesis Prediction with Large Language Model and Dual-task Learning

# 摘要

> 化学反应与逆合成预测是药物发现中的基础任务。近期，大型语言模型（LLMs）在多个领域展现出了巨大潜力，然而，直接将其应用于化学合成领域却面临两大难题：首先，缺乏大规模的化学合成相关指令数据集；其次，现有微调策略忽略了反应与逆合成预测之间的密切关联。为了解决这些问题，我们提出了一种全新的LLM框架——ChemDual，专为精准化学合成而设计。考虑到获取反应与逆合成数据的成本高昂，ChemDual将分子的反应与逆合成过程视为一个重组与断裂的关联过程，并构建了一个包含440万条指令的大型数据集。此外，ChemDual采用了增强版的LLaMA模型，配备多尺度tokenizer和双任务学习策略，实现了对重组与断裂过程的联合优化，以及反应与逆合成预测任务的协同提升。在Mol-Instruction和USPTO-50K数据集上的大量实验表明，ChemDual在反应与逆合成预测方面均达到了当前最先进的性能水平，超越了现有的常规单任务方法和通用开源LLMs。通过分子对接分析，ChemDual生成的化合物展现出多样且强的蛋白质结合亲和力，进一步凸显了其在药物设计中的巨大潜力。

> Chemical reaction and retrosynthesis prediction are fundamental tasks in drug discovery. Recently, large language models (LLMs) have shown potential in many domains. However, directly applying LLMs to these tasks faces two major challenges: (i) lacking a large-scale chemical synthesis-related instruction dataset; (ii) ignoring the close correlation between reaction and retrosynthesis prediction for the existing fine-tuning strategies. To address these challenges, we propose ChemDual, a novel LLM framework for accurate chemical synthesis. Specifically, considering the high cost of data acquisition for reaction and retrosynthesis, ChemDual regards the reaction-and-retrosynthesis of molecules as a related recombination-and-fragmentation process and constructs a large-scale of 4.4 million instruction dataset. Furthermore, ChemDual introduces an enhanced LLaMA, equipped with a multi-scale tokenizer and dual-task learning strategy, to jointly optimize the process of recombination and fragmentation as well as the tasks between reaction and retrosynthesis prediction. Extensive experiments on Mol-Instruction and USPTO-50K datasets demonstrate that ChemDual achieves state-of-the-art performance in both predictions of reaction and retrosynthesis, outperforming the existing conventional single-task approaches and the general open-source LLMs. Through molecular docking analysis, ChemDual generates compounds with diverse and strong protein binding affinity, further highlighting its strong potential in drug design.

[Arxiv](https://arxiv.org/abs/2505.02639)