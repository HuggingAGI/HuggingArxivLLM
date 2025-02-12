# MEMIT-合并：解决 MEMIT 在大语言模型同一主题批量编辑中的键值冲突问题

发布时间：2025年02月11日

`LLM理论` `知识编辑`

> MEMIT-Merge: Addressing MEMIT's Key-Value Conflicts in Same-Subject Batch Editing for LLMs

# 摘要

> 大规模语言模型的持续扩展推动了知识编辑技术的发展，这些技术无需完整重新训练即可修改模型内部知识。其中，MEMIT作为一种突出的批处理编辑算法，因其能够执行大规模知识修改而备受瞩目。然而，我们发现MEMIT在处理包含多个共享同一主题的编辑批次时，其编辑效果显著下降。通过深入分析，我们发现这一问题的根本原因在于MEMIT的关键值建模框架：当一批中包含多个共享同一主题的事实时，相同的键（源自共享的主题）被迫表示不同的值（对应不同的知识），从而在编辑过程中引发更新冲突。为了解决这一问题，我们提出了一种增强方法——MEMIT-Merge。该方法通过合并共享同一主题的事实的价值计算过程，有效解决了同一主题批次编辑场景下的性能下降问题。实验结果表明，当MEMIT的编辑成功率在较大批次规模下降至约50%时，MEMIT-Merge仍能保持超过90%的成功率，展现出对主题实体冲突的显著鲁棒性。

> As large language models continue to scale up, knowledge editing techniques that modify models' internal knowledge without full retraining have gained significant attention. MEMIT, a prominent batch editing algorithm, stands out for its capability to perform mass knowledge modifications. However, we uncover a critical limitation that MEMIT's editing efficacy significantly deteriorates when processing batches containing multiple edits sharing the same subject. Our analysis reveals that the root cause lies in MEMIT's key value modeling framework: When multiple facts with the same subject in a batch are modeled through MEMIT's key value mechanism, identical keys (derived from the shared subject) are forced to represent different values (corresponding to different knowledge), resulting in updates conflicts during editing. Addressing this issue, we propose MEMIT-Merge, an enhanced approach that merges value computation processes for facts sharing the same subject, effectively resolving the performance degradation in same-subject batch editing scenarios. Experimental results demonstrate that when MEMIT's edit success rate drops to around 50% at larger batch sizes, MEMIT-Merge maintains a success rate exceeding 90%, showcasing remarkable robustness to subject entity collisions.

[Arxiv](https://arxiv.org/abs/2502.07322)