# VerifiAgent：统一验证器在语言模型推理中的应用

发布时间：2025年04月01日

`Agent`

> VerifiAgent: a Unified Verification Agent in Language Model Reasoning

# 摘要

> 大型语言模型展现了强大的推理能力，但有时会输出不可靠或错误的结果。现有的验证方法往往局限于特定模型或领域，需要大量计算资源且难以扩展到多样化的推理任务。为了解决这些问题，我们提出了VerifiAgent，一个统一的验证代理，整合了元验证和基于工具的自适应验证。元验证评估模型回答的完整性和一致性，而自适应验证则让VerifiAgent根据推理类型（如数学、逻辑或常识推理）自主选择合适的验证工具。这种自适应方法在各种验证场景中确保了高效性和鲁棒性。实验结果显示，VerifiAgent在所有推理任务中均优于基线验证方法（如演绎验证器、反向验证器）。此外，它还能通过验证结果的反馈进一步提升推理准确性。VerifiAgent还适用于推理扩展，在数学推理领域，与现有过程奖励模型相比，它以更少的生成样本和成本取得了更佳的结果。代码可在https://github.com/Jiuzhouh/VerifiAgent获取。

> Large language models demonstrate remarkable reasoning capabilities but often produce unreliable or incorrect responses. Existing verification methods are typically model-specific or domain-restricted, requiring significant computational resources and lacking scalability across diverse reasoning tasks. To address these limitations, we propose VerifiAgent, a unified verification agent that integrates two levels of verification: meta-verification, which assesses completeness and consistency in model responses, and tool-based adaptive verification, where VerifiAgent autonomously selects appropriate verification tools based on the reasoning type, including mathematical, logical, or commonsense reasoning. This adaptive approach ensures both efficiency and robustness across different verification scenarios. Experimental results show that VerifiAgent outperforms baseline verification methods (e.g., deductive verifier, backward verifier) among all reasoning tasks. Additionally, it can further enhance reasoning accuracy by leveraging feedback from verification results. VerifiAgent can also be effectively applied to inference scaling, achieving better results with fewer generated samples and costs compared to existing process reward models in the mathematical reasoning domain. Code is available at https://github.com/Jiuzhouh/VerifiAgent

[Arxiv](https://arxiv.org/abs/2504.00406)