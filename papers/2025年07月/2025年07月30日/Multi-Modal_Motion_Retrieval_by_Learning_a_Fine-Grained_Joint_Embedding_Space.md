# 多模态运动检索：通过学习细粒度联合嵌入空间实现

发布时间：2025年07月30日

`其他` `人工智能` `计算机视觉`

> Multi-Modal Motion Retrieval by Learning a Fine-Grained Joint Embedding Space

# 摘要

> 动作检索在动作获取中扮演着关键角色，相较于动作生成，它在精度、真实感、可控性和编辑性上表现更优。当前方法主要依赖对比学习，构建统一的嵌入空间，用于从文本或视觉模态进行动作检索。然而，这些方法在交互体验和检索性能上仍有提升空间，尤其是对大多数模态的顺序表示关注不足。针对这些问题，我们提出了一种创新框架，首次将文本、音频、视频和动作四种模态整合到一个细粒度的联合嵌入空间中，从而提升用户的沉浸感和操作便捷性。这一突破性的空间构建得益于序列级对比学习方法，该方法能够精准捕捉跨模态的关键细节，实现更优的对齐效果。为了验证框架的有效性，我们通过加入多样化的合成音频记录，对现有文本-动作数据集进行了增强，成功构建了两个多模态动作检索数据集。实验数据显示，相较于现有最先进方法，我们的框架在多个子任务中表现更优，具体而言，在HumanML3D数据集上，文本到动作检索的R@10指标提升了10.16%，视频到动作检索的R@1指标更是提升了25.43%。此外，我们的四模态框架在性能上显著超越了三模态版本，充分证明了多模态动作检索在推动动作获取技术发展方面的巨大潜力。

> Motion retrieval is crucial for motion acquisition, offering superior precision, realism, controllability, and editability compared to motion generation. Existing approaches leverage contrastive learning to construct a unified embedding space for motion retrieval from text or visual modality. However, these methods lack a more intuitive and user-friendly interaction mode and often overlook the sequential representation of most modalities for improved retrieval performance. To address these limitations, we propose a framework that aligns four modalities -- text, audio, video, and motion -- within a fine-grained joint embedding space, incorporating audio for the first time in motion retrieval to enhance user immersion and convenience. This fine-grained space is achieved through a sequence-level contrastive learning approach, which captures critical details across modalities for better alignment. To evaluate our framework, we augment existing text-motion datasets with synthetic but diverse audio recordings, creating two multi-modal motion retrieval datasets. Experimental results demonstrate superior performance over state-of-the-art methods across multiple sub-tasks, including an 10.16% improvement in R@10 for text-to-motion retrieval and a 25.43% improvement in R@1 for video-to-motion retrieval on the HumanML3D dataset. Furthermore, our results show that our 4-modal framework significantly outperforms its 3-modal counterpart, underscoring the potential of multi-modal motion retrieval for advancing motion acquisition.

[Arxiv](https://arxiv.org/abs/2507.23188)