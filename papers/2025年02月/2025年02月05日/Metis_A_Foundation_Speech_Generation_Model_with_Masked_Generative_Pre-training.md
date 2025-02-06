# Metis: 基于掩码生成预训练的基础语音生成模型

发布时间：2025年02月05日

`其他

理由：这篇论文主要介绍了一个名为Metis的统一语音生成基础模型，它采用预训练加微调的模式，并在多种语音生成任务中表现出色。虽然论文中提到了预训练和微调，但这些内容并不直接涉及大型语言模型（LLM）的理论、应用、代理（Agent）或检索增强生成（RAG）。因此，这篇论文更适合归类为“其他”。` `语音生成` `多模态`

> Metis: A Foundation Speech Generation Model with Masked Generative Pre-training

# 摘要

> 我们推出了Metis，一个统一语音生成的基础模型。与以往的任务特定或多任务模型不同，Metis采用预训练加微调的模式。它先在大规模未标注语音数据上通过掩码生成建模进行预训练，再通过微调适应多种语音生成任务。具体来说，1) Metis采用两种离散语音表示：基于语音自监督学习（SSL）特征的SSL令牌，以及直接从波形量化的声学令牌。2) Metis在300K小时的多样化语音数据上对SSL令牌进行掩码生成预训练，无需额外条件。3) 通过任务特定条件的微调，Metis能够高效适应各种语音生成任务，并支持多模态输入，即使数据量和可训练参数有限。实验证明，Metis在五个语音生成任务中均超越了最先进的任务特定或多任务系统，包括零-shot文本到语音、语音转换、目标说话人提取、语音增强和唇语到语音，且仅需少于20M的可训练参数或300倍少的训练数据。音频样本请访问https://metis-demo.github.io/。

> We introduce Metis, a foundation model for unified speech generation. Unlike previous task-specific or multi-task models, Metis follows a pre-training and fine-tuning paradigm. It is pre-trained on large-scale unlabeled speech data using masked generative modeling and then fine-tuned to adapt to diverse speech generation tasks. Specifically, 1) Metis utilizes two discrete speech representations: SSL tokens derived from speech self-supervised learning (SSL) features, and acoustic tokens directly quantized from waveforms. 2) Metis performs masked generative pre-training on SSL tokens, utilizing 300K hours of diverse speech data, without any additional condition. 3) Through fine-tuning with task-specific conditions, Metis achieves efficient adaptation to various speech generation tasks while supporting multimodal input, even when using limited data and trainable parameters. Experiments demonstrate that Metis can serve as a foundation model for unified speech generation: Metis outperforms state-of-the-art task-specific or multi-task systems across five speech generation tasks, including zero-shot text-to-speech, voice conversion, target speaker extraction, speech enhancement, and lip-to-speech, even with fewer than 20M trainable parameters or 300 times less training data. Audio samples are are available at https://metis-demo.github.io/.

[Arxiv](https://arxiv.org/abs/2502.03128)