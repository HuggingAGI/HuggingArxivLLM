# RAPID：检索增强型差分隐私扩散模型训练

发布时间：2025年02月18日

`RAG` `数据隐私保护` `生成模型`

> RAPID: Retrieval Augmented Training of Differentially Private Diffusion Models

# 摘要

> 差分隐私扩散模型（DPDMs）将扩散模型的强大生成能力与敏感数据的差分隐私（DP）保护相结合。然而，现有的DPDM训练方法往往面临效用下降、内存占用大和推理成本高昂的问题，限制了它们的实际应用。为了解决这些挑战，我们提出了RAPID：一种将检索增强生成（RAG）融入DPDM训练的创新方法。具体而言，RAPID利用公开数据构建样本轨迹的知识库；在训练私有数据的扩散模型时，RAPID将早期采样步骤作为查询，从知识库中检索相似轨迹作为替代，并专注于以差分隐私的方式训练后期采样步骤。通过基准数据集和模型的全面评估表明，在相同的隐私保证下，RAPID在生成质量、内存占用和推理成本方面显著优于现有最优方法，表明检索增强的DP训练是未来开发隐私保护生成模型的有希望方向。代码可从以下链接获取：https://github.com/TanqiuJiang/RAPID

> Differentially private diffusion models (DPDMs) harness the remarkable generative capabilities of diffusion models while enforcing differential privacy (DP) for sensitive data. However, existing DPDM training approaches often suffer from significant utility loss, large memory footprint, and expensive inference cost, impeding their practical uses. To overcome such limitations, we present RAPID: Retrieval Augmented PrIvate Diffusion model, a novel approach that integrates retrieval augmented generation (RAG) into DPDM training. Specifically, RAPID leverages available public data to build a knowledge base of sample trajectories; when training the diffusion model on private data, RAPID computes the early sampling steps as queries, retrieves similar trajectories from the knowledge base as surrogates, and focuses on training the later sampling steps in a differentially private manner. Extensive evaluation using benchmark datasets and models demonstrates that, with the same privacy guarantee, RAPID significantly outperforms state-of-the-art approaches by large margins in generative quality, memory footprint, and inference cost, suggesting that retrieval-augmented DP training represents a promising direction for developing future privacy-preserving generative models. The code is available at: https://github.com/TanqiuJiang/RAPID

[Arxiv](https://arxiv.org/abs/2502.12794)