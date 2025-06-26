# 通用视频时间定位：基于生成式多模态大型语言模型的研究

发布时间：2025年06月23日

`LLM应用` `视频处理` `视频问答系统`

> Universal Video Temporal Grounding with Generative Multi-modal Large Language Models

# 摘要

> 本文提出了一种用于通用视频时间定位的计算模型，该模型能够根据自然语言查询（例如问题或描述）准确地在视频中定位时间点。与现有方法通常局限于特定视频领域或时间段不同，我们提出了UniTime，这是一种强大的通用视频定位模型，利用生成式多模态大型语言模型（MLLMs）强大的视觉-语言理解能力。我们的模型能够有效处理不同视角、类型和长度的视频，同时理解复杂的语言查询。

主要贡献包括：
(i) 我们考虑利用强大的MLLMs进行视频时间定位。为了实现精确的时间戳输出，我们通过交错时间戳标记与视频标记的方式，将时间信息融入模型。
(ii) 通过训练模型处理不同输入粒度的视频（通过自适应帧缩放），我们的方法实现了对短视频和长视频的鲁棒时间定位。
(iii) 全面的实验表明，UniTime在零样本和特定数据集微调设置下，均在五个公共时间定位基准测试中超越了现有最先进方法。
(iv) 当UniTime作为长视频问答（VideoQA）的初步时刻检索器时，显著提高了VideoQA的准确性，突显了其在复杂视频理解任务中的价值。

> This paper presents a computational model for universal video temporal grounding, which accurately localizes temporal moments in videos based on natural language queries (e.g., questions or descriptions). Unlike existing methods that are often limited to specific video domains or durations, we propose UniTime, a robust and universal video grounding model leveraging the strong vision-language understanding capabilities of generative Multi-modal Large Language Models (MLLMs). Our model effectively handles videos of diverse views, genres, and lengths while comprehending complex language queries. The key contributions include: (i) We consider steering strong MLLMs for temporal grounding in videos. To enable precise timestamp outputs, we incorporate temporal information by interleaving timestamp tokens with video tokens. (ii) By training the model to handle videos with different input granularities through adaptive frame scaling, our approach achieves robust temporal grounding for both short and long videos. (iii) Comprehensive experiments show that UniTime outperforms state-of-the-art approaches in both zero-shot and dataset-specific finetuned settings across five public temporal grounding benchmarks. (iv) When employed as a preliminary moment retriever for long-form video question-answering (VideoQA), UniTime significantly improves VideoQA accuracy, highlighting its value for complex video understanding tasks.

[Arxiv](https://arxiv.org/abs/2506.18883)