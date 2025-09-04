# 从评估走向防御：为大型语言模型构建基于持久编辑的指纹

发布时间：2025年09月03日

`LLM应用` `法律科技`

> From Evaluation to Defense: Constructing Persistent Edit-Based Fingerprints for Large Language Models

# 摘要

> 大型语言模型（LLMs）的知识产权（IP）保护日益关键。通过指令微调向LLMs注入特定指纹是常见的IP保护手段，但这种方法不仅可能大幅降低模型性能、耗费大量计算资源，在模型修改时还存在持久性差的问题。我们提出，知识编辑可作为一种更轻量、更适合指纹注入的替代方案。为此，我们首次将知识编辑应用于指纹注入，并证实了其强大性能。尽管采用乱序文本作为指纹以避免微调时被覆盖，但大规模微调仍会导致性能下降。针对这一问题，我们提出指纹子空间感知微调（FSFT），通过约束指纹子空间的更新来减少性能损耗——即使在最坏情况下，FSFT的性能也比普通微调高出10%。此外，我们发现，由于指纹与相似文本的特征高度相似，注入指纹的模型难以区分二者。这一发现凸显了为LLMs开发更鲁棒、更细粒度指纹注入方法的迫切性。

> The intellectual property (IP) protection of Large Language Models (LLMs) is increasingly critical. Injecting specialized fingerprints into LLMs through instruction tuning is a common IP protection technique. However, this may significantly degrade model performance, requires substantial computational resources, and exhibits poor persistence under model modifications. We argue that knowledge editing offers a lightweight alternative that is more suitable for fingerprint injection. Accordingly, we apply knowledge editing to fingerprint injection for the first time and demonstrate its strong capability. Despite using scrambled text as fingerprints to prevent them from being overwritten during fine-tuning, degradation still occurs under large-scale fine-tuning. To address this, we propose Fingerprint Subspace-aware Fine-Tuning (FSFT), which reduces fingerprint degradation by constraining the update of the fingerprint subspace. The performance of FSFT exceeds fine-tuning by 10% even in the worst-case scenario. Additionally, we observe that the fingerprint-injected models struggle to distinguish between fingerprints and similar texts due to the high similarity of their features. This finding underscores the urgent need for more robust and fine-grained fingerprinting injection methods for LLMs.

[Arxiv](https://arxiv.org/abs/2509.03122)