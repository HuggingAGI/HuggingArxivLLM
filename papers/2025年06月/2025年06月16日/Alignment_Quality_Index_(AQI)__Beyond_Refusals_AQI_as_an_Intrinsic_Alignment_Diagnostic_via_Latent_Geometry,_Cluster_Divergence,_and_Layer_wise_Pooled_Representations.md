# 对齐质量指数（AQI）：超越拒绝——一种基于潜在几何、聚类差异和分层池化表示的内在对齐诊断方法

发布时间：2025年06月16日

`LLM理论`

> Alignment Quality Index (AQI) : Beyond Refusals: AQI as an Intrinsic Alignment Diagnostic via Latent Geometry, Cluster Divergence, and Layer wise Pooled Representations

# 摘要

> 对齐不再是可有可无的选择，而是不可或缺的需求。随着大型语言模型（LLMs）逐步进入教育、医疗、治理和法律等高风险领域，其行为必须可靠地体现符合人类价值观和安全约束。然而，目前的评估体系过度依赖于行为代理指标，如拒绝率、G-Eval分数和毒性分类器，这些指标均存在明显局限性。即使模型看似对齐，仍可能面临 jailbreaking、生成随机性和对齐欺骗等风险。
    为解决这一问题，我们推出了一种全新的评估工具——对齐质量指数（AQI）。这一创新性的几何和提示不变性指标通过分析潜在空间中安全与不安全激活的分离程度，实证评估 LLM 的对齐情况。AQI 结合了戴维斯-鲍尔丁分数（DBS）、邓恩指数（DI）、谢-贝尼指数（XBI）和卡林斯基-哈拉巴斯指数（CHI）等多维度指标，全面捕捉模型的聚类质量，从而识别隐藏的对齐偏差和 jailbreak 风险。即使模型输出看似合规，AQI 仍能提供可靠的风险预警。
    此外，我们还构建了 LITMUS 数据集，以支持在复杂条件下进行稳健评估。在 DPO、GRPO 和 RLHF 等不同训练条件下进行的跨模型实证测试表明，AQI 不仅与外部评委的评估结果高度相关，还能揭示传统拒绝指标所忽视的潜在漏洞。我们已将这一工具的实现方案公开，以推动相关领域的进一步研究。

> Alignment is no longer a luxury, it is a necessity. As large language models (LLMs) enter high-stakes domains like education, healthcare, governance, and law, their behavior must reliably reflect human-aligned values and safety constraints. Yet current evaluations rely heavily on behavioral proxies such as refusal rates, G-Eval scores, and toxicity classifiers, all of which have critical blind spots. Aligned models are often vulnerable to jailbreaking, stochasticity of generation, and alignment faking.
  To address this issue, we introduce the Alignment Quality Index (AQI). This novel geometric and prompt-invariant metric empirically assesses LLM alignment by analyzing the separation of safe and unsafe activations in latent space. By combining measures such as the Davies-Bouldin Score (DBS), Dunn Index (DI), Xie-Beni Index (XBI), and Calinski-Harabasz Index (CHI) across various formulations, AQI captures clustering quality to detect hidden misalignments and jailbreak risks, even when outputs appear compliant. AQI also serves as an early warning signal for alignment faking, offering a robust, decoding invariant tool for behavior agnostic safety auditing.
  Additionally, we propose the LITMUS dataset to facilitate robust evaluation under these challenging conditions. Empirical tests on LITMUS across different models trained under DPO, GRPO, and RLHF conditions demonstrate AQI's correlation with external judges and ability to reveal vulnerabilities missed by refusal metrics. We make our implementation publicly available to foster future research in this area.

[Arxiv](https://arxiv.org/abs/2506.13901)