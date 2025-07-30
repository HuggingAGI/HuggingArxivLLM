# # 基于 LLM 的 GitHub 仓库内容分类方法——通过 README 文件实现

发布时间：2025年07月29日

`LLM应用` `软件工程`

> LLM-based Content Classification Approach for GitHub Repositories by the README Files

# 摘要

> GitHub作为全球领先的代码存储、共享和管理平台，每个仓库都配有README文件。根据GitHub建议，README应包含项目相关信息以支持仓库的使用与优化，但仓库所有者有时会忽视这些建议，从而限制了仓库的潜力。本研究发现，README文件的全面性对其被采用和使用具有显著影响，信息不全可能阻碍其在研究社区中的广泛应用与影响。

大型语言模型（LLMs）在文本分类、生成、摘要和翻译等任务中表现出色。本研究开发了一种方法，利用LLMs自动分类GitHub README文件的不同部分。我们采用了BERT、DistilBERT和RoBERTa三种编码器型LLMs，并基于包含4226个README文件部分的黄金标准数据集进行微调。该方法超越了现有最优技术，实现了0.98的F1分数。此外，我们还探索了参数高效微调（PEFT）技术如低秩适配（LoRA），提供了一种经济高效的替代方案，性能表现同样出色。研究结果证明了使用LLMs设计自动分类器来分类GitHub README文件内容的潜力，为GitHub仓库自动化工具的开发提供了重要贡献，助力提升仓库识别与应用能力。

> GitHub is the world's most popular platform for storing, sharing, and managing code. Every GitHub repository has a README file associated with it. The README files should contain project-related information as per the recommendations of GitHub to support the usage and improvement of repositories. However, GitHub repository owners sometimes neglected these recommendations. This prevents a GitHub repository from reaching its full potential. This research posits that the comprehensiveness of a GitHub repository's README file significantly influences its adoption and utilization, with a lack of detail potentially hindering its full potential for widespread engagement and impact within the research community. Large Language Models (LLMs) have shown great performance in many text-based tasks including text classification, text generation, text summarization and text translation. In this study, an approach is developed to fine-tune LLMs for automatically classifying different sections of GitHub README files. Three encoder-only LLMs are utilized, including BERT, DistilBERT and RoBERTa. These pre-trained models are then fine-tuned based on a gold-standard dataset consisting of 4226 README file sections. This approach outperforms current state-of-the-art methods and has achieved an overall F1 score of 0.98. Moreover, we have also investigated the use of Parameter-Efficient Fine-Tuning (PEFT) techniques like Low-Rank Adaptation (LoRA) and shown an economical alternative to full fine-tuning without compromising much performance. The results demonstrate the potential of using LLMs in designing an automatic classifier for categorizing the content of GitHub README files. Consequently, this study contributes to the development of automated tools for GitHub repositories to improve their identifications and potential usages.

[Arxiv](https://arxiv.org/abs/2507.21899)