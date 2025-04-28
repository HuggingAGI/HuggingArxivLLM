# TextTIGER：基于文本的智能生成，结合实体提示优化实现文本到图像生成

发布时间：2025年04月25日

`LLM应用` `图像生成` `计算机视觉`

> TextTIGER: Text-based Intelligent Generation with Entity Prompt Refinement for Text-to-Image Generation

# 摘要

> 从包含特定实体的提示生成图像，要求模型尽可能保留与实体相关的知识。然而，由于实体数量庞大且不断涌现，完全记忆这些知识并不实际。为了解决这一问题，我们提出了基于文本的智能生成与实体提示优化（TextTIGER）。该方法通过增强提示中的实体知识，然后使用大型语言模型（LLMs）对增强后的描述进行总结，以缓解较长输入带来的性能下降。为了评估我们的方法，我们引入了WiT-Cub（带有说明和简单背景解释的WiT），这是一个包含说明、图像和实体列表的数据集。实验结果表明，TextTIGER在图像生成的多项标准指标上优于仅使用描述的提示方法。此外，多位标注者的评估证实，总结后的描述更具信息量，验证了LLMs生成简洁而丰富的描述的能力。这些发现表明，通过增强和总结与实体相关的描述来优化提示可以显著提升图像生成能力。代码和数据集将在接受后公开。

> Generating images from prompts containing specific entities requires models to retain as much entity-specific knowledge as possible. However, fully memorizing such knowledge is impractical due to the vast number of entities and their continuous emergence. To address this, we propose Text-based Intelligent Generation with Entity prompt Refinement (TextTIGER), which augments knowledge on entities included in the prompts and then summarizes the augmented descriptions using Large Language Models (LLMs) to mitigate performance degradation from longer inputs. To evaluate our method, we introduce WiT-Cub (WiT with Captions and Uncomplicated Background-explanations), a dataset comprising captions, images, and an entity list. Experiments on four image generation models and five LLMs show that TextTIGER improves image generation performance in standard metrics (IS, FID, and CLIPScore) compared to caption-only prompts. Additionally, multiple annotators' evaluation confirms that the summarized descriptions are more informative, validating LLMs' ability to generate concise yet rich descriptions. These findings demonstrate that refining prompts with augmented and summarized entity-related descriptions enhances image generation capabilities. The code and dataset will be available upon acceptance.

[Arxiv](https://arxiv.org/abs/2504.18269)