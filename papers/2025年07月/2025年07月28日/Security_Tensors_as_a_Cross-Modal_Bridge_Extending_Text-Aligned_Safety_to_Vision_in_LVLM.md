# 安全张量：构建跨模态桥梁，将文本对齐的安全性扩展至视觉领域（LVLM）

发布时间：2025年07月28日

`LLM应用` `多模态处理` `网络安全`

> Security Tensors as a Cross-Modal Bridge: Extending Text-Aligned Safety to Vision in LVLM

# 摘要

> 大型视觉语言模型（LVLMs）结合了对齐的大型语言模型（LLMs）与视觉模块，用于处理多模态输入。然而，现有的文本基LLMs安全机制无法直接应用于视觉模态，导致LVLMs易受有害图像输入的影响。为解决这一跨模态安全问题，我们提出了安全张量——在推理过程中通过文本或视觉模态应用的可训练输入向量。这些张量能够将文本的安全对齐机制迁移至视觉处理，而无需修改模型参数。我们通过精心策划的数据集对安全张量进行优化，该数据集包含三类样本：（i）需要被拒绝的恶意图像-文本对，（ii）与恶意查询在结构上相似的对比良性对，用于指导视觉依赖，以及（iii）保留模型功能的一般良性样本。实验结果表明，无论是文本还是视觉安全张量都能显著提升LVLMs抵御多种有害视觉输入的能力，同时在良性任务上保持几乎相同的表现。进一步的内部分析表明，安全张量成功激活了语言模块的文本“安全层”在视觉输入中的作用，从而有效地将基于文本的安全扩展至视觉模态。

> Large visual-language models (LVLMs) integrate aligned large language models (LLMs) with visual modules to process multimodal inputs. However, the safety mechanisms developed for text-based LLMs do not naturally extend to visual modalities, leaving LVLMs vulnerable to harmful image inputs. To address this cross-modal safety gap, we introduce security tensors - trainable input vectors applied during inference through either the textual or visual modality. These tensors transfer textual safety alignment to visual processing without modifying the model's parameters. They are optimized using a curated dataset containing (i) malicious image-text pairs requiring rejection, (ii) contrastive benign pairs with text structurally similar to malicious queries, with the purpose of being contrastive examples to guide visual reliance, and (iii) general benign samples preserving model functionality. Experimental results demonstrate that both textual and visual security tensors significantly enhance LVLMs' ability to reject diverse harmful visual inputs while maintaining near-identical performance on benign tasks. Further internal analysis towards hidden-layer representations reveals that security tensors successfully activate the language module's textual "safety layers" in visual inputs, thereby effectively extending text-based safety to the visual modality.

[Arxiv](https://arxiv.org/abs/2507.20994)