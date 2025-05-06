# # 预训练语言模型与分子表征助力TCR-肽相互作用预测
结合预训练语言模型与分子表征，提升TCR-肽相互作用预测的准确性与效果

发布时间：2025年04月22日

`LLM应用` `生物医药` `人工智能`

> Enhancing TCR-Peptide Interaction Prediction with Pretrained Language Models and Molecular Representations

# 摘要

> 理解T细胞受体（TCR）与肽-主要组织相容性复合体（pMHC）之间的结合特异性是免疫治疗和疫苗开发的关键。然而，现有的预测模型在数据稀缺和面对新表位时，往往难以实现良好的泛化。为此，我们提出了LANTERN（基于大规模语言模型的增强TCR识别网络），一个结合蛋白质语言模型和肽化学表示的深度学习框架。通过使用ESM-1b对TCR β链序列进行编码，并将肽序列转换为由MolFormer处理的SMILES字符串，LANTERN能够捕获TCR-肽识别所需的丰富生物和化学特征。在与ChemBERTa、TITAN和NetTCR等现有模型的对比中，LANTERN展现了卓越的性能，尤其在零样本和小样本学习场景中表现突出。此外，我们的模型还采用了一种强大的负采样策略，并通过嵌入分析显示出显著的聚类改进。这些结果表明，LANTERN在推进TCR-pMHC结合预测方面具有巨大潜力，并为个性化免疫疗法的发展提供了有力支持。

> Understanding the binding specificity between T-cell receptors (TCRs) and peptide-major histocompatibility complexes (pMHCs) is central to immunotherapy and vaccine development. However, current predictive models struggle with generalization, especially in data-scarce settings and when faced with novel epitopes. We present LANTERN (Large lAnguage model-powered TCR-Enhanced Recognition Network), a deep learning framework that combines large-scale protein language models with chemical representations of peptides. By encoding TCR \b{eta}-chain sequences using ESM-1b and transforming peptide sequences into SMILES strings processed by MolFormer, LANTERN captures rich biological and chemical features critical for TCR-peptide recognition. Through extensive benchmarking against existing models such as ChemBERTa, TITAN, and NetTCR, LANTERN demonstrates superior performance, particularly in zero-shot and few-shot learning scenarios. Our model also benefits from a robust negative sampling strategy and shows significant clustering improvements via embedding analysis. These results highlight the potential of LANTERN to advance TCR-pMHC binding prediction and support the development of personalized immunotherapies.

[Arxiv](https://arxiv.org/abs/2505.01433)