# 大型语言模型能否通过自然语言预测音频效果参数？

发布时间：2025年05月27日

`LLM应用` `音乐制作` `音频处理`

> Can Large Language Models Predict Audio Effects Parameters from Natural Language?

# 摘要

> 在音乐制作领域，通过自然语言操控音频效果参数为非专业人士降低了技术门槛。我们提出了LLM2Fx框架，该框架利用大型语言模型直接从文本描述中预测Fx参数，无需特定任务的训练或微调。我们的方法通过将自然语言描述映射到均衡和混响的相应Fx参数，来解决文本到效果参数预测任务。我们证明，LLMs可以以零样本的方式生成Fx参数，从而阐明音乐制作中音色语义与音频效果之间的关系。为了提升性能，我们引入了三种类型的上下文示例：音频数字信号处理特征、DSP函数代码以及少量样本示例。实验结果表明，基于LLMs的Fx参数生成优于之前的优化方法，在将自然语言描述转化为合适的Fx设置方面表现出竞争力。此外，LLMs还可作为文本驱动的音频制作界面，为更直观、更易用的音乐制作工具铺平道路。

> In music production, manipulating audio effects (Fx) parameters through natural language has the potential to reduce technical barriers for non-experts. We present LLM2Fx, a framework leveraging Large Language Models (LLMs) to predict Fx parameters directly from textual descriptions without requiring task-specific training or fine-tuning. Our approach address the text-to-effect parameter prediction (Text2Fx) task by mapping natural language descriptions to the corresponding Fx parameters for equalization and reverberation. We demonstrate that LLMs can generate Fx parameters in a zero-shot manner that elucidates the relationship between timbre semantics and audio effects in music production. To enhance performance, we introduce three types of in-context examples: audio Digital Signal Processing (DSP) features, DSP function code, and few-shot examples. Our results demonstrate that LLM-based Fx parameter generation outperforms previous optimization approaches, offering competitive performance in translating natural language descriptions to appropriate Fx settings. Furthermore, LLMs can serve as text-driven interfaces for audio production, paving the way for more intuitive and accessible music production tools.

[Arxiv](https://arxiv.org/abs/2505.20770)