# 抗拒绝集合装填的ETH紧固定参数可解算法及其在肾脏交换中的应用

发布时间：2025年09月15日

`Agent` `医疗健康` `基础理论`

> An ETH-Tight FPT Algorithm for Rejection-Proof Set Packing with Applications to Kidney Exchange

# 摘要

> 我们研究了肾脏交换问题最新提出的多智能体变体的参数化复杂度。给定有向图G及整数d、k，标准问题旨在判断G中是否存在顶点不相交的圈装填——每个圈长度≤d，且总共覆盖至少k个顶点。在我们研究的多智能体场景中，顶点集被分配给多个智能体；若某个圈装填能被修改为覆盖更多自身顶点的替代装填，智能体便会拒绝接受该装填为解决方案。若某个圈装填未被任何智能体拒绝，则称之为“防拒绝装填”，而问题即询问是否存在覆盖至少k个顶点的此类装填。
  我们基于问题的集合装填模型，利用向日葵引理为这一Σ₂ᴾ完全问题构造了核：当d为常数时，该核的规模是k的多项式。据此，我们设计了复杂度为2^O(k log k) + n^O(1)的算法，并证明该固定参数可解（FPT）算法在指数时间假设（ETH）下是渐近最优的。进一步，我们对问题进行了推广：在输入中引入正整数c，用于刻画智能体为拒绝某个圈装填可对其进行的修改程度。当c为常数时，推广问题的复杂度从Σ₂ᴾ完全降至NP完全。针对c=1的场景，我们提出了单指数算法，并证明在ETH下，该场景严格比c=2时更容易求解。反之，我们证明当c≥2时，问题难度本质上与c无界的原始问题相当。这一发现揭示了该问题经典复杂度与参数化复杂度间的有趣差异，也清晰阐释了其困难性的根源。

> We study the parameterized complexity of a recently introduced multi-agent variant of the Kidney Exchange problem. Given a directed graph $G$ and integers $d$ and $k$, the standard problem asks whether $G$ contains a packing of vertex-disjoint cycles, each of length $\leq d$, covering at least $k$ vertices in total. In the multi-agent setting we consider, the vertex set is partitioned over several agents who reject a cycle packing as solution if it can be modified into an alternative packing that covers more of their own vertices. A cycle packing is called rejection-proof if no agent rejects it and the problem asks whether such a packing exists that covers at least $k$ vertices.
  We exploit the sunflower lemma on a set packing formulation of the problem to give a kernel for this $Σ_2^P$-complete problem that is polynomial in $k$ for all constant values of $d$. We also provide a $2^{\mathcal{O}(k \log k)} + n^{\mathcal{O}(1)}$ algorithm based on it and show that this FPT algorithm is asymptotically optimal under the ETH. Further, we generalize the problem by including an additional positive integer $c$ in the input that naturally captures how much agents can modify a given cycle packing to reject it. For every constant $c$, the resulting problem simplifies from being $Σ_2^P$-complete to NP-complete. With a single-exponential algorithm for the setting where $c = 1$, we show this to be strictly easier under the ETH than when $c = 2$. In turn, we show that any $c \geq 2$ yields a problem that is essentially as hard as the original problem with $c$ unbounded. This displays an interesting discrepancy between the classical and parameterized complexity of the problem and gives a good view of what makes it hard.

[Arxiv](https://arxiv.org/abs/2509.11965)