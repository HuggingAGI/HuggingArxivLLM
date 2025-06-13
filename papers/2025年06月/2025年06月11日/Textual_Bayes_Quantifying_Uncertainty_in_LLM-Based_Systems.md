# 文本贝叶斯：基于LLM系统的不确定性量化研究

发布时间：2025年06月11日

`LLM理论` `不确定性量化`

> Textual Bayes: Quantifying Uncertainty in LLM-Based Systems

# 摘要

> 尽管大型语言模型（LLMs）在解决现实任务方面的能力不断提升，但准确量化其不确定性仍是关键难题，限制了其在高风险领域的应用。这一挑战因许多先进LLMs的闭源、黑箱特性而更加复杂。此外，基于LLM的系统对提示的高度敏感性通常需要大量手动调整（即提示工程）。在这项研究中，我们通过贝叶斯视角来应对这些挑战。我们将提示视为统计模型中的文本参数，从而利用小规模训练数据集对这些提示进行贝叶斯推断。这一创新视角使我们能够对模型的文本参数及其下游预测进行系统性的不确定性量化，同时整合以自由文本形式表达的先验信念。为实现贝叶斯推断，即使是针对研究充分的数据模式，我们提出了一种结合提示优化技术与标准MCMC方法的新型马尔可夫链蒙特卡洛（MCMC）算法——通过LLM提议的Metropolis-Hastings算法（MHLP）。MHLP可作为即插即用的修改，适用于包括仅依赖闭源模型在内的现有LLM流水线。实证研究表明，我们的方法在多个LLM基准测试和不确定性量化（UQ）任务中，均显著提升了预测准确性和不确定性量化效果。更广泛而言，我们的研究展示了一条将丰富贝叶斯文献中的方法引入LLM时代的可行路径，为构建更可靠、更校准的基于LLM的系统奠定了基础。

> Although large language models (LLMs) are becoming increasingly capable of solving challenging real-world tasks, accurately quantifying their uncertainty remains a critical open problem, which limits their applicability in high-stakes domains. This challenge is further compounded by the closed-source, black-box nature of many state-of-the-art LLMs. Moreover, LLM-based systems can be highly sensitive to the prompts that bind them together, which often require significant manual tuning (i.e., prompt engineering). In this work, we address these challenges by viewing LLM-based systems through a Bayesian lens. We interpret prompts as textual parameters in a statistical model, allowing us to use a small training dataset to perform Bayesian inference over these prompts. This novel perspective enables principled uncertainty quantification over both the model's textual parameters and its downstream predictions, while also incorporating prior beliefs about these parameters expressed in free-form text. To perform Bayesian inference, a difficult problem even for well-studied data modalities, we introduce Metropolis-Hastings through LLM Proposals (MHLP), a novel Markov chain Monte Carlo (MCMC) algorithm that combines prompt optimization techniques with standard MCMC methods. MHLP is a turnkey modification to existing LLM pipelines, including those that rely exclusively on closed-source models. Empirically, we demonstrate that our method yields improvements in both predictive accuracy and uncertainty quantification (UQ) on a range of LLM benchmarks and UQ tasks. More broadly, our work demonstrates a viable path for incorporating methods from the rich Bayesian literature into the era of LLMs, paving the way for more reliable and calibrated LLM-based systems.

[Arxiv](https://arxiv.org/abs/2506.10060)