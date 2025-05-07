# 上下文为王：即插即用的AMC在无需训练的开放集调节中与大型语言模型结合。

发布时间：2025年05月05日

`LLM应用` `无线通信` `频谱管理`

> Plug-and-Play AMC: Context Is King in Training-Free, Open-Set Modulation with LLMs

# 摘要

> 自动调制分类（AMC）是实现高效频谱管理和稳健无线通信的关键技术。然而，由于信号干扰与噪声的复杂相互作用，AMC仍然面临诸多挑战。本研究提出了一种创新性框架，将传统信号处理技术与大型语言模型（LLMs）相结合，以解决AMC问题。我们的方法通过高阶统计和累积量估计，将定量信号特征转化为结构化的自然语言提示。通过将示例上下文融入这些提示，我们的方法能够充分发挥LLM对经典信号处理的熟悉度，从而实现无需额外训练或预处理（如去噪）的有效一次性分类。我们在涵盖无噪声和有噪声条件的合成数据集上进行了实验评估，结果表明，我们的框架在各种调制方案和信噪比（SNR）下均表现优异。此外，我们的方法为无线通信中不同信道条件下的稳健基础模型奠定了基础，显著降低了开发特定信道模型的成本。这项工作为下一代无线网络中可扩展、可解释且功能多样的信号分类系统奠定了基础。源代码可在https://github.com/RU-SIT/context-is-king获取。

> Automatic Modulation Classification (AMC) is critical for efficient spectrum management and robust wireless communications. However, AMC remains challenging due to the complex interplay of signal interference and noise. In this work, we propose an innovative framework that integrates traditional signal processing techniques with Large-Language Models (LLMs) to address AMC. Our approach leverages higher-order statistics and cumulant estimation to convert quantitative signal features into structured natural language prompts. By incorporating exemplar contexts into these prompts, our method exploits the LLM's inherent familiarity with classical signal processing, enabling effective one-shot classification without additional training or preprocessing (e.g., denoising). Experimental evaluations on synthetically generated datasets, spanning both noiseless and noisy conditions, demonstrate that our framework achieves competitive performance across diverse modulation schemes and Signal-to-Noise Ratios (SNRs). Moreover, our approach paves the way for robust foundation models in wireless communications across varying channel conditions, significantly reducing the expense associated with developing channel-specific models. This work lays the foundation for scalable, interpretable, and versatile signal classification systems in next-generation wireless networks. The source code is available at https://github.com/RU-SIT/context-is-king

[Arxiv](https://arxiv.org/abs/2505.03112)