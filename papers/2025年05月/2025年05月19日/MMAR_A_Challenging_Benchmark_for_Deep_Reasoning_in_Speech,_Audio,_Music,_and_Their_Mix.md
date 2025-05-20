# MMAR：语音、音频、音乐及其混合领域中深度推理的挑战性基准

发布时间：2025年05月19日

`其他` `多模态`

> MMAR: A Challenging Benchmark for Deep Reasoning in Speech, Audio, Music, and Their Mix

# 摘要

> 我们推出了全新的MMAR基准测试，专注于评估音频语言模型（ALMs）在大规模跨学科任务中的深度推理能力。MMAR包含1,000个精心策划的音频-问题-答案三元组，这些数据源自真实互联网视频，并经过多次迭代校验和质量把控，以确保数据的高质量。与现有仅限于声音、音乐或语音特定领域的基准测试不同，MMAR将其扩展到广泛的现实世界音频场景，包括声音、音乐和语音的混合模态组合。MMAR中的每个问题都按照四个推理层次进行分类：信号、感知、语义和文化，每个层次内还有额外的子类别，以反映任务的多样性和复杂性。为了进一步促进该领域的研究，我们为每个问题标注了链式思维（CoT）推理过程，以推动未来在音频推理方面的进展。基准测试中的每个项目都需要超越表面理解的多步骤深度推理。此外，其中一部分问题需要研究生级别的感知和领域专业知识，从而提高了基准测试的难度和深度。我们使用多种模型对MMAR进行了评估，包括大型音频语言模型（LALMs）、大型音频推理模型（LARMs）、全语言模型（OLMs）、大型语言模型（LLMs）和大型推理模型（LRMs），并采用音频字幕作为输入。这些模型在MMAR上的表现突显了该基准测试的挑战性，我们的分析进一步揭示了当前模型在理解和推理能力方面的关键局限性。我们希望MMAR能够成为未来在这一重要但尚未充分探索领域中取得进展的催化剂。
    

> We introduce MMAR, a new benchmark designed to evaluate the deep reasoning capabilities of Audio-Language Models (ALMs) across massive multi-disciplinary tasks. MMAR comprises 1,000 meticulously curated audio-question-answer triplets, collected from real-world internet videos and refined through iterative error corrections and quality checks to ensure high quality. Unlike existing benchmarks that are limited to specific domains of sound, music, or speech, MMAR extends them to a broad spectrum of real-world audio scenarios, including mixed-modality combinations of sound, music, and speech. Each question in MMAR is hierarchically categorized across four reasoning layers: Signal, Perception, Semantic, and Cultural, with additional sub-categories within each layer to reflect task diversity and complexity. To further foster research in this area, we annotate every question with a Chain-of-Thought (CoT) rationale to promote future advancements in audio reasoning. Each item in the benchmark demands multi-step deep reasoning beyond surface-level understanding. Moreover, a part of the questions requires graduate-level perceptual and domain-specific knowledge, elevating the benchmark's difficulty and depth. We evaluate MMAR using a broad set of models, including Large Audio-Language Models (LALMs), Large Audio Reasoning Models (LARMs), Omni Language Models (OLMs), Large Language Models (LLMs), and Large Reasoning Models (LRMs), with audio caption inputs. The performance of these models on MMAR highlights the benchmark's challenging nature, and our analysis further reveals critical limitations of understanding and reasoning capabilities among current models. We hope MMAR will serve as a catalyst for future advances in this important but little-explored area.

[Arxiv](https://arxiv.org/abs/2505.13032)