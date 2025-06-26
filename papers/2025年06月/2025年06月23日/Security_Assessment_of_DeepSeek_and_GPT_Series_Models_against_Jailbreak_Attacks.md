# # 安全评估
评估 DeepSeek 和 GPT 系列模型抵御越狱攻击的能力

发布时间：2025年06月23日

`LLM理论

论文摘要分析：这篇论文探讨了大型语言模型（LLMs）的架构设计如何影响其安全性，特别是针对越狱攻击的脆弱性。研究比较了不同模型的架构，如MoE和Transformer，分析了它们在对抗性提示下的表现，并揭示了架构与安全对齐之间的权衡。这些内容属于模型的理论层面，因此归类为LLM理论。` `模型安全` `开源技术`

> Security Assessment of DeepSeek and GPT Series Models against Jailbreak Attacks

# 摘要

> 大型语言模型（LLMs）的广泛应用引发了对其易受越狱攻击漏洞的严重担忧，即那些绕过对齐机制并引发有害或违反政策输出的对抗性提示。尽管像GPT-4这样的专有模型已经过广泛评估，但像DeepSeek这样的新兴开源替代模型的稳健性仍未得到充分探索，尽管它们在现实世界中的应用日益增多。本文中，我们首次对DeepSeek系列模型进行了系统性的越狱攻击评估，使用HarmBench基准测试将其与GPT-3.5和GPT-4进行了比较。我们评估了7种具有代表性的攻击策略，涵盖了按功能和语义领域分类的510种有害行为。我们的分析表明，DeepSeek的专家混合（MoE）架构引入了路由稀疏性，这在一定程度上增强了对基于优化的攻击（如TAP-T）的鲁棒性，但在基于提示和手动设计的攻击下，其脆弱性显著增加。相比之下，GPT-4 Turbo在多样化行为中展现出更强且更一致的安全对齐性能，这可能得益于其密集的Transformer架构和基于人类反馈的强化学习。细致的行为分析和案例研究进一步表明，DeepSeek往往会将对抗性提示路由到对齐不足的专家模块，导致拒绝行为的不一致性。这些发现揭示了架构效率与对齐泛化之间的根本权衡，强调了针对安全调优和模块化对齐策略的需求，以确保开源LLMs的安全部署。

> The widespread deployment of large language models (LLMs) has raised critical concerns over their vulnerability to jailbreak attacks, i.e., adversarial prompts that bypass alignment mechanisms and elicit harmful or policy-violating outputs. While proprietary models like GPT-4 have undergone extensive evaluation, the robustness of emerging open-source alternatives such as DeepSeek remains largely underexplored, despite their growing adoption in real-world applications. In this paper, we present the first systematic jailbreak evaluation of DeepSeek-series models, comparing them with GPT-3.5 and GPT-4 using the HarmBench benchmark. We evaluate seven representative attack strategies across 510 harmful behaviors categorized by both function and semantic domain. Our analysis reveals that DeepSeek's Mixture-of-Experts (MoE) architecture introduces routing sparsity that offers selective robustness against optimization-based attacks such as TAP-T, but leads to significantly higher vulnerability under prompt-based and manually engineered attacks. In contrast, GPT-4 Turbo demonstrates stronger and more consistent safety alignment across diverse behaviors, likely due to its dense Transformer design and reinforcement learning from human feedback. Fine-grained behavioral analysis and case studies further show that DeepSeek often routes adversarial prompts to under-aligned expert modules, resulting in inconsistent refusal behaviors. These findings highlight a fundamental trade-off between architectural efficiency and alignment generalization, emphasizing the need for targeted safety tuning and modular alignment strategies to ensure secure deployment of open-source LLMs.

[Arxiv](https://arxiv.org/abs/2506.18543)