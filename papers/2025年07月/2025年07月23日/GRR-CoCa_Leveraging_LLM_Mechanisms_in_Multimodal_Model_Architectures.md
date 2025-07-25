# GRR-CoCa：多模态模型架构中的LLM机制利用

发布时间：2025年07月23日

`其他` `多模态模型` `视觉-语言`

> GRR-CoCa: Leveraging LLM Mechanisms in Multimodal Model Architectures

# 摘要

> 最先进（SOTA）的图像与文本生成模型是多模态模型，与大型语言模型（LLMs）有许多相似之处。尽管取得了强大的性能，但当前多模态基础模型架构在复杂性上仍落后于当代LLMs。我们提出了一种改进的SOTA对比式描述生成器（CoCa）模型——GRR-CoCa，它将高斯误差门控线性单元、均方根归一化和旋转位置嵌入整合到文本解码器和视觉变压器（ViT）编码器中。这些架构修改在LLMs中已被证明可以提升性能，但尚未被CoCa采用。

我们通过改进的文本解码器但保留CoCa原始ViT编码器的Baseline CoCa作为基准模型，使用标准的预训练和微调工作流程在对比和生成任务上对模型进行了基准测试。结果显示，GRR-CoCa在预训练数据集和三个多样化的微调数据集上均显著优于Baseline CoCa。具体而言，预训练阶段的改进包括对比损失降低27.25%、困惑度降低3.71%、CoCa损失降低7.15%。微调阶段的改进平均值为对比损失降低13.66%、困惑度降低5.18%、CoCa损失降低5.55%。这表明，GRR-CoCa的改进架构在视觉-语言领域不仅提升了性能，还增强了模型的泛化能力。

> State-of-the-art (SOTA) image and text generation models are multimodal models that have many similarities to large language models (LLMs). Despite achieving strong performances, leading foundational multimodal model architectures frequently lag behind the architectural sophistication of contemporary LLMs. We propose GRR-CoCa, an improved SOTA Contrastive Captioner (CoCa) model that incorporates Gaussian error gated linear units, root mean squared normalization, and rotary positional embedding into the textual decoders and the vision transformer (ViT) encoder. Each architectural modification has been shown to improve model performance in LLMs, but has yet to be adopted in CoCa. We benchmarked GRR-CoCa against Baseline CoCa, a model with the same modified textual decoders but with CoCa's original ViT encoder. We used standard pretraining and fine-tuning workflows to benchmark the models on contrastive and generative tasks. Our GRR-CoCa significantly outperformed Baseline CoCa on the pretraining dataset and three diverse fine-tuning datasets. Pretraining improvements were 27.25% in contrastive loss, 3.71% in perplexity, and 7.15% in CoCa loss. The average fine-tuning improvements were 13.66% in contrastive loss, 5.18% in perplexity, and 5.55% in CoCa loss. We show that GRR-CoCa's modified architecture improves performance and generalization across vision-language domains.

[Arxiv](https://arxiv.org/abs/2507.18009)