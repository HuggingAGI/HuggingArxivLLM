# 跨图像对比解码：缓解大型视觉语言模型中的语言偏见

发布时间：2025年05月15日

`LLM应用` `计算机视觉` `图像处理`

> Mitigate Language Priors in Large Vision-Language Models by Cross-Images Contrastive Decoding

# 摘要

> 语言先验是大型视觉-语言模型（LVLMs）产生幻觉的主要原因之一，会导致模型生成语言合理但视觉不一致的内容。这些先验源自其预训练的大型语言模型（LLM）主干中的语言知识，是模型的固有属性，与视觉输入无关。受这一发现启发，我们提出了一种简单有效的无训练方法——跨图像对比解码（CICD），用于缓解LVLMs中的语言先验问题。CICD首先识别关键和有害的先验，然后通过对比解码消除有害的先验。这种方法既防止生成幻觉内容，又保持文本的流畅性和连贯性。此外，图像间信息重叠有限，有助于防止对比解码过程中视觉信息丢失。我们在四个基准数据集上，使用六种LVLMs验证了CICD的有效性。实验表明，CICD在缓解语言先验方面表现出色，尤其在图像描述任务中，该问题最为突出。代码将在被接受后公开发布。

> Language priors constitute one of the primary causes of hallucinations in Large Vision-Language Models (LVLMs), driving the models to generate linguistically plausible yet visually inconsistent content. The language priors in LVLMs originate from the linguistic knowledge inherited from their pre-trained Large Language Model (LLM) backbone. Consequently, this characteristic is an intrinsic property of the model that remains independent of visual inputs. Inspired by the finding that language priors are consistent across images, we propose Cross-Image Contrastive Decoding (CICD), a simple yet effective training-free method to alleviate language priors in LVLMs. CICD first identifies essential and detrimental priors, and then employs contrastive decoding to eliminate the detrimental ones. This approach simultaneously prevents LVLMs from generating hallucinated content while maintaining textual fluency and coherence. Furthermore, the limited information overlap between images helps prevent visual information loss during contrastive decoding. We validate the effectiveness of CICD on four benchmarks with six LVLMs. Our experiments demonstrate that CICD performs remarkably well in mitigating language priors, especially in the image captioning task, where such priors are most pronounced. Code will be released once accepted.

[Arxiv](https://arxiv.org/abs/2505.10634)