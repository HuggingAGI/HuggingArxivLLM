# FLAME-MoE：一个透明化的端到端混合专家语言模型研究平台。

发布时间：2025年05月26日

`LLM理论` `人工智能` `开源社区`

> FLAME-MoE: A Transparent End-to-End Research Platform for Mixture-of-Experts Language Models

# 摘要

> 近期，大语言模型如Gemini-1.5、DeepSeek-V3和Llama-4纷纷采用专家混合架构（MoE），通过仅激活部分模型参数实现了效率与性能的精妙平衡。然而，学术界仍缺乏一个完全开放的端到端MoE研究平台，用于深入探究模型扩展、路由机制和专家行为。为此，我们推出了FLAME-MoE——一个完全开源的研究套件，包含7个解码器模型，参数规模从38M到1.7B不等。其架构设计——64个专家、top-8门控机制以及2个共享专家——高度贴近现代生产环境中的大语言模型。所有训练数据管道、脚本、日志和检查点均公开可用，支持可复现的实验研究。在6项评估任务中，FLAME-MoE相比参数量相同的密集基线模型，平均准确率提升了3.4个百分点。借助完整的训练轨迹透明度，我们进行了初步分析，结果表明：专家逐渐专注于不同的token子集，共同激活矩阵保持稀疏状态，反映专家使用的多样性，且路由行为在训练初期即趋于稳定。所有代码、训练日志和模型检查点均可在GitHub上获取：https://github.com/cmu-flame/FLAME-MoE。


> Recent large language models such as Gemini-1.5, DeepSeek-V3, and Llama-4 increasingly adopt Mixture-of-Experts (MoE) architectures, which offer strong efficiency-performance trade-offs by activating only a fraction of the model per token. Yet academic researchers still lack a fully open, end-to-end MoE platform for investigating scaling, routing, and expert behavior. We release FLAME-MoE, a completely open-source research suite composed of seven decoder-only models, ranging from 38M to 1.7B active parameters, whose architecture--64 experts with top-8 gating and 2 shared experts--closely reflects modern production LLMs. All training data pipelines, scripts, logs, and checkpoints are publicly available to enable reproducible experimentation. Across six evaluation tasks, FLAME-MoE improves average accuracy by up to 3.4 points over dense baselines trained with identical FLOPs. Leveraging full training trace transparency, we present initial analyses showing that (i) experts increasingly specialize on distinct token subsets, (ii) co-activation matrices remain sparse, reflecting diverse expert usage, and (iii) routing behavior stabilizes early in training. All code, training logs, and model checkpoints are available at https://github.com/cmu-flame/FLAME-MoE.

[Arxiv](https://arxiv.org/abs/2505.20225)