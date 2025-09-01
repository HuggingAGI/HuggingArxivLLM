# 面向Web的多智能体渗透测试AI

发布时间：2025年08月28日

`Agent` `基础理论`

> Multi-Agent Penetration Testing AI for the Web

# 摘要

> AI驱动的开发平台让更多人能轻松参与软件创作，但这种普及也带来了安全审计的规模化难题。研究显示，高达40%的AI生成代码存在漏洞，如今的开发节奏已远远超出全面安全评估的能力范围。
  为此，我们提出MAPTA——一个融合大语言模型编排、工具落地执行与端到端漏洞验证的多智能体Web安全自主评估系统。在104个挑战的XBOW基准测试中，MAPTA总体成功率达76.9%：SSRF和配置错误漏洞检测表现完美，权限绕过漏洞成功率83%，注入攻击领域也成绩斐然，服务器端模板注入（85%）和SQL注入（83%）尤为突出。不过跨站脚本（57%）和盲注SQL注入（0%）仍是待攻克的难点。成本分析显示，所有挑战总开销仅21.38美元，成功案例的中位成本为0.073美元，失败案例则为0.357美元。值得注意的是，成功与否与资源效率高度相关，这意味着可设置实用的提前停止阈值——约40次工具调用或每个挑战0.30美元即可。
  被扫描的GitHub仓库均为热门项目（8K-70K星标），而MAPTA每次开源评估的平均成本仅3.67美元，其实际应用价值不言而喻：它发现了远程代码执行（RCE）、命令注入、密钥泄露、任意文件写入等多个高危漏洞。所有发现均已负责任披露，其中10项正在CVE审核中。

> AI-powered development platforms are making software creation accessible to a broader audience, but this democratization has triggered a scalability crisis in security auditing. With studies showing that up to 40% of AI-generated code contains vulnerabilities, the pace of development now vastly outstrips the capacity for thorough security assessment.
  We present MAPTA, a multi-agent system for autonomous web application security assessment that combines large language model orchestration with tool-grounded execution and end-to-end exploit validation. On the 104-challenge XBOW benchmark, MAPTA achieves 76.9% overall success with perfect performance on SSRF and misconfiguration vulnerabilities, 83% success on broken authorization, and strong results on injection attacks including server-side template injection (85%) and SQL injection (83%). Cross-site scripting (57%) and blind SQL injection (0%) remain challenging. Our comprehensive cost analysis across all challenges totals $21.38 with a median cost of $0.073 for successful attempts versus $0.357 for failures. Success correlates strongly with resource efficiency, enabling practical early-stopping thresholds at approximately 40 tool calls or $0.30 per challenge.
  MAPTA's real-world findings are impactful given both the popularity of the respective scanned GitHub repositories (8K-70K stars) and MAPTA's low average operating cost of $3.67 per open-source assessment: MAPTA discovered critical vulnerabilities including RCEs, command injections, secret exposure, and arbitrary file write vulnerabilities. Findings are responsibly disclosed, 10 findings are under CVE review.

[Arxiv](https://arxiv.org/abs/2508.20816)