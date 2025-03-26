# # FALCONEye：利用多模态大语言模型在一小时长视频中快速找到答案并精准定位内容

发布时间：2025年03月25日

`Agent

理由：这篇论文主要介绍了一个名为FALCONEye的视频代理，结合了VLM和LLM来高效检索和定位视频中的信息。它作为自动化系统执行特定任务，符合Agent的定义，因此归类为Agent。` `视频检索` `视频分析`

> FALCONEye: Finding Answers and Localizing Content in ONE-hour-long videos with multi-modal LLMs

# 摘要

> 在长达数小时的视频中进行信息检索，即使是当前最先进的视觉-语言模型（VLM）也面临重大挑战，尤其是当目标信息仅集中在少数帧中时。长视频数据对VLM提出了双重挑战：一方面受限于上下文窗口，另一方面难以精准定位包含答案的帧。我们的创新视频代理FALCONEye结合了VLM和大型语言模型（LLM），能够在视频中高效搜索相关信息并准确定位到包含答案的帧。FALCONEye的三大创新点包括：1）突破性的元架构设计，相较于现有最先进的短视频方法，更能胜任处理长达数小时的视频；2）全新的高效探索算法，通过短视频片段、字幕和答案置信度实现精准信息定位；3）我们对VLMs的校准分析在答案置信度评估方面达到了当前最先进的水平。FALCONEye基于小型VLM和中型LLM构建，能够轻松运行在标准计算资源上。我们还发布了FALCON-Bench，这是一个用于评估长时间（平均时长超过1小时）视频答案搜索挑战的基准，突显了开放性问题评估的重要性。实验结果表明，FALCONEye在FALCON-Bench上优于现有最先进的模型，并在相关基准上表现相似或更优。

> Information retrieval in hour-long videos presents a significant challenge, even for state-of-the-art Vision-Language Models (VLMs), particularly when the desired information is localized within a small subset of frames. Long video data presents challenges for VLMs due to context window limitations and the difficulty of pinpointing frames containing the answer. Our novel video agent, FALCONEye, combines a VLM and a Large Language Model (LLM) to search relevant information along the video, and locate the frames with the answer. FALCONEye novelty relies on 1) the proposed meta-architecture, which is better suited to tackle hour-long videos compared to short video approaches in the state-of-the-art; 2) a new efficient exploration algorithm to locate the information using short clips, captions and answer confidence; and 3) our state-of-the-art VLMs calibration analysis for the answer confidence. Our agent is built over a small-size VLM and a medium-size LLM being accessible to run on standard computational resources. We also release FALCON-Bench, a benchmark to evaluate long (average > 1 hour) Video Answer Search challenges, highlighting the need for open-ended question evaluation. Our experiments show FALCONEye's superior performance than the state-of-the-art in FALCON-Bench, and similar or better performance in related benchmarks.

[Arxiv](https://arxiv.org/abs/2503.19850)