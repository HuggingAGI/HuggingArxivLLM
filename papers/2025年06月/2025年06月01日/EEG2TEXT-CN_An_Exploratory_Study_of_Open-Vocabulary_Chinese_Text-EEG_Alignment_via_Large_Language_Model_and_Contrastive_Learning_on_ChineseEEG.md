# EEG2TEXT-CN：利用大型语言模型与对比学习探索开放词汇中文文本与EEG的对齐关系。

发布时间：2025年06月01日

`LLM应用` `脑机接口`

> EEG2TEXT-CN: An Exploratory Study of Open-Vocabulary Chinese Text-EEG Alignment via Large Language Model and Contrastive Learning on ChineseEEG

# 摘要

> 我们提出了 EEG2TEXT-CN，据我们所知，这是首个专为中文设计的开源词汇集 EEG 到文本生成框架。该框架基于生物基础的 EEG 编码器（NICE-EEG）和紧凑型预训练语言模型（MiniLM），通过掩码预训练和对比学习技术，实现了多通道脑电信号与自然语言表示的精准对齐。我们采用 ChineseEEG 数据集的一部分进行实验，每个句子包含约十个中文字符，并与 128 通道、256 Hz 采样的 EEG 信号同步记录。通过将 EEG 信号分割为每个字符的嵌入表示，并结合教师强制和填充掩码技术，我们在零样本设置下成功实现了完整句子的预测。在包含 1,500 个训练-验证句子和 300 个独立测试样本的实验中，我们的模型展现了令人鼓舞的词汇对齐能力，最佳 BLEU-1 得分达到了 6.38%。尽管在语法流畅性方面仍存在挑战，但我们的研究结果充分证明了从 EEG 信号中进行非语音、跨模态语言解码的可行性。这一突破不仅为多语言脑机接口研究开辟了新方向，更为未来中文认知-语言界面的开发奠定了坚实基础。

> We propose EEG2TEXT-CN, which, to the best of our knowledge, represents one of the earliest open-vocabulary EEG-to-text generation frameworks tailored for Chinese. Built on a biologically grounded EEG encoder (NICE-EEG) and a compact pretrained language model (MiniLM), our architecture aligns multichannel brain signals with natural language representations via masked pretraining and contrastive learning. Using a subset of the ChineseEEG dataset, where each sentence contains approximately ten Chinese characters aligned with 128-channel EEG recorded at 256 Hz, we segment EEG into per-character embeddings and predict full sentences in a zero-shot setting. The decoder is trained with teacher forcing and padding masks to accommodate variable-length sequences. Evaluation on over 1,500 training-validation sentences and 300 held-out test samples shows promising lexical alignment, with a best BLEU-1 score of 6.38\%. While syntactic fluency remains a challenge, our findings demonstrate the feasibility of non-phonetic, cross-modal language decoding from EEG. This work opens a new direction in multilingual brain-to-text research and lays the foundation for future cognitive-language interfaces in Chinese.

[Arxiv](https://arxiv.org/abs/2506.00854)