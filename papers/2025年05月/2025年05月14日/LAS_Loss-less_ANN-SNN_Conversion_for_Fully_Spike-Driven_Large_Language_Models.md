# LAS: 面向全脉冲驱动大型语言模型的无损ANN到SNN转换

发布时间：2025年05月14日

`LLM理论` `人工智能`

> LAS: Loss-less ANN-SNN Conversion for Fully Spike-Driven Large Language Models

# 摘要

> 脉冲式大型语言模型（LLMs）凭借其事件驱动的计算机制，成为传统LLMs的高效能源替代方案。为了有效构建脉冲式LLMs，研究人员基于预训练的人工神经网络（ANN）参数，结合脉冲神经网络（SNN）的节能优势，开发了多种ANN到SNN的转换方法。然而，现有的转换方法在处理基于ANN的LLMs中的极端激活异常值和不兼容的非线性操作时仍存在困难。针对这一问题，我们提出了一种无损的ANN-SNN转换方法LAS，专为完全由脉冲驱动的LLMs设计。具体而言，LAS创新性地引入了两种新型神经元，用于处理基于ANN的LLMs中的激活异常值和非线性操作。此外，LAS还为脉冲式LLMs量身定制了与脉冲等效的Transformer组件，确保了无损的全脉冲转换，且性能不受任何损失。实验结果在六种语言模型和两种视觉-语言模型上证实了LAS的无损转换能力。特别地，在OPT-66B模型上，LAS甚至将WSC任务的准确率提升了2%。此外，参数和消融研究表明，LAS具有显著的有效性。源代码可在https://github.com/lc783/LAS获取。

> Spiking Large Language Models (LLMs) have emerged as an energy-efficient alternative to conventional LLMs through their event-driven computation. To effectively obtain spiking LLMs, researchers develop different ANN-to-SNN conversion methods by leveraging pre-trained ANN parameters while inheriting the energy efficiency of SNN. However, existing conversion methods struggle with extreme activation outliers and incompatible nonlinear operations of ANN-based LLMs. To address this, we propose a loss-less ANN-SNN conversion for fully spike-driven LLMs, termed LAS. Specifically, LAS introduces two novel neurons to convert the activation outlier and nonlinear operation of ANN-based LLMs. Moreover, LAS tailors the spike-equivalent Transformer components for spiking LLMs, which can ensure full spiking conversion without any loss of performance. Experimental results on six language models and two vision-language models demonstrate that LAS achieves loss-less conversion. Notably, on OPT-66B, LAS even improves the accuracy of 2\% on the WSC task. In addition, the parameter and ablation studies further verify the effectiveness of LAS. The source code is available at https://github.com/lc783/LAS

[Arxiv](https://arxiv.org/abs/2505.09659)