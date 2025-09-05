# 合成乐谱问题以用于评估与强化学习

发布时间：2025年09月04日

`LLM应用` `媒体与娱乐`

> Synthesizing Sheet Music Problems for Evaluation and Reinforcement Learning

# 摘要

> 提升大型语言模型（LLMs）和多模态大型语言模型（MLLMs）的乐谱解读能力，是打造AI音乐家的核心环节。然而，目前针对乐谱推理的研究既缺少评估基准，也缺乏训练数据。为此，我们提出基于音乐理论合成乐谱问题的方案——该方案既能作为评估基准，也可充当带可验证奖励的强化学习（RLVR）训练数据。我们构建了一个数据合成框架，可生成文本与视觉双模态的可验证乐谱问题，进而形成合成乐谱推理基准（SSMR-Bench）及配套训练集。在SSMR-Bench上的评估结果显示，模型的推理能力对乐谱解读至关重要；而Gemini 2.5-Pro的表现欠佳，则凸显了MLLMs在解读视觉形式乐谱时仍面临的难题。借助RLVR合成数据训练后，Qwen3-8B-Base和Qwen2.5-VL-Instruct在SSMR-Bench上的性能均有提升。此外，经训练的Qwen3-8B-Base在MusicTheoryBench上的整体表现超越GPT-4，且结合角色扮演与思维链策略时，推理性能达到了与GPT-4相当的水平。值得注意的是，其数学问题解决能力也较原始Qwen3-8B-Base有所增强。研究结果还表明，强化后的推理能力对音乐创作亦有助益。总之，我们首次提出基于音乐理论规则合成乐谱问题的思路，不仅证实了其在提升模型乐谱理解推理能力上的有效性，更为AI辅助音乐创作开辟了新可能。

> Enhancing the ability of Large Language Models (LLMs) and Multimodal Large Language Models (MLLMs) to interpret sheet music is a crucial step toward building AI musicians. However, current research lacks both evaluation benchmarks and training data for sheet music reasoning. To address this, we propose the idea of synthesizing sheet music problems grounded in music theory, which can serve both as evaluation benchmarks and as training data for reinforcement learning with verifiable rewards (RLVR). We introduce a data synthesis framework that generates verifiable sheet music questions in both textual and visual modalities, leading to the Synthetic Sheet Music Reasoning Benchmark (SSMR-Bench) and a complementary training set. Evaluation results on SSMR-Bench show the importance of models' reasoning abilities in interpreting sheet music. At the same time, the poor performance of Gemini 2.5-Pro highlights the challenges that MLLMs still face in interpreting sheet music in a visual format. By leveraging synthetic data for RLVR, Qwen3-8B-Base and Qwen2.5-VL-Instruct achieve improvements on the SSMR-Bench. Besides, the trained Qwen3-8B-Base surpasses GPT-4 in overall performance on MusicTheoryBench and achieves reasoning performance comparable to GPT-4 with the strategies of Role play and Chain-of-Thought. Notably, its performance on math problems also improves relative to the original Qwen3-8B-Base. Furthermore, our results show that the enhanced reasoning ability can also facilitate music composition. In conclusion, we are the first to propose the idea of synthesizing sheet music problems based on music theory rules, and demonstrate its effectiveness not only in advancing model reasoning for sheet music understanding but also in unlocking new possibilities for AI-assisted music creation.

[Arxiv](https://arxiv.org/abs/2509.04059)