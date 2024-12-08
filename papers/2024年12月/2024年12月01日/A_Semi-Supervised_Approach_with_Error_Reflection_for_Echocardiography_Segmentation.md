# 一种针对超声心动图分割的带有错误反射的半监督式方法

发布时间：2024年12月01日

`其他` `超声心动图`

> A Semi-Supervised Approach with Error Reflection for Echocardiography Segmentation

# 摘要

> 从超声心动图中分割内部结构对于各类心脏病的诊断和治疗极为关键。半监督学习在缓解标注稀缺问题上展现出了能力。尽管现有的半监督方法在多种医学成像模式的图像分割中成效显著，但针对超声心动图对比度低、边缘细节模糊及噪声所带来的挑战而专门设计的方法却寥寥无几。这些特性给基于均值教师的半监督分割中高质量伪标签的生成造成了难题。受人类对错误实践进行反思的启发，我们为超声心动图半监督分割架构制定了一种错误反思策略。此策略促使模型对未标记图像分割中的不准确之处进行反思，进而增强伪标签生成的稳健性。具体来说，该策略分为两步。第一步称作重建反思。网络需要从未标记图像的语义掩码及其辅助草图重建真实的代理图像，同时让原始输入与代理之间的结构相似度达到最大。第二步叫做引导校正。重建误差图将不可靠的分割区域解耦。接着，利用更可能出现在高密度区域附近的可靠数据来引导可能位于决策边界周围的不可靠数据的优化。另外，我们引入了一种有效的数据增强策略，名为多尺度混合策略，以缩小有标记和无标记图像之间的经验分布差距，并感知心脏解剖结构的不同尺度。大量实验表明了所提方法的竞争力。

> Segmenting internal structure from echocardiography is essential for the diagnosis and treatment of various heart diseases. Semi-supervised learning shows its ability in alleviating annotations scarcity. While existing semi-supervised methods have been successful in image segmentation across various medical imaging modalities, few have attempted to design methods specifically addressing the challenges posed by the poor contrast, blurred edge details and noise of echocardiography. These characteristics pose challenges to the generation of high-quality pseudo-labels in semi-supervised segmentation based on Mean Teacher. Inspired by human reflection on erroneous practices, we devise an error reflection strategy for echocardiography semi-supervised segmentation architecture. The process triggers the model to reflect on inaccuracies in unlabeled image segmentation, thereby enhancing the robustness of pseudo-label generation. Specifically, the strategy is divided into two steps. The first step is called reconstruction reflection. The network is tasked with reconstructing authentic proxy images from the semantic masks of unlabeled images and their auxiliary sketches, while maximizing the structural similarity between the original inputs and the proxies. The second step is called guidance correction. Reconstruction error maps decouple unreliable segmentation regions. Then, reliable data that are more likely to occur near high-density areas are leveraged to guide the optimization of unreliable data potentially located around decision boundaries. Additionally, we introduce an effective data augmentation strategy, termed as multi-scale mixing up strategy, to minimize the empirical distribution gap between labeled and unlabeled images and perceive diverse scales of cardiac anatomical structures. Extensive experiments demonstrate the competitiveness of the proposed method.

[Arxiv](https://arxiv.org/abs/2412.00715)