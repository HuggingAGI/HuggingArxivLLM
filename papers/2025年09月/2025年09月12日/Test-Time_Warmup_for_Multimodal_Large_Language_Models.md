# 测试时预热：多模态大语言模型

发布时间：2025年09月12日

`LLM应用` `基础理论`

> Test-Time Warmup for Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在文本与图像交叉领域的高级推理中潜力巨大，却尚未充分释放。这类模型通常集成LLM、视觉编码器和连接器，后者将视觉编码器的嵌入映射至LLM的文本嵌入空间。尽管各组件均在数十亿样本的大规模数据集上预训练，但整个多模态模型的训练样本却通常仅有数千（或数百万）个，这导致其在复杂推理任务中表现欠佳。为弥补这一缺陷，我们摒弃了依赖大规模标注数据微调的思路，转而提出测试时预热（Test-Time Warmup）方法——借助弱监督辅助任务的数据，针对每个测试样本动态调整MLLM。在Llama-Vision-Instruct模型上，该方法实现了显著性能提升：MMMU任务上相对提升4.03%，VQA-Rad上提升5.28%，GQA上提升1.63%。这证明推理前的“预热”操作能有效增强MLLMs在各类推理任务中的鲁棒性。

> Multimodal Large Language Models (MLLMs) hold great promise for advanced reasoning at the intersection of text and images, yet they have not fully realized this potential. MLLMs typically integrate an LLM, a vision encoder, and a connector that maps the vision encoder's embeddings into the LLM's text embedding space. Although each component is pretrained on massive datasets with billions of samples, the entire multimodal model is typically trained on only thousands (or a few million) samples, which can result in weak performance on complex reasoning tasks. To address these shortcomings, instead of relying on extensive labeled datasets for fine-tuning, we propose a Test-Time Warmup method that adapts the MLLM per test instance by leveraging data from weakly supervised auxiliary tasks. With our approach, we observe a relative performance improvement of 4.03% on MMMU, 5.28% on VQA-Rad, and 1.63% on GQA on the Llama-Vision-Instruct model. Our method demonstrates that 'warming up' before inference can enhance MLLMs' robustness across diverse reasoning tasks.

[Arxiv](https://arxiv.org/abs/2509.10641)