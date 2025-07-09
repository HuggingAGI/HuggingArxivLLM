# AIGI-Holmes：迈向通过多模态大型语言模型实现可解释且通用的AI生成图像检测

发布时间：2025年07月03日

`LLM应用` `计算机视觉` `信息安全`

> AIGI-Holmes: Towards Explainable and Generalizable AI-Generated Image Detection via Multimodal Large Language Models

# 摘要

> AI生成内容（AIGC）技术的快速发展导致了高度逼真的AI生成图像（AIGI）被滥用，用于传播虚假信息，对公共信息安全构成了威胁。尽管现有的AIGI检测技术通常有效，但它们面临两个关键问题：1）缺乏人类可验证的解释，2）在最新一代技术中缺乏泛化能力。为了解决这些问题，我们引入了一个大规模综合性数据集——霍姆斯数据集，其中包括霍姆斯SFT数据集（带有关于图像是否为AI生成的解释的指令微调数据集）和霍姆斯DPO数据集（与人类偏好对齐的数据集）。我们还介绍了一种高效的数据标注方法——多专家陪审团，通过结构化的多模态大语言模型解释和跨模型评估、专家缺陷过滤以及人类偏好修改的质量控制来增强数据生成。此外，我们提出了霍姆斯管道，这是一个精心设计的三阶段训练框架，包括视觉专家预训练、监督微调和直接偏好优化。霍姆斯管道将多模态大语言模型（MLLMs）适应于AIGI检测，同时生成人类可验证和与人类对齐的解释，最终得到我们的模型AIGI-霍姆斯。在推理阶段，我们引入了一种协作解码策略，将视觉专家对图像的感知与多模态大语言模型的语义推理相结合，进一步增强了模型的泛化能力。在三个基准上的广泛实验验证了我们AIGI-霍姆斯的有效性。

> The rapid development of AI-generated content (AIGC) technology has led to the misuse of highly realistic AI-generated images (AIGI) in spreading misinformation, posing a threat to public information security. Although existing AIGI detection techniques are generally effective, they face two issues: 1) a lack of human-verifiable explanations, and 2) a lack of generalization in the latest generation technology. To address these issues, we introduce a large-scale and comprehensive dataset, Holmes-Set, which includes the Holmes-SFTSet, an instruction-tuning dataset with explanations on whether images are AI-generated, and the Holmes-DPOSet, a human-aligned preference dataset. Our work introduces an efficient data annotation method called the Multi-Expert Jury, enhancing data generation through structured MLLM explanations and quality control via cross-model evaluation, expert defect filtering, and human preference modification. In addition, we propose Holmes Pipeline, a meticulously designed three-stage training framework comprising visual expert pre-training, supervised fine-tuning, and direct preference optimization. Holmes Pipeline adapts multimodal large language models (MLLMs) for AIGI detection while generating human-verifiable and human-aligned explanations, ultimately yielding our model AIGI-Holmes. During the inference stage, we introduce a collaborative decoding strategy that integrates the model perception of the visual expert with the semantic reasoning of MLLMs, further enhancing the generalization capabilities. Extensive experiments on three benchmarks validate the effectiveness of our AIGI-Holmes.

[Arxiv](https://arxiv.org/abs/2507.02664)