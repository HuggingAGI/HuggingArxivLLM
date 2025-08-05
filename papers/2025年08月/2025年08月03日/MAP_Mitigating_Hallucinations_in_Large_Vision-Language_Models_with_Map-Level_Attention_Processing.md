# MAP：通过地图级注意力处理缓解大型视觉语言模型中的幻觉问题

发布时间：2025年08月03日

`LLM应用` `视觉语言模型`

> MAP: Mitigating Hallucinations in Large Vision-Language Models with Map-Level Attention Processing

# 摘要

> 大型视觉语言模型（LVLMs）在多模态任务中表现卓越，但幻觉问题依然存在，即生成内容语法正确却与视觉输入不符。为解决这一问题，我们提出了一种创新的地图级视角，将模型的隐藏状态视为二维语义地图。通过研究发现，事实信息在这一地图中分布广泛，远超现有方法（如对比解码和分层一致性）关注的局部区域。基于此发现，我们提出无需训练的地图级注意力处理（MAP）方法，通过基于注意力的地图级操作有效利用事实信息，提升模型的事实一致性。具体而言，我们采用分层交叉注意力，逐步通过跨层和跨层维度的token聚合，优化每层解码中的token表示。此外，全局-局部逻辑融合机制结合全局注意力前后获得的逻辑值，进一步优化预测并提升准确性。实验结果表明，我们的方法在多个基准测试（如POPE、MME和MMHal-Bench）中显著提升了LVLMs的真实性和性能，充分展现了地图级解码策略的潜力。

> Large Vision-Language Models (LVLMs) have achieved impressive performance in multimodal tasks, but they still suffer from hallucinations, i.e., generating content that is grammatically accurate but inconsistent with visual inputs. In this work, we introduce a novel map-level perspective to mitigate hallucinations in LVLMs, interpreting the hidden states of the model as a 2D semantic map. We observe that factual information is widely distributed across this map, extending beyond the localized inter- or intra-layer regions targeted by most existing methods (e.g., contrastive decoding and layer-wise consistency). Building on this insight, we propose Map-Level Attention Processing (MAP), a training-free decoding method that effectively leverages factual information through attention-based map-level operations to improve factual consistency. Specifically, we employ Layer-Wise Criss-Cross Attention to progressively refine token representations at each decoding layer by aggregating tokens from both inter- and intra-layer dimensions. Additionally, a Global-Local Logit Fusion mechanism combines logits obtained before and after global attention to further refine predictions and improve accuracy. Our method consistently improves the truthfulness and performance of LVLMs across benchmarks, such as POPE, MME, and MMHal-Bench, demonstrating the potential of the map-level decoding strategy.

[Arxiv](https://arxiv.org/abs/2508.01653)