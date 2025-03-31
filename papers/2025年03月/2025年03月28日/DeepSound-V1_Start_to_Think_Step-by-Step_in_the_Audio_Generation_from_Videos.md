# DeepSound-V1：从视频中实现音频生成的逐步思考

发布时间：2025年03月28日

`LLM应用` `视频处理` `音频生成`

> DeepSound-V1: Start to Think Step-by-Step in the Audio Generation from Videos

# 摘要

> 目前，通过多种多模态联合学习框架，我们能够从视频和可选文本输入中合成高质量的同步音频。然而，视觉与生成音频领域之间的精确对齐仍远未达到理想状态。其中一个关键因素是开源的视频-音频和文本-音频基准中缺乏足够的时序和语义对齐标注。因此，我们提出了一种从视频中生成音频的框架，利用多模态大型语言模型（MLLM）的内部思维链（CoT）实现逐步推理，而无需额外的标注。此外，我们还构建了一个对应的多模态推理数据集，以促进音频生成中初始推理的学习。在实验中，我们验证了所提出的框架在减少生成音频中的对位不准（配音错位）和与各种最先进模型相比实现具有竞争力的性能方面的有效性。评估结果显示，所提出的方法在多个指标上优于现有最先进方法。具体来说，F DP aSST指标降低达10.07%，F DP AN N s指标降低达11.62%，F DV GG指标降低达38.61%。此外，IS指标提升达4.95%，IB-score指标提升达6.39%，DeSync指标降低达0.89%。

> Currently, high-quality, synchronized audio is synthesized from video and optional text inputs using various multi-modal joint learning frameworks. However, the precise alignment between the visual and generated audio domains remains far from satisfactory. One key factor is the lack of sufficient temporal and semantic alignment annotations in open-source video-audio and text-audio benchmarks. Therefore, we propose a framework for audio generation from videos, leveraging the internal chain-of-thought (CoT) of a multi-modal large language model (MLLM) to enable step-by-step reasoning without requiring additional annotations. Additionally, a corresponding multi-modal reasoning dataset is constructed to facilitate the learning of initial reasoning in audio generation. In the experiments, we demonstrate the effectiveness of the proposed framework in reducing misalignment (voice-over) in generated audio and achieving competitive performance compared to various state-of-the-art models. The evaluation results show that the proposed method outperforms state-of-the-art approaches across multiple metrics. Specifically, the F DP aSST indicator is reduced by up to 10.07%, the F DP AN N s indicator by up to 11.62%, and the F DV GG indicator by up to 38.61%. Furthermore, the IS indicator improves by up to 4.95%, the IB-score indicator increases by up to 6.39%, and the DeSync indicator is reduced by up to 0.89%.

[Arxiv](https://arxiv.org/abs/2503.22208)