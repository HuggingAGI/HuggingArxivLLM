# 大规模模型犯罪监控视频分析基准

发布时间：2025年02月13日

`LLM应用` `计算机视觉` `公共安全`

> A Benchmark for Crime Surveillance Video Analysis with Large Models

# 摘要

> 监控视频异常分析是计算机视觉领域的关键课题。近年来，多模态大型语言模型（MLLMs）在多个领域表现优于特定任务模型。尽管MLLMs高度 versatile，但它们对异常概念和细节的理解能力研究不足，主要是因为现有基准未提供MLLM风格的问答及有效算法来评估模型的开放式文本响应。为填补这一空白，我们提出了一种用于大型模型的犯罪监控视频分析基准UCVL，包含1,829个视频和从UCF-Crime及UCF-Crime Annotation数据集中重新整理的标注。我们设计了六种类型的问题并生成了多样化的问答对。随后制定了详细指令，并使用OpenAI的GPT-4o进行准确评估。我们对八种流行的MLLMs（参数规模从0.5B到40B）进行了基准测试，结果验证了该基准的可靠性。此外，我们在UCVL的训练集上微调了LLaVA-OneVision，改进效果证明了我们数据集在视频异常分析中的高质量。

> Anomaly analysis in surveillance videos is a crucial topic in computer vision. In recent years, multimodal large language models (MLLMs) have outperformed task-specific models in various domains. Although MLLMs are particularly versatile, their abilities to understand anomalous concepts and details are insufficiently studied because of the outdated benchmarks of this field not providing MLLM-style QAs and efficient algorithms to assess the model's open-ended text responses. To fill this gap, we propose a benchmark for crime surveillance video analysis with large models denoted as UCVL, including 1,829 videos and reorganized annotations from the UCF-Crime and UCF-Crime Annotation datasets. We design six types of questions and generate diverse QA pairs. Then we develop detailed instructions and use OpenAI's GPT-4o for accurate assessment. We benchmark eight prevailing MLLMs ranging from 0.5B to 40B parameters, and the results demonstrate the reliability of this bench. Moreover, we finetune LLaVA-OneVision on UCVL's training set. The improvement validates our data's high quality for video anomaly analysis.

[Arxiv](https://arxiv.org/abs/2502.09325)