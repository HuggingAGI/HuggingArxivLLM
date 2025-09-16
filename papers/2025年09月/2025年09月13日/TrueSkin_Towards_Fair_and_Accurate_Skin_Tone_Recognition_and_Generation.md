# TrueSkin：迈向公平准确的肤色识别与生成

发布时间：2025年09月13日

`其他` `医疗健康`

> TrueSkin: Towards Fair and Accurate Skin Tone Recognition and Generation

# 摘要

> 肤色识别与生成在模型公平性、医疗健康及生成式AI领域中扮演着关键角色，然而，受限于缺乏全面的数据集和稳健的方法，这一任务至今仍颇具挑战。与其他人体图像分析任务相比，当前最先进的大型多模态模型（LMMs）和图像生成模型在准确识别与合成肤色方面表现欠佳。为此，我们构建了TrueSkin数据集——该数据集包含7299张图像，按6个类别系统分类，并在多样化的光照条件、相机角度及拍摄参数下采集。借助TrueSkin，我们对现有识别与生成方法进行了基准测试，结果发现了显著偏差：LMMs倾向于将中等肤色误判为较浅肤色，而生成模型在提示中无关属性（如发型或环境背景）的固有偏差影响下，难以准确生成指定肤色。我们进一步验证，在TrueSkin上训练的识别模型相较于LMMs和传统方法，分类准确率提升超20%；同时，使用TrueSkin进行微调能显著增强图像生成模型中肤色的保真度。研究结果表明，TrueSkin这类全面数据集至关重要——它不仅可作为评估现有模型的基准，还能提供宝贵的训练资源，从而提升肤色识别与生成任务的公平性和准确性。

> Skin tone recognition and generation play important roles in model fairness, healthcare, and generative AI, yet they remain challenging due to the lack of comprehensive datasets and robust methodologies. Compared to other human image analysis tasks, state-of-the-art large multimodal models (LMMs) and image generation models struggle to recognize and synthesize skin tones accurately. To address this, we introduce TrueSkin, a dataset with 7299 images systematically categorized into 6 classes, collected under diverse lighting conditions, camera angles, and capture settings. Using TrueSkin, we benchmark existing recognition and generation approaches, revealing substantial biases: LMMs tend to misclassify intermediate skin tones as lighter ones, whereas generative models struggle to accurately produce specified skin tones when influenced by inherent biases from unrelated attributes in the prompts, such as hairstyle or environmental context. We further demonstrate that training a recognition model on TrueSkin improves classification accuracy by more than 20\% compared to LMMs and conventional approaches, and fine-tuning with TrueSkin significantly improves skin tone fidelity in image generation models. Our findings highlight the need for comprehensive datasets like TrueSkin, which not only serves as a benchmark for evaluating existing models but also provides a valuable training resource to enhance fairness and accuracy in skin tone recognition and generation tasks.

[Arxiv](https://arxiv.org/abs/2509.10980)