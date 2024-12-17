# ColorFlow：检索增强型图像序列着色

发布时间：2024年12月16日

`其他`

> ColorFlow: Retrieval-Augmented Image Sequence Colorization

# 摘要

> 自动为黑白图像序列着色并保留角色和对象标识（ID）是一项复杂且市场需求巨大的任务，比如在卡通或漫画系列的着色中。尽管利用大规模生成模型（如扩散模型）在视觉着色方面有所进展，但可控性和标识一致性方面仍存在挑战，导致当前方案不适用于工业应用。为此，我们提出了 ColorFlow，这是一个专为工业应用中的图像序列着色打造的基于扩散的三阶段框架。与需要对每个 ID 进行微调或提取显式 ID 嵌入的现有方法不同，我们提出了一种新颖、强大且通用的检索增强着色管线，用于借助相关颜色参考为图像着色。我们的管线还采用了双分支设计：一个分支用于颜色标识提取，另一个用于着色，充分发挥了扩散模型的优势。我们在扩散模型中运用自注意力机制，实现强大的上下文学习和颜色标识匹配。为评估我们的模型，我们引入了 ColorFlow-Bench，这是一个基于参考着色的综合基准。结果显示，ColorFlow 在多个指标上优于现有模型，为顺序图像着色树立了新标杆，有望为艺术行业带来益处。我们在项目页面（https://zhuang2002.github.io/ColorFlow/）上发布了代码和模型。

> Automatic black-and-white image sequence colorization while preserving character and object identity (ID) is a complex task with significant market demand, such as in cartoon or comic series colorization. Despite advancements in visual colorization using large-scale generative models like diffusion models, challenges with controllability and identity consistency persist, making current solutions unsuitable for industrial application.To address this, we propose ColorFlow, a three-stage diffusion-based framework tailored for image sequence colorization in industrial applications. Unlike existing methods that require per-ID finetuning or explicit ID embedding extraction, we propose a novel robust and generalizable Retrieval Augmented Colorization pipeline for colorizing images with relevant color references. Our pipeline also features a dual-branch design: one branch for color identity extraction and the other for colorization, leveraging the strengths of diffusion models. We utilize the self-attention mechanism in diffusion models for strong in-context learning and color identity matching. To evaluate our model, we introduce ColorFlow-Bench, a comprehensive benchmark for reference-based colorization. Results show that ColorFlow outperforms existing models across multiple metrics, setting a new standard in sequential image colorization and potentially benefiting the art industry. We release our codes and models on our project page: https://zhuang2002.github.io/ColorFlow/.

[Arxiv](https://arxiv.org/abs/2412.11815)