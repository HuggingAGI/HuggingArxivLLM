# 健忘智能体利用量子卵石在匿名图中的寻宝

发布时间：2025年09月02日

`Agent` `基础理论`

> Treasure Hunt in Anonymous Graphs with Quantum Pebbles by Oblivious Agents

# 摘要

> 我们研究了如何利用无记忆智能体在匿名图中寻找静态宝藏，并提出了一种借助量子信息的全新方法。匿名图的顶点无标记且无法区分，边则通过端口号进行局部标记。智能体通常依靠神谕放置的静止经典标记石来引导搜索，但这种经典方法存在信息传输受限、遍历复杂度高的问题。若智能体无记忆，经典标记石便无法满足搜索需求。为此，我们首次提出将量子标记石应用于匿名图搜索：量子标记石会周期性发射处于固定量子态的量子比特，每个标记石通过独特的量子态对下一个节点的端口号进行编码；智能体则通过在多个基下执行测量来确定正确路径，并借助量子测量的概率特性区分不同状态。我们证明，该策略能让无记忆智能体用【数学公式】个量子标记石在【数学公式】步内找到宝藏，其中【数学公式】为起点到宝藏的最短路径长度。此外，在最大度为【数学公式】的图中，只需对每个节点进行【数学公式】次测量即可保证高成功概率，其中【数学公式】。

> We investigate the problem of finding a static treasure in anonymous graphs using oblivious agents and introduce a novel approach that leverages quantum information. In anonymous graphs, vertices are unlabelled, indistinguishable, and edges are locally labelled with port numbers. Agents typically rely on stationary classical pebbles placed by an oracle to guide their search. However, this classical approach is constrained by limited information transmission and high traversal complexity. Classical pebbles are not sufficient for search if the agents are oblivious. We propose the first use of quantum pebbles for search in anonymous graphs. Quantum pebbles periodically emit qubits in a fixed quantum state. Each pebble encodes the port number to the next node using a unique quantum state. The agent determines the correct path by performing measurements in multiple bases, exploiting the probabilistic nature of quantum measurement to distinguish states. We show that this strategy enables an oblivious agent to locate the treasure in $D$ steps using $D$ quantum pebbles, where $D$ is the length of the shortest path between the starting point and the treasure. Moreover, only $O((\log D + \log Δ)/(\log 1/δ))$ measurements per node are required to ensure high success probability in a graph with maximum degree $Δ$ where $δ= \cos^2(\fracπ{2Δ})$. We propose the use of quantum information as a guidance mechanism in anonymous graph search. We demonstrate that quantum pebbles can not only emulate the functionality of classical pebbles but can do so with improved efficiency, offering a promising direction for future quantum-enhanced distributed algorithms.

[Arxiv](https://arxiv.org/abs/2509.02909)