# 自动主题审查预防未来死亡报告：使用大型语言模型复制ONS儿童自杀研究

发布时间：2025年07月28日

`LLM应用` `公共卫生` `公共安全`

> Automating Thematic Review of Prevention of Future Deaths Reports: Replicating the ONS Child Suicide Study using Large Language Models

# 摘要

> # 摘要
英格兰和威尔士的验尸官发布的预防未来死亡报告（PFD）会指出可能导致更多人丧生的系统性风险。由于需要手动识别和编码相关案例，此前对这些报告的分析一直受到限制。2025年，英国国家统计局（ONS）发布了一份关于儿童自杀PFD报告的全国主题审查（$\leq$ 18岁），从2015年1月至2023年11月期间识别出37例案例——这一过程完全基于手动整理和编码。我们评估了是否可以使用一个完全自动化的开源“文本到表格”语言模型管道（PFDToolkit）来重现ONS对儿童自杀PFD报告的识别和主题分析，并评估效率和可靠性的提升。

通过PFDToolkit的大型语言模型管道处理了从2013年7月至2023年11月发布的所有4,249份PFD报告。自动化筛选识别出验尸官认定18岁或以下个体死于自杀的案例，并对符合条件的报告进行接收者类别和23个关注子主题的编码，复现了ONS的编码框架。PFDToolkit识别出72份儿童自杀PFD报告——几乎是ONS统计数量的两倍。

三位匿名临床医生对分层抽样的144份报告进行了验证，以验证儿童自杀筛查的准确性。与共识临床注释相比，基于LLM的工作流显示出显著到几乎完美的一致性（Cohen's $κ$ = 0.82，95% CI: 0.66-0.98，原始一致率 = 91%）。从开始到结束的脚本运行时间为8分16秒，将此前需要数月完成的过程缩短到了只需几分钟即可完成。

这表明，基于LLM的自动化分析可以可靠且高效地重现手动主题审查的 coronial 数据，为公共卫生和安全提供可扩展、可重复和及时的见解。PFDToolkit可供未来研究使用，现已公开发布。

> Prevention of Future Deaths (PFD) reports, issued by coroners in England and Wales, flag systemic hazards that may lead to further loss of life. Analysis of these reports has previously been constrained by the manual effort required to identify and code relevant cases. In 2025, the Office for National Statistics (ONS) published a national thematic review of child-suicide PFD reports ($\leq$ 18 years), identifying 37 cases from January 2015 to November 2023 - a process based entirely on manual curation and coding. We evaluated whether a fully automated, open source "text-to-table" language-model pipeline (PFD Toolkit) could reproduce the ONS's identification and thematic analysis of child-suicide PFD reports, and assessed gains in efficiency and reliability. All 4,249 PFD reports published from July 2013 to November 2023 were processed via PFD Toolkit's large language model pipelines. Automated screening identified cases where the coroner attributed death to suicide in individuals aged 18 or younger, and eligible reports were coded for recipient category and 23 concern sub-themes, replicating the ONS coding frame. PFD Toolkit identified 72 child-suicide PFD reports - almost twice the ONS count. Three blinded clinicians adjudicated a stratified sample of 144 reports to validate the child-suicide screening. Against the post-consensus clinical annotations, the LLM-based workflow showed substantial to almost-perfect agreement (Cohen's $κ$ = 0.82, 95% CI: 0.66-0.98, raw agreement = 91%). The end-to-end script runtime was 8m 16s, transforming a process that previously took months into one that can be completed in minutes. This demonstrates that automated LLM analysis can reliably and efficiently replicate manual thematic reviews of coronial data, enabling scalable, reproducible, and timely insights for public health and safety. The PFD Toolkit is openly available for future research.

[Arxiv](https://arxiv.org/abs/2507.20786)