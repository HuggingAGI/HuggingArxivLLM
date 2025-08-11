# # EICAP：通过多轮对话深入研究大型语言模型的情感智能评估与提升

发布时间：2025年08月08日

`LLM应用` `心理学` `人工智能`

> EICAP: Deep Dive in Assessment and Enhancement of Large Language Models in Emotional Intelligence through Multi-Turn Conversations

# 摘要

> 情感智能（EI）是开发符合人类价值观的大型语言模型（LLMs）中一个关键但研究较少的维度。为了解决这一空白，我们引入了一个统一的、基于心理学的四层EI分类框架，专门针对大型语言模型，包括情感追踪、原因推断、评估以及情感适宜的响应生成。基于此框架，我们提出了EICAP-Bench，这是一个新型的多轮MCQ风格基准测试，旨在评估开源LLMs在不同语言和文化背景下的EI能力。我们对六种LLMs进行了评估：LLaMA3（8B）、LLaMA3-Instruct、Gemma（9B）、Gemma-Instruct、Qwen2.5（7B）和Qwen2.5-Instruct，在EmoCap-Bench上发现Qwen2.5-Instruct表现最佳。为了评估提升EI能力的潜力，我们使用LoRA适配器在 UltraChat（UC）上对Qwen2.5-Base和Qwen2.5-Instruct进行了微调，UC是一个大规模、指令优化的对话数据集，支持英语和阿拉伯语。统计分析显示，在五个EI层中，只有评估层通过基于UC的微调显示出显著提升。这些发现凸显了现有预训练和指令微调范式在为LLMs配备更深层次情感推理方面的局限性，并强调了需要针对数据和建模策略，以实现全面的情感智能对齐。

> Emotional Intelligence (EI) is a critical yet underexplored dimension in the development of human-aligned LLMs. To address this gap, we introduce a unified, psychologically grounded four-layer taxonomy of EI tailored for large language models (LLMs), encompassing emotional tracking, cause inference, appraisal, and emotionally appropriate response generation. Building on this framework, we present EICAP-Bench, a novel MCQ style multi-turn benchmark designed to evaluate EI capabilities in open-source LLMs across diverse linguistic and cultural contexts. We evaluate six LLMs: LLaMA3 (8B), LLaMA3-Instruct, Gemma (9B), Gemma-Instruct, Qwen2.5 (7B), and Qwen2.5-Instruct on EmoCap-Bench, identifying Qwen2.5-Instruct as the strongest baseline. To assess the potential for enhancing EI capabilities, we fine-tune both Qwen2.5-Base and Qwen2.5-Instruct using LoRA adapters on UltraChat (UC), a large-scale, instruction-tuned dialogue dataset, in both English and Arabic. Our statistical analysis reveals that among the five EI layers, only the Appraisal layer shows significant improvement through UC-based fine-tuning. These findings highlight the limitations of existing pretraining and instruction-tuning paradigms in equipping LLMs with deeper emotional reasoning and underscore the need for targeted data and modeling strategies for comprehensive EI alignment.

[Arxiv](https://arxiv.org/abs/2508.06196)