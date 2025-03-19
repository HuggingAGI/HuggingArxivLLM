# MoonCast：高质零样本播客创作

发布时间：2025年03月18日

`LLM应用` `语音合成`

> MoonCast: High-Quality Zero-Shot Podcast Generation

# 摘要

> 近年来，文本到语音合成技术在生成个性化短语音方面取得了显著成功。然而，面对长篇、多角色及即兴对话等真实场景（如播客），现有系统仍面临两大挑战：1）长语音：播客通常持续几分钟，超出了现有大多数工作的上限；2）即兴性：播客以自然口语化为特点，与正式书面语形成鲜明对比；现有方法往往难以捕捉这种即兴感。本文提出MoonCast，一种面向高质量零样本播客生成的解决方案。MoonCast能够从纯文本来源（如故事、技术报告、新闻等TXT、PDF或Web URL格式文档）生成自然的播客风格语音，且可使用未见过说话人的声音。为生成长音频，我们采用基于长上下文语言模型的音频建模方法，并利用大规模长上下文语音数据。为增强即兴感，我们引入播客生成模块，生成包含即兴细节的脚本。实证研究表明，这些即兴细节与文本到语音建模本身同等重要。实验结果表明，MoonCast在生成播客语音方面优于现有方法，尤其是在自发性和连贯性方面有显著提升。

> Recent advances in text-to-speech synthesis have achieved notable success in generating high-quality short utterances for individual speakers. However, these systems still face challenges when extending their capabilities to long, multi-speaker, and spontaneous dialogues, typical of real-world scenarios such as podcasts. These limitations arise from two primary challenges: 1) long speech: podcasts typically span several minutes, exceeding the upper limit of most existing work; 2) spontaneity: podcasts are marked by their spontaneous, oral nature, which sharply contrasts with formal, written contexts; existing works often fall short in capturing this spontaneity. In this paper, we propose MoonCast, a solution for high-quality zero-shot podcast generation, aiming to synthesize natural podcast-style speech from text-only sources (e.g., stories, technical reports, news in TXT, PDF, or Web URL formats) using the voices of unseen speakers. To generate long audio, we adopt a long-context language model-based audio modeling approach utilizing large-scale long-context speech data. To enhance spontaneity, we utilize a podcast generation module to generate scripts with spontaneous details, which have been empirically shown to be as crucial as the text-to-speech modeling itself. Experiments demonstrate that MoonCast outperforms baselines, with particularly notable improvements in spontaneity and coherence.

[Arxiv](https://arxiv.org/abs/2503.14345)