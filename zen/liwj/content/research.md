---
title: "Research"

---


##  Mathematical logic, theory of computation

#### Infinite games  

The *determinacy* of Gale-Stewart games, *i.e.*, one of the two players has a winning strategy, has been intensively studied in descriptive set theory. One of the celebrated results due to  D.A. Martin (1975) states that "All the Gale-Stewart games with Borel winning sets are determined".  On the other hand, the winning sets can also be defined by some kinds of automata. 
Büchi and Landweber (1969), and  Walukiewicz (2001) constructed the winning strategies of infinite games in which winning sets are the $\omega$-languages accepted by some deterministic finite/pushdown automata. Finkel (2013) further studied the infinite games in which the winning sets are $\omega$-languages accepted by nondeterministic pushdown automata and proves such games are not determined even within the set theory $\mathsf{ZFC}$.

We downscale Finkel's results to lower level $\omega$-languages. We investigate the determinacy strength of infinite games whose winning sets are recognized by nondeterministic pushdown automata with various acceptance conditions, *e.g.*, safety, reachability and co-Büchi conditions. In terms of the foundational program "Reverse Mathematics", the determinacy strength of such games is measured by the complexity of a winning strategy required by the determinacy. Noticing that infinite games recognized by nondeterministic pushdown automata have some resemblance to those by deterministic 2-stack visibly pushdown automata (2DVPA) with the same acceptance conditions, we start with investigating the determinacy of infinite games recognized by 2DVPA and the nondeterministic ones and then establish the relation with the infinite games recognized with nondeterministic pushdown automata with the same acceptance conditions. 

Recently, I also extended the study along this line to variants of probabilistic automata. Probabilistic automata is a natural extension of non-deterministic automata by replacing the non-determinism with a probability. In such a case, the accepting of an infinite word is evaluated not only by the usual acceptance conditions but also its probability, which is characterized by the so-called probability semantics.

- Wenjuan Li, and Kazuyuki Tanaka, Determinacy of probabilistic ω-languages with strict threshold semantics, accepted by RIMS Kokyuroku(2024).
- Wenjuan Li and Kazuyuki Tanaka, Second-order logic and related systems: a game-semantical perspective. Mathematical Logic and its Applications (SAML2022), RIMS Kokyuroku 2233 (2022), 1-19.
- Wenjuan Li, Kazuyuki Tanaka. The determinacy strength of pushdown $\omega$-languages. RAIRO-Theoretical Informatics and Applications,  51(2017), pp.29-50.
- Wenjuan Li, Shohei Okisaka, Kazuyuki Tanaka. Infinite games recognized by 2-stack visibly pushdown automata. RIMS Kokyuroku (京都大学数理解析研究所講究録), 1950(2015), pp.121-137.


#### Modal $\mu$-calculus 

Modal $\mu$-calculus, an extension of modal logic by adding greatest and least fixpoint operators ($\mu$/$\nu$), is closely related with tree automata and parity games, which has wide applications in theoretical computer science due to its monotone iteration  property. One fundamental issue is the *complexity measure* of formulas of modal $\mu$-calculus, *e.g.*, alternation depths and number of variables. That is, whether more alternation of $\mu/ \nu$ and variables are necessary to express some complex properties. The alternation hierarchy ($\Sigma^{\mu}_n$/$\Pi^{\mu}_n$, $n\in \mathbb{N}$) and variable hierarchy are proved to be strict respectively (Bradfield, 1998; Berwanger, Grädel, Lenzi, 2007), over the class of all transition systems.

We study the one-variable fragment of modal $\mu$-calculus and weak modal $\mu$-calculus, which is essential the same as $\Sigma^{\mu}_2\cap \Pi^{\mu}_2$ in the alternation hierarchy.
Our proof of strictness relies on weak parity games.

I am also intereted in the interaction of games and fixed point property, especially from the viewpoint of determinacy.

- Leonard Pacheco, Wenjuan Li, Kazuyuki Tanaka. On one-variable fragments of modal $\mu$-calculus. Computability Theory and Foundations of Mathematics, World-Scientific, pp. 17-45, 2022.
- Wenjuan Li, Yasuhiko Omata, Kazuyuki Tanaka. Alternation hierarchies and fragments of modal $\mu$-calculus. RIMS Kokyuroku (京都大学数理解析研究所講究録), 2083(2018), pp.98-110.



#### Query complexity of game trees 

The evaluation of game trees plays a crucial role in artificial intelligence, especially Boolean AND-OR trees, which provides a game-theoretic technique to design and analyze randomized algorithms (Saks and Wigderson, 1986; Yao, 1977). 

Liu and Tanaka (2007) characterize the eigen-distributions that achieve the distributional complexity, and prove the uniqueness of eigen-distribution for uniform binary trees. We extend the results to balanced and even general multi-braching trees via studying the weighted game trees.

- Kazuyuki Tanaka, NingNing Peng, Weiguang Peng, and Wenjuan Li, The equilibria of independent distributions on unbalanced game trees, Computational and Applied Mathematics, 43(2024), 5, 267.
- Shohei Okisaka, Weiguang Peng, Wenjuan Li, Kazuyuki Tanaka. The eigen-distribution of weighted game trees. Lecture Notes in Computer Science,  10627(2017), pp.286-297.
- Weiguang Peng, Shohei Okisaka, Wenjuan Li, Kazuyuki Tanaka. The uniqueness of eigen-distribution under non-directional algorithms. IAENG International Journal of Computer Science, 43(2016), pp.318-325.

##  Decision analysis

I have not given up my interest in modeling real-life problems and making decision analysis. I am learning more on the data-driven method to solve such problems. 

- Task dispatching in reconfigurable *seru* production systems to minimize total earliness and tardness, European Journal of Industrial Engineering, 16(3), 241-267, 2022. （with  J. Lian, C. Liu,  J. Su, H. Xue）
- A multi-skilled worker assignment problem in seru production systems considering the worker heterogeneity. Computers & Industrial Engineering, 2018, 118: 366-382. (with J. Lian, C. Liu, Y. Yin)
- Effects of key enabling technologies for *seru* production on sustainable performance. OMEGA -The International Journal of Management Science, 66(2017), pp.290-307. (with X. Zhang, C. Liu, S. Evans, Y. Yin)
- Formation of independent manufacturing cells with the consideration of multiple identical machines.  International Journal of Production Research, 52(2014), pp.1363-1400. (with J, C. Liu, W. Li, S. Evans, Y. Yin)
- Reconfiguration of assembly systems: from conveyor assembly line to *seru*s.  Journal of Manufacturing Systems , 31(2012), pp.312-325. (with C. Liu, J. Lian, Y. Yin)
- Decision making on production mode selection for manufacturing enterprises under two types of market structure (In Chinese).  Systems Engineering - Theory \& Practice , 33(2012), pp.49-59. (C. Liu, Y. Bai, J. Lian, Y. Yin)