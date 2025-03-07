# RetinalGPT：由大型视觉-语言模型驱动的视网膜临床偏好对话助手

发布时间：2025年03月05日

`LLM应用` `医学影像`

> RetinalGPT: A Retinal Clinical Preference Conversational Assistant Powered by Large Vision-Language Models

# 摘要

> 最近，多模态大型语言模型（MLLMs）因其处理和分析非文本数据（如图像、视频和音频）的强大能力而备受关注。值得注意的是，一些通用领域MLLMs在医学领域的应用，如LLaVA-Med，已经被探索。然而，这些医学领域的适应性模型在理解和解释视网膜图像方面仍显不足。相比之下，医学专家强调定量分析在疾病检测和解释中的重要性。这凸显了通用领域与医学领域MLLMs之间的差距：通用领域MLLMs在广泛应用中表现出色，但它们缺乏在医学领域进行精确诊断和解释任务所需的专业知识。

为了解决这些挑战，我们引入了	extit{RetinalGPT}，这是一个专注于临床偏好定量分析视网膜图像的多模态对话助手。具体而言，我们通过编译大型视网膜图像数据集、开发新型数据管道以及采用定制化视觉指令微调来提升视网膜分析能力并丰富医学知识。特别地，在8个基准视网膜数据集上，RetinalGPT在视网膜疾病诊断方面显著优于通用领域的MLLM。除了疾病诊断，RetinalGPT还提供定量分析和病灶定位功能，这标志着在利用LLMs构建可解释的端到端临床研究框架方面迈出了开创性的一步。代码可在https://github.com/Retinal-Research/RetinalGPT获取

> Recently, Multimodal Large Language Models (MLLMs) have gained significant attention for their remarkable ability to process and analyze non-textual data, such as images, videos, and audio. Notably, several adaptations of general-domain MLLMs to the medical field have been explored, including LLaVA-Med. However, these medical adaptations remain insufficiently advanced in understanding and interpreting retinal images. In contrast, medical experts emphasize the importance of quantitative analyses for disease detection and interpretation. This underscores a gap between general-domain and medical-domain MLLMs: while general-domain MLLMs excel in broad applications, they lack the specialized knowledge necessary for precise diagnostic and interpretative tasks in the medical field. To address these challenges, we introduce \textit{RetinalGPT}, a multimodal conversational assistant for clinically preferred quantitative analysis of retinal images. Specifically, we achieve this by compiling a large retinal image dataset, developing a novel data pipeline, and employing customized visual instruction tuning to enhance both retinal analysis and enrich medical knowledge. In particular, RetinalGPT outperforms MLLM in the generic domain by a large margin in the diagnosis of retinal diseases in 8 benchmark retinal datasets. Beyond disease diagnosis, RetinalGPT features quantitative analyses and lesion localization, representing a pioneering step in leveraging LLMs for an interpretable and end-to-end clinical research framework. The code is available at https://github.com/Retinal-Research/RetinalGPT

[Arxiv](https://arxiv.org/abs/2503.03987)