# MemHunter：LLM 中数据集规模上的自动且可验证的记忆检测

发布时间：2024年12月10日

`LLM应用` `隐私检测` `语言模型`

> MemHunter: Automated and Verifiable Memorization Detection at Dataset-scale in LLMs

# 摘要

> 大型语言模型（LLMs）已被证实会从其训练数据中记忆并重现内容，这引发了极大的隐私忧虑，尤其针对网络规模的数据集。现有的记忆检测方法大多针对样本，依赖于手动打造或逐个样本离散优化生成的记忆诱导提示，由于对所有样本进行迭代的计算成本过高，这对于数据集层面的检测难以实行。在实际场景中，数据所有者或许需要核实易受影响的 LLM 是否记住了他们的数据集，特别是当 LLM 可能未经授权从网络收集数据时。为应对此问题，我们推出了	extit{MemHunter}，它训练一个记忆诱导的 LLM，并运用假设检验来高效地在数据集级别检测记忆，无需针对样本的记忆诱导。在 Pythia 和 Llama-2 等模型上的实验显示，	extit{MemHunter}在有限时间资源下能比现有方法多提取高达 40％的训练数据，作为插件集成时能将搜索时间减少多达 80％。关键在于，	extit{MemHunter}是首个能够进行数据集级别记忆检测的方法，为评估由大量网络来源数据集驱动的 LLMs 中的隐私风险提供了不可或缺的工具。

> Large language models (LLMs) have been shown to memorize and reproduce content from their training data, raising significant privacy concerns, especially with web-scale datasets. Existing methods for detecting memorization are largely sample-specific, relying on manually crafted or discretely optimized memory-inducing prompts generated on a per-sample basis, which become impractical for dataset-level detection due to the prohibitive computational cost of iterating over all samples. In real-world scenarios, data owners may need to verify whether a susceptible LLM has memorized their dataset, particularly if the LLM may have collected the data from the web without authorization. To address this, we introduce \textit{MemHunter}, which trains a memory-inducing LLM and employs hypothesis testing to efficiently detect memorization at the dataset level, without requiring sample-specific memory inducing. Experiments on models such as Pythia and Llama-2 demonstrate that \textit{MemHunter} can extract up to 40\% more training data than existing methods under constrained time resources and reduce search time by up to 80\% when integrated as a plug-in. Crucially, \textit{MemHunter} is the first method capable of dataset-level memorization detection, providing an indispensable tool for assessing privacy risks in LLMs that are powered by vast web-sourced datasets.

[Arxiv](https://arxiv.org/abs/2412.07261)