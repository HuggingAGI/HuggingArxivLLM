# KoGEC：基于预训练翻译模型的韩语语法错误修正

发布时间：2025年06月12日

`LLM应用

这篇论文主要探讨了将预训练翻译模型应用于韩语语法错误修正任务，属于大语言模型的具体应用。研究中涉及模型微调、评估方法以及实际应用工具的开发，因此归类为LLM应用。` `语言修正`

> KoGEC : Korean Grammatical Error Correction with Pre-trained Translation Models

# 摘要

> 本研究推出了一款名为KoGEC的韩语语法错误修正系统，采用预训练翻译模型构建。我们对NLLB模型进行了针对性微调，用于韩语语法修正，并与GPT-4和HCX-3等大模型进行了对比测试。研究使用了两个社交媒体对话数据集作为训练和测试集。微调过程中，我们通过特殊语言标记区分原句与修正句。评估采用BLEU分数和"LLM作为裁判"的方法进行错误分类。结果显示，微调后的NLLB（即KoGEC）在韩语语法修正任务中表现优于GPT-4和HCX-3。KoGEC在各类错误修正上表现均衡，而大模型则对标点错误关注较少。我们还开发了Chrome插件，方便用户使用KoGEC系统。最后，我们在模型优化方面进行了探索，发现扩展词表反而影响了模型性能。这项研究为NLP领域贡献了一套高效专业的韩语语法修正方案和创新评估方法，同时也证明了专门任务的小型模型在特定NLP任务中具有与大型通用模型竞争的潜力。

> This research introduces KoGEC, a Korean Grammatical Error Correction system using pre\--trained translation models. We fine-tuned NLLB (No Language Left Behind) models for Korean GEC, comparing their performance against large language models like GPT-4 and HCX-3. The study used two social media conversation datasets for training and testing. The NLLB models were fine-tuned using special language tokens to distinguish between original and corrected Korean sentences. Evaluation was done using BLEU scores and an "LLM as judge" method to classify error types. Results showed that the fine-tuned NLLB (KoGEC) models outperformed GPT-4o and HCX-3 in Korean GEC tasks. KoGEC demonstrated a more balanced error correction profile across various error types, whereas the larger LLMs tended to focus less on punctuation errors. We also developed a Chrome extension to make the KoGEC system accessible to users. Finally, we explored token vocabulary expansion to further improve the model but found it to decrease model performance. This research contributes to the field of NLP by providing an efficient, specialized Korean GEC system and a new evaluation method. It also highlights the potential of compact, task-specific models to compete with larger, general-purpose language models in specialized NLP tasks.

[Arxiv](https://arxiv.org/abs/2506.11432)