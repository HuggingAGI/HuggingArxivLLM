# 本研究利用大型语音识别技术，专注于在失语症患者的言语中识别并分析不适当的停顿现象。

发布时间：2024年02月29日

`Agent`

> Inappropriate Pause Detection In Dysarthric Speech Using Large-Scale Speech Recognition

# 摘要

> 失语症导致患者言语含糊不清，其中不恰当的停顿尤为关键，它既影响病情评估，也关乎言语治疗效果。我们计划借助大型语音识别技术来探测失语症患者的不恰当停顿现象。具体而言，我们创新了任务设计方案、标注策略，并构建了一个具备不恰当停顿预测功能的语音识别模型。第一步，我们巧妙地将停顿检测融入语音识别过程，利用ASR模型将语音转译成标记了停顿信息的文本。基于全新的任务设定，我们在文本层面细致地标记出停顿位置及其是否恰当，并携手言语语言病理学专家共同制定了严谨的标注准则，确保高质量的数据标注。最终，我们在原有ASR模型基础上增加不恰当停顿预测层，实现了从头至尾一体化的不恰当停顿检测。不仅如此，我们还专门设计了一项任务针对性的评估指标，以独立衡量不恰当停顿检测性能，不受ASR整体表现的影响。实验证明，这种方法相较于基准方法，在检测失语症患者言语中的不恰当停顿时具有更好的效果，其不恰当停顿错误率为14.47%。

> Dysarthria, a common issue among stroke patients, severely impacts speech intelligibility. Inappropriate pauses are crucial indicators in severity assessment and speech-language therapy. We propose to extend a large-scale speech recognition model for inappropriate pause detection in dysarthric speech. To this end, we propose task design, labeling strategy, and a speech recognition model with an inappropriate pause prediction layer. First, we treat pause detection as speech recognition, using an automatic speech recognition (ASR) model to convert speech into text with pause tags. According to the newly designed task, we label pause locations at the text level and their appropriateness. We collaborate with speech-language pathologists to establish labeling criteria, ensuring high-quality annotated data. Finally, we extend the ASR model with an inappropriate pause prediction layer for end-to-end inappropriate pause detection. Moreover, we propose a task-tailored metric for evaluating inappropriate pause detection independent of ASR performance. Our experiments show that the proposed method better detects inappropriate pauses in dysarthric speech than baselines. (Inappropriate Pause Error Rate: 14.47%)

[Arxiv](https://arxiv.org/abs/2402.18923)