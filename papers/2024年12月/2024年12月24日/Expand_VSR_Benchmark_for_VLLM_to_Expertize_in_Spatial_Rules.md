# 拓展 VLLM 的 VSR 基准，以精通空间规则

发布时间：2024年12月24日

`LLM应用` `视觉语言模型` `空间推理`

> Expand VSR Benchmark for VLLM to Expertize in Spatial Rules

# 摘要

> 区分空间关系是人类认知的基础部分，需要对跨实例进行精细感知。尽管诸如 MME、MMBench 和 SEED 等基准已全面评估了多种能力，其中涵盖视觉空间推理（VSR），但针对视觉大语言模型（VLLMs）的视觉位置推理，仍缺少足量且优质的评估与优化数据集。为此，我们先用 VSR 数据集对当下的 VLLMs 进行诊断，提出了统一测试集。我们发现当前的 VLLMs 存在对语言指令过度敏感、对视觉位置信息不够敏感的矛盾。从调整数据和模型结构两方面拓展原始基准，我们缓解了这一现象。据了解，我们首次利用扩散模型可控地扩充了空间定位图像数据，并将原始视觉编码（CLIP）与其他 3 个强大的视觉编码器（SigLIP、SAM 和 DINO）相整合。对缩放数据和模型开展组合实验后，我们得到了一个 VLLM VSR 专家（VSRE），它不仅对不同指令的泛化能力更强，还能精准区分视觉位置信息的差异。VSRE 在 VSR 测试集上的准确率提升超 27%，成为在 VSR 数据集及其他评估基准相关子集的位置推理方面表现出色的 VLLM。我们在 url{https://github.com/peijin360/vsre} 开源了扩展模型、数据及附录，期望能推动 VLLM 在 VSR 学习上的进步。

> Distinguishing spatial relations is a basic part of human cognition which requires fine-grained perception on cross-instance. Although benchmarks like MME, MMBench and SEED comprehensively have evaluated various capabilities which already include visual spatial reasoning(VSR). There is still a lack of sufficient quantity and quality evaluation and optimization datasets for Vision Large Language Models(VLLMs) specifically targeting visual positional reasoning. To handle this, we first diagnosed current VLLMs with the VSR dataset and proposed a unified test set. We found current VLLMs to exhibit a contradiction of over-sensitivity to language instructions and under-sensitivity to visual positional information. By expanding the original benchmark from two aspects of tunning data and model structure, we mitigated this phenomenon. To our knowledge, we expanded spatially positioned image data controllably using diffusion models for the first time and integrated original visual encoding(CLIP) with other 3 powerful visual encoders(SigLIP, SAM and DINO). After conducting combination experiments on scaling data and models, we obtained a VLLM VSR Expert(VSRE) that not only generalizes better to different instructions but also accurately distinguishes differences in visual positional information. VSRE achieved over a 27\% increase in accuracy on the VSR test set. It becomes a performant VLLM on the position reasoning of both the VSR dataset and relevant subsets of other evaluation benchmarks. We open-sourced the expanded model with data and Appendix at url{https://github.com/peijin360/vsre} and hope it will accelerate advancements in VLLM on VSR learning.

[Arxiv](https://arxiv.org/abs/2412.18224)