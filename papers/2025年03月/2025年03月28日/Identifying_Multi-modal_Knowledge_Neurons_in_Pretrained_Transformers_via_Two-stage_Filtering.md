# 预训练变换器中的多模态知识神经元识别：基于双阶段过滤方法

发布时间：2025年03月28日

`LLM理论` `计算机视觉` `人工智能`

> Identifying Multi-modal Knowledge Neurons in Pretrained Transformers via Two-stage Filtering

# 摘要

> 大型语言模型（LLMs）的最新进展催生了自然语言处理（NLP）和计算机视觉领域中的多模态大型语言模型（MLLMs）。这些模型虽实现了视觉与语言的深度理解，但也带来了内部处理不透明及生成幻觉和错误信息等挑战。因此，探索多模态模型中知识位置的定位方法成为当务之急。

    本研究提出了一种基于Transformer架构的多模态大型语言模型MiniGPT-4，用于识别与特定知识相关联的神经元。具体而言，我们通过"基于图像修复的激活差异过滤"和"基于GradCAM的梯度过滤"两个阶段提取知识神经元。在MS COCO 2017数据集上进行的图像 caption 生成任务实验，结合BLEU、ROUGE和BERTScore的定量评估，以及基于激活热图的定性评估均表明，我们的方法在知识定位的准确性上优于现有方法。

    本研究不仅为多模态大型语言模型中知识的可视化和可解释性提供了新思路，更为未来知识的编辑与控制开辟了激动人心的探索之旅。

> Recent advances in large language models (LLMs) have led to the development of multimodal LLMs (MLLMs) in the fields of natural language processing (NLP) and computer vision. Although these models allow for integrated visual and language understanding, they present challenges such as opaque internal processing and the generation of hallucinations and misinformation. Therefore, there is a need for a method to clarify the location of knowledge in MLLMs.
  In this study, we propose a method to identify neurons associated with specific knowledge using MiniGPT-4, a Transformer-based MLLM. Specifically, we extract knowledge neurons through two stages: activation differences filtering using inpainting and gradient-based filtering using GradCAM. Experiments on the image caption generation task using the MS COCO 2017 dataset, BLEU, ROUGE, and BERTScore quantitative evaluation, and qualitative evaluation using an activation heatmap showed that our method is able to locate knowledge with higher accuracy than existing methods.
  This study contributes to the visualization and explainability of knowledge in MLLMs and shows the potential for future knowledge editing and control.

[Arxiv](https://arxiv.org/abs/2503.22941)