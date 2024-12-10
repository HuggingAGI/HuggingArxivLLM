# 通过具有遮挡鲁棒性的流预测和神经纹理实现一次性人体运动转移

发布时间：2024年12月08日

`其他` `动作迁移` `计算机视觉`

> One-shot Human Motion Transfer via Occlusion-Robust Flow Prediction and Neural Texturing

# 摘要

> 人类动作迁移旨在借助驱动视频让静态源图像动起来。尽管一次性人类动作迁移的最新进展显著提升了效果，但对于运用 2D 身体地标、骨骼和语义掩码的方法而言，由于动作和关节复杂程度变化巨大，要精准捕捉源姿势与驱动姿势之间的对应关系仍颇具挑战。此外，DensePose 的准确度和精度降低了基于神经渲染方法的图像质量。为应对这些局限，同时鉴于外观和几何对于动作迁移的重要性，在本研究中，我们提出了一个统一框架，它融合了多尺度特征扭曲和神经纹理映射，部分利用 DensePose 的信息来恢复更优的 2D 外观和 2.5D 几何，同时适应其固有的有限精度。我们的模型通过联合训练和融合多种模态来发挥优势，使其具备强大的神经纹理特征以应对几何误差，以及能更好保留外观的多尺度密集运动流。全视角和半视角身体视频数据集的实验结果表明，我们的模型泛化能力良好，能取得有竞争力的成果，在处理诸如存在大量自我遮挡等棘手情况时尤其有效。

> Human motion transfer aims at animating a static source image with a driving video. While recent advances in one-shot human motion transfer have led to significant improvement in results, it remains challenging for methods with 2D body landmarks, skeleton and semantic mask to accurately capture correspondences between source and driving poses due to the large variation in motion and articulation complexity. In addition, the accuracy and precision of DensePose degrade the image quality for neural-rendering-based methods. To address the limitations and by both considering the importance of appearance and geometry for motion transfer, in this work, we proposed a unified framework that combines multi-scale feature warping and neural texture mapping to recover better 2D appearance and 2.5D geometry, partly by exploiting the information from DensePose, yet adapting to its inherent limited accuracy. Our model takes advantage of multiple modalities by jointly training and fusing them, which allows it to robust neural texture features that cope with geometric errors as well as multi-scale dense motion flow that better preserves appearance. Experimental results with full and half-view body video datasets demonstrate that our model can generalize well and achieve competitive results, and that it is particularly effective in handling challenging cases such as those with substantial self-occlusions.

[Arxiv](https://arxiv.org/abs/2412.06174)