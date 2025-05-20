# 蒸馏语音音乐编码器：结合任务策略

发布时间：2025年05月19日

`其他` `语音处理` `音频处理`

> Distilling a speech and music encoder with task arithmetic

# 摘要

> 语音和音乐领域的自监督学习（SSL）虽有长足进步，但现有模型通常将二者割裂处理，限制了统一音频理解的能力。对于需要通用表示的应用（如音频大型语言模型），统一模型是理想选择。然而，直接为语音和音乐训练通用模型在计算上成本高昂。虽然教师模型集合的知识蒸馏可能是一个自然的解决方案，但我们认为将语音和音乐 SSL 模型的蒸馏过程解耦可以提供更大的灵活性。因此，我们提出学习蒸馏任务向量，然后通过线性插值将它们组合成一个统一的语音+音乐模型。这种策略通过可调节的权重实现了灵活的领域侧重，同时也简化了训练过程。在语音和音乐基准测试中的实验表明，与集合蒸馏相比，我们的方法在整体性能上表现更优。

> Despite the progress in self-supervised learning (SSL) for speech and music, existing models treat these domains separately, limiting their capacity for unified audio understanding. A unified model is desirable for applications that require general representations, e.g. audio large language models. Nonetheless, directly training a general model for speech and music is computationally expensive. Knowledge Distillation of teacher ensembles may be a natural solution, but we posit that decoupling the distillation of the speech and music SSL models allows for more flexibility. Thus, we propose to learn distilled task vectors and then linearly interpolate them to form a unified speech+music model. This strategy enables flexible domain emphasis through adjustable weights and is also simpler to train. Experiments on speech and music benchmarks demonstrate that our method yields superior overall performance compared to ensemble distillation.

[Arxiv](https://arxiv.org/abs/2505.13270)