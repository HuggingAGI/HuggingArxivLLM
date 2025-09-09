# 证明携带数字（PCN）：一种基于声明验证从LLMs获取可信数值答案的协议

发布时间：2025年09月08日

`LLM应用` `金融科技`

> Proof-Carrying Numbers (PCN): A Protocol for Trustworthy Numeric Answers from LLMs via Claim Verification

# 摘要

> 大型语言模型（LLMs）作为随机系统，可能生成与实际数据不符的数字，这种问题被称为“数字幻觉”。现有的保障机制——如检索增强生成、引用标注和不确定性估计——虽提升了透明度，却无法确保数值的准确性：虚构或误引的数值仍可能被当作正确结果呈现。为此，我们提出**Proof-Carrying Numbers (PCN)**（带证明数字），一种通过机械验证确保数字准确性的表示层协议。在PCN机制下，数字片段会作为“声明绑定令牌”生成，这些令牌与结构化声明相关联；验证器会依据声明的策略（如精确匹配、四舍五入、别名或带限定条件的容差范围）对每个令牌进行检查。关键在于，PCN将验证过程置于“渲染器”而非模型中：只有通过声明检查的数字才会被标记为“已验证”，其余数字则默认“未验证”。这种分离机制可防止伪造，并确保系统呈现故障关闭状态。我们对PCN进行了形式化定义，并证明了其可靠性、诚实令牌下的完整性、故障关闭特性以及策略细化时的单调性。PCN轻量且不依赖特定模型，能无缝集成到现有应用中，还可通过加密承诺进一步扩展功能。通过将验证设为显示前的强制步骤，PCN为数字敏感场景构建了一个简明契约：“信任需以证明为凭”，而验证标记的缺失则表明存在不确定性。

> Large Language Models (LLMs) as stochastic systems may generate numbers that deviate from available data, a failure known as \emph{numeric hallucination}. Existing safeguards -- retrieval-augmented generation, citations, and uncertainty estimation -- improve transparency but cannot guarantee fidelity: fabricated or misquoted values may still be displayed as if correct. We propose \textbf{Proof-Carrying Numbers (PCN)}, a presentation-layer protocol that enforces numeric fidelity through mechanical verification. Under PCN, numeric spans are emitted as \emph{claim-bound tokens} tied to structured claims, and a verifier checks each token under a declared policy (e.g., exact equality, rounding, aliases, or tolerance with qualifiers). Crucially, PCN places verification in the \emph{renderer}, not the model: only claim-checked numbers are marked as verified, and all others default to unverified. This separation prevents spoofing and guarantees fail-closed behavior. We formalize PCN and prove soundness, completeness under honest tokens, fail-closed behavior, and monotonicity under policy refinement. PCN is lightweight and model-agnostic, integrates seamlessly into existing applications, and can be extended with cryptographic commitments. By enforcing verification as a mandatory step before display, PCN establishes a simple contract for numerically sensitive settings: \emph{trust is earned only by proof}, while the absence of a mark communicates uncertainty.

[Arxiv](https://arxiv.org/abs/2509.06902)