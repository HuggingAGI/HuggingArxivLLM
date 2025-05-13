# L-SWAG：一种结合层样本激活与梯度信息的零样本视觉Transformer神经架构搜索方法

发布时间：2025年05月12日

`其他

<example>
论文摘要：无训练神经架构搜索（NAS）通过零成本（ZC）代理高效识别高性能神经网络。与多轮和单轮NAS方法不同，ZC-NAS不仅时间效率高，无需模型训练，还具有可解释性，代理设计通常基于理论。尽管该领域发展迅速，当前最优的ZC代理通常局限于已建立的卷积搜索空间。随着大型语言模型（LLMs）引领深度学习的未来，本研究将ZC代理的应用扩展至视觉变换器（ViTs）。我们提出了一种新的基准，使用Autoformer搜索空间在6个不同任务上进行评估，并提出了层样本激活与梯度信息（L-SWAG），这是一种新颖且可泛化的指标，能够表征卷积和变换器架构在14个任务中的特性。此外，先前研究强调了不同代理之间互补信息的重要性，推动了机器学习模型识别有用组合的需求。为了进一步提升ZC-NAS，我们引入了LIBRA-NAS（低信息增益与偏见再对齐），这是一种策略性结合代理以最佳表示特定基准的方法。将LIBRA-NAS整合到NAS搜索中，其在ImageNet1k上仅需0.1 GPU天即可识别出测试误差为17.0%的架构，优于进化和基于梯度的NAS技术。
其他
</example>` `计算机视觉` `神经架构搜索`

> L-SWAG: Layer-Sample Wise Activation with Gradients information for Zero-Shot NAS on Vision Transformers

# 摘要

> 无训练神经架构搜索（NAS）通过零成本（ZC）代理高效识别高性能神经网络。与多轮和单轮NAS方法不同，ZC-NAS不仅时间效率高，无需模型训练，还具有可解释性，代理设计通常基于理论。尽管该领域发展迅速，当前最优的ZC代理通常局限于已建立的卷积搜索空间。随着大型语言模型（LLMs）引领深度学习的未来，本研究将ZC代理的应用扩展至视觉变换器（ViTs）。我们提出了一种新的基准，使用Autoformer搜索空间在6个不同任务上进行评估，并提出了层样本激活与梯度信息（L-SWAG），这是一种新颖且可泛化的指标，能够表征卷积和变换器架构在14个任务中的特性。此外，先前研究强调了不同代理之间互补信息的重要性，推动了机器学习模型识别有用组合的需求。为了进一步提升ZC-NAS，我们引入了LIBRA-NAS（低信息增益与偏见再对齐），这是一种策略性结合代理以最佳表示特定基准的方法。将LIBRA-NAS整合到NAS搜索中，其在ImageNet1k上仅需0.1 GPU天即可识别出测试误差为17.0%的架构，优于进化和基于梯度的NAS技术。

> Training-free Neural Architecture Search (NAS) efficiently identifies high-performing neural networks using zero-cost (ZC) proxies. Unlike multi-shot and one-shot NAS approaches, ZC-NAS is both (i) time-efficient, eliminating the need for model training, and (ii) interpretable, with proxy designs often theoretically grounded. Despite rapid developments in the field, current SOTA ZC proxies are typically constrained to well-established convolutional search spaces. With the rise of Large Language Models shaping the future of deep learning, this work extends ZC proxy applicability to Vision Transformers (ViTs). We present a new benchmark using the Autoformer search space evaluated on 6 distinct tasks and propose Layer-Sample Wise Activation with Gradients information (L-SWAG), a novel, generalizable metric that characterizes both convolutional and transformer architectures across 14 tasks. Additionally, previous works highlighted how different proxies contain complementary information, motivating the need for a ML model to identify useful combinations. To further enhance ZC-NAS, we therefore introduce LIBRA-NAS (Low Information gain and Bias Re-Alignment), a method that strategically combines proxies to best represent a specific benchmark. Integrated into the NAS search, LIBRA-NAS outperforms evolution and gradient-based NAS techniques by identifying an architecture with a 17.0% test error on ImageNet1k in just 0.1 GPU days.

[Arxiv](https://arxiv.org/abs/2505.07300)