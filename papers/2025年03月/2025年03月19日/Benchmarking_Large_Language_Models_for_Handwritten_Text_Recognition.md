# 用于手写文本识别的大型语言模型基准测试

发布时间：2025年03月19日

`LLM应用` `文档处理` `文本识别`

> Benchmarking Large Language Models for Handwritten Text Recognition

# 摘要

> 传统的手写文本识别 (HTR) 机器学习模型依赖于监督式训练，需要大量的手动标注，并且由于布局与文本处理的分离，常常产生错误。相比之下，多模态大型语言模型 (MLLMs) 提供了一种通用方法，能够识别多种手写风格，而无需进行特定于模型的训练。

这项研究将各种专有和开源的 LLM 与 Transkribus 模型进行了基准测试，评估它们在英语、法语、德语和意大利语书写的现代及历史数据集上的性能。此外，研究还重点测试了模型自主修正先前生成输出的能力。研究结果表明，在零样本设置下，专有模型，尤其是 Claude 3.5 Sonnet，优于开源替代方案。MLLMs 在识别现代手写方面表现出色，并由于其预训练数据集的构成，对英语表现出偏好。与 Transkribus 的比较显示，两种方法均无明显优势。此外，LLMs 在零样本转录中自主修正错误的能力有限。

> Traditional machine learning models for Handwritten Text Recognition (HTR) rely on supervised training, requiring extensive manual annotations, and often produce errors due to the separation between layout and text processing. In contrast, Multimodal Large Language Models (MLLMs) offer a general approach to recognizing diverse handwriting styles without the need for model-specific training. The study benchmarks various proprietary and open-source LLMs against Transkribus models, evaluating their performance on both modern and historical datasets written in English, French, German, and Italian. In addition, emphasis is placed on testing the models' ability to autonomously correct previously generated outputs. Findings indicate that proprietary models, especially Claude 3.5 Sonnet, outperform open-source alternatives in zero-shot settings. MLLMs achieve excellent results in recognizing modern handwriting and exhibit a preference for the English language due to their pre-training dataset composition. Comparisons with Transkribus show no consistent advantage for either approach. Moreover, LLMs demonstrate limited ability to autonomously correct errors in zero-shot transcriptions.

[Arxiv](https://arxiv.org/abs/2503.15195)