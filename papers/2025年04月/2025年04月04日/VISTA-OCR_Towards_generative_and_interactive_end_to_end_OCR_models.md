# VISTA-OCR：实现生成式交互式端到端OCR模型

发布时间：2025年04月04日

`LLM应用` `OCR` `数据集构建与应用`

> VISTA-OCR: Towards generative and interactive end to end OCR models

# 摘要

> 我们推出了	extbf{VISTA-OCR}（视觉与空间感知文本分析OCR），这是一个创新的轻量级架构，首次在单一生成模型中实现了文本检测与识别的无缝结合。与传统方法需要为检测和识别分别设计独立模块不同，VISTA-OCR采用Transformer解码器，在同一分支中依次生成文本内容及其空间位置信息。该模型基于编码器-解码器架构，采用分阶段训练策略：先提取视觉特征，再通过多模态令牌生成进行多任务学习。为应对复杂OCR场景的需求，我们在预训练中引入了可提示控制的新型OCR任务，例如内容驱动的文本定位ef{content_based_localization}。为了进一步提升模型性能，我们构建了一个全新的数据集，包含丰富的边界框标注的真实世界样本和合成样本。尽管当前的视觉大型语言模型（VLLMs）在处理这些任务时表现出色，但其高昂的计算成本限制了实际应用。相比之下，我们的VISTA$_{	ext{omni}}$变体仅需1.5亿参数，即可通过提示交互式处理手写和印刷文档。实验结果表明，VISTA-OCR在标准OCR任务中超越现有专用模型，同时在复杂OCR应用中展现出巨大潜力，完美契合了市场对交互式OCR系统的需求。VISTA-OCR的所有代码和标注将在项目 acceptance 后开放共享。

> We introduce \textbf{VISTA-OCR} (Vision and Spatially-aware Text Analysis OCR), a lightweight architecture that unifies text detection and recognition within a single generative model. Unlike conventional methods that require separate branches with dedicated parameters for text recognition and detection, our approach leverages a Transformer decoder to sequentially generate text transcriptions and their spatial coordinates in a unified branch. Built on an encoder-decoder architecture, VISTA-OCR is progressively trained, starting with the visual feature extraction phase, followed by multitask learning with multimodal token generation. To address the increasing demand for versatile OCR systems capable of advanced tasks, such as content-based text localization \ref{content_based_localization}, we introduce new prompt-controllable OCR tasks during pre-training.To enhance the model's capabilities, we built a new dataset composed of real-world examples enriched with bounding box annotations and synthetic samples. Although recent Vision Large Language Models (VLLMs) can efficiently perform these tasks, their high computational cost remains a barrier for practical deployment. In contrast, our VISTA$_{\text{omni}}$ variant processes both handwritten and printed documents with only 150M parameters, interactively, by prompting. Extensive experiments on multiple datasets demonstrate that VISTA-OCR achieves better performance compared to state-of-the-art specialized models on standard OCR tasks while showing strong potential for more sophisticated OCR applications, addressing the growing need for interactive OCR systems. All code and annotations for VISTA-OCR will be made publicly available upon acceptance.

[Arxiv](https://arxiv.org/abs/2504.03621)