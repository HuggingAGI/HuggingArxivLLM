# PrefixKV：自适应前缀 KV 缓存乃视觉指令跟随模型实现高效生成之所需。

发布时间：2024年12月04日

`LLM应用` `计算机视觉` `多模态`

> PrefixKV: Adaptive Prefix KV Cache is What Vision Instruction-Following Models Need for Efficient Generation

# 摘要

> 最近，大型视觉语言模型（LVLMs）凭借其面对多样多模态输入时强大的生成与推理能力迅速走红。然而，这些模型在推理时会产生巨大的计算和内存开销，严重阻碍了在实际场景中的有效运用。由冗长的输入和输出序列所必需的大量键值（KV）缓存，显著拉高了推理成本。基于此，近期的工作探索了减小 KV 缓存大小以提升效率的办法。虽然有效，但它们往往忽略了 KV 向量在各层的不同重要性分布，在预测下一个标记时为每层保持相同的缓存大小。这致使某些层的关键上下文信息丢失，造成性能大幅下滑。为解决此问题，我们推出了 PrefixKV。它将确定所有层的 KV 缓存大小这一挑战重新定义为寻找最优全局前缀配置的任务。通过基于二分搜索的自适应分层 KV 保留方案，能够在每一层保留最多的上下文信息，利于生成。大量实验表明，与其他方法相比，我们的方法达到了业界领先的性能。它展现出卓越的推理效率和生成质量的平衡，在实际应用中显示出巨大潜力。代码可在 url{https://github.com/THU-MIG/PrefixKV}获取。

> Recently, large vision-language models (LVLMs) have rapidly gained popularity for their strong generation and reasoning capabilities given diverse multimodal inputs. However, these models incur significant computational and memory overhead during inference, which greatly hinders the efficient deployment in practical scenarios. The extensive key-value (KV) cache, necessitated by the lengthy input and output sequences, notably contributes to the high inference cost. Based on this, recent works have investigated ways to reduce the KV cache size for higher efficiency. Although effective, they generally overlook the distinct importance distributions of KV vectors across layers and maintain the same cache size for each layer during the next token prediction. This results in the significant contextual information loss for certain layers, leading to notable performance decline. To address this, we present PrefixKV. It reframes the challenge of determining KV cache sizes for all layers into the task of searching for the optimal global prefix configuration. With an adaptive layer-wise KV retention recipe based on binary search, the maximum contextual information can thus be preserved in each layer, facilitating the generation. Extensive experiments demonstrate that our method achieves the state-of-the-art performance compared with others. It exhibits superior inference efficiency and generation quality trade-offs, showing promising potential for practical applications. Code is available at url{https://github.com/THU-MIG/PrefixKV}.

[Arxiv](https://arxiv.org/abs/2412.03409)