# 任务特定适应结合顺序感知对齐方法，用于少量样本动作识别任务。

发布时间：2025年05月09日

`LLM应用

摘要中的研究主要探讨了如何利用大型语言模型（LLMs）在少样本动作识别（FSAR）任务中的应用。通过引入语义顺序适配器和跨模态对齐策略，研究展示了LLMs在生成描述和建模顺序关系中的应用，从而优化了模型性能。因此，这篇论文属于LLM应用类别。` `计算机视觉`

> Task-Adapter++: Task-specific Adaptation with Order-aware Alignment for Few-shot Action Recognition

# 摘要

> 大规模预训练模型在语言和图像任务中取得了显著成功，推动了预训练图像模型（如CLIP）在少样本动作识别（FSAR）领域的广泛应用。然而，现有方法仍存在以下问题：1）直接微调损害了预训练模型的泛化能力；2）视觉任务中任务特定信息探索不足；3）文本建模中语义顺序信息被忽视；4）跨模态对齐技术忽略了多模态信息的时间耦合性。针对这些问题，我们提出了Task-Adapter++，一种参数高效的图像和文本编码器双适应方法。具体而言，我们为图像编码器设计了任务特定的适应机制，以便在特征提取过程中捕捉最具判别性的信息。同时，我们利用大型语言模型（LLMs）为每个动作类别生成详细的顺序子动作描述，并在文本编码器中引入语义顺序适配器，有效建模子动作间的顺序关系。最后，我们提出了一种创新的细粒度跨模态对齐策略，将视觉特征与语义描述对齐至同一时间阶段。实验结果表明，Task-Adapter++在5个基准数据集上均达到了当前最优性能。代码已开源，地址为https://github.com/Jaulin-Bage/Task-Adapter-pp。

> Large-scale pre-trained models have achieved remarkable success in language and image tasks, leading an increasing number of studies to explore the application of pre-trained image models, such as CLIP, in the domain of few-shot action recognition (FSAR). However, current methods generally suffer from several problems: 1) Direct fine-tuning often undermines the generalization capability of the pre-trained model; 2) The exploration of task-specific information is insufficient in the visual tasks; 3) The semantic order information is typically overlooked during text modeling; 4) Existing cross-modal alignment techniques ignore the temporal coupling of multimodal information. To address these, we propose Task-Adapter++, a parameter-efficient dual adaptation method for both image and text encoders. Specifically, to make full use of the variations across different few-shot learning tasks, we design a task-specific adaptation for the image encoder so that the most discriminative information can be well noticed during feature extraction. Furthermore, we leverage large language models (LLMs) to generate detailed sequential sub-action descriptions for each action class, and introduce semantic order adapters into the text encoder to effectively model the sequential relationships between these sub-actions. Finally, we develop an innovative fine-grained cross-modal alignment strategy that actively maps visual features to reside in the same temporal stage as semantic descriptions. Extensive experiments fully demonstrate the effectiveness and superiority of the proposed method, which achieves state-of-the-art performance on 5 benchmarks consistently. The code is open-sourced at https://github.com/Jaulin-Bage/Task-Adapter-pp.

[Arxiv](https://arxiv.org/abs/2505.06002)