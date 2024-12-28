# 通过人类引导的图像生成来拓展小规模训练图像数据集

发布时间：2024年12月23日

`LLM应用` `野生动物观测` `计算机视觉`

> Human-Guided Image Generation for Expanding Small-Scale Training Image Datasets

# 摘要

> 在某些现实应用场景（比如珍稀野生动物观测）里，计算机视觉模型的表现因可用图像数量少而受限。利用预训练的生成模型来扩充数据集是应对这一限制的有效途径。不过，由于自动生成过程难以控制，生成的图像往往在多样性上存在局限，部分图像也不尽如人意。在本文中，我们提出了一种人类引导的图像生成方法，以实现更可控的数据集扩展。我们研发了一种有理论保障的多模态投影方法，便于对原始图像和生成图像进行探索。基于这种探索，用户优化提示并重新生成图像，从而获得更优性能。鉴于新手用户直接优化提示存在困难，我们开发了一种样本级提示优化方法，使其更简便。通过该方法，用户只需提供样本级反馈（比如哪些样本不理想）就能获得更好的提示。我们方法的有效性通过多模态投影方法的定量评估、分类和对象检测任务案例研究中模型性能的提升以及专家的积极反馈得以证实。

> The performance of computer vision models in certain real-world applications (e.g., rare wildlife observation) is limited by the small number of available images. Expanding datasets using pre-trained generative models is an effective way to address this limitation. However, since the automatic generation process is uncontrollable, the generated images are usually limited in diversity, and some of them are undesired. In this paper, we propose a human-guided image generation method for more controllable dataset expansion. We develop a multi-modal projection method with theoretical guarantees to facilitate the exploration of both the original and generated images. Based on the exploration, users refine the prompts and re-generate images for better performance. Since directly refining the prompts is challenging for novice users, we develop a sample-level prompt refinement method to make it easier. With this method, users only need to provide sample-level feedback (e.g., which samples are undesired) to obtain better prompts. The effectiveness of our method is demonstrated through the quantitative evaluation of the multi-modal projection method, improved model performance in the case study for both classification and object detection tasks, and positive feedback from the experts.

[Arxiv](https://arxiv.org/abs/2412.16839)