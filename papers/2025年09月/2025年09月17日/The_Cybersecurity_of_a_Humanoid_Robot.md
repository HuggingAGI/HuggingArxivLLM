# # 人形机器人的网络安全

发布时间：2025年09月17日

`Agent` `工业与制造`

> The Cybersecurity of a Humanoid Robot

# 摘要

> 类人机器人技术的飞速发展带来了前所未有的网络安全挑战，而现有理论框架难以充分应对。本报告对一款量产类人机器人平台展开全面安全评估，填补了抽象安全模型与实际运行漏洞之间的空白。通过系统的静态分析、运行时观察及密码学检测，我们揭示出一幅复杂的安全图景：既有精密的防御机制，也存在严重的安全漏洞。研究发现了一套双层专有加密系统（命名为FMX'），其设计虽具创新性，但存在根本性实现缺陷，例如使用静态加密密钥，导致可通过离线方式解密配置信息。更值得关注的是，我们记录到持续的遥测连接在未经用户明确同意且缺乏通知机制的情况下，向外部服务器传输详细的机器人状态数据——涵盖音频、视觉、空间定位及执行器信息。我们在Unitree G1机器人上部署了网络安全AI代理，成功绘制并准备利用其制造商的云基础设施，直观展示了被入侵的类人机器人如何从隐蔽数据收集升级为主动反击行动。我们认为，保障类人机器人安全需要转向网络安全AI（CAI）框架，以应对物理-网络融合带来的独特挑战。这项研究为制定健全的安全标准提供了实证依据，尤其是在类人机器人正从研究探索阶段向关键领域的实际运行系统过渡之际。

> The rapid advancement of humanoid robotics presents unprecedented cybersecurity challenges that existing theoretical frameworks fail to adequately address. This report presents a comprehensive security assessment of a production humanoid robot platform, bridging the gap between abstract security models and operational vulnerabilities. Through systematic static analysis, runtime observation, and cryptographic examination, we uncovered a complex security landscape characterized by both sophisticated defensive mechanisms and critical vulnerabilities. Our findings reveal a dual-layer proprietary encryption system (designated FMX') that, while innovative in design, suffers from fundamental implementation flaws including the use of static cryptographic keys that enable offline configuration decryption. More significantly, we documented persistent telemetry connections transmitting detailed robot state information--including audio, visual, spatial, and actuator data--to external servers without explicit user consent or notification mechanisms. We operationalized a Cybersecurity AI agent on the Unitree G1 to map and prepare exploitation of its manufacturer's cloud infrastructure, illustrating how a compromised humanoid can escalate from covert data collection to active counter-offensive operations. We argue that securing humanoid robots requires a paradigm shift toward Cybersecurity AI (CAI) frameworks that can adapt to the unique challenges of physical-cyber convergence. This work contributes empirical evidence for developing robust security standards as humanoid robots transition from research curiosities to operational systems in critical domains.

[Arxiv](https://arxiv.org/abs/2509.14096)