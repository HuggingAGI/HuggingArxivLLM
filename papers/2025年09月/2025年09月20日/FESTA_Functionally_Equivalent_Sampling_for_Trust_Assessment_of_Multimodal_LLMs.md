# FESTA：多模态大型语言模型信任评估的功能等效采样

发布时间：2025年09月20日

`LLM应用` `基础理论`

> FESTA: Functionally Equivalent Sampling for Trust Assessment of Multimodal LLMs

# 摘要

> 多模态大型语言模型（MLLMs）生成预测的信任评估若要准确（从而实现选择性预测并提升用户信任），因输入范式的多样性而颇具挑战。为此，我们提出面向信任评估的功能等效采样方法（FESTA）——一种适用于MLLMs的多模态输入采样技术，通过等效与互补输入采样生成不确定性度量。该方法通过任务保持的采样策略进行不确定性量化，扩展输入空间以考察模型的一致性（借助等效样本）与敏感性（借助互补样本）。FESTA仅需模型的输入-输出访问（黑盒模式），无需真实标签（无监督方式）。我们在多款现成的多模态LLM上开展实验，覆盖视觉与音频推理任务。实验表明，FESTA的不确定性估计在选择性预测性能上显著提升：视觉LLM相对提升33.3%，音频LLM相对提升29.6%（基于检测错误预测的受试者工作特征曲线下面积（AUROC）指标）。相关代码已开源。

> The accurate trust assessment of multimodal large language models (MLLMs) generated predictions, which can enable selective prediction and improve user confidence, is challenging due to the diverse multi-modal input paradigms. We propose Functionally Equivalent Sampling for Trust Assessment (FESTA), a multimodal input sampling technique for MLLMs, that generates an uncertainty measure based on the equivalent and complementary input samplings. The proposed task-preserving sampling approach for uncertainty quantification expands the input space to probe the consistency (through equivalent samples) and sensitivity (through complementary samples) of the model. FESTA uses only input-output access of the model (black-box), and does not require ground truth (unsupervised). The experiments are conducted with various off-the-shelf multi-modal LLMs, on both visual and audio reasoning tasks. The proposed FESTA uncertainty estimate achieves significant improvement (33.3% relative improvement for vision-LLMs and 29.6% relative improvement for audio-LLMs) in selective prediction performance, based on area-under-receiver-operating-characteristic curve (AUROC) metric in detecting mispredictions. The code implementation is open-sourced.

[Arxiv](https://arxiv.org/abs/2509.16648)