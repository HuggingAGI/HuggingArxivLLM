# 用于非洲语言的自动语音识别的合成语音数据

发布时间：2025年07月23日

`LLM应用

摘要中的论文探讨了大型语言模型（LLM）在生成文本和语音合成中的应用，特别是在提升非洲语言的自动语音识别（ASR）性能方面。研究通过使用LLM生成文本、TTS合成语音以及微调ASR模型，展示了合成数据对模型性能的显著提升。这属于LLM的实际应用，因此归类为LLM应用。` `语音技术`

> Synthetic Voice Data for Automatic Speech Recognition in African Languages

# 摘要

> 语音技术对非洲2300多种语言中的绝大多数仍难以企及。我们首次系统性评估了大型合成语音语料库在非洲ASR中的应用。我们的方法采用三步流程：LLM驱动的文本生成、TTS语音合成以及ASR微调。在我们创建合成文本的十种语言中，有八种语言的可读性得分超过5分（满分7分）。我们对三种语言（豪萨语、杜卢奥语、奇切瓦语）的ASR改进进行了评估，并创建了超过2500小时的合成语音数据，成本仅为真实数据的1%。基于250小时真实数据和250小时合成豪萨语数据微调的Wav2Vec-BERT-2.0模型，其性能与仅使用500小时真实数据的基线相当。而使用579小时真实数据和450至993小时合成数据时，性能最佳。我们还展示了按性别划分的ASR性能评估结果。对于资源极度匮乏的语言，提升效果因语言而异：奇切瓦语的WER相对降低了约6.5%，当真实数据与合成数据比例为1:2时；杜卢奥语在1:1比例下，某些测试数据上也显示出类似改进，但其他数据则不然。通过分析编码器可靠性、ASR错误和评估数据集，我们发现需要更稳健的审稿协议和更准确的评估数据。所有数据和模型均已公开发布，以鼓励进一步研究，提升非洲语言的合成数据质量。

> Speech technology remains out of reach for most of the over 2300 languages in Africa. We present the first systematic assessment of large-scale synthetic voice corpora for African ASR. We apply a three-step process: LLM-driven text creation, TTS voice synthesis, and ASR fine-tuning. Eight out of ten languages for which we create synthetic text achieved readability scores above 5 out of 7. We evaluated ASR improvement for three (Hausa, Dholuo, Chichewa) and created more than 2,500 hours of synthetic voice data at below 1% of the cost of real data. Fine-tuned Wav2Vec-BERT-2.0 models trained on 250h real and 250h synthetic Hausa matched a 500h real-data-only baseline, while 579h real and 450h to 993h synthetic data created the best performance. We also present gender-disaggregated ASR performance evaluation. For very low-resource languages, gains varied: Chichewa WER improved about 6.5% relative with a 1:2 real-to-synthetic ratio; a 1:1 ratio for Dholuo showed similar improvements on some evaluation data, but not on others. Investigating intercoder reliability, ASR errors and evaluation datasets revealed the need for more robust reviewer protocols and more accurate evaluation data. All data and models are publicly released to invite further work to improve synthetic data for African languages.

[Arxiv](https://arxiv.org/abs/2507.17578)