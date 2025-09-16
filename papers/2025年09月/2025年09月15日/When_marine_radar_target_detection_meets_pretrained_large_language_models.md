# marine雷达目标检测邂逅预训练大模型

发布时间：2025年09月15日

`LLM应用` `交通运输`

> When marine radar target detection meets pretrained large language models

# 摘要

> 深度学习（DL）方法广泛应用于从雷达回波信号的序列特征中提取高维模式。但传统DL算法存在冗余特征片段、模型规模受限等问题。为此，我们提出一种融合特征预处理与大型语言模型（LLMs）的框架：预处理模块先对雷达序列特征进行token化，再通过分块选择算法滤除无信息片段，最后将选中分块投影到与预训练LLMs特征空间匹配的嵌入向量中。借助这些优化嵌入，我们引入预训练LLM，仅微调归一化层以减轻训练负担并提升性能。实测数据集实验显示，该方法在监督学习测试中性能显著超越现有最先进基线模型。

> Deep learning (DL) methods are widely used to extract high-dimensional patterns from the sequence features of radar echo signals. However, conventional DL algorithms face challenges such as redundant feature segments, and constraints from restricted model sizes. To address these issues, we propose a framework that integrates feature preprocessing with large language models (LLMs). Our preprocessing module tokenizes radar sequence features, applies a patch selection algorithm to filter out uninformative segments, and projects the selected patches into embeddings compatible with the feature space of pre-trained LLMs. Leveraging these refined embeddings, we incorporate a pre-trained LLM, fine-tuning only the normalization layers to reduce training burdens while enhancing performance. Experiments on measured datasets demonstrate that the proposed method significantly outperforms the state-of-the-art baselines on supervised learning tests.

[Arxiv](https://arxiv.org/abs/2509.12110)