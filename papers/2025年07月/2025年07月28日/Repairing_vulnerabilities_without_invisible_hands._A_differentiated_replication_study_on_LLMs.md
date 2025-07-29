# 无需“无形之手”，修复漏洞。一项关于大型语言模型的差异化复制研究

发布时间：2025年07月28日

`LLM应用` `软件工程`

> Repairing vulnerabilities without invisible hands. A differentiated replication study on LLMs

# 摘要

> 背景：自动漏洞修复（AVR）是程序修复领域中一个快速发展的分支。近期研究表明，大型语言模型（LLMs）的表现优于传统技术，其成功不仅限于代码生成和故障检测。
    假设：这些改进可能源于隐藏的因素——“无形之手”，如训练数据泄露或完美的故障定位，这些因素使LLMs能够复制人类编写的同一代码修复。
    目标：我们在受控条件下通过在提示中故意添加错误到报告的漏洞位置来复制先前的AVR研究。如果LLMs只是复述记忆中的修复，无论定位错误大小，正确补丁的数量应该相同，因为任何偏移都会使模型偏离原始修复。
    方法：我们的修复流程从Vul4J和VJTrans基准测试中的漏洞开始，将故障位置从真实位置偏移n行。首先由一个LLM生成补丁，然后由另一个LLM审查，最后通过回归测试和漏洞验证测试来验证结果。最后，我们手动审核部分补丁，并使用Agresti-Coull-Wilson方法估计错误率。
    

> Background: Automated Vulnerability Repair (AVR) is a fast-growing branch of program repair. Recent studies show that large language models (LLMs) outperform traditional techniques, extending their success beyond code generation and fault detection.
  Hypothesis: These gains may be driven by hidden factors -- "invisible hands" such as training-data leakage or perfect fault localization -- that let an LLM reproduce human-authored fixes for the same code.
  Objective: We replicate prior AVR studies under controlled conditions by deliberately adding errors to the reported vulnerability location in the prompt. If LLMs merely regurgitate memorized fixes, both small and large localization errors should yield the same number of correct patches, because any offset should divert the model from the original fix.
  Method: Our pipeline repairs vulnerabilities from the Vul4J and VJTrans benchmarks after shifting the fault location by n lines from the ground truth. A first LLM generates a patch, a second LLM reviews it, and we validate the result with regression and proof-of-vulnerability tests. Finally, we manually audit a sample of patches and estimate the error rate with the Agresti-Coull-Wilson method.

[Arxiv](https://arxiv.org/abs/2507.20977)