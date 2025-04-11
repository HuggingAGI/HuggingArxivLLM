# 基于自适应令牌选择的 LLM 幻觉检测方法

发布时间：2025年04月10日

`LLM应用

理由：这篇论文主要关注大型语言模型（LLMs）中的幻觉现象，并提出了一种新的检测方法HaMI。幻觉现象是LLMs在实际应用中面临的安全挑战，而HaMI方法的提出和验证是为了提高检测的鲁棒性，属于对LLM的实际应用研究。因此，将其归类为LLM应用是合适的。` `生成内容`

> Robust Hallucination Detection in LLMs via Adaptive Token Selection

# 摘要

> 大型语言模型（LLMs）中的幻觉现象对广泛应用构成了重大安全挑战。最新研究表明，LLMs的内部表示中蕴含着真实性的线索，可用于训练检测器。然而，现有检测器的表现严重依赖预设标记的内部表示，在处理形式多样、长度不一且幻觉实体分布稀疏的自由生成内容时，效果波动显著。为此，我们提出了HaMI方法，通过自适应选择和学习最具幻觉指示性的关键标记，实现对幻觉的鲁棒检测。我们创新性地将幻觉检测任务建模为基于标记级别表示的多示例（HaMI）学习，实现了标记选择与幻觉检测在多种生成形式上的联合优化。在四个幻觉检测基准数据集上的全面实验结果表明，HaMI显著超越了现有的最先进方法。

> Hallucinations in large language models (LLMs) pose significant safety concerns that impede their broader deployment. Recent research in hallucination detection has demonstrated that LLMs' internal representations contain truthfulness hints, which can be harnessed for detector training. However, the performance of these detectors is heavily dependent on the internal representations of predetermined tokens, fluctuating considerably when working on free-form generations with varying lengths and sparse distributions of hallucinated entities. To address this, we propose HaMI, a novel approach that enables robust detection of hallucinations through adaptive selection and learning of critical tokens that are most indicative of hallucinations. We achieve this robustness by an innovative formulation of the Hallucination detection task as Multiple Instance (HaMI) learning over token-level representations within a sequence, thereby facilitating a joint optimisation of token selection and hallucination detection on generation sequences of diverse forms. Comprehensive experimental results on four hallucination benchmarks show that HaMI significantly outperforms existing state-of-the-art approaches.

[Arxiv](https://arxiv.org/abs/2504.07863)