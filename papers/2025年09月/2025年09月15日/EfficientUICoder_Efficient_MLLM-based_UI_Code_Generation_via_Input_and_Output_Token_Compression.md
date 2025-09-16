# EfficientUICoder：借助输入与输出令牌压缩的MLLM高效UI代码生成

发布时间：2025年09月15日

`LLM应用` `工业与制造`

> EfficientUICoder: Efficient MLLM-based UI Code Generation via Input and Output Token Compression

# 摘要

> 多模态大型语言模型在UI转代码（UI2Code）任务中展现出卓越性能，大幅提升了网站开发效率。然而，由于需处理大量输入图像令牌和生成海量输出代码令牌，这类任务的计算开销远高于传统代码生成。我们的深入研究发现，图像与代码令牌中存在大量冗余——这不仅加剧了计算复杂度，还分散了对关键UI元素的注意力，导致生成的HTML文件冗长且常含无效内容。为此，我们提出了EfficientUICoder——一个用于高效UI代码生成的压缩框架，包含三个核心组件。首先，元素与布局感知令牌压缩模块通过检测元素区域并构建UI元素树，保留关键UI信息；其次，区域感知令牌精化模块利用注意力分数，剔除选定区域的低注意力令牌，同时整合未选定区域的高注意力令牌；最后，自适应重复令牌抑制模块通过跟踪HTML/CSS结构的出现频率并施加指数惩罚，动态减少重复生成。大量实验表明，EfficientUICoder在不降低网页质量的前提下实现了55%-60%的压缩率，并带来显著效率提升：在340亿参数级多模态大型语言模型上，计算成本降低44.9%，生成令牌数量减少41.4%，预填充时间缩短46.6%，推理时间减少48.8%。相关代码已开源，地址为https://github.com/WebPAI/EfficientUICoder。

> Multimodal Large Language Models have demonstrated exceptional performance in UI2Code tasks, significantly enhancing website development efficiency. However, these tasks incur substantially higher computational overhead than traditional code generation due to the large number of input image tokens and extensive output code tokens required. Our comprehensive study identifies significant redundancies in both image and code tokens that exacerbate computational complexity and hinder focus on key UI elements, resulting in excessively lengthy and often invalid HTML files. We propose EfficientUICoder, a compression framework for efficient UI code generation with three key components. First, Element and Layout-aware Token Compression preserves essential UI information by detecting element regions and constructing UI element trees. Second, Region-aware Token Refinement leverages attention scores to discard low-attention tokens from selected regions while integrating high-attention tokens from unselected regions. Third, Adaptive Duplicate Token Suppression dynamically reduces repetitive generation by tracking HTML/CSS structure frequencies and applying exponential penalties. Extensive experiments show EfficientUICoderachieves a 55%-60% compression ratio without compromising webpage quality and delivers superior efficiency improvements: reducing computational cost by 44.9%, generated tokens by 41.4%, prefill time by 46.6%, and inference time by 48.8% on 34B-level MLLMs. Code is available at https://github.com/WebPAI/EfficientUICoder.

[Arxiv](https://arxiv.org/abs/2509.12159)