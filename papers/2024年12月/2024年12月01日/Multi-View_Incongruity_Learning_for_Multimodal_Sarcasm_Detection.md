# 用于多模态讽刺检测的多视图不一致学习

发布时间：2024年12月01日

`LLM应用` `多模态检测`

> Multi-View Incongruity Learning for Multimodal Sarcasm Detection

# 摘要

> 多模态讽刺检测（MSD）对各类下游任务意义重大。现有的 MSD 方法通常依赖于虚假的相关性。这些方法常常错将非关键特征置于优先地位，却仍能做出正确预测，这表明其在训练环境之外的泛化能力欠佳。针对此现象，本文采取了若干举措。其一，我们找出了导致依赖虚假相关性的两大主因。其二，我们通过提出一种用于多模态讽刺检测的、通过对比学习整合多模态不一致性（MICL）的新方法来应对这些挑战。具体而言，我们先是利用不一致性从三个视角（标记补丁、实体对象和情感）驱动多视图学习，接着引入大量的数据增强来缓解文本模态的有偏学习。另外，我们构建了一个测试集 SPMSD，其中包含潜在的虚假相关性，以评估模型的泛化能力。实验结果显示 MICL 在基准数据集上的优势，同时分析也表明 MICL 在减轻虚假相关性影响方面的进展。

> Multimodal sarcasm detection (MSD) is essential for various downstream tasks. Existing MSD methods tend to rely on spurious correlations. These methods often mistakenly prioritize non-essential features yet still make correct predictions, demonstrating poor generalizability beyond training environments. Regarding this phenomenon, this paper undertakes several initiatives. Firstly, we identify two primary causes that lead to the reliance of spurious correlations. Secondly, we address these challenges by proposing a novel method that integrate Multimodal Incongruities via Contrastive Learning (MICL) for multimodal sarcasm detection. Specifically, we first leverage incongruity to drive multi-view learning from three views: token-patch, entity-object, and sentiment. Then, we introduce extensive data augmentation to mitigate the biased learning of the textual modality. Additionally, we construct a test set, SPMSD, which consists potential spurious correlations to evaluate the the model's generalizability. Experimental results demonstrate the superiority of MICL on benchmark datasets, along with the analyses showcasing MICL's advancement in mitigating the effect of spurious correlation.

[Arxiv](https://arxiv.org/abs/2412.00756)