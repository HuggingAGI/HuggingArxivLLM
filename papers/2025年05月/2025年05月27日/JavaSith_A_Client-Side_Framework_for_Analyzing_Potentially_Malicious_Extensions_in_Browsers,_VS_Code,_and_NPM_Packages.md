# JavaSith：一款用于分析潜在恶意扩展的客户端框架，支持浏览器、VS Code 和 NPM 包环境。

发布时间：2025年05月27日

`其他` `软件供应链安全` `网络安全`

> JavaSith: A Client-Side Framework for Analyzing Potentially Malicious Extensions in Browsers, VS Code, and NPM Packages

# 摘要

> 现代软件供应链正日益受到隐藏在浏览器扩展、IDE扩展和开源包等可信组件中的恶意代码的威胁。本文介绍了一个名为JavaSith的新型客户端框架，用于分析Web浏览器、VSCode和Node的NPM包中的潜在恶意扩展。JavaSith结合了模拟浏览器/Node.js扩展API的运行时沙箱（配备一个“时间机器”以加速基于时间的触发器）、静态分析和本地大型语言模型（LLM），以评估代码和元数据的风险。我们展示了JavaSith的设计和架构，包括在模拟时间下拦截扩展行为和提取可疑模式的技术。通过真实攻击案例研究（如Chrome扩展程序的供应链攻击和恶意VSCode扩展程序安装加密矿工），我们演示了JavaSith如何捕捉传统检测方法难以察觉的隐蔽恶意行为。我们评估了该框架的有效性，并讨论了其局限性及未来改进方向。JavaSith的客户端方法使终端用户/组织能够在信任地将其集成到环境中之前审查扩展和包。

> Modern software supply chains face an increasing threat from malicious code hidden in trusted components such as browser extensions, IDE extensions, and open-source packages. This paper introduces JavaSith, a novel client-side framework for analyzing potentially malicious extensions in web browsers, Visual Studio Code (VSCode), and Node's NPM packages. JavaSith combines a runtime sandbox that emulates browser/Node.js extension APIs (with a ``time machine'' to accelerate time-based triggers) with static analysis and a local large language model (LLM) to assess risk from code and metadata. We present the design and architecture of JavaSith, including techniques for intercepting extension behavior over simulated time and extracting suspicious patterns. Through case studies on real-world attacks (such as a supply-chain compromise of a Chrome extension and malicious VSCode extensions installing cryptominers), we demonstrate how JavaSith can catch stealthy malicious behaviors that evade traditional detection. We evaluate the framework's effectiveness and discuss its limitations and future enhancements. JavaSith's client-side approach empowers end-users/organizations to vet extensions and packages before trustingly integrating them into their environments.

[Arxiv](https://arxiv.org/abs/2505.21263)