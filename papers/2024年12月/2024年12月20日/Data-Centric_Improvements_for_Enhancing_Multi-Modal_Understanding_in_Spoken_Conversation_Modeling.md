# 以数据为中心的改进，用于增强口语对话建模中的多模态理解

发布时间：2024年12月20日

`LLM应用` `对话建模` `语音交互`

> Data-Centric Improvements for Enhancing Multi-Modal Understanding in Spoken Conversation Modeling

# 摘要

> 对话助手在各类现实应用中日益流行，这凸显了对先进多模态语音建模的需求。语音作为一种自然的交流方式，蕴含着丰富的用户特定特征，比如说话速度和音高，这对于实现有效交互至关重要。我们的工作引入了一种以数据为核心的定制化方法，能够高效增强对话语音建模中的多模态理解。我们的核心贡献在于一种新颖的多任务学习模式，包括设计辅助任务以利用少量语音数据。我们的方法在 Spoken-SQuAD 基准测试中，仅用 10%的训练数据和开放权重模型就达到了顶尖水平，为以音频为重点的对话建模构建了一个强大且高效的框架。此外，我们还推出了 ASK-QA，这是首个针对具有模糊用户请求和动态评估输入的多轮口语对话的数据集。代码和数据即将发布。

> Conversational assistants are increasingly popular across diverse real-world applications, highlighting the need for advanced multimodal speech modeling. Speech, as a natural mode of communication, encodes rich user-specific characteristics such as speaking rate and pitch, making it critical for effective interaction. Our work introduces a data-centric customization approach for efficiently enhancing multimodal understanding in conversational speech modeling. Central to our contributions is a novel multi-task learning paradigm that involves designing auxiliary tasks to utilize a small amount of speech data. Our approach achieves state-of-the-art performance on the Spoken-SQuAD benchmark, using only 10% of the training data with open-weight models, establishing a robust and efficient framework for audio-centric conversational modeling. We also introduce ASK-QA, the first dataset for multi-turn spoken dialogue with ambiguous user requests and dynamic evaluation inputs. Code and data forthcoming.

[Arxiv](https://arxiv.org/abs/2412.15995)