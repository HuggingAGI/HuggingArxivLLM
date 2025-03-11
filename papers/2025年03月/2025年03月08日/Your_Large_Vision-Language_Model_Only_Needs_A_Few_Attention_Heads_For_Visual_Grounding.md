# # 您的大型视觉-语言模型只需少量注意力头即可实现视觉定位

发布时间：2025年03月08日

`LLM理论` `计算机视觉`

> Your Large Vision-Language Model Only Needs A Few Attention Heads For Visual Grounding

# 摘要

> # 视觉定位
视觉定位的目标是定位与自由形式文本描述相对应的图像区域。近期，大型视觉语言模型（LVLMs）强大的多模态能力推动了视觉定位的显著改进，尽管它们不可避免地需要微调和额外的模型组件来显式生成边界框或分割掩码。然而，我们发现冻结的LVLMs中的一些注意力头具有强大的视觉定位能力。我们称这些始终捕捉与文本语义相关的目标位置的注意力头为定位头。利用定位头，我们引入了一个简单有效的无需训练的视觉定位框架，该框架利用定位头生成的文本到图像注意力图来识别目标物体。令人惊讶的是，仅需数千个注意力头中的三个就足以实现与现有基于LVLM的视觉定位方法相媲美的定位性能，而这些方法需要微调。我们的发现表明，LVLMs能够基于对文本-图像关系的深刻理解，天然地实现物体定位，因为它们会隐式地关注相关图像区域以生成信息丰富的文本输出。所有源代码将对公众开放。


> Visual grounding seeks to localize the image region corresponding to a free-form text description. Recently, the strong multimodal capabilities of Large Vision-Language Models (LVLMs) have driven substantial improvements in visual grounding, though they inevitably require fine-tuning and additional model components to explicitly generate bounding boxes or segmentation masks. However, we discover that a few attention heads in frozen LVLMs demonstrate strong visual grounding capabilities. We refer to these heads, which consistently capture object locations related to text semantics, as localization heads. Using localization heads, we introduce a straightforward and effective training-free visual grounding framework that utilizes text-to-image attention maps from localization heads to identify the target objects. Surprisingly, only three out of thousands of attention heads are sufficient to achieve competitive localization performance compared to existing LVLM-based visual grounding methods that require fine-tuning. Our findings suggest that LVLMs can innately ground objects based on a deep comprehension of the text-image relationship, as they implicitly focus on relevant image regions to generate informative text outputs. All the source codes will be made available to the public.

[Arxiv](https://arxiv.org/abs/2503.06287)