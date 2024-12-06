# 具备集成专家模型和上下文理解的综合音频查询处理系统

发布时间：2024年12月05日

`LLM应用` `聊天机器人`

> Comprehensive Audio Query Handling System with Integrated Expert Models and Contextual Understanding

# 摘要

> 这篇论文呈现了一个综合性的聊天机器人系统，旨在借助整合多个专门的音频处理模型来应对各式各样的音频相关查询。此系统采用了一个在丰富多样的音频查询数据集上训练而成的意图分类器，将有关音频内容的查询导向诸如自动语音识别（ASR）、说话人区分、音乐识别和文本转音频生成等专家模型。一个 3.8 B 的 LLM 模型接着从音频上下文检测（ACD）模块获取输入，该模块从音频中提取音频事件信息，并对专家模型的文本域输出进行后续处理，从而算出给用户的最终回应。我们在自定义音频任务和 MMAU 声音集基准上对该系统予以评估。自定义数据集是由行业基准未涵盖的目标用例所推动的，涵盖了 ACD 时间戳 - QA（问答）以及 ACD 时间 - QA 数据集，分别用于评估时间戳和时间推理问题。首先，我们确定基于 BERT 的意图分类器在查询路由方面比 LLM 少样本意图分类器表现更优。实验进一步显示，与最先进的大型音频语言模型相比，我们的方法在一些自定义任务上显著提升了准确性，并且在 MMAU 基准的声音测试集上优于 7B 参数规模范围的模型，进而为设备部署提供了颇具吸引力的选择。

> This paper presents a comprehensive chatbot system designed to handle a wide range of audio-related queries by integrating multiple specialized audio processing models. The proposed system uses an intent classifier, trained on a diverse audio query dataset, to route queries about audio content to expert models such as Automatic Speech Recognition (ASR), Speaker Diarization, Music Identification, and Text-to-Audio generation. A 3.8 B LLM model then takes inputs from an Audio Context Detection (ACD) module extracting audio event information from the audio and post processes text domain outputs from the expert models to compute the final response to the user. We evaluated the system on custom audio tasks and MMAU sound set benchmarks. The custom datasets were motivated by target use cases not covered in industry benchmarks and included ACD-timestamp-QA (Question Answering) as well as ACD-temporal-QA datasets to evaluate timestamp and temporal reasoning questions, respectively. First we determined that a BERT based Intent Classifier outperforms LLM-fewshot intent classifier in routing queries. Experiments further show that our approach significantly improves accuracy on some custom tasks compared to state-of-the-art Large Audio Language Models and outperforms models in the 7B parameter size range on the sound testset of the MMAU benchmark, thereby offering an attractive option for on device deployment.

[Arxiv](https://arxiv.org/abs/2412.03980)