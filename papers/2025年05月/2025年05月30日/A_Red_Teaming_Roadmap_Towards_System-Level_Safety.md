# # 系统安全的红队探索路线图
# 红队方法的安全路线图，朝着系统级别安全的方向

发布时间：2025年05月30日

`LLM应用` `AI安全` `系统安全`

> A Red Teaming Roadmap Towards System-Level Safety

# 摘要

> 大型语言模型（LLM）的安全防护措施，通过实施请求拒绝机制，已成为防范滥用的通用策略。在对抗机器学习与AI安全的交叉领域，安全防护红队测试已成功识别出最先进的拒绝训练LLM中的关键漏洞。然而，我们认为，目前大量关于LLM红队测试的会议提交论文并未在整体上优先关注正确的研究问题。首先，针对明确的产品安全规范进行测试应优先于抽象的社会偏见或伦理原则。其次，红队测试应优先考虑代表不断扩展的风险格局以及真实攻击者可能采取行为的现实威胁模型。最后，我们认为，系统级安全是推进红队研究的必要步骤，因为一旦AI模型被部署到实际应用中，它们既会带来新的威胁，也会提供威胁缓解的新手段（例如恶意用户的检测与封禁）。为了使红队研究能够充分应对快速AI进步所带来的一系列新威胁，以及未来即将出现的威胁，采用这些优先事项将是必要的。

> Large Language Model (LLM) safeguards, which implement request refusals, have become a widely adopted mitigation strategy against misuse. At the intersection of adversarial machine learning and AI safety, safeguard red teaming has effectively identified critical vulnerabilities in state-of-the-art refusal-trained LLMs. However, in our view the many conference submissions on LLM red teaming do not, in aggregate, prioritize the right research problems. First, testing against clear product safety specifications should take a higher priority than abstract social biases or ethical principles. Second, red teaming should prioritize realistic threat models that represent the expanding risk landscape and what real attackers might do. Finally, we contend that system-level safety is a necessary step to move red teaming research forward, as AI models present new threats as well as affordances for threat mitigation (e.g., detection and banning of malicious users) once placed in a deployment context. Adopting these priorities will be necessary in order for red teaming research to adequately address the slate of new threats that rapid AI advances present today and will present in the very near future.

[Arxiv](https://arxiv.org/abs/2506.05376)