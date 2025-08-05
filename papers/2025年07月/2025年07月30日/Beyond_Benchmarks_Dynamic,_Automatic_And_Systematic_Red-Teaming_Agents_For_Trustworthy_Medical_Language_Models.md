# 超越基准：动态、自动且系统化的红队测试代理，打造值得信赖的医疗语言模型

发布时间：2025年07月30日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在临床实践中的安全性和可靠性问题，并提出了一种动态、自动化的红队框架来持续测试模型在不同安全领域的表现。研究的重点在于模型的应用安全性和实际应用中的风险评估，而不是模型的理论或架构本身。因此，它属于LLM应用类别。` `模型安全`

> Beyond Benchmarks: Dynamic, Automatic And Systematic Red-Teaming Agents For Trustworthy Medical Language Models

# 摘要

> 在临床实践中确保大型语言模型（LLMs）的安全性和可靠性至关重要，这不仅能够防止患者受到伤害，还能推动AI在医疗领域的可信应用。然而，LLMs的发展速度极快，导致静态安全基准往往在发布时就已过时，仅能提供一个不完整且有时具有误导性的模型可信度图景。我们提出了一种动态、自动且系统化的（DAS）红队框架，通过持续对LLMs进行压力测试，可以揭示当前LLMs在四个关键安全领域中的显著弱点：鲁棒性、隐私、偏见/公平性以及幻觉。

我们开发了一组对抗性代理，用于自主地变异测试案例、识别/进化触发不安全行为的策略，并对模型响应进行评估，从而在无需人工干预的情况下实时发现漏洞。将DAS框架应用于15个专有和开源的LLMs后，我们发现静态基准性能与在对抗压力下的脆弱性之间存在显著差异。尽管在MedQA测试中模型的中位准确率超过80%，但94%的先前正确答案未能通过我们的动态鲁棒性测试。我们在其他领域也观察到了类似的高失败率：86%的场景中出现了隐私泄露，81%的公平性测试中认知偏见引导改变了临床建议，而在广泛使用的模型中，幻觉率超过66%。这种深层次的残余风险与常规临床实践的要求不符。

通过将红队测试从静态检查转变为动态压力测试审计，DAS红队框架为医院、监管机构和技术供应商提供了所需的安全监控，因为LLMs正逐渐嵌入到患者聊天机器人、决策支持仪表盘以及更广泛的医疗工作流程中。我们的框架为下一代医疗AI提供了可演进、可扩展且可靠的保障措施。


> Ensuring the safety and reliability of large language models (LLMs) in clinical practice is critical to prevent patient harm and promote trustworthy healthcare applications of AI. However, LLMs are advancing so rapidly that static safety benchmarks often become obsolete upon publication, yielding only an incomplete and sometimes misleading picture of model trustworthiness. We demonstrate that a Dynamic, Automatic, and Systematic (DAS) red-teaming framework that continuously stress-tests LLMs can reveal significant weaknesses of current LLMs across four safety-critical domains: robustness, privacy, bias/fairness, and hallucination. A suite of adversarial agents is applied to autonomously mutate test cases, identify/evolve unsafe-triggering strategies, and evaluate responses, uncovering vulnerabilities in real time without human intervention. Applying DAS to 15 proprietary and open-source LLMs revealed a stark contrast between static benchmark performance and vulnerability under adversarial pressure. Despite a median MedQA accuracy exceeding 80\%, 94\% of previously correct answers failed our dynamic robustness tests. We observed similarly high failure rates across other domains: privacy leaks were elicited in 86\% of scenarios, cognitive-bias priming altered clinical recommendations in 81\% of fairness tests, and we identified hallucination rates exceeding 66\% in widely used models. Such profound residual risks are incompatible with routine clinical practice. By converting red-teaming from a static checklist into a dynamic stress-test audit, DAS red-teaming offers the surveillance that hospitals/regulators/technology vendors require as LLMs become embedded in patient chatbots, decision-support dashboards, and broader healthcare workflows. Our framework delivers an evolvable, scalable, and reliable safeguard for the next generation of medical AI.

[Arxiv](https://arxiv.org/abs/2508.00923)