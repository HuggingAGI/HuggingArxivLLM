# 通过精细解析证明结构实现高效神经定理证明

发布时间：2025年01月30日

`LLM应用` `定理证明`

> Efficient Neural Theorem Proving via Fine-grained Proof Structure Analysis

# 摘要

> 深度学习模型与传统自动化工具的协同作用在开发稳健的神经定理证明器（NTP）中发挥着关键作用。然而，对于基于LLMs的证明合成，以往的工作仅在模型显式调用方法时或单一粒度级别下应用自动化工具，未能充分挖掘内置策略和现成自动定理证明器的潜力。本文提出了一种名为ProofAug的新颖定理证明方法，通过精细分析模型生成的证明提案结构，为证明生成LLMs配备了不同粒度级别的自动化方法，从而实现了卓越的样本效率。此外，ProofAug作为一个灵活的即插即用模块，能够无缝集成到任何树搜索算法中，从而支持我们构建一个高效的递归证明（ERP）模块，进一步提升性能。我们采用开源的deepseek-math-7b-base模型和Isabelle证明助手，在miniF2F-test基准上验证了该方法的优越性。值得注意的是，通过额外采用混合提示策略，我们在数据集整理后实现了66.0%的累积通过率（原始版本为61.9%），在仅使用2100个样本预算的情况下，所有证明语言均达到了新的SOTA水平。我们的代码可在https://github.com/haoxiongliu/ProofAug获取。

> The synergy between deep learning models and traditional automation tools plays a pivotal role in developing robust neural theorem provers (NTPs). However, for proof synthesis with LLMs, previous work applies automation tools either only when the model explicitly calls the method, or only at a single granularity level, failing to fully exploit the power of built-in tactics and off-the-shelf automated theorem provers. In this work, we propose ProofAug, a novel theorem proving method that enjoys superior sample efficiency through equipping proof-generation LLMs with automation methods in different granularities via fine-grained structure analysis of model-generated proof proposals. Furthermore, ProofAug serves as a versatile plug-and-play module that seamlessly integrates with any tree-search algorithm, enabling our construction of an efficient recursive proving (ERP) module to further enhance performance. The superiority of our method is validated on the miniF2F-test benchmark using the open-source deepseek-math-7b-base model and the Isabelle proof assistant. Notably, by additionally employing a mixed prompting strategy, we achieve a cumulative pass rate of 66.0% after curation of the dataset (61.9% for the original version), setting a new SOTA across all proof languages with a total sample budget of only 2100. Our code is available at https://github.com/haoxiongliu/ProofAug.

[Arxiv](https://arxiv.org/abs/2501.18310)