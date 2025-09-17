# ResidualViT：实现高效的时间密集型视频编码

发布时间：2025年09月16日

`其他` `媒体与娱乐`

> ResidualViT for Efficient Temporally Dense Video Encoding

# 摘要

> 多项视频理解任务（如自然语言时间视频定位、时间活动定位及音频描述生成）均需对高时间分辨率采样帧进行“时间密集型”推理。但受时间分辨率要求所限，为这些任务计算帧级特征的成本极高。为此，本文提出三项改进，旨在降低时间密集型任务的特征计算成本。首先，我们提出一种名为ResidualViT的视觉Transformer（ViT）架构，该架构借助视频中丰富的时间冗余，高效计算时间密集型帧级特征。该架构包含两部分：（i）可学习残差连接，确保连续帧的时间一致性；（ii）令牌缩减模块，通过选择性丢弃时间冗余信息并复用预训练基础模型权重，提升处理速度。其次，我们提出轻量级蒸馏策略，用于逼近原始基础模型的帧级特征。最后，我们在四个任务、五个数据集上，分别在零样本和全监督设置下验证了所提方法：计算成本降低高达60%，推理速度提升高达2.5倍，且精度仍接近原始基础模型。

> Several video understanding tasks, such as natural language temporal video grounding, temporal activity localization, and audio description generation, require "temporally dense" reasoning over frames sampled at high temporal resolution. However, computing frame-level features for these tasks is computationally expensive given the temporal resolution requirements. In this paper, we make three contributions to reduce the cost of computing features for temporally dense tasks. First, we introduce a vision transformer (ViT) architecture, dubbed ResidualViT, that leverages the large temporal redundancy in videos to efficiently compute temporally dense frame-level features. Our architecture incorporates (i) learnable residual connections that ensure temporal consistency across consecutive frames and (ii) a token reduction module that enhances processing speed by selectively discarding temporally redundant information while reusing weights of a pretrained foundation model. Second, we propose a lightweight distillation strategy to approximate the frame-level features of the original foundation model. Finally, we evaluate our approach across four tasks and five datasets, in both zero-shot and fully supervised settings, demonstrating significant reductions in computational cost (up to 60%) and improvements in inference speed (up to 2.5x faster), all while closely approximating the accuracy of the original foundation model.

[Arxiv](https://arxiv.org/abs/2509.13255)