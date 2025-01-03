# LVD-2M: 一个包含时间密集字幕的长镜头视频数据集

发布时间：2024年10月14日

`其他

理由：这篇论文主要讨论的是视频生成模型的训练数据集构建，特别是长视频生成模型的训练数据集。虽然涉及到生成模型，但主要关注的是视频数据的筛选和标注流程，而不是直接与大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）相关。因此，将其分类为“其他”更为合适。` `视频生成` `数据集构建`

> LVD-2M: A Long-take Video Dataset with Temporally Dense Captions

# 摘要

> # 摘要
视频生成模型的效果高度依赖于训练数据集的质量。以往的视频生成模型大多基于短视频片段进行训练，而近期，直接在长视频上训练长视频生成模型的研究兴趣日益浓厚。然而，高质量长视频的匮乏阻碍了这一领域的进展。为推进长视频生成研究，我们期望构建一个具备四个关键特征的新数据集：（1）至少10秒的长视频，（2）无剪辑的长镜头视频，（3）大动作与多样化内容，（4）时间密集的标注。为此，我们提出了一套新流程，用于筛选高质量长镜头视频并生成时间密集的标注。具体而言，我们定义了一系列量化指标，如场景切换、动态程度和语义质量，以从海量源视频中筛选出高质量长镜头视频。随后，我们开发了分层视频标注流程，为长视频添加时间密集的标注。通过这一流程，我们构建了首个长镜头视频数据集LVD-2M，包含200万个长镜头视频，每个视频时长超过10秒，并配有时间密集的标注。我们通过微调视频生成模型生成动态长视频，进一步验证了LVD-2M的有效性。我们相信，这一工作将为未来长视频生成研究做出重要贡献。

> 
Abstract:The efficacy of video generation models heavily depends on the quality of their training datasets. Most previous video generation models are trained on short video clips, while recently there has been increasing interest in training long video generation models directly on longer videos. However, the lack of such high-quality long videos impedes the advancement of long video generation. To promote research in long video generation, we desire a new dataset with four key features essential for training long video generation models: (1) long videos covering at least 10 seconds, (2) long-take videos without cuts, (3) large motion and diverse contents, and (4) temporally dense captions. To achieve this, we introduce a new pipeline for selecting high-quality long-take videos and generating temporally dense captions. Specifically, we define a set of metrics to quantitatively assess video quality including scene cuts, dynamic degrees, and semantic-level quality, enabling us to filter high-quality long-take videos from a large amount of source videos. Subsequently, we develop a hierarchical video captioning pipeline to annotate long videos with temporally-dense captions. With this pipeline, we curate the first long-take video dataset, LVD-2M, comprising 2 million long-take videos, each covering more than 10 seconds and annotated with temporally dense captions. We further validate the effectiveness of LVD-2M by fine-tuning video generation models to generate long videos with dynamic motions. We believe our work will significantly contribute to future research in long video generation.
    

[Arxiv](https://arxiv.org/pdf/2410.10816)