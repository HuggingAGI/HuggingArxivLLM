# 护盾计划：利用安全增强型表征干预抵御大型语言模型的越狱攻击

发布时间：2025年02月21日

`LLM应用` `模型安全` `安全性`

> SafeInt: Shielding Large Language Models from Jailbreak Attacks via Safety-Aware Representation Intervention

# 摘要

> 大型语言模型（LLMs）在现实世界的广泛应用使得确保其行为安全变得至关重要。Jailbreak攻击通过利用LLM的漏洞诱导不当行为，对模型安全构成重大威胁。传统防御方法往往难以兼顾效果与效率。虽然从表征角度的防御方法提供了新思路，但现有干预手段无法根据查询危害性动态调整表征。为在确保效果与效率的同时解决这一问题，我们提出了一种名为SafeIntervention（SafeInt）的创新防御方法，通过安全感知的表征干预保护LLMs免受Jailbreak攻击。SafeInt基于我们对Jailbreak样本表征的深入分析，通过调整Jailbreak样本的表征分布，使其与不安全样本的表征对齐，同时尽量减少对无关表征的不必要扰动。我们进行了全面实验，涵盖六种Jailbreak攻击、两个Jailbreak数据集和两个效用基准测试。实验结果表明，SafeInt在防御LLMs免受Jailbreak攻击方面优于所有基线方法，同时在很大程度上保持了效用。此外，我们评估了SafeInt在对抗自适应攻击中的表现，并验证了其在缓解实时攻击中的有效性。

> With the widespread real-world deployment of large language models (LLMs), ensuring their behavior complies with safety standards has become crucial. Jailbreak attacks exploit vulnerabilities in LLMs to induce undesirable behavior, posing a significant threat to LLM safety. Previous defenses often fail to achieve both effectiveness and efficiency simultaneously. Defenses from a representation perspective offer new insights, but existing interventions cannot dynamically adjust representations based on the harmfulness of the queries. To address this limitation while ensuring both effectiveness and efficiency, we propose SafeIntervention (SafeInt), a novel defense method that shields LLMs from jailbreak attacks through safety-aware representation intervention. SafeInt is built on our analysis of the representations of jailbreak samples. It adjusts representation distributions of jailbreak samples through intervention to align them with the representations of unsafe samples while minimizing unnecessary perturbations to jailbreak-irrelevant representations. We conduct comprehensive experiments covering six jailbreak attacks, two jailbreak datasets, and two utility benchmarks. Experimental results demonstrate that SafeInt outperforms all baselines in defending LLMs against jailbreak attacks while largely maintaining utility. Additionally, we evaluate SafeInt against adaptive attacks and verify its effectiveness in mitigating real-time attacks.

[Arxiv](https://arxiv.org/abs/2502.15594)