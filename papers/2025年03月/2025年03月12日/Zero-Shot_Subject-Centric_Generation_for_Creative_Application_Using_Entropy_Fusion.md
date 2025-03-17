# # 摘要  
熵融合驱动的零样本主体生成方法及其创意应用探索

发布时间：2025年03月12日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在视觉内容生成中的应用，特别是通过代理框架将用户输入转化为更详细的提示，从而生成高质量的图像。虽然涉及了代理框架，但核心是LLM在图像生成任务中的应用，属于LLM应用类别。` `计算机视觉`

> Zero-Shot Subject-Centric Generation for Creative Application Using Entropy Fusion

# 摘要

> 生成模型在视觉内容创作领域应用广泛。然而，在实际应用中，现有的文本到图像模型常常面临挑战，尤其是在纺织图案设计和表情包生成等场景中，难以用现有方法分离出不想要的元素。与此同时，主体参考生成已成为一个重要研究趋势，强调需要能够生成干净、高质量主体图像同时有效去除多余组件的技术。为了解决这一挑战，我们提出了一种可靠的主体中心图像生成框架。在本研究中，我们提出了一种基于熵的特征加权融合方法，将从预训练文本到图像模型FLUX的每个采样步骤中获得的具有信息量的交叉注意力特征进行融合，从而实现精确的掩膜预测和主体中心生成。此外，我们还开发了一个基于大型语言模型（LLMs）的代理框架，该框架能够将用户的日常输入转化为更具描述性的提示，从而生成高度详细的图像。同时，代理框架从提示中提取主要元素，以指导基于熵的特征融合，确保生成过程中专注于主要元素，避免多余组件的出现。实验结果和用户研究均表明，我们的方法能够生成高质量的主体中心图像，并在性能上超越现有方法或其它可能的流水线，充分证明了我们方法的有效性。

> Generative models are widely used in visual content creation. However, current text-to-image models often face challenges in practical applications-such as textile pattern design and meme generation-due to the presence of unwanted elements that are difficult to separate with existing methods. Meanwhile, subject-reference generation has emerged as a key research trend, highlighting the need for techniques that can produce clean, high-quality subject images while effectively removing extraneous components. To address this challenge, we introduce a framework for reliable subject-centric image generation. In this work, we propose an entropy-based feature-weighted fusion method to merge the informative cross-attention features obtained from each sampling step of the pretrained text-to-image model FLUX, enabling a precise mask prediction and subject-centric generation. Additionally, we have developed an agent framework based on Large Language Models (LLMs) that translates users' casual inputs into more descriptive prompts, leading to highly detailed image generation. Simultaneously, the agents extract primary elements of prompts to guide the entropy-based feature fusion, ensuring focused primary element generation without extraneous components. Experimental results and user studies demonstrate our methods generates high-quality subject-centric images, outperform existing methods or other possible pipelines, highlighting the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2503.10697)