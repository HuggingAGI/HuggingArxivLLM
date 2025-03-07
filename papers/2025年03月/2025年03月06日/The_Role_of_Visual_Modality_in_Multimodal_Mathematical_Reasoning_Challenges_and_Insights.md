# 视觉元素在多模态数学问题解决中的角色：挑战与启发

发布时间：2025年03月06日

`LLM应用` `数学教育` `计算机视觉`

> The Role of Visual Modality in Multimodal Mathematical Reasoning: Challenges and Insights

# 摘要

>  近年来，研究领域日益关注多模态数学推理，尤其着重于构建相关数据集与基准测试。尽管如此，视觉信息在推理过程中所扮演的角色却鲜有探索。我们的研究表明，现有的多模态数学模型对视觉信息的利用几乎未加重视，且模型性能在数据集图像的更改或移除后仍基本不受影响。这主要归因于文本信息与答案选项的主导地位，它们无意间引导模型走向正确答案。为了改进评估方法，我们推出HC-M3D数据集，专为需要依赖图像解决问题而设计，并通过呈现相似却关键不同的图像来挑战模型，这些图像会改变正确答案。在对领先模型的测试中，它们未能察觉这些细微的视觉差异，这表明当前视觉感知能力存在局限。此外，我们发现通过结合多种图像编码器来提升通用视觉问答（VQA）能力的常见做法，并未对数学推理性能产生助益。这一发现也为提升数学推理过程中对视觉信息的依赖提出了新的挑战。我们的基准测试与代码已开放，详情请访问\href{https://github.com/Yufang-Liu/visual_modality_role}{https://github.com/Yufang-Liu/visual\_modality\_role}。


> Recent research has increasingly focused on multimodal mathematical reasoning, particularly emphasizing the creation of relevant datasets and benchmarks. Despite this, the role of visual information in reasoning has been underexplored. Our findings show that existing multimodal mathematical models minimally leverage visual information, and model performance remains largely unaffected by changes to or removal of images in the dataset. We attribute this to the dominance of textual information and answer options that inadvertently guide the model to correct answers. To improve evaluation methods, we introduce the HC-M3D dataset, specifically designed to require image reliance for problem-solving and to challenge models with similar, yet distinct, images that change the correct answer. In testing leading models, their failure to detect these subtle visual differences suggests limitations in current visual perception capabilities. Additionally, we observe that the common approach of improving general VQA capabilities by combining various types of image encoders does not contribute to math reasoning performance. This finding also presents a challenge to enhancing visual reliance during math reasoning. Our benchmark and code would be available at \href{https://github.com/Yufang-Liu/visual_modality_role}{https://github.com/Yufang-Liu/visual\_modality\_role}.

[Arxiv](https://arxiv.org/abs/2503.04167)