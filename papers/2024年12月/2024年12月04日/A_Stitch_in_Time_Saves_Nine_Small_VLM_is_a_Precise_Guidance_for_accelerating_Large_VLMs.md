# “一针及时省九针”：小型 VLM 是加速大型 VLMs 的精准指引

发布时间：2024年12月04日

`LLM应用` `计算机视觉` `多模态任务`

> A Stitch in Time Saves Nine: Small VLM is a Precise Guidance for accelerating Large VLMs

# 摘要

> 视觉语言模型（VLMs）在各类多模态任务中成绩斐然，然而大型 VLMs 因处理众多视觉标记而面临显著的效率难题。加速大型 VLM 推理的一个可行之法是运用部分信息，比如特定层的注意力图，来评估标记的重要性并修剪不太关键的标记。不过，我们的研究呈现了三个关键发现：（i）部分注意力信息难以精准识别关键视觉标记，致使性能欠佳，在低标记保留率时尤甚；（ii）全局注意力信息，像跨所有层聚合的注意力图，能更有效地保留关键标记，在激进修剪时仍能维持相当的性能。但来自所有层的注意力图需要完整的推理流程，这会增加计算负担，所以在现有方法中不实用；（iii）从小型 VLM 聚合的全局注意力图与大型 VLM 的极为相似，这提示了一种有效的替代方案。基于这些成果，我们引入了一种	extbf{无需训练}的方法，underline{	extbf{S}}mall VLM underline{	extbf{G}}uidance 以加速 underline{	extbf{L}}arge VLMs（	extbf{SGL}）。具体而言，我们利用从小型 VLM 聚合的注意力图来引导大型 VLM 中的视觉标记修剪。此外，还开发了一种提前退出机制，充分利用小型 VLM 的预测，仅在必要时动态调用大型 VLM，在准确性和计算之间实现了出色的平衡。在 11 个基准上的广泛评估证实了 SGL 的有效性和通用性，视觉标记的修剪率高达 91％时仍能保持颇具竞争力的性能。

> Vision-language models (VLMs) have shown remarkable success across various multi-modal tasks, yet large VLMs encounter significant efficiency challenges due to processing numerous visual tokens. A promising approach to accelerating large VLM inference is using partial information, such as attention maps from specific layers, to assess token importance and prune less essential tokens. However, our study reveals three key insights: (i) Partial attention information is insufficient for accurately identifying critical visual tokens, resulting in suboptimal performance, especially at low token retention ratios; (ii) Global attention information, such as the attention map aggregated across all layers, more effectively preserves essential tokens and maintains comparable performance under aggressive pruning. However, the attention maps from all layers requires a full inference pass, which increases computational load and is therefore impractical in existing methods; and (iii) The global attention map aggregated from a small VLM closely resembles that of a large VLM, suggesting an efficient alternative. Based on these findings, we introduce a \textbf{training-free} method, underline{\textbf{S}}mall VLM underline{\textbf{G}}uidance for accelerating underline{\textbf{L}}arge VLMs (\textbf{SGL}). Specifically, we employ the attention map aggregated from a small VLM to guide visual token pruning in a large VLM. Additionally, an early exiting mechanism is developed to fully use the small VLM's predictions, dynamically invoking the larger VLM only when necessary, yielding a superior trade-off between accuracy and computation. Extensive evaluations across 11 benchmarks demonstrate the effectiveness and generalizability of SGL, achieving up to 91\% pruning ratio for visual tokens while retaining competitive performance.

[Arxiv](https://arxiv.org/abs/2412.03324)