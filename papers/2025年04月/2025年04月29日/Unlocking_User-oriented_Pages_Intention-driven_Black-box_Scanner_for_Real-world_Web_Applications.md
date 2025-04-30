# 解锁用户导向页面：意图驱动的黑盒扫描器，应用于实际网络应用

发布时间：2025年04月29日

`LLM应用` `网络安全` `自动化测试`

> Unlocking User-oriented Pages: Intention-driven Black-box Scanner for Real-world Web Applications

# 摘要

> # 摘要
黑盒扫描器在Web应用漏洞检测中扮演了重要角色。目前，提升测试覆盖率（即访问更多网页）是黑盒扫描的核心关注点。然而，由于许多Web应用面向用户，部分深度页面需要通过复杂交互才能访问，这使得现有扫描器难以触及。为解决这一问题，我们发现Web页面蕴含丰富的语义信息，可用于推断用户意图。基于此，我们开发了Hoyen——一款利用大型语言模型预测用户意图并指导扩展扫描范围的黑盒扫描器。在12个开源Web应用上的测试表明，Hoyen的扫描覆盖率平均是其他工具的2倍，且准确率高。它成功识别了90%以上针对应用核心功能的漏洞，包括知名应用中的独特漏洞。我们的数据和代码可在https://hoyen.tjunsl.com/获取。


> Black-box scanners have played a significant role in detecting vulnerabilities for web applications. A key focus in current black-box scanning is increasing test coverage (i.e., accessing more web pages). However, since many web applications are user-oriented, some deep pages can only be accessed through complex user interactions, which are difficult to reach by existing black-box scanners. To fill this gap, a key insight is that web pages contain a wealth of semantic information that can aid in understanding potential user intention. Based on this insight, we propose Hoyen, a black-box scanner that uses the Large Language Model to predict user intention and provide guidance for expanding the scanning scope. Hoyen has been rigorously evaluated on 12 popular open-source web applications and compared with 6 representative tools. The results demonstrate that Hoyen performs a comprehensive exploration of web applications, expanding the attack surface while achieving about 2x than the coverage of other scanners on average, with high request accuracy. Furthermore, Hoyen detected over 90% of its requests towards the core functionality of the application, detecting more vulnerabilities than other scanners, including unique vulnerabilities in well-known web applications. Our data/code is available at https://hoyen.tjunsl.com/

[Arxiv](https://arxiv.org/abs/2504.20801)