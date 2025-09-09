# DCMI：一种针对检索增强生成的差分校准成员推理攻击

发布时间：2025年09月07日

`RAG` `基础理论`

> DCMI: A Differential Calibration Membership Inference Attack Against Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）虽能通过整合外部知识库有效降低幻觉风险，却也带来了成员推断攻击（MIAs）的安全隐患，在处理敏感数据的系统中尤为突出。现有针对RAG外部数据库的成员推断攻击多依赖模型响应，却忽略了非成员检索文档对RAG输出的干扰，导致攻击效果受限。为此，我们提出差分校准成员推断攻击（DCMI），以减轻非成员检索文档的负面影响。具体而言，DCMI利用查询扰动下成员与非成员检索文档的敏感度差异，通过生成扰动查询进行校准，分离成员检索文档的贡献，同时最大限度减少非成员检索文档的干扰。在逐步放宽假设的实验中，DCMI表现持续优于基线——例如，针对基于Flan-T5的RAG系统时，AUC达97.42%、准确率达94.35%，较MBA基线提升超40%。此外，在Dify和MaxKB等真实RAG平台上，DCMI仍保持10%-20%的基线优势。这些结果揭示了RAG系统中严峻的隐私风险，也凸显了强化保护机制的迫切性。我们呼吁研究社区关注此类问题，像我们一样深入探究快速发展的RAG系统中的数据泄露风险。相关代码已开源：https://github.com/Xinyu140203/RAG_MIA。

> While Retrieval-Augmented Generation (RAG) effectively reduces hallucinations by integrating external knowledge bases, it introduces vulnerabilities to membership inference attacks (MIAs), particularly in systems handling sensitive data. Existing MIAs targeting RAG's external databases often rely on model responses but ignore the interference of non-member-retrieved documents on RAG outputs, limiting their effectiveness. To address this, we propose DCMI, a differential calibration MIA that mitigates the negative impact of non-member-retrieved documents. Specifically, DCMI leverages the sensitivity gap between member and non-member retrieved documents under query perturbation. It generates perturbed queries for calibration to isolate the contribution of member-retrieved documents while minimizing the interference from non-member-retrieved documents. Experiments under progressively relaxed assumptions show that DCMI consistently outperforms baselines--for example, achieving 97.42% AUC and 94.35% Accuracy against the RAG system with Flan-T5, exceeding the MBA baseline by over 40%. Furthermore, on real-world RAG platforms such as Dify and MaxKB, DCMI maintains a 10%-20% advantage over the baseline. These results highlight significant privacy risks in RAG systems and emphasize the need for stronger protection mechanisms. We appeal to the community's consideration of deeper investigations, like ours, against the data leakage risks in rapidly evolving RAG systems. Our code is available at https://github.com/Xinyu140203/RAG_MIA.

[Arxiv](https://arxiv.org/abs/2509.06026)