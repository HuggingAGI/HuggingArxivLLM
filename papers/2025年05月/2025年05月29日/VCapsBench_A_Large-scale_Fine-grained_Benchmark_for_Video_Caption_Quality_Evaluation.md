# VCapsBench：用于视频字幕质量评估的大规模细粒度基准

发布时间：2025年05月29日

`LLM应用` `视频处理`

> VCapsBench: A Large-scale Fine-grained Benchmark for Video Caption Quality Evaluation

# 摘要

> 视频字幕在文本到视频生成任务中至关重要，其质量直接影响生成视频的语义连贯性和视觉质量。虽然大型视觉语言模型（VLMs）在字幕生成方面表现突出，但现有评估基准在细粒度评估方面仍有不足，尤其是在捕捉对视频生成至关重要的时空细节方面。为解决这一问题，我们推出了细粒度视频字幕评估基准（VCapsBench）——首个大规模细粒度基准，包含5,677个视频和109,796个问答对。这些问答对跨越21个关键维度（如摄像机运动和镜头类型）进行系统标注，这些维度在实证中被证明对文本到视频生成至关重要。我们还提出了三个评估指标（准确性（AR）、不一致性率（IR）、覆盖率率（CR）），并基于大型语言模型（LLM）构建了一个自动化评估系统，通过对比问答对分析验证字幕质量。通过为字幕优化提供实用见解，我们的基准将助力更 robust 的文本到视频模型开发。数据集和代码现已开源，访问地址：https://github.com/GXYM/VCapsBench。


> Video captions play a crucial role in text-to-video generation tasks, as their quality directly influences the semantic coherence and visual fidelity of the generated videos. Although large vision-language models (VLMs) have demonstrated significant potential in caption generation, existing benchmarks inadequately address fine-grained evaluation, particularly in capturing spatial-temporal details critical for video generation. To address this gap, we introduce the Fine-grained Video Caption Evaluation Benchmark (VCapsBench), the first large-scale fine-grained benchmark comprising 5,677 (5K+) videos and 109,796 (100K+) question-answer pairs. These QA-pairs are systematically annotated across 21 fine-grained dimensions (e.g., camera movement, and shot type) that are empirically proven critical for text-to-video generation. We further introduce three metrics (Accuracy (AR), Inconsistency Rate (IR), Coverage Rate (CR)), and an automated evaluation pipeline leveraging large language model (LLM) to verify caption quality via contrastive QA-pairs analysis. By providing actionable insights for caption optimization, our benchmark can advance the development of robust text-to-video models. The dataset and codes are available at website: https://github.com/GXYM/VCapsBench.

[Arxiv](https://arxiv.org/abs/2505.23484)