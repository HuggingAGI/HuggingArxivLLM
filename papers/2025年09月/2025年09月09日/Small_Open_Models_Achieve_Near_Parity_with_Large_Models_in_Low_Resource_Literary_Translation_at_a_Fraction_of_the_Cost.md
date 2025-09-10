# 小型开放模型：低资源文学翻译性能接近大型模型，成本却仅为其几分之一

发布时间：2025年09月09日

`LLM应用` `媒体与娱乐`

> Small Open Models Achieve Near Parity with Large Models in Low Resource Literary Translation at a Fraction of the Cost

# 摘要

> 文学翻译作为机器翻译研究中一项独特而复杂的任务，近年来备受关注。但小型开源模型在这一领域的表现仍有待突破。为此，我们提出TINYFABULIST翻译框架（TF2）——一个英罗文学翻译的数据集创建、微调与评估统一框架，核心成果包括开源发布的紧凑微调语言模型（TF2-12B）及大规模合成平行数据集（DS-TF2-EN-RO-3M与DS-TF2-EN-RO-15K）。依托目前最大的合成英语寓言集DS-TF1-EN-3M（TF1），我们着力解决罗马尼亚语等低资源语言对丰富高质量文学数据集的迫切需求。

我们的流程首先利用高性能LLM从TF1数据池中生成1.5万条高质量罗马尼亚语参考译文，随后对120亿参数的开源权重模型实施两阶段微调：（i）通过指令微调捕捉特定体裁的叙事风格，（ii）借助适配器压缩实现高效部署。评估环节融合语料库级BLEU值与基于LLM的五维度评分标准（准确性、流畅性、连贯性、风格适配、文化转化），对翻译质量进行细致入微的评估。

结果显示，我们的微调模型在流畅度与准确性上可媲美顶级大型专有模型，同时具备开源、易获取且成本效益显著更高的优势。除模型与数据集外，我们还公开了所有脚本及评估提示。TF2由此为低成本翻译、跨语言叙事生成研究，以及在低资源环境中推广开源模型处理文化重要文学内容，提供了端到端、可复现的完整流程。

> Literary translation has recently gained attention as a distinct and complex task in machine translation research. However, the translation by small open models remains an open problem. We contribute to this ongoing research by introducing TINYFABULIST TRANSLATION FRAMEWORK (TF2), a unified framework for dataset creation, fine tuning, and evaluation in English-Romanian literary translations, centred on the creation and open release of both a compact, fine tuned language model (TF2-12B) and large scale synthetic parallel datasets (DS-TF2-EN-RO-3M and DS-TF2-EN-RO-15K). Building on DS-TF1-EN-3M (TF1), the largest collection of synthetic English fables to date, we address the need for rich, high quality literary datasets in low resource languages such as Romanian. Our pipeline first generates 15k high quality Romanian references from the TF1 pool using a high performing LLM. We then apply a two stage fine tuning process to a 12B parameter open weight model: (i) instruction tuning to capture genre specific narrative style, and (ii) adapter compression for efficient deployment. Evaluation combines corpus level BLEU and a five dimension LLM based rubric (accuracy, fluency, coherence, style, cultural adaptation) to provide a nuanced assessment of translation quality. Results show that our fine tuned model achieves fluency and adequacy competitive with top performing large proprietary models, while being open, accessible, and significantly more cost effective. Alongside the fine tuned model and both datasets, we publicly release all scripts and evaluation prompts. TF2 thus provides an end-to-end, reproducible pipeline for research on cost efficient translation, cross lingual narrative generation, and the broad adoption of open models for culturally significant literary content in low resource settings.

[Arxiv](https://arxiv.org/abs/2509.07829)