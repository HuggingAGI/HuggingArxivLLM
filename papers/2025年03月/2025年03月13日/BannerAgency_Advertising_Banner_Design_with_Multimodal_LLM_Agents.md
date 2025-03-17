# BannerAgency: 广告横幅设计与多模态大语言模型代理

发布时间：2025年03月13日

`LLM应用

理由：这篇论文展示了多模态大型语言模型（MLLMs）在自动化广告横幅设计中的具体应用，属于将LLM技术应用到实际任务中的实例。` `设计工具`

> BannerAgency: Advertising Banner Design with Multimodal LLM Agents

# 摘要

> 广告横幅是吸引用户注意和提升广告效果的关键。然而，设计既美观又能有效传达信息的横幅极具挑战性，因为涉及多个设计元素。此外，广告商需要不同尺寸以适应各种设备，并制作多个版本以针对不同受众。由于设计本质上是迭代且主观的，因此灵活的编辑能力在实际应用中尤为重要。尽管现有模型在设计任务中作为设计师的辅助工具，但它们通常只能处理创意设计的一部分，或生成难以编辑的像素化输出。本文提出了一种无训练的框架，利用前沿多模态大型语言模型（MLLMs），实现全自动化横幅设计，大幅减少人工干预。我们推出了BannerAgency，一个MLLM代理系统，与广告商合作理解品牌和目标，生成背景图像，设计前景元素蓝图，并以可编辑的Figma或SVG格式呈现最终创意。为了促进评估和研究，我们创建了BannerRequest400基准，包含100个独特徽标与400个多样化横幅请求。通过评估，我们展示了该框架在设计质量、适应性和编辑能力方面的优势。


> Advertising banners are critical for capturing user attention and enhancing advertising campaign effectiveness. Creating aesthetically pleasing banner designs while conveying the campaign messages is challenging due to the large search space involving multiple design elements. Additionally, advertisers need multiple sizes for different displays and various versions to target different sectors of audiences. Since design is intrinsically an iterative and subjective process, flexible editability is also in high demand for practical usage. While current models have served as assistants to human designers in various design tasks, they typically handle only segments of the creative design process or produce pixel-based outputs that limit editability. This paper introduces a training-free framework for fully automated banner ad design creation, enabling frontier multimodal large language models (MLLMs) to streamline the production of effective banners with minimal manual effort across diverse marketing contexts. We present BannerAgency, an MLLM agent system that collaborates with advertisers to understand their brand identity and banner objectives, generates matching background images, creates blueprints for foreground design elements, and renders the final creatives as editable components in Figma or SVG formats rather than static pixels. To facilitate evaluation and future research, we introduce BannerRequest400, a benchmark featuring 100 unique logos paired with 400 diverse banner requests. Through quantitative and qualitative evaluations, we demonstrate the framework's effectiveness, emphasizing the quality of the generated banner designs, their adaptability to various banner requests, and their strong editability enabled by this component-based approach.

[Arxiv](https://arxiv.org/abs/2503.11060)