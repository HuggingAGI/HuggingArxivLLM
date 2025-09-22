# # 面向医学深度伪造检测：全面数据集与新方法

发布时间：2025年09月19日

`其他` `医疗健康`

> Toward Medical Deepfake Detection: A Comprehensive Dataset and Novel Method

# 摘要

> 生成式AI在医学影像领域的飞速发展既带来了重大机遇，也伴随着严峻挑战，尤其是伪造医学图像可能对医疗系统造成破坏的风险。这些合成图像带来了诊断误导、财务欺诈和虚假信息等严重风险。然而，针对这些威胁的医学取证研究仍较为有限，且严重缺乏专门为此领域定制的综合数据集。此外，现有的媒体取证方法主要针对自然图像或面部图像设计，无法充分捕捉AI生成医学图像的独特特征和细微伪影。为应对这些挑战，我们提出了	extbf{MedForensics}——一个涵盖六种医学模态和十二种最先进医学生成模型的大规模医学取证数据集。我们还提出了	extbf{DSKI}——一种新颖的	extbf{双}阶段	extbf{知}识	extbf{融}合检测器（Dual-Stage Knowledge Infusing detector），它构建了专为检测AI生成医学图像定制的视觉-语言特征空间。DSKI包含两个核心组件：1）跨域微迹适配器（CDFA），用于在训练阶段从空间域和噪声域提取细微的伪造线索；2）医学取证检索模块（MFRM），通过测试阶段的少样本检索提高检测准确率。实验结果表明，DSKI显著优于现有方法和人类专家，在多种医学模态上均达到了卓越的准确率。

> The rapid advancement of generative AI in medical imaging has introduced both significant opportunities and serious challenges, especially the risk that fake medical images could undermine healthcare systems. These synthetic images pose serious risks, such as diagnostic deception, financial fraud, and misinformation. However, research on medical forensics to counter these threats remains limited, and there is a critical lack of comprehensive datasets specifically tailored for this field. Additionally, existing media forensic methods, which are primarily designed for natural or facial images, are inadequate for capturing the distinct characteristics and subtle artifacts of AI-generated medical images. To tackle these challenges, we introduce \textbf{MedForensics}, a large-scale medical forensics dataset encompassing six medical modalities and twelve state-of-the-art medical generative models. We also propose \textbf{DSKI}, a novel \textbf{D}ual-\textbf{S}tage \textbf{K}nowledge \textbf{I}nfusing detector that constructs a vision-language feature space tailored for the detection of AI-generated medical images. DSKI comprises two core components: 1) a cross-domain fine-trace adapter (CDFA) for extracting subtle forgery clues from both spatial and noise domains during training, and 2) a medical forensic retrieval module (MFRM) that boosts detection accuracy through few-shot retrieval during testing. Experimental results demonstrate that DSKI significantly outperforms both existing methods and human experts, achieving superior accuracy across multiple medical modalities.

[Arxiv](https://arxiv.org/abs/2509.15711)