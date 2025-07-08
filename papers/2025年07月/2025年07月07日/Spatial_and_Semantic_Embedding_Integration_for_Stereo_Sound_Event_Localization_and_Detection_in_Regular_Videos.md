# 空间与语义嵌入整合助力普通视频中的立体声音事件定位与检测

发布时间：2025年07月07日

`LLM应用` `音频处理` `多模态`

> Spatial and Semantic Embedding Integration for Stereo Sound Event Localization and Detection in Regular Videos

# 摘要

> 本报告介绍了我们在DCASE2025任务3挑战中提交的音频仅和视听双轨参赛系统：正则视频内容中的立体声音事件定位与检测（SELD）。SELD是一项结合时间事件分类与空间定位的复杂任务，需要跨空间、时间和语义维度进行推理，其中语义维度的建模是最大的挑战。传统SELD架构依赖多通道输入，这限制了其在大规模预训练上的应用潜力。为解决这一问题，我们通过集成预训练的对比语言对齐模型——CLAP用于音频和OWL-ViT用于视觉输入——将语义信息融入标准SELD架构。这些嵌入被整合到一个为多模态融合定制的改进型Conformer模块中，我们将其命名为跨模态Conformer。此外，我们引入基于自相关性声学特征以提升距离估计的精度。我们在精选的合成音频和视听数据集上对模型进行预训练，并采用左右声道交换增强方法进一步扩大训练数据规模。无论是音频仅系统还是视听系统，在开发集上的表现均显著超越挑战基线，充分证明了我们的策略的有效性。通过模型集成以及基于人体关键点的视觉后处理步骤，性能得到进一步提升。未来的研究将致力于探究各模态的贡献，并探索架构变体以进一步优化结果。

> This report presents our systems submitted to the audio-only and audio-visual tracks of the DCASE2025 Task 3 Challenge: Stereo Sound Event Localization and Detection (SELD) in Regular Video Content. SELD is a complex task that combines temporal event classification with spatial localization, requiring reasoning across spatial, temporal, and semantic dimensions. The last is arguably the most challenging to model. Traditional SELD architectures rely on multichannel input, which limits their ability to leverage large-scale pre-training due to data constraints. To address this, we enhance standard SELD architectures with semantic information by integrating pre-trained, contrastive language-aligned models: CLAP for audio and OWL-ViT for visual inputs. These embeddings are incorporated into a modified Conformer module tailored for multimodal fusion, which we refer to as the Cross-Modal Conformer. Additionally, we incorporate autocorrelation-based acoustic features to improve distance estimation. We pre-train our models on curated synthetic audio and audio-visual datasets and apply a left-right channel swapping augmentation to further increase the training data. Both our audio-only and audio-visual systems substantially outperform the challenge baselines on the development set, demonstrating the effectiveness of our strategy. Performance is further improved through model ensembling and a visual post-processing step based on human keypoints. Future work will investigate the contribution of each modality and explore architectural variants to further enhance results.

[Arxiv](https://arxiv.org/abs/2507.04845)