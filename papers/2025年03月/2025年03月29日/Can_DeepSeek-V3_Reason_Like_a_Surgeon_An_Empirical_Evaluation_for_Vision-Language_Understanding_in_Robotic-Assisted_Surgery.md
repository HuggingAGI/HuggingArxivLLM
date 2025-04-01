# DeepSeek-V3能否像外科医生一样思考？机器人辅助手术中的视觉语言理解实证研究

发布时间：2025年03月29日

`LLM应用` `机器人手术`

> Can DeepSeek-V3 Reason Like a Surgeon? An Empirical Evaluation for Vision-Language Understanding in Robotic-Assisted Surgery

# 摘要

> DeepSeek-V3 是一款新兴的大型语言模型（LLM），凭借高效的训练范式和强大的推理能力，它在通用场景理解、问答（QA）和文本生成任务中表现卓越。本研究聚焦于 DeepSeek-V3 在机器人手术场景中的对话能力，重点考察单一短语问答（Single Phrase QA）、视觉问答（Visual QA）和详细描述任务。其中，单一短语问答进一步细分为手术器械识别、动作理解以及空间位置分析等子任务。我们采用公开数据集 EndoVis18 和 CholecT50 及其对话数据进行了全面评估。研究发现，当提供具体提示时，DeepSeek-V3 在手术器械和组织识别方面表现出色，但在空间位置分析和手术动作理解上存在明显不足。更值得关注的是，在一般提示下，DeepSeek-V3 无法有效分析全局手术概念，也无法提供深入的手术场景见解。基于此，我们认为未经手术特定数据集微调的 DeepSeek-V3 尚未准备好应对手术场景中的视觉-语言任务。

> DeepSeek-V3, a recently emerging Large Language Model (LLM), demonstrates outstanding performance in general scene understanding, question-answering (QA), and text generation tasks, owing to its efficient training paradigm and strong reasoning capabilities. In this study, we investigate the dialogue capabilities of DeepSeek-V3 in robotic surgery scenarios, focusing on tasks such as Single Phrase QA, Visual QA, and Detailed Description. The Single Phrase QA tasks further include sub-tasks such as surgical instrument recognition, action understanding, and spatial position analysis. We conduct extensive evaluations using publicly available datasets, including EndoVis18 and CholecT50, along with their corresponding dialogue data. Our comprehensive evaluation results indicate that, when provided with specific prompts, DeepSeek-V3 performs well in surgical instrument and tissue recognition tasks However, DeepSeek-V3 exhibits significant limitations in spatial position analysis and struggles to understand surgical actions accurately. Additionally, our findings reveal that, under general prompts, DeepSeek-V3 lacks the ability to effectively analyze global surgical concepts and fails to provide detailed insights into surgical scenarios. Based on our observations, we argue that the DeepSeek-V3 is not ready for vision-language tasks in surgical contexts without fine-tuning on surgery-specific datasets.

[Arxiv](https://arxiv.org/abs/2503.23130)