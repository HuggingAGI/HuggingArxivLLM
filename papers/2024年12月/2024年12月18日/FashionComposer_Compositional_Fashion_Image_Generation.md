# FashionComposer：组合式时尚图像的生成

发布时间：2024年12月18日

`LLM应用` `图像生成`

> FashionComposer: Compositional Fashion Image Generation

# 摘要

> 我们推出了用于组合式时尚图像生成的 FashionComposer 。和以往的方法不同，FashionComposer 灵活性极高。它能接收多模态输入（比如文本提示、参数化人体模型、服装图像和面部图像），支持一次性对人体的外观、姿势和身材进行个性化处理，还能分配多件服装。为达成此目标，我们首先构建了一个能够应对各类输入模式的通用框架。我们创建了缩放的训练数据，以提升模型强大的组合能力。为了无缝容纳多个参考图像（服装和面部），我们把这些参考图像整合在一张图像里作为“资产库”，并运用参考 UNet 来提取外观特征。为将外观特征注入生成结果的正确像素，我们提出了主体绑定注意力。它把来自不同“资产”的外观特征与相应的文本特征相绑定。如此一来，模型能够依据其语义理解每个资产，支持任意数量和类型的参考图像。作为一个综合性解决方案，FashionComposer 还支持许多其他应用，例如人类相册生成、多样化的虚拟试穿任务等等。

> We present FashionComposer for compositional fashion image generation. Unlike previous methods, FashionComposer is highly flexible. It takes multi-modal input (i.e., text prompt, parametric human model, garment image, and face image) and supports personalizing the appearance, pose, and figure of the human and assigning multiple garments in one pass. To achieve this, we first develop a universal framework capable of handling diverse input modalities. We construct scaled training data to enhance the model's robust compositional capabilities. To accommodate multiple reference images (garments and faces) seamlessly, we organize these references in a single image as an "asset library" and employ a reference UNet to extract appearance features. To inject the appearance features into the correct pixels in the generated result, we propose subject-binding attention. It binds the appearance features from different "assets" with the corresponding text features. In this way, the model could understand each asset according to their semantics, supporting arbitrary numbers and types of reference images. As a comprehensive solution, FashionComposer also supports many other applications like human album generation, diverse virtual try-on tasks, etc.

[Arxiv](https://arxiv.org/abs/2412.14168)