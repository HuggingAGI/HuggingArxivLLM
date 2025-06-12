# 从判断到干预：借助流式内容监控，提前终止LLM的有害输出

发布时间：2025年06月11日

`LLM应用`

> From Judgment to Interference: Early Stopping LLM Harmful Outputs via Streaming Content Monitoring

# 摘要

> 尽管安全对齐已应用于大多数大型语言模型（LLM），但LLM服务提供商通常会在实际产品中部署后续的内容审核作为外部安全护栏。现有的内容审核主要采用传统的全面检测方式，即根据完整的LLM输出来判断其危害性，导致服务延迟较高。近期研究更关注于部分检测方法，其中审核人员会在生成过程中进行监督，并在检测到危害性时提前终止输出。然而，这些研究直接将基于全面检测范式训练的审核模型应用于不完整的输出，引入了训练-推理不匹配问题，从而降低了性能。本文探讨如何构建一个原生支持部分检测的数据与模型解决方案。在数据方面，我们构建了包含29,000个提示-响应对的FineHarm数据集，这些数据带有细粒度标注，为基于token级别的训练提供了合理的监督信号。然后，我们提出了流式内容监控器（SCM），该模型通过响应级别和token级别标签的双重监督进行训练，并能够跟踪LLM的输出流，及时判断其危害性。实验表明，SCM在仅查看响应中平均前18%的token情况下，获得了与全面检测相当的0.95+的宏F1分数。此外，SCM还可作为伪危害性标注器，用于提升安全对齐效果，并获得比DPO更高的无害性得分。

> Though safety alignment has been applied to most large language models (LLMs), LLM service providers generally deploy a subsequent moderation as the external safety guardrail in real-world products. Existing moderators mainly practice a conventional full detection, which determines the harmfulness based on the complete LLM output, causing high service latency. Recent works pay more attention to partial detection where moderators oversee the generation midway and early stop the output if harmfulness is detected, but they directly apply moderators trained with the full detection paradigm to incomplete outputs, introducing a training-inference gap that lowers the performance. In this paper, we explore how to form a data-and-model solution that natively supports partial detection. For the data, we construct FineHarm, a dataset consisting of 29K prompt-response pairs with fine-grained annotations to provide reasonable supervision for token-level training. Then, we propose the streaming content monitor, which is trained with dual supervision of response- and token-level labels and can follow the output stream of LLM to make a timely judgment of harmfulness. Experiments show that SCM gains 0.95+ in macro F1 score that is comparable to full detection, by only seeing the first 18% of tokens in responses on average. Moreover, the SCM can serve as a pseudo-harmfulness annotator for improving safety alignment and lead to a higher harmlessness score than DPO.

[Arxiv](https://arxiv.org/abs/2506.09996)