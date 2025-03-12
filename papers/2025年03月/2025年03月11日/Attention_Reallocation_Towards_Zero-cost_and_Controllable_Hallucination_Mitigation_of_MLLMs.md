# 注意力重分配：零成本且可控的多语言大型语言模型幻觉缓解方案

发布时间：2025年03月11日

`LLM理论

理由：这篇论文探讨了多模态大型语言模型（MLLMs）中的幻觉问题，并提出了一种新的方法AttnReal来解决这一问题。研究集中在模型的注意力机制和内部工作原理上，属于对模型机制的理论分析和改进，因此归类为LLM理论。` `多模态模型` `模型优化`

> Attention Reallocation: Towards Zero-cost and Controllable Hallucination Mitigation of MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）在各类任务中表现出色，但幻觉问题仍是其痛点。现有无训练的缓解方法多通过回顾策略和对比解码增加推理开销，而我们提出了一种几乎零额外成本的注意力重分配（AttnReal）方法来解决这一问题。基于MLLM的不合理注意力分布导致特征被历史输出token主导，以及不同token类型之间的分布差异进一步引发幻觉的观察，AttnReal通过回收输出token的过多注意力并重新分配给视觉token，减少了模型对语言先验的依赖，使解码过程更依赖视觉输入。更值得一提的是，我们发现通过调节AttnReal的强度，可以在响应忠实度和整体性能之间实现灵活的权衡。来自不同基准的综合实验结果证实了AttnReal在六种开源MLLM和三种解码策略中的有效性。

> Multi-Modal Large Language Models (MLLMs) stand out in various tasks but still struggle with hallucinations. While recent training-free mitigation methods mostly introduce additional inference overhead via retrospection strategy and contrastive decoding, we propose attention reallocation (AttnReal) to mitigate hallucinations with nearly zero extra cost. Our approach is motivated by the key observations that, MLLM's unreasonable attention distribution causes features to be dominated by historical output tokens, which further contributes to hallucinated responses because of the distribution gap between different token types. Based on the observations, AttnReal recycles excessive attention from output tokens and reallocates it to visual tokens, which reduces MLLM's reliance on language priors and ensures the decoding process depends more on the visual inputs. More interestingly, we find that, by controlling the intensity of AttnReal, we can achieve a wide-range trade-off between the response faithfulness and overall performance. Comprehensive results from different benchmarks validate the effectiveness of AttnReal across six open-source MLLMs and three decoding strategies.

[Arxiv](https://arxiv.org/abs/2503.08342)