# AVCD：通过对比解码减轻视听大型语言模型中的幻觉

发布时间：2025年05月27日

`LLM应用` `多模态模型` `音频处理`

> AVCD: Mitigating Hallucinations in Audio-Visual Large Language Models through Contrastive Decoding

# 摘要

> 幻觉依然是多模态大语言模型（MLLMs）中的重要挑战。为此，我们提出了音频-视觉对比解码（AVCD），一种无需训练的解码框架，专注于建模三模态交互并抑制由模态引起的幻觉。与传统的对比解码（CD）方法不同，AVCD 动态识别模态并应用注意力遮罩生成扰动 logits，特别适用于音频、视频和语言的复杂交互场景。我们还重新设计了 CD 框架，以支持三模态输入的联合处理，并引入了基于熵的自适应解码，进一步提升了解码效率。实验结果表明，AVCD 在 AVHBench 数据集上显著提升了 VideoLLaMA2 和 video-SALMONN 的准确率，分别提高了 6% 和 11%，展现了其强大的鲁棒性和泛化能力。

> Hallucination remains a major challenge in multimodal large language models (MLLMs). To address this, various contrastive decoding (CD) methods have been proposed that contrasts original logits with hallucinated logits generated from perturbed inputs. While CD has shown promise in vision-language models (VLMs), it is not well-suited for AV-LLMs, where hallucinations often emerge from both unimodal and cross-modal combinations involving audio, video, and language. These intricate interactions call for a more adaptive and modality-aware decoding strategy. In this paper, we propose Audio-Visual Contrastive Decoding (AVCD)-a novel, training-free decoding framework designed to model trimodal interactions and suppress modality-induced hallucinations in AV-LLMs. Unlike previous CD methods in VLMs that corrupt a fixed modality, AVCD leverages attention distributions to dynamically identify less dominant modalities and applies attentive masking to generate perturbed output logits. To support CD in a trimodal setting, we also reformulate the original CD framework to jointly handle audio, visual, and textual inputs. Finally, to improve efficiency, we introduce entropy-guided adaptive decoding, which selectively skips unnecessary decoding steps based on the model's confidence in its predictions. Extensive experiments demonstrate that AVCD consistently outperforms existing decoding methods. Especially, on the AVHBench dataset, it improves accuracy by 6% for VideoLLaMA2 and 11% for video-SALMONN, demonstrating strong robustness and generalizability.

[Arxiv](https://arxiv.org/abs/2505.20862)