# 本研究致力于揭开未知安全实体间的潜在关联，探寻那些未曾显现的隐性联系。

发布时间：2024年03月04日

`Agent`

> Unveiling Hidden Links Between Unseen Security Entities

# 摘要

> 面对软件漏洞层出不穷的问题，安全数据库与负责快速识别、分类和解决这些问题的安全分析师面临着严峻挑战。随着NVD报告的漏洞数量持续攀升，传统的手工分析不仅耗时漫长，而且错误频发。本文推出一种创新方案VulnScopper，它巧妙地运用多模态表示学习技术，融合了知识图谱（KG）与自然语言处理（NLP），实现对软件漏洞分析过程的自动化和优化。VulnScopper倚仗一个名为ULTRA的知识图谱底层模型与大型语言模型(LLM)的强大组合，成功应对新出现的实体问题，突破了过往依赖KG方法的局限。实验证明，在NVD及红帽CVE数据库这两大数据集中，VulnScopper在 CVEs、CWEs 和 CPEs 之间链接预测上的准确性显著提升，其Hits@10准确率高达78%，并在基于红帽CVE数据库预测CWE标签时，较大型语言模型取得了11.7%的进步。值得关注的是，据统计，在漏洞披露后的首月内，仅6.37%的关联CPE被正式公布，而这些未及时公开的CPE往往与关键或高危漏洞密切相关，按照CISA和PCI等合规框架要求，应在15至30天内得到修补。VulnScopper能挖掘与漏洞相关的未发现产品信息，从而加快修复速度，改善漏洞管理效果。我们通过解析2023年若干CVE案例生动展现了这一强大功能。

> The proliferation of software vulnerabilities poses a significant challenge for security databases and analysts tasked with their timely identification, classification, and remediation. With the National Vulnerability Database (NVD) reporting an ever-increasing number of vulnerabilities, the traditional manual analysis becomes untenably time-consuming and prone to errors. This paper introduces VulnScopper, an innovative approach that utilizes multi-modal representation learning, combining Knowledge Graphs (KG) and Natural Language Processing (NLP), to automate and enhance the analysis of software vulnerabilities. Leveraging ULTRA, a knowledge graph foundation model, combined with a Large Language Model (LLM), VulnScopper effectively handles unseen entities, overcoming the limitations of previous KG approaches. We evaluate VulnScopper on two major security datasets, the NVD and the Red Hat CVE database. Our method significantly improves the link prediction accuracy between Common Vulnerabilities and Exposures (CVEs), Common Weakness Enumeration (CWEs), and Common Platform Enumerations (CPEs). Our results show that VulnScopper outperforms existing methods, achieving up to 78% Hits@10 accuracy in linking CVEs to CPEs and CWEs and presenting an 11.7% improvement over large language models in predicting CWE labels based on the Red Hat database. Based on the NVD, only 6.37% of the linked CPEs are being published during the first 30 days; many of them are related to critical and high-risk vulnerabilities which, according to multiple compliance frameworks (such as CISA and PCI), should be remediated within 15-30 days. Our model can uncover new products linked to vulnerabilities, reducing remediation time and improving vulnerability management. We analyzed several CVEs from 2023 to showcase this ability.

[Arxiv](https://arxiv.org/abs/2403.02014)