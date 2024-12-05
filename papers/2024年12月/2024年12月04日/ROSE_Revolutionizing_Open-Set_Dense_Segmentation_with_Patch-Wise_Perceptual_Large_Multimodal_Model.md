# ROSE：借助基于补丁的感知大型多模态模型实现开放集密集分割的革新

发布时间：2024年12月04日

`LLM应用` `图像分割` `计算机视觉`

> ROSE: Revolutionizing Open-Set Dense Segmentation with Patch-Wise Perceptual Large Multimodal Model

# 摘要

> CLIP 和大型多模态模型（LMMs）的进步实现了开放词汇和自由文本分割，然而现有模型仍需预定义类别提示，这限制了自由形式的类别自生成。大多数分割 LMMs 仍局限于稀疏预测，制约了其在开放集环境中的应用。与此不同，我们提出了 ROSE 这一革命性的开放集密集分割 LMM，它借助逐块感知实现了密集掩码预测和开放类别生成。我们的方法把每个图像块当作独立的感兴趣区域候选，让模型能够同时预测密集和稀疏掩码。另外，新设计的指令响应模式充分发挥了 LMMs 的生成和泛化能力，达成了不受封闭集约束或预定义类别限制的类别预测。为进一步提升掩码细节和类别精度，我们引入了基于对话的细化模式，将前一步的预测结果与文本提示相结合进行修正。大量实验表明，ROSE 在统一框架下的各类分割任务中表现出色。代码将会发布。

> Advances in CLIP and large multimodal models (LMMs) have enabled open-vocabulary and free-text segmentation, yet existing models still require predefined category prompts, limiting free-form category self-generation. Most segmentation LMMs also remain confined to sparse predictions, restricting their applicability in open-set environments. In contrast, we propose ROSE, a Revolutionary Open-set dense SEgmentation LMM, which enables dense mask prediction and open-category generation through patch-wise perception. Our method treats each image patch as an independent region of interest candidate, enabling the model to predict both dense and sparse masks simultaneously. Additionally, a newly designed instruction-response paradigm takes full advantage of the generation and generalization capabilities of LMMs, achieving category prediction independent of closed-set constraints or predefined categories. To further enhance mask detail and category precision, we introduce a conversation-based refinement paradigm, integrating the prediction result from previous step with textual prompt for revision. Extensive experiments demonstrate that ROSE achieves competitive performance across various segmentation tasks in a unified framework. Code will be released.

[Arxiv](https://arxiv.org/abs/2412.00153)