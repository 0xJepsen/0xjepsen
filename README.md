### Hello, I'm 0xJepsen

I’m a computer scientist passionate about high impact technology. My research interests lay at the intersection of mathematics, computer science, and philosophy. I value work ethic, tenacity, and kindness. 

- 📖 I am reading [No Rules Rules](https://www.norulesrules.com/).
- 🏛 I am Currently working on open source rust modules. 
- 🪷 I grew up off-the-grid in a Tibetan Budhist community for the first 13 years of my life. The lineage was the [Nyingma](https://www.rigpawiki.org/index.php?title=Nyingma) school of thought. 

## Education

BS - Mathematics and Philosophy 

MS - Computer Science Advised By [Dr. Craig Partridge](https://scholar.google.com/citations?user=f-E5nFEAAAAJ&hl=en&oi=ao)
  - 🔎 Evaluated the performance of unique generator polynomials for cyclic error detection
  - 📦 Evaluated the performance of tropical algebraic models for TCP and identified key assumptions and produced theoretical improvments

Ph.D. - Computer Science
  - Advised by Dr [Amani Altarawneh](https://scholar.google.com/citations?user=CfjaUOsAAAAJ&hl=en) 
  - Studying the economic activity in distributed ledgers. 

## Research

### [Constant Function Market Makers](https://github.com/0xJepsen/CFMMs/blob/master/Jepsen_Darpa_Fall2022.pdf)
**Abstract**: In Decentralized Finance (DeFi), the CFMM acts as a trusted escrow that automatically makes the market with its contained reserves. Trades are facilitated against the reserves of assets held in a CFMMs. Any actor can add or remove liquidity to the reserves at any moment to participate in making the market. Actors are incentivized to add liquidity to the reserves because they earn swap fees denoted by $\gamma \in (0,1]$. The available actions to interact with a CFMM are determined by its convex trading function $\varphi$. Formally, a CFMM is an $n$-asset pool $\mathbb{R}_n^+$, and a trading function $\varphi$ such that $\varphi: \mathbb{R}_n^+ → \mathbb{R}$. Given any $R$, the value $\varphi(R) = k$ is called the invariant. For example, suppose we have a collection of n assets (e.g., tokens) that can be exchanged for another. The reserves of n assets $R \in \mathbb{R}_n^+$ is called an n-asset liquidity pool where for every $i \in {1, . . . , n}$, the quantity $R_i$ represents the quantity of asset $i$ in the pool. Reserves change when trades are executed.

### 🏦 [Replicating Portfolios: Constructing Permissionless Derivatives](https://arxiv.org/abs/2205.09890)

**Abstract**: The current design space of derivatives in Decentralized Finance (DeFi) relies heavily on oracle systems. Replicating market makers (RMMs) provide a mechanism for converting specific payoff functions to an associated Constant Function Market Makers (CFMMs). We leverage RMMs to replicate the approximate payoff of a Black-Scholes covered call option. RMM-01 is the first implementation of an on-chain, black scholes priced, expiring option mechanism that relies on arbitrage rather than an external oracle for price. We provide frameworks for derivative instruments and structured products achievable on-chain without relying on oracles. We construct long and binary options and briefly discuss perpetual covered call strategies commonly referred to as "theta vaults." Moreover, we introduce a procedure to eliminate liquidation risk in lending markets. The results suggest that CFMMs are essential for structured product design with minimized trust dependencies.

### 🌴 [Modeling TCP congesting with Tropical Algebra](https://github.com/0xJepsen/Max-PlusTCPModel/blob/master/Modeling_TCP_Congestion_with_Tropical_Algebra.pdf)

Max-Plus tropical algebra is the semi-ring structure over real numbers with operations $\oplus$ and $\otimes$ where the $\oplus$ operator performs the max operation such that $x \oplus y = max(x,y)$, and the $\otimes$ operator is the traditional addition operation such that $x \otimes y = x+y$ where $x , y \in \mathbb{R} \cup \ { - \infty \ }$. More concretely think of the addition operator being replaced by the maximum operator and the multiplication operator being replaced by traditional addition. The zero element for $\otimes$ is $\varepsilon \equiv - \infty$. Since the max-plus algebra is a semi ring there does not exist an inverse element for $\oplus$. Let $R_{max} = R \cup \{ - \infty \}$, and let ${R_{max}^{d, d}, \oplus, \otimes\}$ define the set of square matrices in this algebra of dimension $d \times d$. Extending the algebra to matrices we can define linear algebra in terms of $\oplus$ and $\otimes$. If $A, B \in R_{max}^{m \times n}$, then $A \oplus B_{i,j}$ = $a_{i,j} \oplus b_{i,j}$ and $A\otimes B_{ij} = \bigoplus_{1\leq k \leq d} A_{ik} \otimes B_{kj} = max_{1 \leq k \leq d}(a_{ik} \otimes b_{kj})$

### 🚴 [Cyclic Redundancy Checks and Error Detection](https://github.com/0xJepsen/CRC_Research/blob/master/Cyclic_Redundancy_Checks_and_Error_Detection.pdf)

**Abstract**: This study investigates the capabilities of Cyclic Redundancy \\ Checks(CRCs) to detect burst and random errors. Researchers have favored these error detection codes throughout the evolution of computing and have implemented them in communication protocols worldwide. CRCs are integrated into almost every device, in software and hardware. CRCs play a critical role in ensuring that our digital communication systems are efficient and erroneous packets are detected. Because the quantity of data generated and transmitted has increased over the last twenty years, we are more likely to encounter errors. It is important that the tools and methodologies used to ensure the integrity of digital communication systems are evaluated to handle higher frequencies of information. In this study, we explore the need to improve the capabilities of error-detecting codes to handle higher quantities of data by testing the error detection properties of CRC's in a restricted domain. 

## My Favorite Books

- 🧮 [Theory of Computation](https://www.mog.dog/files/SP2019/Sipser_Introduction.to.the.Theory.of.Computation.3E.pdf)
- 🧑🏼‍🍳 [Numerical Recipes](https://e-maxx.ru/bookz/files/numerical_recipes.pdf)
- 🧹 [Clean Code](https://github.com/jnguyen095/clean-code/blob/master/Clean.Code.A.Handbook.of.Agile.Software.Craftsmanship.pdf)
- 🪨 [The Myth of Sisyphus](https://people.brandeis.edu/~teuber/Albert_Camus_The_Myth_of_Sisyphus_Complete_Text_.pdf)
- 🌸 [When Things Fall Apart](https://www.amazon.com/When-Things-Fall-Apart-Difficult/dp/1611803438)

## Articles, Blogs, and lower case r research 

- 🪞 [Sybil detection on DeFi protocols](https://primitive.mirror.xyz/DThGkT55cfzJmEhkPaQqze7GKvPXxrSNwCo2xiddeko)
- 🏙 [Joining Primitive](https://website-git-blog-jepsen-primitivexyz.vercel.app/blog/jepsen)
- 📑 [How to Deploy Smart Contracts on Hedera](https://dev.to/0xjepsen/how-to-deploy-cost-effective-smart-contracts-3a3l)
- ⚖️ [Cryptography in Distributed Ledgers](https://dev.to/0xjepsen/an-introduction-to-cryptography-in-distributed-ledger-technology-268l)

![](https://img.shields.io/github/stars/0xjepsen?style=social)
![](https://img.shields.io/github/last-commit/0xjepsen/0xjepsen)
![](https://visitor-badge.laobi.icu/badge?page_id=0xjepsen)
