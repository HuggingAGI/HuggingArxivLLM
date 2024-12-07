# LUMIA：借助内部 LLM 状态针对单模态和多模态成员推理攻击的线性探测

发布时间：2024年12月02日

`LLM应用` `语言模型` `成员推理攻击`

> LUMIA: Linear probing for Unimodal and MultiModal Membership Inference Attacks leveraging internal LLM states

# 摘要

> 大型语言模型（LLMs）在各类应用中愈发常用，然而对成员推理的顾虑也与日俱增。此前的工作侧重于黑箱到灰箱模型，从而忽略了内部LLM信息的潜在益处。为应对此问题，我们提议将线性探测器（LPs）用作通过检查LLMs内部激活来检测成员推理攻击（MIAs）的方法。我们的方法，名为LUMIA，逐层应用LPs以获取模型内部运作的细粒度数据。我们在多种模型架构、规模和数据集上测试了此方法，涵盖单模态和多模态任务。在单模态MIA中，LUMIA在曲线下面积（AUC）方面较之前的技术平均提升了15.71％。尤为显著的是，LUMIA在65.33％的情形下达到AUC>60％——相比现有技术增加了46.80％。此外，我们的方法揭示了关键的洞察，例如MIAs最易检测的模型层。在多模态模型中，LPs显示视觉输入对检测MIAs有显著贡献——在85.90％的实验中达到AUC>60％。

> Large Language Models (LLMs) are increasingly used in a variety of applications, but concerns around membership inference have grown in parallel. Previous efforts focus on black-to-grey-box models, thus neglecting the potential benefit from internal LLM information. To address this, we propose the use of Linear Probes (LPs) as a method to detect Membership Inference Attacks (MIAs) by examining internal activations of LLMs. Our approach, dubbed LUMIA, applies LPs layer-by-layer to get fine-grained data on the model inner workings. We test this method across several model architectures, sizes and datasets, including unimodal and multimodal tasks. In unimodal MIA, LUMIA achieves an average gain of 15.71 % in Area Under the Curve (AUC) over previous techniques. Remarkably, LUMIA reaches AUC>60% in 65.33% of cases -- an increment of 46.80% against the state of the art. Furthermore, our approach reveals key insights, such as the model layers where MIAs are most detectable. In multimodal models, LPs indicate that visual inputs can significantly contribute to detect MIAs -- AUC>60% is reached in 85.90% of experiments.

[Arxiv](https://arxiv.org/abs/2411.19876)