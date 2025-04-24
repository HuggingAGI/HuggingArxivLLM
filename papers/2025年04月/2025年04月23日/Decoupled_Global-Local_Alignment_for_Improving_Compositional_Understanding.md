# 解耦全局与局部对齐，增强组合理解能力

发布时间：2025年04月23日

`由于摘要翻译失败，无法获取论文的具体内容和主题，因此无法进行分类。请提供完整的摘要以便进行分类。` `知识图谱`

> Decoupled Global-Local Alignment for Improving Compositional Understanding

# 摘要

> <翻译失败>

> Contrastive Language-Image Pre-training (CLIP) has achieved success on multiple downstream tasks by aligning image and text modalities. However, the nature of global contrastive learning limits CLIP's ability to comprehend compositional concepts, such as relations and attributes. Although recent studies employ global hard negative samples to improve compositional understanding, these methods significantly compromise the model's inherent general capabilities by forcibly distancing textual negative samples from images in the embedding space. To overcome this limitation, we introduce a Decoupled Global-Local Alignment (DeGLA) framework that improves compositional understanding while substantially mitigating losses in general capabilities. To optimize the retention of the model's inherent capabilities, we incorporate a self-distillation mechanism within the global alignment process, aligning the learnable image-text encoder with a frozen teacher model derived from an exponential moving average. Under the constraint of self-distillation, it effectively mitigates the catastrophic forgetting of pretrained knowledge during fine-tuning. To improve compositional understanding, we first leverage the in-context learning capability of Large Language Models (LLMs) to construct about 2M high-quality negative captions across five types. Subsequently, we propose the Image-Grounded Contrast (IGC) loss and Text-Grounded Contrast (TGC) loss to enhance vision-language compositionally. Extensive experimental results demonstrate the effectiveness of the DeGLA framework. Compared to previous state-of-the-art methods, DeGLA achieves an average enhancement of 3.5% across the VALSE, SugarCrepe, and ARO benchmarks. Concurrently, it obtains an average performance improvement of 13.0% on zero-shot classification tasks across eleven datasets. Our code will be released at https://github.com/xiaoxing2001/DeGLA

[Arxiv](https://arxiv.org/abs/2504.16801)