# # 跨层视觉平滑：通过持续关注关键对象增强大型视觉语言模型的视觉理解

发布时间：2025年09月16日

`LLM应用` `基础理论`

> Cross-Layer Vision Smoothing: Enhancing Visual Understanding via Sustained Focus on Key Objects in Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）虽能准确定位图像中的关键物体，但其对这些物体的关注却转瞬即逝。基于“持续聚焦关键物体能增强LVLMs视觉能力”这一假设，我们提出了跨层视觉平滑（CLVS）方法。CLVS的核心思路是引入视觉记忆模块，用于平滑跨层的注意力分布。具体来说，我们在第一层用位置无偏的视觉注意力初始化该视觉记忆。在后续层中，模型的视觉注意力会综合参考前层的视觉记忆，同时记忆会迭代更新，以此维持对关键物体的平滑关注。考虑到视觉理解主要发生在模型的早期和中间层，我们将不确定性作为视觉理解完成的标志，并据此终止平滑过程。在三个LVLMs上的四项基准测试实验验证了我们方法的有效性和普适性。CLVS在多项视觉理解任务中均达到了当前最优性能，尤其在关系与属性理解上提升显著。

> Large Vision-Language Models (LVLMs) can accurately locate key objects in images, yet their attention to these objects tends to be very brief. Motivated by the hypothesis that sustained focus on key objects can improve LVLMs' visual capabilities, we propose Cross-Layer Vision Smoothing (CLVS). The core idea of CLVS is to incorporate a vision memory that smooths the attention distribution across layers. Specifically, we initialize this vision memory with position-unbiased visual attention in the first layer. In subsequent layers, the model's visual attention jointly considers the vision memory from previous layers, while the memory is updated iteratively, thereby maintaining smooth attention on key objects. Given that visual understanding primarily occurs in the early and middle layers of the model, we use uncertainty as an indicator of completed visual understanding and terminate the smoothing process accordingly. Experiments on four benchmarks across three LVLMs confirm the effectiveness and generalizability of our method. CLVS achieves state-of-the-art performance on a variety of visual understanding tasks, with particularly significant improvements in relation and attribute understanding.

[Arxiv](https://arxiv.org/abs/2509.12897)