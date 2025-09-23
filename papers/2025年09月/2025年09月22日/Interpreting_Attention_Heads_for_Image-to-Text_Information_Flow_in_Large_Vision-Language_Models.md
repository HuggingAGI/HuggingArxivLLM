# 解读大型视觉-语言模型中图像到文本信息流的注意力头

发布时间：2025年09月22日

`LLM理论` `基础理论`

> Interpreting Attention Heads for Image-to-Text Information Flow in Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）通过一系列注意力头将图像信息转化为文本，从而回答视觉问题。尽管这种图像到文本的信息流是视觉问答的核心，但由于大量注意力头同时运作，其背后的机制仍难以解读。为解决这一难题，我们提出了“头归因”技术——受组件归因方法启发，旨在识别信息传递中关键注意力头的一致模式。借助头归因技术，我们研究了LVLMs如何依靠特定注意力头识别并回答图像中主要对象的相关问题。分析发现，有一个独特的注意力头子集会促进图像到文本的信息流，且这些头的选择由输入图像的语义内容而非视觉外观决定。我们还在token层面考察了信息流，发现：（1）文本信息会先传播到角色相关token和最终token，之后才接收图像信息；（2）图像信息同时嵌入在对象相关token和背景token中。我们的研究表明，图像到文本的信息流遵循结构化过程，而在注意力头层面进行分析，为理解大型视觉语言模型的机制提供了一个富有前景的方向。

> Large Vision-Language Models (LVLMs) answer visual questions by transferring information from images to text through a series of attention heads. While this image-to-text information flow is central to visual question answering, its underlying mechanism remains difficult to interpret due to the simultaneous operation of numerous attention heads. To address this challenge, we propose head attribution, a technique inspired by component attribution methods, to identify consistent patterns among attention heads that play a key role in information transfer. Using head attribution, we investigate how LVLMs rely on specific attention heads to identify and answer questions about the main object in an image. Our analysis reveals that a distinct subset of attention heads facilitates the image-to-text information flow. Remarkably, we find that the selection of these heads is governed by the semantic content of the input image rather than its visual appearance. We further examine the flow of information at the token level and discover that (1) text information first propagates to role-related tokens and the final token before receiving image information, and (2) image information is embedded in both object-related and background tokens. Our work provides evidence that image-to-text information flow follows a structured process, and that analysis at the attention-head level offers a promising direction toward understanding the mechanisms of LVLMs.

[Arxiv](https://arxiv.org/abs/2509.17588)