# UniCrossAdapter：CLIP 多模态适配，助力放射科报告生成

发布时间：2025年03月20日

`LLM应用` `计算机视觉`

> UniCrossAdapter: Multimodal Adaptation of CLIP for Radiology Report Generation

# 摘要

> 自动放射科报告生成旨在为放射科医生提供快速、准确的报告生成工具，从而解决传统报告流程繁琐且易出错的问题。尽管 recent works 在这一领域取得了进展，但医学图像与文本发现的对齐学习仍然面临挑战，主要原因在于标注的医学数据相对匮乏。例如，用于此任务的数据集远小于计算机视觉中用于图像描述的数据集。在这项工作中，我们提出了一种创新方法，通过迁移大规模预训练的视觉-语言模型CLIP的表征能力，以更好地捕捉图像和文本之间的跨模态语义。然而，由于自然图像与放射学之间的领域差距，直接应用CLIP效果不佳。为了解决这一问题，我们引入了UniCrossAdapter，这是一种轻量级的适配器模块。这些模块集成到CLIP中，并在目标任务上进行微调，同时保持基础模型参数不变。通过跨模态及其交互分布的方式，这些适配器模块能够有效增强视觉-语言的对齐效果。我们在两个公共数据集上的实验验证了我们方法的有效性，并在放射科报告生成领域推动了现有技术水平。我们提出的迁移学习框架为利用大规模预训练模型中的语义知识来解决数据稀缺的医学视觉-语言任务提供了一种有效手段。代码可在https://github.com/chauncey-tow/MRG-CLIP获取。

> Automated radiology report generation aims to expedite the tedious and error-prone reporting process for radiologists. While recent works have made progress, learning to align medical images and textual findings remains challenging due to the relative scarcity of labeled medical data. For example, datasets for this task are much smaller than those used for image captioning in computer vision. In this work, we propose to transfer representations from CLIP, a large-scale pre-trained vision-language model, to better capture cross-modal semantics between images and texts. However, directly applying CLIP is suboptimal due to the domain gap between natural images and radiology. To enable efficient adaptation, we introduce UniCrossAdapter, lightweight adapter modules that are incorporated into CLIP and fine-tuned on the target task while keeping base parameters fixed. The adapters are distributed across modalities and their interaction to enhance vision-language alignment. Experiments on two public datasets demonstrate the effectiveness of our approach, advancing state-of-the-art in radiology report generation. The proposed transfer learning framework provides a means of harnessing semantic knowledge from large-scale pre-trained models to tackle data-scarce medical vision-language tasks. Code is available at https://github.com/chauncey-tow/MRG-CLIP.

[Arxiv](https://arxiv.org/abs/2503.15940)