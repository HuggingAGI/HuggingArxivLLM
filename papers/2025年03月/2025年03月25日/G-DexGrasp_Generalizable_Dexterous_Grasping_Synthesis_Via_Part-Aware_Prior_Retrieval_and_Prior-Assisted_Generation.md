# G-DexGrasp：通用灵巧抓取合成，基于部件感知先验检索与先验辅助生成

发布时间：2025年03月25日

`其他` `机器人技术` `人工智能`

> G-DexGrasp: Generalizable Dexterous Grasping Synthesis Via Part-Aware Prior Retrieval and Prior-Assisted Generation

# 摘要

> 灵巧抓取合成领域近期取得了显著进展，能够为多种任务生成合理且可信的抓取方案。然而，如何将其成功推广到未见过的对象类别和多样化任务指令仍是一个难题。本文提出了一种名为 G-DexGrasp 的检索增强生成方法，能够为未见过的对象类别和语言描述的任务指令生成高质量的灵巧手部配置。其核心在于检索可推广的抓取先验知识，包括精细接触部位和与任务相关的抓取实例分布，为后续合成流程提供指导。具体而言，精细接触部位和任务需求作为通用指导，帮助生成模型推断出适合未见过对象的合理抓取方案，而相关抓取分布则作为正则化手段，确保合成抓取在优化过程中的可信度。我们的对比实验验证了这一创新设计的有效性，并展示了其相较于现有方法的显著优势。项目页面：https://g-dexgrasp.github.io/

> Recent advances in dexterous grasping synthesis have demonstrated significant progress in producing reasonable and plausible grasps for many task purposes. But it remains challenging to generalize to unseen object categories and diverse task instructions. In this paper, we propose G-DexGrasp, a retrieval-augmented generation approach that can produce high-quality dexterous hand configurations for unseen object categories and language-based task instructions. The key is to retrieve generalizable grasping priors, including the fine-grained contact part and the affordance-related distribution of relevant grasping instances, for the following synthesis pipeline. Specifically, the fine-grained contact part and affordance act as generalizable guidance to infer reasonable grasping configurations for unseen objects with a generative model, while the relevant grasping distribution plays as regularization to guarantee the plausibility of synthesized grasps during the subsequent refinement optimization. Our comparison experiments validate the effectiveness of our key designs for generalization and demonstrate the remarkable performance against the existing approaches. Project page: https://g-dexgrasp.github.io/

[Arxiv](https://arxiv.org/abs/2503.19457)