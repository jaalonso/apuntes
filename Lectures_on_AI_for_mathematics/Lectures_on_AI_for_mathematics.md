# Lectures on AI for mathematics

**Author:** Xiaoyang Chen & Xiang Jiang

**Institute:** School of Mathematical Sciences, Tongji University

**Date:** Apr. 8, 2026

**Version:** 1.0

## Chapter 1: Overview

For a long time, mathematics has been regarded as the pinnacle of pure human intellect. Mathematicians rely on insight, intuition, and rigorous logic to prove conjectures and create theories in an abstract world. Currently, artificial intelligence, especially data-driven machine learning technology, has made breakthrough progress. A natural question arises: How will the combination of artificial intelligence and mathematics reshape our way of exploring the mathematical world?

This book aims to systematically organize and answer this question. We will take mathematical research as the main thread to explain the significant value of artificial intelligence’s involvement. This is not a simple additive combination of “how A helps B” in a tool-like manner, but rather an exploration of a deeper structural question: When the complexity and scale of mathematical problems reach a certain level, what inherent limitations do the traditional paradigms of discovery and proof face? What new conceptual tools and possible pathways do artificial intelligence methods provide for addressing these limitations? By constructing a clear cognitive map of the “AI for Math” field, we hope readers will understand that this is not merely a technological application, but a methodological transformation concerning “how mathematics is researched.”

### 1.1 Core elements of mathematical research

To understand how artificial intelligence can play a role, we first need to understand the nature of mathematical research work. Although the specific work of each mathematician varies greatly, its core activities can roughly be summarized into three interrelated yet distinct stages: discovery, proof, and refutation. These three form a cyclical, mutually reinforcing exploratory loop.

    1. Discovering mathematical patterns: This is the source of mathematical creativity. Starting from concrete examples, observed patterns, or phenomena in the physical world, mathematicians propose new concepts, conjectures, or theories through intuition, analogy, and insight. For example, conjecturing a general formula after observing a pattern in a sequence of numbers, or pro posing a proposition about invariants while studying geometric objects. The essence of this process is searching and filtering    within a vast, potentially infinite space of possibilities, aiming to locate structures that are “mathematically meaningful” or “likely true.” Human intuition plays a central heuristic search role here, allowing mathematicians to quickly focus on promising “regions,” but it may also miss certain non-intuitive yet important patterns due to cognitive biases or the complexity of the problem.

2. Proving theorems: Once a conjecture is proposed, the core value of mathematics—rigor—demands that we establish its truth. Proof is the process of transforming intuition and conjecture into irrefutable logical truth. It ensures the necessity of the conclusion given the axioms and definitions. The activity of proving itself can also be seen as a complex search: within the logical space constituted by axioms, theorems, and rules of inference, finding a path from known facts to the proposition to be proven. As mathematical theories become highly abstract and branches become more specialized, proofs become increasingly long, complex, and reliant on more lemmas and cross-disciplinary knowledge.

3. Constructing counterexamples: Constructing counterexamples is often extremely challenging, as it requires us to precisely find a specific instance within a vast set of candidate objects. Human constructions often rely on ingenious induction or recursion techniques, but when constraints are complex or the search space is huge, constructing counterexamples typically becomes extremely difficult.

### 1.2 The role of AI in mathematical research

#### 1.2.1. From automated theorem proving to deep learning

##### 1.2.1.1 The development history of automated theorem proving

The history of automated theorem proving can be traced back to Leibniz’s 17th-century conception of a “calculus of reasoning,” but significant breakthroughs were only realized in the 20th century with the development of computer technology. In the 1950s, AI pioneers like Allen Newell and others first attempted to use computer programs to prove mathematical theorems. In 1976, mathematicians, with the aid of a computer, completed the proof of the Four Color Theorem, a milestone event that garnered widespread attention in the mathematical community. The exhaustive case analysis required for the proof of the Four Color Theorem far exceeded the capacity of manual human processing. This successful case fully demonstrated the unique value of computers in solving extremely large-scale mathematical problems. The development of automated theorem proving has gone through several important stages: from early exhaustive proof methods, to Wu Wenjun’s algebraic method, and later to automated reasoning and interactive proof systems. With the exponential increase in computer performance, the capabilities of automated theorem proving have also continuously strengthened. Formal verification methods represented by systems like Coq, Isabelle, and Lean can ensure absolute rigor in proofs, avoiding potential oversights present in traditional mathematical proofs.

The value of automated theorem proving is reflected not only in improving the efficiency of mathematical research but also, more profoundly, in changing the way of thinking in mathematical research. It breaks through the limitations of human cognition, enabling the handling of extremely complex calculations and reasoning processes; simultaneously, it promotes the development of mathematical rigor, making mathematical proofs more reliable and verifiable. In the future, with the advancement of artificial intelligence technology, automated theorem proving will undoubtedly play an even more important role in mathematical research.

##### 1.2.1.2 The deep learning revolution

Deep learning, as an important branch of machine learning, has a development history traceable to the proposal of the neural network concept in the 1940s, but its explosive growth truly began after 2010. The core of this technological revolution lies in constructing neural network architectures with multiple layers of nonlinear transformations, endowing computers with unprecedented capabilities for feature learning and pattern recognition. The breakthrough performance of AlexNet in the 2012 ImageNet competition marked the official arrival of the deep learning era. Subsequently, with increased computing power, optimized algorithms, and the accumulation of big data, deep learning achieved a series of remarkable accomplishments in fields such as computer vision and natural language processing.

In the field of mathematical research, the value of deep learning is mainly manifested in three key dimensions. First, in discovering new mathematical patterns, deep learning has shown astonishing potential. In a 2021 study published in _Nature_ by the DeepMind team, by analyzing invariants in knot theory, they discovered mathematical connections that human mathematicians had long failed to notice.

In the verification of mathematical proofs, the combination of deep learning and formal proof systems has opened up new possibilities. By integrating neural networks with formal verification, AI systems can assist in completing complex proof processes. This “neural-symbolic” system retains strict logical rigor while possessing powerful mathematical reasoning capabilities.

In constructing counterexamples, deep learning also performs exceptionally well. Through reinforcement learning algorithms, AI systems can efficiently search for potential counterexample structures within vast combinatorial spaces. In the field of graph theory, this method has successfully constructed counterexamples for several famous conjectures.

The unique value of deep learning lies in its ability to break through the inherent limitations of human thinking. It can handle high-dimensional data spaces that are difficult for humans to manage, discover nonintuitive mathematical patterns, and provide new ideas in proof and counterexample construction. With the development of new technologies like neural-symbolic systems, deep learning is pushing mathematical research into a new era of human-machine collaboration. This technology not only improves research efficiency but, more importantly, expands human understanding of the essence of mathematics, injecting new vitality into this oldest discipline.

#### 1.2.2. How does AI assist mathematical research?

Mathematical research, as a systematic cognitive activity, mainly consists of three core stages: discovering new mathematical patterns, verifying the correctness of these patterns, and constructing counterexamples. In this subsection, we briefly summarize the capabilities currently demonstrated by AI in these three key areas: 2.1 AI Discovers Mathematical Patterns

In 2021, the DeepMind team published groundbreaking results in the journal _Nature_ . Their developed AI system could help mathematicians discover new connections between knot invariants. This research proved that AI can guide mathematicians’ intuition to discover mathematical connections that humans might overlook.

A knot is a closed curve in three-dimensional space, and mathematicians typically use invariants such as the Jones polynomial and hyperbolic volume to describe its properties. DeepMind encoded the algebraic and geometric invariants of knots as high-dimensional vectors and used a deep neural network (DNN) to learn the latent relationships between them, i.e., learning how to predict one invariant (e.g., hyperbolic volume) from another (e.g., the Jones polynomial). Based on the AI’s predictions, mathematicians further constructed rigorous mathematical proofs, ultimately discovering new connections between invariants in knot theory.

In another paper published in _Nature_ , DeepMind used deep reinforcement learning (DRL) to discover more efficient matrix multiplication algorithms, surpassing the best records held by human mathematicians in this field. This achievement demonstrates how AI can discover mathematical optimization strategies unthought of by humans through autonomous exploration. Matrix multiplication is a fundamental operation in computer science and mathematics, and traditional algorithms (like Strassen’s algorithm) have been optimized for decades. For multiplying two _n × n_ matrices, the standard method requires _O_ ( _n_[3] ) scalar multiplications. DeepMind’s goal was to find combinations requiring fewer multiplications, thereby reducing computational complexity. DeepMind employed AlphaTensor (an improved model based on AlphaZero), with core components including:

- State Representation

   - Encoding the matrix multiplication problem as a three-dimensional tensor, where each element represents a possible multiplication combination.

   - For example, 2 _×_ 2 matrix multiplication can be represented as a 4 _×_ 4 _×_ 4 tensor, where each dimension corresponds to elements of the input/output matrices.

- Action Space:

   - Each action corresponds to a basic multiplication operation (e.g., scalar multiply-add).

   - The AI’s goal is to decompose the tensor through a series of actions to find the minimal number of multiplication steps.

- Reward Function:

   - Primary optimization objective: Reduce the number of multiplications (i.e., the rank of the tensor decomposition).

- Additional reward: Discover structured patterns (e.g., symmetry) to facilitate generalization to larger matrices.

By combining Monte Carlo Tree Search (MCTS) with deep learning, DeepMind ultimately discovered more efficient matrix multiplication algorithms.

##### 1.2.2.1 AI automatically proves theorems

Modern artificial intelligence systems have made significant progress in the field of mathematical proof, with their technical implementation primarily manifested in two important directions: solving Olympiad-level geometry problems and formal mathematical proof. These breakthrough developments demonstrate the powerful capabilities of AI in mathematical reasoning.

In geometric proof, DeepMind’s AlphaGeometry system represents the current state-of-the-art technology. The system adopts a neuro-symbolic hybrid architecture, combining the logical reasoning capabilities of a language model and a symbolic engine. Specifically, AlphaGeometry first analyzes the geometric diagram to generate potential auxiliary construction points (such as midpoints, foots of perpendiculars, etc.). Then, the symbolic reasoning engine incorporates these construction points into a deduction database, applying geometric axioms and theorems for rigorous logical derivation. The system was trained using over 100 million synthetic geometry problems generated by a random theorem generation algorithm, ensuring the diversity and complexity of the training data. Notably, in 2023 testing, AlphaGeometry solved 25 out of 30 IMO geometry problems.

In the field of formal verification, interactive theorem provers like Lean play the core role of the verification kernel. Such systems, based on dependent type theory, can perform ultimate machine checking of mathematical reasoning—once a user or external tool provides complete proof steps, the Lean kernel verifies their logical correctness in an indisputable manner.

To improve the efficiency of this verification process, AI technology has been introduced in recent years as a proof assistant to aid humans or automate the construction of proofs. The collaboration model is as follows:

- Formal Encoding and Semantic Understanding: First, informal mathematical propositions are transformed into strict, machine-readable formal statements (e.g., Lean code). AI (such as pre-trained large language models) understands this semantics to provide intelligent suggestions for the next proof strategies.

- Intelligent Search and Strategy Optimization: Faced with complex proof spaces, AI is used for heuristic search to predict which proof paths are more likely to succeed, thereby avoiding inefficient exhaustive attempts.

- Automated Filling and Final Verification: AI tools are responsible for filling in specific proof steps. Once these steps are fully submitted to the Lean kernel, the kernel performs strict formal verification, ensuring the entire proof process is flawless.

In this model, AI is responsible for “exploration” and “conjecture,” while Lean is responsible for “verification” and “confirmation.” The combination of the two retains the absolute reliability of formal verification while significantly improving the efficiency of constructing proofs.

The core technical breakthroughs of these AI systems lie in: 1) combining the intuitive capabilities of neural networks with the strict reasoning of symbolic systems; 2) constructing large-scale mathematical problem datasets to train and validate system performance. Current research focus is expanding towards more complex mathematical fields, indicating that AI will become an indispensable intelligent assistant in mathematical research.

- 2.3 AI Constructs Counterexamples

In recent years, reinforcement learning algorithms have made breakthrough progress in the field of graph theory, particularly demonstrating unique advantages in constructing counterexamples to combinatorial mathematical conjectures. This method, through a carefully designed algorithmic framework, can efficiently search for potential counterexample structures within enormous combinatorial possibility spaces. Its core technologies mainly include:

- Problem Modeling and State Representation: First, the graph theory problem is transformed into a form suitable for machine learning. For graph theory conjectures, the state space is typically represented as the adjacency matrix or feature vector of a graph. For example, when constructing a counterexample, the system initializes a graph with _n_ vertices, where each possible edge is treated as an independent decision variable.

- Reinforcement Learning Framework Design: A reinforcement learning algorithm is employed, where:

   - Action Space: Includes graph modification operations such as adding/deleting edges, changing vertex attributes.

   - Reward Function: Carefully designed as a multi-objective optimization form, containing:

   - Primary reward: The degree of violation of the target conjecture (e.g., the magnitude of violating a certain inequality).

   - Auxiliary reward: Maintaining other properties of the graph (e.g., connectivity, regularity). Penalty term: Controlling the complexity of the graph (e.g., number of edges, vertices).

Through reinforcement learning, AI has successfully constructed counterexamples for several famous conjectures, demonstrating AI’s unique advantages in exploring mathematical problems.

#### 1.2.3. The Mathematical revolution in the era of large models

Mathematics, this ancient discipline exploring the truths of the universe, is undergoing a profound transformation brought about by artificial intelligence large models. From ChatGPT to AlphaGeometry, these AI systems are not only changing the way mathematical research is conducted but are also redefining the very nature of mathematical discovery. The core of this transformation lies in the fact that artificial intelligence is breaking through the limitations of human cognition, integrating mathematical knowledge, discovering hidden patterns, and creatively solving open problems in unprecedented ways. This shift not only improves the efficiency of mathematical research but, more importantly, expands the boundaries of mathematical exploration, injecting new vitality into this most rigorous science.

In terms of knowledge integration, artificial intelligence large models are becoming “super assistants” that break down disciplinary barriers. A major challenge in traditional mathematical research is the high degree of specialization within the field. As mathematics develops, various subfields become increasingly profound. An expert in one area may know little about progress in adjacent fields, and this fragmentation of knowledge often hinders major breakthroughs. The famous mathematician Hilbert once noted: “Mathematics is an organic whole, and its vitality stems precisely from unexpected connections between its various parts.” However, in practice, discovering these connections often requires researchers to possess rare breadth of knowledge and extraordinary insight.

Large language models, with their vast knowledge reserves and powerful associative capabilities, are changing this landscape. Large models represented by GPT can instantly draw upon knowledge from tens of thousands of mathematical papers, build cross-domain knowledge graphs, and discover deep connections between different branches. For example, when a researcher studies a difficult problem in algebraic geometry, the AI might suggest: “This structure bears a striking resemblance to homology theory in topology”; or when studying a number theory problem, point out: “This conjecture corresponds to the phase estimation algorithm in quantum computing.” This cross-disciplinary associative ability, which in the past required mathematicians decades of extensive reading and deep thought to acquire, can now be achieved in a short time with AI assistance.

DeepMind’s FunSearch system vividly demonstrates the power of such knowledge integration. By cleverly combining the creative thinking of a large language model with the precise verification of evaluation code, the system discovered new cap set constructions in combinatorics, solving the open cap set problem that had remained unsolved for years. The key to this breakthrough lies in the AI’s ability to freely establish connections between seemingly unrelated fields like discrete mathematics, algorithm design, and information theory, discovering associative patterns that human researchers might overlook. Here, AI plays the role not of a calculator, but more like a collaborator with an interdisciplinary perspective, capable of examining problems from completely different angles. The value of this knowledge integration is reflected not only in solving specific problems but, more importantly, in its potential to change the paradigm of mathematical research. First, AI assistance can significantly shorten mathematicians’ “learning curves,” enabling researchers to quickly grasp the fundamentals of related fields; second, it can reveal “hidden bridges” between different mathematical branches, providing clues for new research directions; finally, this cross-domain knowledge fusion often catalyzes entirely new mathematical tools and methods, driving innovative development of the discipline.

#### 1.2.4. Can AI create new mathematics?

Creative thinking is the most dazzling jewel in the crown of human intelligence. From Euclid’s axiomatic system to Gauss’s differential geometry, from Riemann’s complex functions to Grothendieck’s scheme theory, every major breakthrough in the history of mathematics shines with the brilliance of creative thinking. What are the key elements of this thinking? And why is current artificial intelligence finding it so difficult to match? Genuine mathematical creative thinking encompasses at least three interrelated levels:

1. Conceptual abstraction ability is the cornerstone of mathematical creation. Excellent mathematicians can extract essential features from concrete problems to form new mathematical concepts. For instance, when Euler saw the Königsberg bridge problem, he did not dwell on the specific bridges and rivers but abstracted the basic concepts of topology. This leap from the concrete to the abstract requires profound intuitive insight.

2. Analogical transfer ability allows mathematical ideas to flow between different fields. In the 19th century, Riemann transferred ideas from Gauss’s theory of surfaces to the study of complex functions, pioneering Riemann surface theory. This cross-domain associative ability relies on a deep understanding of the essence of mathematics, not a simple correspondence of surface features.

3. Constructing entirely new mathematical theories is the highest level of mathematical creation. Grothendieck’s scheme theory in algebraic geometry not only solved specific problems but also built an entirely new theoretical framework. This systematic creation requires a combination of a macroscopic mathematical vision and rigorous logical thinking.

The essence of mathematical creative thinking lies in perfectly combining intuitive leaps with logical rigor. Current AI cannot yet replicate the “flash of inspiration” creative process of human mathematicians. Studying mathematical creative thinking is not only relevant to the development of mathematics itself but also an important avenue for advancing artificial intelligence to higher levels.

In summary, from Wu Wenjun’s automated theorem proving to today’s AlphaGeometry, the integration of AI and mathematics is creating new research paradigms. Although AI currently cannot fully replace the creativity and insight of mathematicians, it has become an indispensable research partner. In the future, with technological progress, we may witness AI proposing entirely new mathematical theories, opening a new era in mathematical research. In this new era of human-machine collaboration, the development of mathematics will no longer be limited by individual intelligence but will be jointly propelled by humans and AI. This transformation will not only change the way mathematical research is conducted but may also help us uncover deeper mathematical mysteries of the universe.

### 1.3 Core idea: Mathematical problems as the main thread

Throughout this book, we will consistently adhere to a core narrative principle: starting from the mathematical problem itself, we examine how AI technology serves as a new methodology to solve these problems. This means the logical chain of our thinking is:

**Mathematical Problem** _→_ **Suitable AI Technology** _→_ **Specific Implementation Process**

For example, when facing the deep mathematical problem of “understanding the relationship between geometric invariants and algebraic invariants of knots”, the challenge lies in learning the connections between invariants from unstructured data. This guides us to use neural networks for learning and to distill mathematical insights.

This problem-oriented perspective helps us avoid falling into blind worship of AI technology or the mere piling up of tools. Instead, we consistently focus on: what new, essential help does this technology bring to our understanding of a particular mathematical structure?

### 1.4 Controversies and reflections: New issues in mathematical research in the AI era

In the discussions of the preceding three parts, we systematically reviewed the core elements of mathematical research, the multiple roles AI plays in mathematical research, and the core idea of taking mathematical problems as the main thread. So far, we have seen the enormous potential brought by the deep integration of AI and mathematics—from assisting in conjecture generation to accelerating theorem proving, from discovering conceptual metaphors to exploring through computational experiments.

However, just as every technological revolution brings profound social and academic changes, the entry of AI into the field of mathematics has also triggered a series of controversies worthy of deep thought. These issues are not simple technical challenges; they concern the most fundamental definition of mathematics as a discipline—who is the creator? How is trust established? What capabilities should future mathematicians possess?

Following this line of thought, the first issue that emerges is the blurring boundary from “assistive tool” to “collaborator.” When AI systems are not merely performing calculations but can independently propose core conjectures and discover key proof steps, we are compelled to re-examine the attribution and authorship of mathematical discoveries. If the core insight of a paper is generated by AI, how should the human authors attribute it? Should it be considered a tool and not credited, or should the AI’s status as a “co-author” be acknowledged? Furthermore, if AI generates new results based on a vast corpus of existing human knowledge, how should the intellectual property rights be assigned? Although these questions have not yet reached a general consensus in academia, as AI’s role in mathematical research deepens, they are gradually moving from theoretical discussion to practical concern.

Closely related to the issue of attribution is the need to reconstruct the system of verification and trust. Mathematics, as the most rigorous discipline, builds its edifice of knowledge on the cornerstone that “proofs must be correct.” Traditionally, the correctness of a paper relies on peer review—a few experts reading and endorsing its logical derivation. But when the proof process involves complex AI models, massive computational experiments, or even internal representations difficult for humans to directly understand, the traditional review mechanism reveals its limitations. The mathematical community needs to consider: what level of AI involvement is acceptable? To ensure the reproducibility of results, what materials do authors need to disclose—only the final results, or also including training code, data, model weights, and even hyperparameter configurations? How does one distinguish between AI’s “effective inspiration” and “potential errors”? These questions are sparking initial discussions in academia, and their future direction will profoundly affect the foundation of trust in mathematical research.

Finally, the most far-reaching impact is reflected in the field of mathematical education. When AI can solve more and more standard mathematical problems, and even demonstrate capabilities surpassing humans in certain areas, we cannot help but ask: where should the focus of mathematics education shift? Should we continue to train students in techniques that machines can already execute perfectly, or should we shift towards cultivating abilities that AI still lacks? Critical thinking, the ability to formulate problems stemming from an understanding of the essence of mathematics, cross-domain metaphorical association, and the judgment to verify the reasonableness of AI outputs—the importance of these abilities will become increasingly prominent. Future mathematics education may no longer be about “imparting known solutions,” but about “cultivating the ability to solve problems in collaboration with AI”—this requires us to rethink curriculum design, assessment methods, and even the definition of mathematical literacy.

Faced with these controversies, we need to avoid two extreme attitudes: neither blindly embracing them while ignoring potential risks, nor rejecting change due to fear of difficulties. Just as the invention of the telescope did not replace astronomers but greatly expanded human vision, the goal of AI should also be to enhance mathematicians’ capabilities, not to replace mathematicians themselves. The key lies in establishing a framework that can fully leverage the potential of AI while maintaining academic rigor and humanistic values.

We stand at an exciting crossroads. Mathematics, the oldest and most rigorous discipline continuing from ancient Greek times, is undergoing an unprecedented deep integration with artificial intelligence. This integration will not only change the tools and methods of mathematical research but will also reshape the epistemological foundation of mathematical discovery—what is proof? What is understanding? What is creation? In the following chapters, we will explore these questions together, witnessing and participating in this transformation that profoundly affects the future face of mathematics.

### References

- [1] Kenneth Appel and Wolfgang Haken. “The solution of the four-color-map problem”. In: _Scientific American_ 237.4 (1977), pp. 108–121.

- [2] Xiaoyang Chen. “AI Reshaping Mathematical Research”. In: _Science (China)_ (2025).

- [3] François Chollet. “On the measure of intelligence”. In: _arXiv preprint arXiv:1911.01547_ (2019).

- [4] Alex Davies et al. “Advancing mathematics by guiding human intuition with AI”. In: _Nature_ 600.7887 (2021), pp. 70–74.

- [5] Alhussein Fawzi et al. “Discovering faster matrix multiplication algorithms with reinforcement learning”. In: _Nature_ 610.7930 (2022), pp. 47–53.

- [6] Gal Raayoni et al. “Generating conjectures on fundamental constants with the Ramanujan Machine”. In: _Nature_ 590.7844 (2021), pp. 67–73.

- [7] Bernardino Romera-Paredes et al. “Mathematical discoveries from program search with large language models”. In: _Nature_ 625.7995 (2024), pp. 468–475.

- [8] Richard S Sutton and Andrew G Barto. _Reinforcement learning: An introduction_ . MIT press, 2018.

- [9] Trieu H Trinh et al. “Solving olympiad geometry without human demonstrations”. In: _Nature_ 625.7995 (2024), pp. 476–482.

- [10] Ashish Vaswani et al. “Attention is all you need”. In: _Advances in neural information processing systems_ . Vol. 30. 2017, pp. 5998–6008.

- [11] Adam Zsolt Wagner. “Constructions in combinatorics via neural networks”. In: _arXiv preprint arXiv:2104.14516_ (2021).

## Chapter 2: Introduction to machine learning

### 2.1 Overview of machine learning

In the previous chapter, we outlined the broad landscape of the emerging interdisciplinary field “AI for Math.” Its core foundation stems from a set of methodologies known as machine learning. Through mathematical tools, machine learning establishes a computational framework for automatically learning patterns from data and making predictions or decisions about the future based on these patterns. Understanding the mathematical essence of this framework is a prerequisite for mastering all subsequent content in this book.

The core idea of machine learning is to automatically learn an “optimal” mapping from an input space to an output space from data. This artificial intelligence approach of “automatically optimizing a mapping based on data” opens the door to using computational power to handle complex patterns. This is precisely the starting point for artificial intelligence to intervene in mathematical research: finding a good mapping that can learn the intrinsic laws of mathematics from existing mathematical objects and data.

Any machine learning task can be decomposed into three fundamental components: data, model, and algorithm. Together, they define a specific and computable mathematical optimization problem.

1. Data

Data is the raw material for learning, typically given as a set of samples: _D_ = _{_ ( _x_[1] _, y_[1] ) _,_ ( _x_[2] _, y_[2] ) _, . . . ,_ ( _x[N] , y[N]_ ) _}_ . Here, _N_ is the number of samples. Here _x[i]_ is the input data, and _y[i]_ is the output data. In practical problems, data samples are usually represented by vectors, responsible for transforming real-world problems (such as images, text, mathematical formulas) into a numerical form that algorithms can process.

2. Model

The model _f_ ( _x_ ; _θ_ ) is the mapping we use to approximate the true data distribution, where _θ_ are the parameters to be optimized. Common mathematical models include:

- Linear models: The simplest example is _f_ ( _x_ ; _w, b_ ) = _w[T] x_ + _b_ , where _w, b_ are unknown parameters. This type of model is simple in form, easy to interpret, and suitable for situations where the data has a strong linear relationship. For example:

   - House price prediction: Predicting price ( _y_ ) based on floor area ( _x_ ), assuming a fixed price per square meter, then the total price is approximately linearly related to the area.

   - Academic performance analysis: Studying the relationship between study time ( _x_ ) and exam score ( _y_ ). Within a reasonable range, longer study time may lead to a linear improvement in scores.

   - Advertising effectiveness evaluation: Analyzing whether there is a stable linear growth trend between advertising expenditure ( _x_ ) and product sales ( _y_ ).

- Nonlinear models: When the data relationship is more complex and a simple straight line cannot describe its variation pattern, nonlinear models need to be introduced. For example, polynomial models:

**==> picture [203 x 14] intentionally omitted <==**

where _w_ 0 _, w_ 1 _, . . . , wM_ are the coefficients to be determined. It can approximate very complex functions and is a powerful tool for handling high-dimensional, unstructured mathematical objects. For example: Free-falling object: The relationship between the distance fallen ( _y_ ) and time ( _x_ ) is _y ∝ x_[2], requiring a quadratic polynomial for description.

3. Algorithm

The algorithm is responsible for automatically finding the optimal parameters _θ_ within the predefined mathematical model _f_ ( _x_ ; _θ_ ) based on the data _D_ . This leads to the next core question: How do we define “optimal”?

We want the model to perform well on all data it might encounter. In a probabilistic framework, assuming the data is generated by an unknown true distribution _p_ ( _x, y_ ), optimality is defined as minimizing the Expected Risk or expected loss:

**==> picture [152 x 13] intentionally omitted <==**

ˆ where _L_ ( _y,_ ˆ _y_ ) is called the loss function, measuring the discrepancy between the predicted output _y_ = _f_ ( _x_ ; _θ_ ) and the true output _y_ . Therefore, the ideal objective is

**==> picture [89 x 16] intentionally omitted <==**

However, the true distribution _p_ ( _x, y_ ) is usually unknown. The only information we have is a sample from that distribution: the training set _D_ . A natural and practical approximation is to replace the expected risk with the Empirical Risk:

**==> picture [169 x 33] intentionally omitted <==**

This leads to the core principle of machine learning—Empirical Risk Minimization (ERM):

**==> picture [102 x 17] intentionally omitted <==**

ERM transforms the learning problem into a pure mathematical optimization problem. The underlying statistical belief is that by optimizing the model’s performance on the training set, we expect the model to also perform well on unseen data, i.e., to possess generalization ability. Overfitting is precisely the core challenge faced by the ERM principle with limited samples: the model may overly “cater” to specific samples (including noise) in the training data, harming generalization performance.

In summary, data provides the material for learning, the model defines the form of expression, and the algorithm indicates the path for optimization. These three elements together constitute the basic framework of machine learning. However, the framework itself does not dictate the specific way of learning—just as having paper, pen, and writing rules, we still need to know what type of text to write. This leads to a higher-level distinction: based on the form of data and learning objectives, machine learning can be divided into three basic paradigms, which determine how the three elements are combined to solve problems.

1. Supervised Learning

   - The most distinctive feature of supervised learning is that the data consists of labeled input-output pairs ( _x, y_ ), and the goal is to learn the best mapping _f_ : _X →Y_ from the input space to the output space. In supervised learning, the data samples we collect contain both the real input and the labeled true output. This is a distinctive feature of supervised learning. Based on the type of output space, it is mainly divided into:

      - Regression problems: _Y ⊆_ R, meaning the output samples are continuously varying numerical values. For example, predicting tomorrow’s temperature based on historical weather data, or predicting the integral value of a function based on its values at a finite number of points.

      - Classification problems: _Y_ = _{_ 1 _,_ 2 _, ..., C}_ , meaning the output samples are discrete values. For example, determining whether an email is spam, or classifying a mathematical proposition as true or false.

2. Unsupervised Learning

   - In unsupervised learning, we only have input data _{x_[(1)] _, ..., x_[(] _[N]_[)] _}_ , without labeled true output data _y_ . Since the true output _y_ is not labeled in advance, we do not know the values of _y_ beforehand. This is a significant difference between unsupervised learning and supervised learning. The goal of unsupervised learning is to discover hidden structures, patterns, or distributions in the data, for example:

      - Clustering: Partitioning data into several clusters such that samples within the same cluster are similar to each other, while samples from different clusters are dissimilar. This is equivalent to discovering natural “groupings” or “categories” in the data space without predefining what these categories are.

      - Dimensionality reduction: Projecting high-dimensional data into a low-dimensional space while preserving as much important information (such as variance, manifold structure) as possible. This aids in visualization, denoising, and reducing computational complexity for subsequent tasks. Density estimation: Generating the underlying probability distribution of the observed data.

3. Reinforcement Learning (RL)

Reinforcement learning deals with an agent learning in an environment, changing the environment state by executing actions, and receiving reward signals from the environment. The goal is to learn a policy model (a mapping from states to actions) to maximize long-term cumulative reward.

The training data in reinforcement learning comes from the interaction between the agent and the environment and does not need to be collected in advance. This is a significant difference between reinforcement learning and other learning paradigms. In reinforcement learning, the reward function is one of the key elements used to optimize the parameters in the policy model (in supervised and unsupervised learning, a loss function is typically used to optimize the parameters in the prediction model).

### 2.2 Linear models

This section briefly describes linear models in machine learning. An important class of nonlinear models— artificial neural networks—will be discussed in the next section.

#### 2.2.1 Linear models in supervised learning

1. Linear Regression Model

Linear regression is the most fundamental regression model. Its core assumption is that the output variable

_y_ can be expressed as a linear combination of the input feature vector _x_ :

**==> picture [63 x 14] intentionally omitted <==**

This model uses the squared loss function: _L_ ( _y,_ ˆ _y_ ) = ( _y − y_ ˆ)[2] , and its empirical risk is defined as:

**==> picture [201 x 33] intentionally omitted <==**

The optimal parameters _w, b_ that minimize this empirical risk function can be solved using the Lagrangian multiplier method. Iterative optimization algorithms such as gradient descent can also be used for solving (refer to the subsequent material in this section for gradient descent).

2. Classification Model: Perceptron

The perceptron is an important classification model. From a geometric perspective, it automatically finds a linear hyperplane that can correctly separate two classes of data through iterative learning. It is mathematically defined as follows:

- A perceptron is a function _f_ : R _[d] →{−_ 1 _,_ +1 _}_ that maps a _d_ -dimensional real-valued input vector **x** =

- [ _x_ 1 _, x_ 2 _, ..., xd_ ] _[T]_ to a binary output (typically +1 and -1, representing two classes).

   - Its computation consists of two steps:

   - (1). Weighted Sum (Net Input): Compute the linear combination of input features.

**==> picture [133 x 33] intentionally omitted <==**

Here, **w** = [ _w_ 1 _, w_ 2 _, ..., wd_ ] _[T]_ is called the weight vector, and _b_ is called the bias. The weight _wi_ measures the importance of the corresponding feature _xi_ for the decision, and the bias _b_ determines the offset of the decision plane relative to the origin.

- (2). Activation Function: Apply a step function (or Heaviside function) to the net input _z_ .

**==> picture [156 x 40] intentionally omitted <==**

Interpreting the perceptron from a geometric perspective, it essentially seeks a decision hyperplane in the sample space. The perceptron’s decision rule **w** _[T]_ **x** + _b_ = 0 defines a decision hyperplane in the feature space, where the parameters have the following meanings:

- Weight vector **w** : The normal vector perpendicular to this decision hyperplane, indicating the positive direction of classification.

- Bias _b_ : Determines the distance from the hyperplane to the origin. When _b_ = 0, the hyperplane passes through the origin.

- Decision: For any data point **x** , if it lies on the side pointed to by the normal vector **w** (i.e., **w** _[T]_ **x** + _b >_ 0), it is classified as +1; otherwise, it is classified as -1.

Therefore, the learning objective of the perceptron is to find such a hyperplane that can correctly separate

all positive samples ( _y_ = +1) and negative samples ( _y_ = _−_ 1) on opposite sides.

Learning Algorithm: Weight Update Rule

the algorithm proceeds as follows:

1. Initialization: Initialize the weight **w** and bias _b_ to zero or small random numbers.

2. Iteration: For each sample ( **x** _, y_ ) in the training set (or in random order):

   - ˆ

   - (a). Compute the prediction: _y_ = sign( **w** _[T]_ **x** + _b_ ).

   - (b). Update weights (if and only if the prediction is incorrect):

ˆ **w** _←_ **w** + _η ·_ ( _y − y_ ) _·_ **x**

**==> picture [88 x 12] intentionally omitted <==**

Here, _η >_ 0 is a crucial hyperparameter called the learning rate, which controls the step size of each update.

After understanding the basic form of the perceptron, let’s delve into the geometric intuition behind its update rule—why can such a seemingly simple rule gradually correct classification errors?

When a sample is misclassified, the predicted value ˆ _y_ must be inconsistent with the true label _y_ . In this case, ˆ the value of ( _y − y_ ) is +2 or _−_ 2 (considering ˆ _y_ = sign( _w[T] x_ + _b_ ) takes values _±_ 1). To understand the geometric meaning of parameter adjustment more clearly, let’s examine the two misclassification scenarios separately:

ˆ Scenario One: True label _y_ = +1, but model predicts _y_ = _−_ 1

This means the current linear output from the model is _w[T] x_ + _b <_ 0, i.e., the sample point lies on the wrong side of the decision plane.

The update rule is: _w ← w_ + _η · x_ , _b ← b_ + _η ·_ (1) Geometric interpretation: This update effectively “pushes” the entire decision plane away from the current sample point. To understand this, we need to observe the change in the sample point’s position relative to the new plane after the update.

Before the update, we have _w[T] x_ + _b <_ 0. After the update, the new linear output is:

( _w_ + _ηx_ ) _[T] x_ + ( _b_ + _η_ ) = _w[T] x_ + _η∥x∥_[2] + _b_ + _η_ = ( _w[T] x_ + _b_ ) + _η_ ( _∥x∥_[2] + 1)

Since _∥x∥_[2] + 1 _>_ 0 and _η >_ 0, the new output value adds a positive term to the original negative value. This means the sample point’s “score” relative to the new plane increases—although it may still be negative, it has moved a step towards the positive direction. If the adjustment magnitude of this step is large enough, the sample point may cross the decision plane and enter the positive half-space.

From the perspective of the plane: The direction of the weight vector _w_ determines the normal direction of the plane, and the bias _b_ determines the plane’s position along the normal. When we increase the component of _w_ in the direction of _x_ , it is equivalent to rotating the plane around some axis, making its normal direction more inclined towards _x_ ; simultaneously increasing _b_ is equivalent to translating the plane along the normal direction. The combined effect is to move the plane away from _x_ , attempting to place _x_ on the correct side.

ˆ Scenario Two: True label _y_ = _−_ 1, but model predicts _y_ = +1

In this case, _w[T] x_ + _b >_ 0, and the sample point also lies on the wrong side of the decision plane, but in the opposite direction.

The update rule is: _w ← w − η · x_ , _b ← b_ + _η ·_ ( _−_ 1) = _b − η_

Geometric interpretation: This update also pushes the decision plane away from the current sample point, but in the opposite direction to Scenario One.

Before the update, _w[T] x_ + _b >_ 0. After the update, the new linear output is:

( _w − ηx_ ) _[T] x_ + ( _b − η_ ) = _w[T] x − η∥x∥_[2] + _b − η_ = ( _w[T] x_ + _b_ ) _− η_ ( _∥x∥_[2] + 1)

The new output value subtracts a positive term from the original positive value, decreasing the sample point’s “score”. This means the sample point moves towards the negative direction, gradually approaching or even crossing the decision plane into the negative half-space.

From the plane’s perspective: Subtracting the component in the _x_ direction is equivalent to making the plane’s normal _w_ deviate from the direction of _x_ , while decreasing the bias _b_ is equivalent to translating the plane along the negative normal direction. These two adjustments work together to move the plane away from the current sample point, attempting to place it in the negative half-space.

Understanding the above two updates, we can visualize the dynamic changes of the decision plane during the perceptron’s learning process:

Each time a misclassified sample is encountered, the algorithm applies a local adjustment to the decision plane based on the sample’s position and the direction of misclassification. This adjustment always moves the currently misclassified sample towards the correct side—specifically manifested as the sample’s linear output value relative to the new plane moving closer to zero until it crosses the boundary. However, this adjustment comes at the cost of sacrificing the classification status of other samples: some originally correctly classified samples may be pushed back to the wrong side. This is precisely the characteristic of the perceptron algorithm—it does not seek a one-step global optimum but rather achieves a balanced state through continuous trial and error and repeated corrections: all samples lie on the correct side of the decision plane, provided the data is linearly separable.

From a geometric intuition, the entire learning process is like a tilted plate (the decision plane) constantly flipping and translating among data points, slightly lifting one end each time it encounters a point that is pressed incorrectly, until all points lie on the correct side of the plate or the iteration limit is reached.

Can this repeated adjustment process eventually stop? The Perceptron Convergence Theorem [Novikoff, 1963] gives an affirmative answer: if the training data is linearly separable, i.e., there exists some hyperplane that can perfectly separate the two classes of samples, then regardless of the initial plane, the above update rule guarantees convergence to a solution that correctly classifies all training samples within a finite number of iterations.

However, the convergence theorem only guarantees the “existence of a solution” and does not promise that this solution is “optimal.” In fact, the decision plane finally found by the perceptron heavily depends on the order in which samples appear and the initial parameters. It may happen to lie in the marginal zone between the two classes—extremely close to some sample points, even tightly adhering to the boundary of one class. Although such a solution performs perfectly on the training set, it often performs poorly on unseen test data due to a lack of robustness. This limitation later gave rise to the birth of the support vector machine (SVM): SVM not only seeks a hyperplane that can classify but also pursues the one with the “maximum margin,” thereby mathematically guaranteeing stronger generalization ability. This difference between the perceptron and SVM precisely reflects the evolution of machine learning thought from “finding a feasible solution” to “finding an optimal solution.”

3. Classification Model: Support Vector Machine (SVM)

The perceptron provides us with a method to find a classification hyperplane, but it only guarantees finding “some” plane that can separate the two classes of samples, without caring whether this plane is “good.” When there are infinitely many possible classification hyperplanes, we naturally ask: Which one is the best?

The idea of maximum margin. From a geometric perspective, the support vector machine gives a clear answer: the best classification hyperplane should be the one that is as far away as possible from both classes of samples. This “distance” is measured by the margin—defined as the distance from the hyperplane to the nearest sample point. The intuition behind maximizing the margin is that such a hyperplane has the strongest robustness: when new samples fluctuate slightly near the boundary, they are less likely to be misclassified, potentially leading to optimal generalization ability. It is worth noting that for linearly separable data, the hyperplane that maximizes the margin is unique, as shown in Figure2.1 (adapted from Qiu Xipeng’s “Neural Networks and Deep Learning” Figure 3.6).

- (1). Linearly Separable Case: Hard-Margin SVM

When the data is linearly separable, the SVM optimization problem can be formulated as:

**==> picture [204 x 43] intentionally omitted <==**

Here, we need to explain where the “1” in the constraint comes from. We know that for any hyperplane _w[T] x_ + _b_ = 0 that can correctly classify the two classes of samples, we can always scale _w_ and _b_ proportionally so that _|w[T] x_ + _b| ≥_ 1 holds for all samples, and equality holds at least at the points closest to the plane. This “1” essentially normalizes the functional margin, eliminating the uncertainty caused by parameter scaling and giving the optimization problem a definite form. At this point, the margin is exactly 1 _/∥w∥_ , so minimizing _∥w∥_[2] is equivalent to maximizing the margin.

**Figure 2.1:** Support Vector Machine

This is a convex quadratic programming problem—the objective function is quadratic, and the constraints are linear—so there exists a unique global optimal solution. The decision function obtained after solving is _f_ ( _x_ ) = sign( _w[T] x_ + _b_ ), where only those samples on the margin boundary (i.e., points satisfying _y_[(] _[n]_[)] ( _w[T] x_[(] _[n]_[)] + _b_ ) = 1) contribute to the final hyperplane; they are called support vectors.

(2). Linearly Inseparable Case: Soft-Margin SVM

Real-world data is often not perfectly linearly separable; there may be noise, overlap, or even individual outliers. If we insist on using the above “hard-margin” constraint, the problem will have no solution. For this reason, we need to allow the model to make mistakes on some samples—this is the starting point of soft-margin SVM.

Introduce non-negative slack variables _ξn ≥_ 0, each corresponding to a sample _ξn_ , which measures the degree to which that sample violates the constraint. Specifically, we relax the original strict constraint to:

**==> picture [204 x 14] intentionally omitted <==**

- When _ξn_ = 0, the sample lies on the correct side and satisfies the margin requirement;

- When 0 _< ξn <_ 1, the sample is on the correct side but lies inside the margin (i.e., between the decision plane and the margin boundary);

When _ξn ≥_ 1, the sample is misclassified (lies on the wrong side of the decision plane).

The introduction of slack variables gives the model “tolerance space,” but we need to control the total error. Thus, the optimization objective becomes seeking a balance between maximizing the margin and minimizing the total error:

**==> picture [105 x 33] intentionally omitted <==**

Here, _ξn_ is the total penalty for all samples’ constraint violations, and the penalty coefficient _C >_ 0 is a hyperparameter that needs to be manually set, regulating the weight between the two objectives:

- A larger _C_ means low tolerance for misclassification; the model will try its best to classify each sample correctly, even if this means a smaller margin;

- A smaller _C_ allows more misclassification in exchange for a larger margin, thereby obtaining stronger generalization ability.

The choice of _C_ is crucial—it essentially controls the model’s sensitivity to noise and is the key knob for balancing fitting ability and generalization ability.

##### 2.2.1.1 Kernel trick: From linear to nonlinear

The idea of maximum margin is elegant, but it is still limited to linear classifiers. How can we make SVM handle nonlinearly separable data? Intuition tells us that if data cannot be linearly separated in the original feature space, perhaps we can map it to a higher-dimensional space through some transformation, making them linearly separable there.

This is precisely the core idea of the kernel trick. Consider a nonlinear mapping _ϕ_ : _X →F_ that maps data points from the original space to a high-dimensional feature space _F_ . In this new space, we can perform standard linear SVM. However, directly computing _ϕ_ ( _x_ ) and performing inner products in the high-dimensional space is often computationally expensive and may even face the curse of dimensionality.

The key insight of the kernel trick is that in both the SVM optimization problem and the final decision function, data appears in the form of inner products—i.e., the form _x[T] i[x][j]_[.][If we can find a function] _[ K]_[(] _[x][i][, x][j]_[)] that directly equals the inner product in the high-dimensional space _⟨ϕ_ ( _xi_ ) _, ϕ_ ( _xj_ ) _⟩_ , then we do not need to explicitly compute _ϕ_ ( _x_ ) or know the specific form of the mapping; we only need to compute this kernel function. This not only avoids the computational burden caused by high dimensionality but even allows us to implicitly work in infinite-dimensional spaces.

Commonly used kernel functions include:

- Linear kernel: _K_ ( _x, z_ ) = _x[T] z_ , degenerating to ordinary linear SVM;

- Polynomial kernel: _K_ ( _x, z_ ) = ( _x[T] z_ + _c_ ) _[d]_ , introducing polynomial combination features;

- Gaussian Radial Basis Function (RBF) kernel: _K_ ( _x, z_ ) = exp( _−γ∥x − z∥_[2] ), capable of approximating any nonlinear function, one of the most commonly used kernel functions, where the parameter _γ_ controls the influence range of a single sample.

After introducing the kernel trick, the SVM decision function becomes:

**==> picture [165 x 12] intentionally omitted <==**

where _αi_ are the Lagrange multipliers obtained by solving the dual problem, and only those samples with _αi >_ 0 (i.e., support vectors) influence the decision outcome. This reflects an elegant property of SVM: the solution has sparsity, and the final model is determined only by a few key samples.

From the perceptron to hard-margin SVM, then to soft-margin SVM and the kernel trick, we have witnessed an important leap in machine learning thought: from “finding a feasible solution” to “finding an optimal solution,” from linear to nonlinear, from parametric models to sample-based kernel methods. With its elegant mathematical form and solid theoretical foundation, the support vector machine has become a milestone in the history of machine learning development.

#### 2.2.2 Linear models in unsupervised learning: Principal component analysis (PCA)

Unlike supervised learning, unsupervised learning deals with data without labels—we only have inputs _x_ , but no corresponding outputs _y_ to tell the model what to learn. So, in the absence of a “standard answer,” what can the model learn? The answer is: the structure, patterns, or distribution inherent in the data itself. The goal of unsupervised learning is for the model to autonomously discover this hidden information.

Unsupervised learning encompasses many different tasks, with the two most representative categories being dimensionality reduction and clustering. Dimensionality reduction attempts to compress high-dimensional data into a low-dimensional space while preserving key information; clustering attempts to automatically group similar samples together. Here, we focus on one of the most classic methods in dimensionality reduction: Principal Component Analysis.

In real-world problems, we often face high-dimensional data—an image may have thousands of pixels, a text may have tens of thousands of vocabulary words. High-dimensional data is not only difficult to visualize but also imposes a significant computational burden. More importantly, it often contains a large amount of redundant information. The goal of dimensionality reduction is to find a way to map data from a high-dimensional space to a low-dimensional space while preserving the most important information in the data as much as possible.

As an analogy: Suppose you need to describe a person’s appearance to someone else. You could describe a photo pixel by pixel, but this is obviously highly inefficient. A better way is to capture key features—a few dimensions such as face shape, eye color, hairstyle—to roughly reconstruct a person’s appearance. Dimensionality reduction does something similar: it finds the directions that best capture the variation in the data and discards directions with little variation or dominated by noise.

The value of dimensionality reduction is reflected in several aspects:

- Visualization: Reducing data to two or three dimensions allows direct observation of sample distribution and clustering;

- Denoising: Discarding directions with small variation often simultaneously removes noise;

- Computational efficiency: Low-dimensional data significantly reduces the computational cost of subsequent algorithms;

- Feature extraction: The new features after dimensionality reduction are sometimes more representative than the original features.

Principal Component Analysis is the most commonly used and classic linear dimensionality reduction method. Its core idea is very intuitive: If we could only choose one direction to project the data onto, which direction should we choose to preserve the variation of the original data to the greatest extent?

Imagine a group of points scattered on a two-dimensional plane. If we project them onto a straight line, some projection directions will cause all points to be squeezed together (small variance), while other directions will cause the points to spread out as much as possible (large variance). Clearly, the latter preserves more information about the original data distribution—because the relative distances between points are better preserved. What Principal Component Analysis seeks are precisely such directions: the variance of the data projected onto these directions should be as large as possible, and these directions are orthogonal to each other. As shown in Figure2.2 (adapted from Qiu Xipeng’s “Neural Networks and Deep Learning” Figure 9.1).

These directions are called principal components. The first principal component is the direction with the largest variance; the second principal component is the direction with the next largest variance under the constraint of being orthogonal to the first; and so on.

So, how do we find these directions mathematically? This requires the use of the covariance matrix. Given _N N d_ -dimensional samples _x_[(1)] _, x_[(2)] _, . . . , x_[(] _[N]_[)] , we first compute the sample mean ¯ _x_ = _N_[1] _i_ =1 _[x]_[(] _[i]_[)][, then center] each sample (subtract the mean). The centered data forms a matrix, and its covariance matrix is defined as:

**Figure 2.2:** Schematic diagram of Principal Component Analysis

**==> picture [147 x 34] intentionally omitted <==**

This matrix has dimensions _d×d_ , and it captures the covariance relationships between the original features— the diagonal elements are the variances of each feature, and the off-diagonal elements are the covariances between features.

The key to Principal Component Analysis is: the variance of the data projected onto a certain direction is precisely equal to a certain relationship between that direction and the covariance matrix. Mathematically, it can be proven that the eigenvectors of the covariance matrix Σ indicate the directions of variance, and the corresponding eigenvalues measure the magnitude of variance in those directions. A larger eigenvalue means more information is preserved in that direction.

Therefore, the steps for solving PCA are very clear:

   1. Compute the covariance matrix Σ of the data;

   2. Solve for all eigenvalues and eigenvectors of Σ;

   3. Sort the eigenvalues in descending order and select the eigenvectors corresponding to the top _k_ largest eigenvalues;

   4. Form the projection matrix _W ∈_ R _[d][×][k]_ from these eigenvectors;

   5. For any sample _x_ , the reduced-dimensional representation is _z_ = _W[T]_ ( _x − x_ ¯).

- Thus, we have compressed the original _d_ -dimensional data into _k_ dimensions ( _k ≪ d_ ), while preserving the main variation in the data as much as possible.

Principal Component Analysis also has an equivalent interpretation: it attempts to find a low-dimensional representation such that when reconstructing back to the original space from this representation, the resulting error is as small as possible. In other words, if we view dimensionality reduction as a form of compression, then good compression should be able to restore the original data as much as possible. PCA is optimal in this sense among all linear dimensionality reduction methods—it achieves the best in terms of minimizing the reconstruction error (i.e., the sum of squared Euclidean distances between the original data and the reconstructed data).

This perspective is equivalent to “maximizing variance”: preserving the direction with the largest variance is also the direction that minimizes reconstruction error. Both interpret the same essence from different angles— Principal Component Analysis attempts to capture the most essential patterns of variation in the data.

Note: Another typical application of unsupervised learning is cluster analysis, which partitions data into several clusters such that samples within the same cluster are similar to each other, while samples from different clusters are more dissimilar. This is equivalent to discovering natural “groupings” or “categories” in the data space without predefining what these categories are. We briefly introduce here a special type of clustering method (although this method is not a linear model):

K-means Clustering: The goal is to partition _N_ samples into _K_ clusters, minimizing the sum of squared distances from each sample to its assigned cluster center:

**==> picture [132 x 33] intentionally omitted <==**

where _rnk ∈{_ 0 _,_ 1 _}_ indicates whether sample _n_ belongs to cluster _k_ , and _µk_ is the center of cluster _k_ . The algorithm solves this by alternately executing the following steps:

1. Assignment step: Fix _{µk}_ , assign each sample to the nearest cluster center;

2. Update step: Fix _{rnk}_ , recalculate each cluster center as the mean of the samples in that cluster. K-means is simple and efficient but sensitive to initial centers, requires pre-specifying the number of clusters _K_ , and has limited effectiveness for non-spherical clusters or clusters of different densities.

#### 2.2.3 Optimization algorithms: Gradient descent

In the previous discussion, we established the model and clarified the learning objective—typically minimizing a certain loss function. However, for the vast majority of models with practical value, this minimization problem cannot be solved directly through analytical methods (like solving a quadratic equation to obtain an explicit formula). The reality we face is: we need to find a method to let the model iteratively approach the optimal solution. This is precisely where optimization algorithms come into play. Gradient descent and its numerous variants form the core of machine learning optimization.

Imagine you are standing at a certain point on a mountain, with thick fog obscuring the entire landscape, but you can feel the slope of the ground beneath your feet. What would you do to reach the valley as quickly as possible? Naturally, you would take a step in the direction of the steepest descent, then reassess the slope at the new position, take another step—and repeat this process until you no longer feel a significant downward slope.

This is an intuitive depiction of gradient descent. Mathematically, the gradient _∇θR_ ( _θ_ ) points in the direction of the fastest increase of the function value; its opposite direction is naturally the direction of the fastest decrease. Each component of the gradient is the partial derivative of the loss function with respect to the corresponding parameter—it tells us whether adjusting this parameter will increase or decrease the loss, and by how much.

Based on this idea, the update rule for gradient descent can be written as:

**==> picture [127 x 12] intentionally omitted <==**

Here, _θt_ represents the parameters at the _t_ -th iteration, _∇θR_ emp( _θt_ ) is the gradient of the empirical risk function (i.e., the average loss on the training set) at the current parameters. The learning rate _α >_ 0 controls how large a step we take—too small a step leads to slow convergence; too large a step may overshoot the valley or even diverge.

The specific implementation of gradient descent depends on how much data we use to compute the gradient each time. Based on the amount of data used, three basic variants can be distinguished.

- Batch gradient descent uses the entire training dataset to compute the gradient. The advantage of this approach is that the gradient direction is accurate, with each step moving toward the global optimum; but the cost is also obvious—when the dataset is huge, each iteration requires traversing the entire dataset, making the computational cost prohibitively high.

- Stochastic gradient descent [Nemirovskietal.,2009] goes to the other extreme: each time, it randomly selects only one sample and uses its loss gradient as an estimate of the global gradient. This makes the computation extremely lightweight, allowing updates to be very frequent. More importantly, the randomness introduced by the single-sample gradient actually helps the algorithm escape local minima, offering a chance to find better solutions. However, the cost is that the update direction oscillates violently, leading to an unstable convergence process.

- Mini-batch gradient descent [Bottou,2010] is a compromise between the two: each time, it uses a small batch of data (e.g., 32, 64, or 128 samples) to compute the gradient. It both reduces variance through batch averaging, making the update direction relatively stable, and maintains high computational efficiency.

##### 2.2.3.1 Advanced optimization methods

Although basic gradient descent is effective, it encounters two thorny challenges on complex problems: first, it easily oscillates back and forth in steep valleys, leading to slow convergence; second, using a uniform learning rate for all parameters cannot adapt to the update needs of different parameters. To address these, researchers have proposed a series of “smarter” optimization methods.

Momentum: The inspiration for momentum comes from physics: imagine a small ball rolling down a hill; it accumulates momentum, and when it encounters an opposing slope, it does not stop immediately but rushes past due to inertia. Momentum introduces a velocity variable _v_ to simulate this effect:

**==> picture [235 x 12] intentionally omitted <==**

The current gradient is responsible for “acceleration,” while the velocity accumulated from historical gradients maintains the direction of motion. The hyperparameter _β_ (usually set around 0.9) controls the degree of reliance on historical information. The effect of momentum is: accelerating convergence in dimensions where the gradient direction is consistent, and suppressing oscillations in dimensions where the gradient direction fluctuates—like adding inertia to the rolling ball, making it run more steadily and quickly.

Adam (Adaptive Moment Estimation) combines momentum with adaptive learning rates. It maintains two state variables:

- First moment estimate _mt_ : the exponentially weighted moving average of gradients, equivalent to gradient with momentum;

- Second moment estimate _vt_ : the exponentially weighted moving average of squared gradients, reflecting the variance of gradients (i.e., the historical update magnitude for each parameter).

The specific update process is as follows. First, compute the current gradient _gt_ = _∇θL_ ( _θt_ ), then update the two moment estimates:

**==> picture [123 x 36] intentionally omitted <==**

Here, _β_ 1 and _β_ 2 are decay rates. Since _mt_ and _vt_ are biased towards 0 in the initial stages, bias correction is necessary:

**==> picture [130 x 24] intentionally omitted <==**

Finally, update the parameters:

**==> picture [108 x 26] intentionally omitted <==**

where _ϵ_ is a small constant (e.g., 10 _[−]_[8] ) to prevent division by zero.

The ingenuity of Adam lies in: each parameter has its own adaptive learning rate. For parameters with historically large gradients (frequent updates), _[√] v_ ˆ _t_ is large, and the effective learning rate is automatically reduced; for parameters with small gradients (slow updates), the effective learning rate is automatically increased. This adaptive mechanism makes Adam less sensitive to the choice of initial learning rate and allows it to perform well on various problems, making it one of the preferred optimizers for training neural networks (see the next section on artificial neural networks).

#### 2.2.4 Model evaluation and selection

In machine learning practice, the fundamental question we face is not “can the model memorize the training data,” but “can the model handle new, unseen samples”—this is generalization ability. How to accurately evaluate a model’s generalization ability and, based on that, select the optimal model configuration constitutes the core issue of model evaluation and selection.

##### 2.2.4.1 The three-way split of data

To evaluate generalization ability, we must first clarify: we cannot use the data that trained the model to test it—this is like taking an exam with a paper you’ve already seen, which cannot reflect true proficiency. Therefore, we need to properly split the available data.

- The training set is the material for the model to learn from. The model uses it to update parameters and fit the data distribution, analogous to a student’s textbooks and practice problems.

- The validation set plays the role of a “mock exam.” It does not participate in parameter learning but is used to guide model selection and hyperparameter tuning—when we need to decide the polynomial degree, the learning rate, etc., the performance on the validation set is the basis for decision-making. The reason a validation set is needed is that if we directly use the test set for tuning, it would be like knowing the exam answers in advance, rendering the final evaluation meaningless.

- The test set is the final “college entrance exam.” It must remain completely unseen throughout the entire training and tuning process, used only once after the model is fully finalized, to provide an unbiased estimate of generalization ability. The performance on the test set is the model performance we report externally.

This three-way split forms the basic framework for evaluation, ensuring clear data boundaries at every stage from model development to final assessment.

While the single split described above is simple, it harbors a risk: the result may depend on a particular, specific split. If the validation set happens to contain some easy or difficult samples, the evaluation result will be biased. To mitigate this issue, k-fold cross-validation was developed.

The procedure is as follows: randomly divide the training data into k equal parts (typically 5 or 10). Then perform k training-validation cycles—the first cycle uses the first part as the validation set and the rest as the training set; the second cycle uses the second part as the validation set, and so on. Each cycle records the model’s performance metric on the validation set, and finally, the average of the k results is taken as the performance estimate.

The advantages of this method are: every sample has a chance to be in the validation set, making the performance estimate more stable and reliable; simultaneously, all data is used for both training and validation, avoiding data waste. Cross-validation is particularly valuable when the amount of data is limited.

It is important to emphasize that cross-validation is still conducted *within* the training data—it is used for model selection and hyperparameter tuning. The final test set must still be kept untouched until the very last evaluation.

##### 2.2.4.2 Parameters and hyperparameters

In the context of machine learning, “parameters” and “hyperparameters” are two easily confused but fundamentally different concepts. Understanding their distinction helps grasp the hierarchical structure of model learning.

Parameters are the internal variables of the model; they constitute the core of the model itself. The weight coefficients _w_ and bias _b_ in a linear model, the coefficients of various terms in a polynomial model—all belong to parameters. The characteristic of these variables is: their values are entirely driven by the training data, learned automatically through optimization algorithms (such as gradient descent). In other words, parameters are the knowledge “summarized” by the model from the data.

Hyperparameters are completely different. They are configuration options set manually before training begins, controlling the training process itself and the model’s structure. The learning rate _α_ , the batch size in gradient descent, the degree _M_ of a polynomial model, the regularization coefficient—all these are hyperparameters. Their values cannot be learned directly from the data; they need to be determined based on human experience or some search strategy.

One can understand the relationship between the two as follows: parameters are the kernel of the model, while hyperparameters are the external instructions that shape this kernel. Hyperparameters determine *how* and under *what constraints* the model learns the parameters. Precisely because the choice of hyperparameters directly affects learning outcomes, we need to rely on the validation set or cross-validation to “tune” them— trying different hyperparameter combinations, observing performance on the validation set, and finally selecting the most suitable set.

This hierarchical structure runs through the entire practice of machine learning: within the framework determined by hyperparameters, the model learns parameters from data; while the hyperparameters themselves require a higher-level validation mechanism for optimization. The two complement each other, together forming the complete chain from data to model.

### 2.3 Artificial neural networks

So far, we have introduced the fundamental paradigm of machine learning, whose core lies in learning an optimal mapping from data. Linear models serve as the cornerstone due to their simplicity and interpretability, but their ability to handle complex nonlinear relationships is limited. This chapter will focus on a powerful and revolutionary family of nonlinear models—Artificial Neural Networks (Neural Networks).

The study of artificial neural networks is inspired by a simplified simulation of how networks of neurons operate in the biological brain. Artificial neural networks play a unique and crucial role: they are an extremely flexible nonlinear function approximator and a powerful feature transformation engine. This means that when faced with complex problems—for example, finding hidden patterns in high-dimensional, unstructured data (such as recognizing geometric structures in images), or approximating an unknown function that has no explicit formula but can be described by samples (such as solving partial differential equations)—artificial neural networks provide a way to directly “learn” the solution from data.

Artificial neural networks, especially deep neural networks, form the foundation of most current breakthrough advances in artificial intelligence. From image recognition and natural language processing to game systems like AlphaGo, and further to mathematical discovery tools like FunSearch and AlphaTensor, artificial neural networks have played a central role. This section will start from a mathematical perspective, strip away engineering details, and delve into the three core components of neural networks: activation functions, network architecture, and learning algorithms, explaining the underlying mathematical ideas and theoretical guarantees.

Before introducing artificial neural networks, we first introduce its predecessor: logistic regression.

Despite containing “regression” in its name, logistic regression is actually a classic binary classification model. Its core idea is to use the model’s output to fit the log-odds of a sample belonging to the positive class. The model first computes a linear score _z_ = _w[T] x_ + _b_ , then maps it to the interval (0 _,_ 1) via the Sigmoid function _σ_ ( _z_ ) = 1 _/_ (1 + _e[−][z]_ ), interpreting it as the probability of the positive class:

**==> picture [141 x 13] intentionally omitted <==**

The classification decision rule is: if _p_ ( _y_ = 1 _|x_ ) _>_ 0 _._ 5, predict the positive class; otherwise, predict the negative class.

Logistic regression employs the classic cross-entropy loss function. For a single sample, with true label ˆ _y ∈{_ 0 _,_ 1 _}_ and predicted probability _y_ = _p_ ( _y_ = 1 _|x_ ), the loss is:

**==> picture [195 x 12] intentionally omitted <==**

This function measures the difference between the predicted probability distribution and the true label distribution; minimizing cross-entropy is equivalent to maximum likelihood estimation. Its gradient has a simple form: _∂L/∂w_ = (ˆ _y − y_ ) _x_ .

Building upon binary classification, logistic regression can be further generalized to multi-class classification tasks, leading to Softmax regression (also known as multinomial logistic regression). When the number of classes _C >_ 2, we need to compute a score _zc_ = _wc[T][x]_[ +] _[ b][c]_[for][each][class][and][transform][these][scores][into][a] probability distribution via the Softmax function:

**==> picture [221 x 31] intentionally omitted <==**

Thus, Softmax regression unifies predictions for multiple classes into a normalized probabilistic framework. Correspondingly, its loss function also adopts the cross-entropy form. For the true class _c_ , the loss is:

**==> picture [269 x 33] intentionally omitted <==**

where I( _·_ ) is the indicator function. Softmax regression is concise and effective, making it a standard configuration for the output layer in multi-class tasks in deep learning.

Artificial neural networks are a generalization of the logistic regression function, comprising the following three core components: activation functions, network architecture, and learning algorithms.

**From Biological Neurons to Artificial Neurons**

The basic computational unit of a neural network is the artificial neuron, whose design is inspired by biological neurons. A simplified biological neuron receives electrical signals from other neurons; when the total signal strength exceeds a certain threshold, the neuron is activated and transmits signals downstream. The artificial neuron is a mathematical abstraction and modeling of this process.

The mathematical description of a typical artificial neuron (also known as a Perceptron in early days) is as follows:

Given an input vector **x** = [ _x_ 1 _, x_ 2 _, ..., xd_ ] _[T] ∈_ R _[d]_ , the neuron first computes a weighted sum and adds a bias term. This intermediate result is called the neuron’s net input or pre-activation value:

**==> picture [133 x 33] intentionally omitted <==**

where **w** = [ _w_ 1 _, w_ 2 _, ..., wd_ ] _[T] ∈_ R _[d]_ is the weight vector, with each _wi_ measuring the importance or connection strength of the corresponding input _xi_ ; _b ∈_ R is the bias, used to control how easily the neuron is activated. Figure2.3 shows a typical neuron structure example (adapted from Figure 4.1 in Qiu Xipeng’s “Neural Networks and Deep Learning”):

**Figure 2.3:** Neuron Structure

However, if the neuron merely outputs the linear combination _z_ , then a network composed of multiple such linear units would essentially remain a combination of linear models, unable to break through the limitations of linear transformations. To endow the network with the ability to approximate arbitrarily complex functions, nonlinearity must be introduced. Therefore, the neuron passes the net input _z_ to an activation function _f_ ( _·_ ), obtaining the final output or activation value:

**==> picture [112 x 14] intentionally omitted <==**

It is precisely the nonlinear nature of the activation function _f_ that gives neural networks their powerful expressive capacity, enabling them to learn complex patterns and hierarchical features in data.

#### 2.3.1 Core nonlinear component: Activation functions

The choice of activation function is crucial; it directly determines how the neuron responds to input signals and profoundly affects the training effectiveness and performance of the entire network. Ideal activation functions typically need to possess properties such as nonlinearity, continuous differentiability (or almost everywhere differentiability), computational simplicity, and easy-to-compute derivatives. Here are several classic and widely used activation functions.

1. Sigmoid function (Logistic function)

**==> picture [73 x 24] intentionally omitted <==**

The Sigmoid function “squeezes” any real number _z_ into the interval (0 _,_ 1), and its output can be interpreted as a probability. It was very popular in early neural networks. Its derivative is _σ[′]_ ( _z_ ) = _σ_ ( _z_ )(1 _− σ_ ( _z_ )). However, when the absolute value of the input _z_ is large, its derivative approaches 0, which can lead to the “vanishing gradient” problem in deep network training.

2. Hyperbolic tangent function (Tanh function)

**==> picture [92 x 24] intentionally omitted <==**

The Tanh function maps the input to the interval ( _−_ 1 _,_ 1) and is zero-centered (mean 0), which in practice can sometimes allow the network to train faster. Its derivative is tanh _[′]_ ( _z_ ) = 1 _−_ tanh[2] ( _z_ ).

3. Rectified Linear Unit (ReLU) [Nair et al., 2010]

**==> picture [100 x 12] intentionally omitted <==**

ReLU is one of the most popular activation functions today. Its computation is extremely simple: when _z >_ 0, the output is _z_ ; otherwise, the output is 0. Its derivative is 1 for _z >_ 0 and 0 for _z <_ 0. The non-saturating nature of ReLU (constant derivative of 1 in the positive region) effectively alleviates the vanishing gradient problem and speeds up training. Its drawback is that when the input is negative, the gradient is 0, which may cause some neurons to never activate (the “dying neuron” problem).

4. Leaky ReLU and ELU

To mitigate the “dying” problem of ReLU, variants have been proposed. Leaky ReLU gives a small slope (e.g., 0.01) in the negative region:

**==> picture [100 x 12] intentionally omitted <==**

The Exponential Linear Unit (ELU) uses an exponentially decaying function in the negative region:

**==> picture [156 x 40] intentionally omitted <==**

where _γ_ is a hyperparameter.

These nonlinear activation functions are the foundation for neural networks to construct complex, hierarchical feature representations. A single neuron acts like a “mini-classifier” or “feature detector,” and by combining countless such neurons, the network can learn and represent extremely complex features.

#### 2.3.2 Network architecture: From fully connected to locally connected

A single neuron has limited capability. Connecting a large number of neurons according to a specific topology forms an artificial neural network. The network architecture defines the paths and manner of information flow between neurons.

#### 2.3.3 Fully connected feedforward neural networks

The fully connected feedforward neural network is one of the most basic and core network architectures. Often referred to as “Multilayer Perceptron” (MLP) or “Deep Neural Network” (DNN), it typically refers to this type of network.

Architectural characteristics: The network consists of multiple layers of neurons, typically including an input layer, one or more hidden layers, and an output layer. There are no connections between neurons within the same layer. Each neuron in a layer is connected to all neurons in the previous layer. Information starts from the input layer and propagates unidirectionally layer by layer, with no feedback, hence the term “feedforward.” This structure can be represented by a directed acyclic graph.

Mathematical description: Consider a network with _L_ layers (the input layer is not counted).

_Ml_ : Number of neurons in layer _l_ ( _l_ = 0 is the input layer). _fl_ ( _·_ ): Activation function for neurons in layer _l_ . **W**[(] _[l]_[)] _∈_ R _[M][l][×][M][l][−]_[1] : Weight matrix connecting layer _l −_ 1 to layer _l_ . Its element _Wij_[(] _[l]_[)][represents the connection] weight from the _j_ -th neuron in layer _l −_ 1 to the _i_ -th neuron in layer _l_ . **b**[(] _[l]_[)] _∈_ R _[M][l]_ : Bias vector for layer _l_ . **z**[(] _[l]_[)] _∈_ R _[M][l]_ : Net input vector for neurons in layer _l_ . **a**[(] _[l]_[)] _∈_ R _[M][l]_ : Output (activation value) vector for neurons in layer _l_ , with **a**[(0)] = **x** (input).

The forward propagation process of the network can be described recursively as:

**==> picture [110 x 34] intentionally omitted <==**

Finally, the network’s output is **a**[(] _[L]_[)] = _ϕ_ ( **x** ; **W** _,_ **b** ), where _ϕ_ denotes the composite function of the entire network.

The structure of a fully connected feedforward neural network is shown in Figure2.4 (adapted from Figure 4.7 in Qiu Xipeng’s “Neural Networks and Deep Learning”).

**Figure 2.4:** Feedforward Neural Network

The powerful capability of fully connected neural networks has solid mathematical theoretical support. The Universal Approximation Theorem states: A fully connected network with at least one hidden layer containing a sufficient number of neurons and using a nonlinear activation function (such as Sigmoid, ReLU, etc.) can approximate any continuous function defined on a compact set to arbitrary accuracy.

Theorem conditions and intuitive understanding: The classical form of this theorem usually requires the activation function _φ_ ( _·_ ) to be non-constant, bounded, monotonic increasing, and continuous (the Sigmoid function satisfies this condition; ReLU, although unbounded, is supported by subsequent extended theories). Also, the approximation holds on a “compact set” (e.g., a bounded closed interval). This means that no matter how complex or irregular the function you want to approximate is, as long as the network is sufficiently wide (enough neurons in the hidden layer), there always exists a network whose input-output relationship differs from your target function by an error within any allowable range. A simple intuition is: each hidden layer neuron can be seen as a “basis function” (like an “S-shaped” peak or trough formed by the Sigmoid function). By adjusting the weights and biases of enough such basis functions, we can “sculpt” arbitrarily complex continuous function shapes using their linear combination. This theorem establishes the theoretical foundation for neural networks as “universal function approximators,” explaining why they can handle a wide variety of problems from image classification to solving mathematical equations. Of course, the theorem guarantees “existence” but does not tell us how to find (i.e., train) this network, which relies on the learning algorithms introduced in the next section.

#### 2.3.4 Convolutional neural networks (CNN)

Fully connected networks have significant drawbacks when processing data with local correlations and translation invariance, such as images and audio: excessive parameters lead to huge computational and storage overhead, and they struggle to effectively capture local features.

Convolutional neural networks cleverly address these issues by introducing convolutional layers. Their core idea originates from the “receptive field” mechanism of the biological visual system. The core of a convolutional neural network is the convolution operation:

One-dimensional convolution: For an input sequence _x_ and a filter (or convolution kernel) _w_ , the convolution output _yt_ =[�] _[K] k_ =1 _[w][k][x][t][−][k]_[+1][.][The filter slides over the input, computing the dot product at each position,] thereby extracting local features.

Two-dimensional convolution: For two-dimensional inputs like images **X** _∈_ R _[H][×][W]_ and a small filter **W** _∈_ R _[U][×][V]_ (e.g., U=3, V=3), the convolution operation **Y** = **W** _∗_ **X** is defined as:

**==> picture [149 x 33] intentionally omitted <==**

Here is an intuitive example: Suppose the input image **X** is a 6x6 matrix, and the filter **W** is a 3x3 matrix. The filter starts from the top-left corner of the input image, covering a 3x3 area. The corresponding elements are multiplied and summed to obtain the first element _y_ 11 of the output feature map **Y** . Then the filter slides one step to the right (stride=1), computing _y_ 12, and so on, until the entire image is scanned, generating a new feature map.

A comparison between fully connected layers and convolutional layers is shown in Figure2.5 (adapted from Figure 5.5 in Qiu Xipeng’s “Neural Networks and Deep Learning”).

The advantages brought by the characteristics of the convolutional structure are:

1. Local connectivity: Each neuron is only connected to a local region (receptive field) of the input, not to all of it. This significantly reduces the number of parameters.

2. Weight sharing: The same filter shares the same set of weights _wuv_ at different positions of the input. This means that whether the target appears in the top-left or bottom-right corner of the image, it is recognized by the same “feature detector,” which endows the model with translation invariance. Simultaneously, this further compresses the number of parameters.

3. Hierarchical feature extraction: A typical CNN consists of multiple convolutional layers, pooling layers (Pooling Layer, such as max pooling, used for downsampling and enhancing translation robustness), and fully connected layers (for final classification or regression) stacked alternately. Shallow convolutions learn low-level features like edges and corners; deep convolutions combine low-level features into more complex high-level features, such as object parts or wholes. This architecture has led to tremendous success for CNNs in fields like image and video analysis.

4. Trend towards fully convolutional: Modern advanced CNN architectures (like ResNet, DenseNet) tend towards “small convolution kernels, large depth,” and reduce or even eliminate fully connected layers, using operations like global average pooling, making the network more flexible to input sizes.

**Figure 2.5:** Convolutional Layer

CNNs are essentially function approximators with strong structural priors (locality and translation invariance). They impose powerful constraints on high-dimensional input spaces (like image pixel space), making the functions learned by the network possess specific symmetries. This “symmetry” can be understood as: if we translate the input image, the feature representation output by the network will also shift correspondingly without changing its intrinsic semantic information.

#### 2.3.5 Recurrent neural networks (RNN): Memory models for sequential data

Fully connected networks and convolutional networks primarily handle independent and identically distributed samples. However, for sequential data like time series, natural language, and speech, samples have sequential dependencies. Recurrent neural networks handle this dynamic temporal information by introducing a “memory” mechanism.

The core idea is: RNNs have “recurrent” connections, allowing the network to pass information from past time steps to the current time step. At each time step _t_ , the network receives the current input **x** _t_ and the hidden state from the previous time step **h** _t−_ 1, computing the current hidden state **h** _t_ and output **y** _t_ .

**==> picture [129 x 32] intentionally omitted <==**

where _f, g_ are activation functions. The hidden state **h** _t_ is considered the network’s “memory” at time _t_ , encapsulating all historical input information up to the current moment. The structure of a recurrent neural network is shown in Figure2.6 (adapted from Figure 6.2 in Qiu Xipeng’s “Neural Networks and Deep Learning”).

Similar to feedforward networks, RNNs also have their own universal approximation theorem: A fully connected recurrent network with a sufficient number of sigmoid-type neurons can approximate any nonlinear dynamical system to arbitrary accuracy. This theoretically guarantees that RNNs have the capacity to simulate complex temporal processes.

**Figure 2.6:** Recurrent Neural Network

Basic RNNs, when training on long sequences, are prone to gradient vanishing or explosion problems because error backpropagation through time involves multiple matrix multiplications, making it difficult to learn long-term dependencies. LSTM addresses this issue by introducing an ingenious “gating mechanism.” The core of an LSTM unit is the cell state **C** _t_ , which acts like a conveyor belt, maintaining information flow throughout the chain. LSTM regulates information through three “gates”:

   1. Forget gate **f** _t_ = _σ_ ( **W** _f ·_ [ **h** _t−_ 1 _,_ **x** _t_ ] + **b** _f_ ): Decides what information to discard from the cell state.

   2. Input gate **i** _t_ = _σ_ ( **W** _i ·_ [ **h** _t−_ 1 _,_ **x** _t_ ] + **b** _i_ ): Decides what new information will be stored in the cell state.

   3. Output gate **o** _t_ = _σ_ ( **W** _o ·_ [ **h** _t−_ 1 _,_ **x** _t_ ] + **b** _o_ ): Based on the current cell state, decides what information to output to the hidden state.

- The cell state update formula is: **C** _t_ = **f** _t ⊙_ **C** _t−_ 1 + **i** _t ⊙_ **C**[˜] _t_ , where **C**[˜] _t_ is the candidate new information.

The key to LSTM lies in additive updates: the cell state is updated via element-wise multiplication with the forget gate and element-wise addition with the input gate. This additive connection allows gradients to flow through the cell state path during backpropagation without easily vanishing (gradients can be directly passed through the additive path).

GRU is a simplified variant of LSTM, merging the forget gate and input gate into an “update gate,” resulting in a simpler structure with comparable performance. These gating mechanisms endow RNNs with the ability to remember long-term information and selectively forget or retain it.

RNNs and their variants (LSTM, GRU) are crucial in fields like machine translation, speech recognition, and text generation. In mathematics, they can be used for generating symbolic sequences (like mathematical expressions), time series forecasting, or as components of reinforcement learning agents (e.g., AlphaGo’s policy network included CNNs and RNNs to evaluate board positions).

#### 2.3.6 Learning algorithms: How to find the “right” network

The Universal Approximation Theorem tells us that theoretically, there exists a neural network that can solve our problem. But how do we find that high-performing network from the countless possible ones? This is precisely the task of learning algorithms. The training process of neural networks can be summarized into three core steps: forward propagation to compute predictions, backpropagation to compute parameter gradients, and parameter update to optimize network performance.

Step One: Forward Propagation and Loss Function—Defining “Good” and “Bad”

Before training begins, we first need a quantitative criterion to measure the discrepancy between the network’s output and the true target. This is the role of the loss function _L_ ( **y** _,_ ˆ **y** ). For different tasks, we choose different loss functions: mean squared error is commonly used for regression problems, while cross-entropy loss is typical for classification. Loss Function: Defining “Good” and “Bad”

Take a _C_ -class classification problem as an example. During forward propagation, the input sample **x** passes through the network layers sequentially. Finally, the last layer typically uses the Softmax function to transform the net input into a class probability distribution ˆ **y** = softmax( **z**[(] _[L]_[)] ). Subsequently, the cross-entropy loss computes the difference between the predicted distribution and the true label:

**==> picture [114 x 33] intentionally omitted <==**

where **y** is the true one-hot label vector.

Given a training set _D_ = _{_ ( **x**[(] _[n]_[)] _,_ **y**[(] _[n]_[)] ) _}[N] n_ =1[containing] _[ N]_[samples,][we typically minimize the empirical] risk, which is the average loss over all samples, possibly with an added regularization term (like weight decay 1 2 _[λ][∥]_ **[W]** _[∥] F_[2][) to prevent overfitting:]

**==> picture [206 x 33] intentionally omitted <==**

At this point, forward propagation has completed its mission: it not only generated the prediction **y** ˆ but also computed the loss value _R_ that measures network performance, and cached necessary intermediate variables for subsequent steps.

Step Two: Backpropagation Algorithm—The Efficient Engine for Computing Gradients

With the loss function _R_ , our goal is to find a set of parameters ( **W** _,_ **b** ) that minimize it. However, _R_ is a complex non-convex function with respect to all network parameters, making direct computation of gradients for each layer’s parameters extremely difficult.

The backpropagation algorithm is the key to solving this challenge. Its essence is the efficient implementation of the chain rule from calculus on deep composite functions. The algorithm starts from the output layer and propagates error signals backward layer by layer:

1. Compute error term: First, define the error term for layer _l_ as _**δ**_[(] _[l]_[)] = _∂∂_ **z** _L_[(] _[l]_[)][,][i.e.,][the gradient of the loss] function with respect to that layer’s net input.

2. Error backward recurrence: Using the chain rule, we obtain the recurrence formula for propagating the error term backward:

**==> picture [166 x 20] intentionally omitted <==**

where _⊙_ denotes element-wise multiplication. The intuitive meaning of this formula is: the error at the current layer depends on the derivative of the current layer’s activation function (local gradient) and the weighted combination of errors from the next layer.

3. Compute parameter gradients: Based on the error term _**δ**_[(] _[l]_[)] , the gradients for that layer’s parameters can be concisely computed:

**==> picture [175 x 25] intentionally omitted <==**

The brilliance of the backpropagation algorithm lies in the fact that through one forward pass and one backward pass, it efficiently computes the gradients for all parameters, with computational complexity comparable to forward propagation. This provides the crucial gradient information for subsequent parameter updates. Step Three: Parameter Update—Gradient Descent Drives Network Evolution

After obtaining the gradients, the final step is to use this gradient information to update the network parameters, thereby reducing the loss function value. The most commonly used optimization method is gradient descent and its various variants. Its core idea is simple yet profound: parameters are updated in the direction opposite to the gradient of the loss function (i.e., the direction of steepest descent).

**==> picture [226 x 24] intentionally omitted <==**

where _α >_ 0 is the learning rate, controlling the step size of parameter updates—too small steps lead to slow convergence, while too large steps may overshoot the optimum or even cause divergence.

In practical training, we typically do not compute gradients on all samples at once (batch gradient descent). Instead, we use mini-batch stochastic gradient descent (Mini-batch SGD): each time, a small batch of samples is randomly selected, their average gradient is computed, and parameters are updated. This strategy achieves a good balance between computational efficiency and convergence stability.

These three steps—forward propagation to compute loss, backpropagation to compute gradients, and parameter update to optimize the network—constitute the basic training loop for neural networks. This loop repeats, the loss value gradually decreases, network performance improves step by step, and eventually, the “right” network capable of solving the practical problem is found.

#### 2.3.7 Optimizers and challenges

Training deep neural networks not only requires understanding the basic gradient descent framework but also faces numerous core mathematical and engineering challenges. The continuous improvement of optimization algorithms is key to addressing these challenges and driving the development of deep learning.

Standard gradient descent (also known as batch gradient descent) requires computing the gradient using the entire training set at each step. When the dataset is massive, this approach is computationally expensive and unsuitable for online learning scenarios. Therefore, stochastic gradient descent (SGD) and its variant— mini-batch stochastic gradient descent (Mini-batch SGD)—are more commonly used in practice. The latter randomly samples a small batch of data each time to compute the gradient and update parameters. Although the introduced randomness brings some noise, it greatly improves iteration efficiency, and appropriate noise can even help escape local minima.

However, standard SGD still has room for improvement. To make the training process more intelligent and efficient, researchers have proposed various adaptive optimization algorithms.

1. SGD with Momentum

The momentum method simulates the concept of inertia in the physical world. When updating parameters, it not only considers the current gradient but also accumulates historical gradient directions, forming a “velocity” effect. The update rule is:

**==> picture [145 x 11] intentionally omitted <==**

where _β_ is the momentum decay coefficient (typically around 0.9). This mechanism helps accelerate convergence, reduce oscillations, and makes it easier for the network to traverse flat regions and saddle points, especially when the loss landscape contains narrow ravines.

2. Adam (Adaptive Moment Estimation)

   - Adam is currently one of the most popular optimizers (Kingma & Ba, 2015). It cleverly combines the advantages of momentum and adaptive learning rates. Adam maintains two state variables: an estimate of the first moment (mean) of the gradient _mt_ and an estimate of the second moment (uncentered variance) _vt_ :

**==> picture [254 x 13] intentionally omitted <==**

where _gt_ is the current gradient. Then, bias correction is applied to these moment estimates, and finally, parameters are updated:

**==> picture [109 x 26] intentionally omitted <==**

Adam can automatically adjust the learning rate for each parameter, is relatively robust to hyperparameter

   - choices, and performs excellently on numerous tasks in natural language processing, computer vision, etc., making it one of the preferred optimizers in deep learning practice.

3. Learning Rate Scheduling

   - Dynamically adjusting the learning rate _α_ is another important strategy. Common practices include: step decay (multiplying by a decay factor after a certain number of epochs), cosine annealing, or adaptive adjustment based on validation performance (e.g., reducing the learning rate when validation loss plateaus, known as ReduceLROnPlateau). Reasonable learning rate scheduling often leads to significant performance improvements.

Through the organic combination of these techniques, modern deep learning training can achieve a better balance between convergence speed, stability, and final performance.

Deep learning also faces several other important challenges in practical training:

- Non-convex optimization: The loss function of neural networks is a non-convex function in high-dimensional space, containing numerous local minima and saddle points. However, practice and some theoretical studies show that many local minima have similar loss values and may generalize well, and adaptive optimizers help escape certain saddle points.

- Vanishing and exploding gradients: In deep networks, the error signal _**δ**_[(] _[l]_[)] needs to be backpropagated through multiple layers of multiplication. If the norm of the gradient at each layer is less than 1, successive multiplication causes exponential decay of the gradient, i.e., vanishing gradients; conversely, if greater than 1, it may cause exponential growth, i.e., exploding gradients. This problem severely hinders the training of deep networks. Techniques such as ReLU activation functions, appropriate weight initialization (e.g., Xavier, He initialization), batch normalization, and residual connections (the core idea of ResNet) have proven effective in mitigating these issues.

- Hyperparameter tuning: The choice of hyperparameters like learning rate _α_ , network depth, width, regularization coefficient _λ_ , etc., greatly impacts model performance. Their optimization is itself a metaoptimization problem, typically addressed through methods like grid search, random search, or more advanced Bayesian optimization.

#### 2.3.8 A glimpse of neural network applications

Neural networks have many important applications. Here are a few landmark results:

Image Classification and Pattern Recognition: This is the most classic application scenario for convolutional neural networks (CNNs). From a mathematical perspective, image classification essentially learns a complex function mapping from a high-dimensional pixel space to a discrete class space. This capability is widely used for recognizing mathematical symbols, parsing charts, and even automatically mining potential patterns from scientific images (like astronomical observations, biological microscopy images), greatly enhancing the processing efficiency of scientific data.

AlphaGo and Reinforcement Learning: AlphaGo, proposed by DeepMind, combined CNNs (policy network and value network for evaluating board positions) with Monte Carlo tree search. Its success demonstrated that neural networks can approximate or even surpass human expert-level complex decision functions. From a mathematical perspective, this breakthrough inspired the modeling of mathematical problems like theorem proving and algorithm search as reinforcement learning problems. In this framework, neural networks act as agents, autonomously learning optimal solving strategies through interaction with the environment (like a prover or computational environment). Representative works include AlphaProof, AlphaTensor, and FunSearch.

Symbolic Regression and Equation Discovery: Works represented by AI Feynman and Ramanujan Machine use neural networks to fit data and then attempt to extract or induce concise, human-readable mathematical expressions from the trained network structure, such as physical laws or mathematical identities. These methods build a bridge between “black-box” models and symbolic mathematics, aiding in the automatic discovery of new scientific laws.

Construction of Combinatorial Objects: In combinatorics, many challenging problems require constructing extremal structures with specific properties, such as large graphs or special set families. Neural networks, especially generative models, can learn to generate candidate constructions that satisfy constraints, thereby providing mathematicians with new conjectures and research directions. Related research, such as “Constructions in combinatorics via neural networks,” demonstrates the potential in this direction.

Scientific Computing: Physics-Informed Neural Networks (PINNs) incorporate partial differential equations (PDEs) describing physical processes as regularization terms into the loss function. The network must satisfy the physical laws defined by the PDEs while fitting observational data. This makes PINNs a flexible, mesh-free, data-driven approach suitable for scientific computing tasks like forward PDE solving and parameter inversion.

Despite numerous successes, neural networks still face a series of profound challenges:

- Interpretability: The decision-making process of neural networks is often seen as a “black box,” making it difficult to provide human-understandable reasoning chains. How to make neural networks not only output predictions but also provide “proofs” or “explanations” that meet mathematical rigor is a core challenge in current neuro-symbolic methods research. Lack of interpretability limits their application in high-stakes fields like mathematical proof and medical diagnosis.

- Lack of Generalization Theory: Although deep neural networks exhibit strong generalization ability in practice, their theoretical foundation remains incomplete. Traditional statistical learning theory often provides generalization bounds that are too loose for over-parameterized deep models, failing to explain the observed success. Although there have been preliminary explorations, such as analyses of simplified models like linear networks or two-layer ReLU networks, and research on “implicit regularization” (gradient descent tends to converge to flat minima, which usually correspond to better generalization) and the “double descent” phenomenon, a unified, universal generalization theory for deep networks has not yet been established.

- Computational Cost: Training large neural networks requires massive computational resources and data, leading to high economic costs and raising concerns about environmental impact. High energy consumption and the concentration of hardware resources limit participation from some research groups and regions, making the accessibility of deep learning a non-negligible issue.

### 2.4 Introduction to reinforcement learning

The core idea of reinforcement learning is to allow an agent to learn how to take actions through trial and error during continuous interaction with an environment, in order to achieve long-term goals. It differs from supervised learning (which requires labeled data) and unsupervised learning (which seeks the intrinsic structure of data), as its learning signal comes from the environment’s feedback on the agent’s actions—rewards. **Basic Framework and Core Elements of Reinforcement Learning**

The interaction process of reinforcement learning can be abstracted as a loop: at time _t_ , the agent observes the environment state _st_ and selects an action _at_ to execute accordingly. After receiving the action, the environment transitions to a new state _st_ +1 and provides an immediate reward _rt_ . The agent’s ultimate goal is to maximize the total cumulative reward throughout the entire process. Figure 2.7 (cited from Qiu Xipeng’s “Neural Networks and Deep Learning” Figure 14.2) illustrates the interaction between the agent and the environment:

**Figure 2.7:** Schematic diagram of agent-environment interaction

This process is perfectly characterized mathematically by a Markov Decision Process (MDP). Figure 2.8 (cited from Qiu Xipeng’s “Neural Networks and Deep Learning” Figure 14.3) shows the graphical model representation of an MDP. Its quintuple ( _S, A, P, R, γ_ ) constitutes the fundamental elements of reinforcement learning.

**Figure 2.8:** Markov diagram

1. State Space (State Space, _S_ ): The set of all possible environmental situations. A state _s_ should contain all information necessary for decision-making (satisfying the Markov property). Example forms:

   - Board games (e.g., Go, Chess): The state can be the layout of all pieces on the entire board. Video games (e.g., Atari games): The state can be raw pixel images from several consecutive frames to capture dynamic information.

Robot control: The state can be the angles and angular velocities of the robot’s joints, as well as external environment information collected by sensors (e.g., cameras, LiDAR, IMU).

Recommendation systems: The state can include user profile features, historical click sequences, and current contextual information (e.g., time, device, location).

2. Action Space (Action Space, _A_ ): The set of all possible actions the agent can execute in a given state. Example forms:

   - Discrete action space: Actions are enumerable. For example: up, down, left, right in a maze game; placing a stone on one of the 361 intersections, passing in Go.

Continuous action space: Actions are real-valued vectors, typically used in scenarios requiring fine control. For example: steering wheel angle (continuous value), throttle and brake depth (continuous value) in autonomous driving; target torque or position increments for each joint motor in robotic arm control.

3. State Transition Probability (Transition Probability, _P_ ( _s[′] | s, a_ )): Defines the dynamic model of the environment. It represents the probability of the environment transitioning to state _s[′]_ after executing action _a_ in state _s_ .

Example forms:

In simple problems with known models (e.g., grid worlds), it can be an exact probability table. In most complex problems (e.g., real physical world, complex games), this transition model is unknown, complex, and stochastic. Reinforcement learning algorithms typically do not require prior knowledge of _P_ ; instead, they learn optimal behavior indirectly through sampled experiences ( _s, a, r, s[′]_ ) from interacting with the environment.

4. Reward Function (Reward Function, _R_ ( _s, a, s_ )): The immediate feedback signal provided by the environment to the agent. It is the fundamental driving force and design core in reinforcement learning. It quantifies the immediate goodness or badness of taking action _a_ in state _s_ resulting in a transition to state _s[′]_ .

The specific roles of the reward function are:

- Define the goal: The reward function essentially defines the task the agent needs to accomplish. All learning by the agent revolves around “maximizing cumulative reward,” so the design of the reward function directly determines what policy the agent ultimately learns.

- Guide learning: Through positive rewards (e.g., scoring, approaching a goal) and negative rewards (e.g., collision, losing points), it acts like a beacon, guiding the agent to explore beneficial behaviors and avoid harmful ones.

- Provide evaluation criteria: Value functions _V_ ( _s_ ) and _Q_ ( _s, a_ ) are both expectations of “future cumulative reward”; reward is the foundation of these evaluation functions.

Below, we illustrate the reward rules of reinforcement learning with several concrete examples.

For a maze navigation game: Reaching the goal gives +10 points; each step taken gives _−_ 0 _._ 1 points (encouraging finding the goal quickly); hitting a wall gives _−_ 1 point. The reward rule is as follows:

**==> picture [227 x 60] intentionally omitted <==**

For Go/Chess: Define winning as +1 point; losing as _−_ 1 point; draw or intermediate states as 0 points. This is a typical example of sparse reward, where most moves have no immediate feedback, and the agent must learn to plan long-term for the final outcome.

For autonomous driving: Safe driving within the lane gives +0 _._ 01 points; deviating from the lane gives

_−_ 0 _._ 1 points; comfort (smooth acceleration/braking) gives +0 _._ 001 points; emergency braking or collision gives _−_ 10 points.

For energy consumption management: Specify a fixed reward + for completing a specific task; energy consumed _−_ (energy consumption amount × coefficient).

5. Discount Factor (Discount Factor, _γ ∈_ [0 _,_ 1)): Used to calculate the present value of future rewards. A _γ_ closer to 0 makes the agent more “short-sighted,” focusing only on immediate rewards; closer to 1 makes the agent more “far-sighted,” considering long-term returns. Its role is to mathematically guarantee that the cumulative reward over infinite time steps is bounded; in practice, it helps balance immediate and future gains.

Under the definition of the above five elements, the agent’s core task is to learn a policy _π_ ( _a|s_ ), which is the rule for selecting actions in each state (can be a deterministic function or a probability distribution). Its goal is to maximize the expected cumulative discounted reward (also called return):

**==> picture [64 x 34] intentionally omitted <==**

To evaluate and find the optimal policy, two key value functions are introduced:

   - State-value function _V[π]_ ( _s_ ): The expected return starting from state _s_ under policy _π_ .

   - Action-value function _Q[π]_ ( _s, a_ ): The expected return after taking action _a_ in state _s_ under policy _π_ .

- The _Q[∗]_ function corresponding to the optimal policy _π[∗]_ satisfies the Bellman optimality equation, which provides the theoretical foundation for many algorithms.

#### 2.4.1 Major algorithm categories

1. Value-based methods (e.g., Q-learning, DQN): Idea: Instead of learning the policy directly, first learn the optimal value function _Q[∗]_ ( _s, a_ ). The optimal policy naturally becomes selecting the action that maximizes the _Q_ value: _π[∗]_ ( _s_ ) = arg max _a Q[∗]_ ( _s, a_ ). The idea is not to learn the policy directly, but to first learn to assess “which action is more valuable”—that is, to learn the optimal value function _Q[∗]_ ( _s, a_ ). The optimal policy is then: in each state, choose the action with the highest value. These methods are suitable for discrete action spaces and can efficiently reuse historical experience.

2. Policy gradient methods (e.g., REINFORCE): The idea is to directly parameterize the policy _πθ_ ( _a|s_ ) (e.g., using a neural network), compute the gradient of the expected return with respect to the policy parameters _θ_ , and use gradient ascent to optimize the policy. These methods are naturally suitable for continuous action spaces and can learn stochastic policies, but they often have high variance and less stable training.

3. Actor-Critic methods: This approach combines the above two. The “Actor” is the policy function, responsible for selecting actions based on the state; the “Critic” is the value function (e.g., _V_ ( _s_ ) or _Q_ ( _s, a_ )), responsible for evaluating the actor’s performance and guiding its updates. This method uses the lowvariance estimates provided by the critic to reduce the variance of the policy gradient, significantly improving learning efficiency and stability. This is the basic architecture of current mainstream reinforcement learning algorithms (e.g., A3C, PPO, SAC).

Reinforcement learning is a goal-oriented, interactive learning paradigm. Its basic principles revolve around the MDP quintuple. The agent learns a policy that maximizes long-term return through the reward signals obtained from interacting with the environment. The design of the reward function is crucial to the success or failure of the task; it acts like the designer’s “baton” and needs to precisely and carefully reflect the ultimate goal. From classic Q-learning to modern deep actor-critic algorithms, various methods are attempting to solve this core problem more efficiently and stably, achieving remarkable success in fields such as games, robotics, autonomous driving, and resource management.

### 2.5 Introduction to generative artificial intelligence

According to the type of task, machine learning can be divided into two major categories: discriminative artificial intelligence and generative artificial intelligence. The goal of discriminative artificial intelligence is to learn to “draw boundaries” between different data points and make judgments about unknown data. It answers the question “What is this?”. For example, training a model to distinguish between pictures of cats and dogs, the model learns “which combinations of pixel features are more likely to correspond to cats and which to dogs”, and establishes a decision boundary. When it sees a new picture, it judges which side of the boundary the picture falls on. Discriminative models care about the dividing line between categories, not the complete picture of the data itself. The goal of generative artificial intelligence is even more ambitious: to understand and imitate the essential structure and distribution of data. It learns how the training data is generated—that is, the underlying probability distribution. Then, it can sample from the learned distribution to create brand new instances that conform to the data patterns. If discriminative models answer “What is this?”, generative models answer “How to create this kind of thing”. By learning the patterns hidden in massive data, it can generate text, images, code, music, and even scientific hypotheses that did not originally exist but conform to the patterns of that data. The achievements of generative AI have flooded into our work and lives, with its impact spanning multiple fields:

1. Natural Language Processing:

   - Intelligent Dialogue and Creation: Dialogue models represented by ChatGPT and Claude can engage in deep Q&A, write articles, translate, program, etc.

   - Code Generation: Tools like GitHub Copilot can automatically generate, complete, or explain code based on comments or context, greatly improving development efficiency.

2. Visual and Multimedia Creation:

   - Text-to-Image/Video: Models like Midjourney, Stable Diffusion, and Sora can generate highly realistic or artistic images and dynamic videos based solely on a text description.

   - Design Assistance: Automatically generate product prototypes, marketing materials, interior design drawings, etc.

3. Science and Discovery:

   - Molecule and Material Design: For example, generating new drug molecules or battery material structures with specific properties, accelerating the R&D process.

   - Mathematics and Algorithm Discovery: Such as DeepMind’s AlphaEvolve, which directly improved a core computational task that had not been optimized for 50 years by generating new algorithms.

The leap of generative AI is primarily built upon breakthroughs in three major technical approaches.

#### 2.5.1 Generative adversarial networks: Evolving through gameplay

Generative Adversarial Networks (GANs) were proposed by Ian Goodfellow et al. in 2014. Their core idea

- is full of game theory wisdom: let two neural networks compete and co-evolve. Basic Architecture: A GAN consists of two roles:

   - Generator: An artist trying to “forge” data. It receives a random noise vector _z_ (usually sampled from a Gaussian or uniform distribution) and transforms it into a fake sample _G_ ( _z_ ), such as a fake image. The generator’s goal is to make the generated sample realistic enough to be undetectable.

   - Discriminator: An expert trying to “authenticate”. It receives real samples _x_ and fake samples _G_ ( _z_ ) produced by the generator, and judges whether each sample is real or fake. The discriminator’s output is a probability value _D_ ( _x_ ), indicating the confidence that the sample is real.

The process of a generative adversarial network is shown in Figure 2.9.

During adversarial training, the two networks compete in a zero-sum game:

- The generator continuously improves its forgery skills, trying to fool the discriminator into misclassifying fake samples as real.

- The discriminator continuously hones its discrimination ability, trying to expose the generator’s tricks.

**Figure 2.9:** Generative Adversarial Network

The entire training process can be formalized as a minimax game problem:

**==> picture [306 x 17] intentionally omitted <==**

where _p_ data is the real data distribution and _pz_ is the noise distribution. Intuitive understanding: the discriminator _D_ tries to maximize the log-likelihood of correctly classifying real and fake samples; the generator _G_ tries to minimize the probability that the discriminator correctly identifies fake samples (i.e., maximize the chance of the discriminator making a mistake).

Dynamic Training Balance: Ideally, this game will eventually reach a Nash equilibrium—the samples produced by the generator are indistinguishable from real data, and the discriminator’s judgment probability for any sample is close to 0.5 (completely uncertain about authenticity). At this point, the generator has learned the distribution of the real data.

However, the balance of this game is extremely delicate, and GAN training is therefore notorious for being unstable. The capabilities of the generator and discriminator need to grow synchronously—if the discriminator is too strong, it can easily expose all fake samples, causing the generator to stop learning due to ineffective gradients; if the generator is too strong, it may exploit certain weaknesses of the discriminator and only learn to generate a few types of samples that can fool the discriminator, a phenomenon known as mode collapse. Furthermore, when the discriminator is overconfident, its output gradients may approach zero, causing the generator to fall into the dilemma of vanishing gradients, making training unsustainable. Researchers have proposed numerous improvement schemes, such as WGAN, LSGAN, StyleGAN, etc., to alleviate these problems by improving loss functions, network architectures, and training strategies. Classic Application Examples:

- Face Generation: The StyleGAN series of models can generate realistic faces with resolutions up to 1024×1024. These faces do not exist in reality, but the richness of detail is astonishing. Users can control attributes such as age, pose, hairstyle, and expression of the generated results. Image Translation: The Pix2Pix model can transform sketches into realistic photos (e.g., converting edge maps into pictures of cats), or convert daytime maps into nighttime maps. CycleGAN goes further, achieving image style transfer without paired data—for example, transforming ordinary horse photos into zebras, or applying Monet’s painting style to any landscape photo.

Super-Resolution: Models like SRGAN can restore high-resolution details from low-resolution images, with important applications in fields such as medical imaging and satellite imagery.

Despite the challenges of unstable training, GANs remain a milestone in the field of image generation due to their unique adversarial learning paradigm and stunning generative results.

#### 2.5.2 Diffusion models: From chaos to order

Diffusion Models are a technical approach that has risen to prominence in recent years and have become the “ace” in the current field of image generation—mainstream text-to-image tools like Stable Diffusion, DALLE 2, and Midjourney are all based on this technology. Its inspiration comes from the diffusion process in nonequilibrium thermodynamics.

Its core idea is: Diffusion models consist of two opposite processes—the forward diffusion process and the reverse generative process.

Forward Diffusion Process: This process is fixed and non-trainable. We start with a real image _x_ 0 and gradually add small Gaussian noise to it. After _T_ steps, the original image is completely corrupted, becoming a pure noise image _xT ∼N_ (0 _, I_ ). This process can be seen as the progressive destruction of information, with the noise addition at each step following a fixed pattern:

**==> picture [177 x 14] intentionally omitted <==**

where _βt_ is a predefined noise schedule parameter that increases over time. A clever point is that, due to the additivity of Gaussian distributions, we can directly calculate the noisy result at any time step _t_ from _x_ 0 in one step:

**==> picture [182 x 13] intentionally omitted <==**

¯ _t_ where _αt_ = IT _s_ =1[(1] _[ −][β][s]_[)][.][This closed-form solution greatly simplifies the training process.]

Reverse Generative Process: This is the part the model actually learns—how to start from pure noise _xT_ , gradually denoise, and finally reconstruct a clear image _x_ 0. Each reverse step _pθ_ ( _xt−_ 1 _|xt_ ) is modeled as a Gaussian distribution, with its mean and variance predicted by a neural network:

**==> picture [195 x 12] intentionally omitted <==**

In practical implementations (such as DDPM, Denoising Diffusion Probabilistic Models), the model is usually trained to predict the noise _ϵ_ added to _x_ 0, rather than directly predicting the image itself. The training objective simplifies to:

**==> picture [148 x 14] intentionally omitted <==**

This means the model learns: given a noisy image _xt_ and time step _t_ , predict what noise was added at that time. After mastering this ability, during generation, the predicted noise can be gradually subtracted to rebuild order from chaos.

To extend diffusion models to text-to-image tasks, the basic diffusion model described above can only generate images unconditionally. To achieve “generating images based on text descriptions”, conditional control needs to be introduced. This is typically achieved through a cross-attention mechanism:

Use a text encoder (such as CLIP or T5) to convert the user’s input text description into a text embedding vector.

During the denoising process of the diffusion model, through cross-attention layers, let image features interact with text features, guiding the denoising process towards a direction that conforms to the text description.

Stable Diffusion further introduces the idea of Latent Diffusion Models: instead of performing diffusion directly in pixel space, first train an autoencoder to compress the image into a low-dimensional latent space, and then perform diffusion in the latent space. This significantly reduces computational costs while maintaining generation quality.

Example of the Generation Process: When a user inputs “a corgi in an astronaut suit” into Stable Diffusion, the model performs the following operations in sequence:

1. The text encoder converts this sentence into a vector representation.

2. The model starts from a random noise latent representation.

3. After dozens of iterative denoising steps, each step is guided by referencing the text vector.

4. The final latent representation is decoded by the decoder into a pixel image—a corgi wearing a miniature astronaut suit, with a serious expression, appears vividly on the page.

Compared to GANs, diffusion models train more stably, are less prone to mode collapse, and can generate more diverse results. Their step-by-step denoising process also gives users more control—they can intervene mid-generation, perform image inpainting, editing, and other operations. Of course, the trade-off is slower generation speed (requiring dozens to hundreds of iterative steps), but accelerated sampling methods proposed in recent years (such as DDIM, DPM-Solver) have significantly improved efficiency.

#### 2.5.3 Transformer architecture and large language models

This is the cornerstone of current generative AI (especially in the language field). Its core self-attention mechanism enables the model to process in parallel and deeply understand the complex relationships between all words in a text. By pre-training on terabytes of massive text, large language models acquire general knowledge and logic of language. Then, through alignment techniques like instruction fine-tuning, they are enabled to follow human instructions for creative work. The detailed principles of the Transformer architecture will be discussed in the next section, Introduction to Large Language Models, and will not be elaborated here.

Generative AI is evolving from a cool technology into a fundamental creative infrastructure. It is reshaping the ways of content creation, software development, and scientific research. Its core value lies in greatly unleashing human creativity, freeing us from repetitive labor, and allowing us to focus on higher-level strategic, aesthetic, and innovative decisions. With the deepening of multimodal integration (such as models that can simultaneously understand and generate text, images, and sound), an era of intelligent interaction driven by natural language has begun.

### 2.6 Introduction to large language models

To understand how large language models (LLMs) work, we need to approach it from two levels: first, the overall architecture of the model, examining how information flows in and out; second, its core mechanisms, understanding how the model comprehends language.

#### 2.6.1 The overall framework of large language models: Input, processing, output

At its core, a large language model is a neural network system that predicts the next word based on input text. Taking the GPT series of models as an example, its workflow can be summarized in three stages:

1. Input Processing: Converting text into vectors

   - Computers cannot directly understand text, so the first step is to convert the input text into a numerical representation. This process includes:

      - Tokenization: Splitting the text into smaller units (such as words or subwords). For example, “I like AI” might be tokenized into ‘[“I”, “like”, “AI”]‘, resulting in a token sequence of length _L_ .

      - Word Embedding: Mapping each token to a high-dimensional vector. Let the vocabulary size be _V_ and the embedding dimension be _d_ model. Then each token, based on its index, looks up its corresponding vector from an embedding matrix _E ∈_ R _[V][ ×][d]_[model] :

**==> picture [108 x 14] intentionally omitted <==**

These vectors carry semantic information about the words—words with similar meanings are close to each other in the vector space.

- Positional Encoding: Since the self-attention mechanism itself is order-insensitive, additional positional information needs to be injected. For position _i_ , its positional encoding **p** _i_ is added to the word embedding:

**==> picture [67 x 16] intentionally omitted <==**

The positional encoding can be a fixed sine/cosine function (as in the original Transformer):

**==> picture [326 x 24] intentionally omitted <==**

or it can be a learnable parameter. Finally, we obtain the input representation matrix _H_[(0)] _∈_ R _[L][×][d]_[model] .

2. Core Processing: Feature extraction through multiple Transformer blocks

   - This is the “brain” of the large language model. The input vector sequence passes sequentially through dozens or even hundreds of identical processing modules—Transformer blocks. Each block performs a “global information fusion and local feature transformation” on the sequence, allowing the representation at each position to continuously absorb contextual information.

3. Output Generation: Predicting the next word

After multi-layer processing, the model outputs a high-dimensional representation for each position. For the output **h**[(] _L[N]_[)] at the last position, the model transforms it into a probability distribution over all words in the vocabulary via a linear transformation and a Softmax function:

**==> picture [229 x 34] intentionally omitted <==**

where **w** _v ∈_ R _[d]_[model] is the output weight vector for word _v_ (often shared with the input embedding matrix). The model selects the word with the highest probability (or samples according to the probability) as the prediction result. For example, given the input “I like”, the model might predict the next word as “AI” (probability 0.3), “eat” (probability 0.2), “study” (probability 0.1), etc.

This “input-processing-output” cycle constitutes the basic way large models generate text: predict a word, append the new word to the input, predict the next, and so on, until a complete sentence is generated.

#### 2.6.2 Core mechanism: Attention—teaching the model to “focus on what matters”

In the above process, the most critical question is: when processing each word, how does the model know which parts of the context it should focus on? This is precisely the problem the attention mechanism solves.

**Origin of the Idea: Allocating Attention Like Humans**

When we read the sentence “The cat in the detention center chases its own tail,” to understand what “its” refers to, we need to look back to find “cat”—this is the naive form of attention. The attention mechanism is designed to give the model this ability of “selective focus”: when processing the current position, it dynamically decides which words in the context are more important and fuses their information.

Mathematically, the attention mechanism is a dynamic weighted average. It involves three basic roles: Query (Q): Represents the current focus point, equivalent to asking “Where should I look now?” Key (K): Represents the identifier for each context word, equivalent to “Who am I”

Value (V): Represents the actual content of each context word, equivalent to “What information do I have” Given a query vector **q** _∈_ R _[d][k]_ and a set of key-value pairs _{_ ( **k** _i,_ **v** _i_ ) _}[L] i_ =1[,][where] **[k]** _[i][∈]_[R] _[d][k][,]_ **[ v]** _[i][∈]_[R] _[d][v]_[,][the] attention output is:

**==> picture [137 x 33] intentionally omitted <==**

where the weight _αi_ is calculated from the similarity between the query and the key and normalized via softmax:

**==> picture [116 x 30] intentionally omitted <==**

The similarity function _s_ ( _·, ·_ ) is most commonly the scaled dot product:

**==> picture [68 x 28] intentionally omitted <==**

Here, _[√] dk_ is the scaling factor, used to prevent the dot product from becoming too large when the vector dimension is high, which could cause the softmax to enter a region with extremely small gradients.

In practical implementation, we compute attention for all positions in the entire sequence simultaneously, which can be written in matrix form:

**==> picture [191 x 28] intentionally omitted <==**

where _Q ∈_ R _[L][×][d][k] , K ∈_ R _[L][×][d][k] , V ∈_ R _[L][×][d][v]_ , and softmax is applied row-wise.

The weight _αi_ intuitively reflects the degree of attention the current query pays to the _i_ -th piece of information. Through learnable linear transformations, the model can dynamically generate _Q, K, V_ vectors from the input sequence. This means that at every position when generating a sequence, the model can flexibly “look back” and focus on the most relevant content—this is the essence of the attention mechanism.

The computational process of the attention mechanism is shown in Figure 2.10 (cited from Qiu Xipeng’s “Neural Networks and Deep Learning” Figure 8.4).

##### 2.6.2.1 Self-attention

In large language models, we use a special form—Self-Attention. The “self” here means that the queries, keys, and values all come from different linear transformations of the same input sequence. Let the input matrix be _X ∈_ R _[L][×][d]_[model] . We project it into query, key, and value spaces using three learnable weight matrices _W[Q] , W[K] , W[V] ∈_ R _[d]_[model] _[×][d][k]_ :

**==> picture [189 x 14] intentionally omitted <==**

Then we compute self-attention:

**==> picture [181 x 29] intentionally omitted <==**

The ingenuity of this design lies in the fact that every word in the sequence is both a “questioner” (issuing queries) and a “respondent” (providing keys and values). Regardless of how far apart two words are in the sentence, self-attention allows them to establish a direct connection. In traditional models (like RNNs), the influence of “cat” on “its” needs to pass through multiple time steps, causing information to easily decay; whereas in self-attention, this influence is direct in one step, fundamentally solving the long-range dependency problem.

**Figure 2.10:** Attention computation process

##### 2.6.2.2 Multi-head attention: Understanding language from multiple perspectives

Instead of computing only one set of attention, it’s better to let the model observe from multiple angles simultaneously. Multi-Head Attention projects the queries, keys, and values into _h_ different low-dimensional subspaces (each head has dimension _dk_ = _d_ model _/h_ ), computes attention independently on each head, and then concatenates the outputs of all heads and projects them again:

**==> picture [209 x 34] intentionally omitted <==**

where _Wi[Q][, W][ K] i[, W][ V] i ∈_ R _[d]_[model] _[×][d][k]_ , and _W[O] ∈_ R _[hd][v][×][d]_[model] are all learnable projection matrices.

This is akin to having multiple “experts” read the same text simultaneously: one expert focuses on grammatical relationships (subject-verb-object), another on referential relationships (who refers to whom), and another on semantic associations (synonyms). The multi-head mechanism allows the model to capture different types of relationships in parallel, greatly enhancing its expressive power.

##### 2.6.2.3 Structure of a transformer block

Combining the above components yields a standard Transformer encoder layer (or Transformer block). Its structure is as follows:

- Multi-Head Self-Attention Layer: Computes the interrelationships among all positions in the sequence, allowing each position to aggregate information from other positions.

- First Residual Connection and Layer Normalization: Adds the input of the self-attention layer to its output (residual connection), then performs layer normalization. The residual connection provides a “highway” for gradients, greatly alleviating the vanishing gradient problem in deep networks; layer normalization stabilizes the training process.

- Feed-Forward Network: A simple two-layer fully connected network that independently transforms the representation at each position. This step introduces non-linearity and enhances the expressive power of each position.

Second Residual Connection and Layer Normalization: Applies residual connection and layer normalization again, completing the processing of the entire block.

By stacking multiple such Transformer blocks, the model can build increasingly abstract representations layer by layer—lower layers may focus on lexicons and phrases, middle layers on syntactic structures, and higher layers may capture semantics and discourse relationships.

The Transformer network architecture is shown in Figure 2.11 (cited from [Vaswanietal.,2017]):

**Figure 2.11:** Transformer network architecture

After understanding the above mechanisms, we can see why the Transformer architecture has become the ideal framework for processing large-scale sequential data (such as natural language, code, mathematical symbol sequences):

- Parallel Computation: Self-attention can compute relationships among all positions at once, unlike RNNs which must process sequentially. This makes large-scale training possible.

- Long-Range Dependencies: Any two positions can interact directly, regardless of distance, without information decay.

- Hierarchical Understanding: Through multi-layer stacking, the model can build a deep understanding of language from local phrases to global semantics, layer by layer.

- Scalability: The architectural design of the Transformer is naturally suited to stacking more layers, using more heads, and processing longer sequences—this is the embodiment of the “large” in “large language models”.

It is these advantages that enable Transformer-based large language models to learn the patterns of language from massive amounts of text and demonstrate astonishing capabilities in tasks such as understanding, generation, and reasoning.

#### 2.6.3 Training mechanisms and process of large language models

With the powerful Transformer architecture in place, the next core question emerges: How can we, through an engineered training process, endow the model with language understanding, logical reasoning, and even mathematical capabilities? The training of modern large language models is not a single stage but a meticulously designed multi-stage pipeline. Each stage has a different mission, collectively shaping the final, highly capable model.

1. Pretraining: Building the Foundation of Language and Knowledge

Pretraining is the most resource-intensive and data-heavy stage of the entire training process. Its goal is to lay a solid foundation of language and broad world knowledge for the model. This stage belongs to selfsupervised learning—the supervision signal does not come from manual annotation but is automatically generated from the structure of the data itself.

Data Format: Large-scale, diverse text corpora are used, including web pages, books, academic papers, code repositories, social media, etc. After tokenization, the data forms continuous token sequences as input to the model. This data requires no manual labeling.

Training Objective: Depending on the model architecture, there are two main paradigms for pretraining objectives:

- Masked Language Modeling (MLM): Encoder models like BERT[Devlin J, Chang M W, Lee K, et al. BERT] adopt this strategy. The specific method is to randomly mask a portion of tokens in the input sequence (typically 15%) and then train the model to predict the original masked tokens. This is similar to a “cloze” task, enabling the model to understand bidirectional context information. The labels here— the masked tokens—are extracted from the input sequence itself.

- Next Token Prediction: Autoregressive decoder models like GPT adopt this strategy. Given a preceding token sequence, the model is trained to predict the next most likely token. This is similar to a “word chain” game, giving the model inherent text generation capability. The labels here—the actual next token in the sequence—also come from the data itself. Due to the universality of generation tasks, this paradigm has become the mainstream for pretraining current large language models.

- Mathematically, for a sequence **x** = ( _x_ 1 _, x_ 2 _, ..., xT_ ) of length _T_ , the training objective of an autoregressive

language model is to maximize the following likelihood:

**==> picture [137 x 33] intentionally omitted <==**

where _θ_ represents the model parameters, and _P_ ( _xt|x_ 1: _t−_ 1; _θ_ ) is the conditional probability predicted by the model at the _t_ -th position. Note that the supervision signal _xt_ here is precisely part of the input sequence itself—this is the core characteristic of self-supervised learning.

Pretraining such large-scale models requires a series of sophisticated engineering techniques:

- Large-Scale Distributed Training: When model parameters reach hundreds of billions and training data reaches trillions of tokens, the memory and computational power of a single GPU are far from sufficient. Complex parallelization strategies must be employed to distribute computation across thousands of GPUs:

   - Data Parallelism: Splits the training data across multiple devices, each holding a complete copy of the model, with periodic gradient synchronization.

   - Tensor Parallelism: Splits the weight matrix of a single layer across multiple devices, collaboratively performing matrix operations.

   - Pipeline Parallelism: Assigns different layers to different devices, forming a computational pipeline that processes multiple micro-batches simultaneously.

   - Mixed Precision Training: Using FP16 (half-precision) or BF16 floating-point formats for forward and backward propagation can significantly save GPU memory and accelerate computation. Meanwhile, parameters and optimizer states are kept in FP32 format in the master copy to ensure numerical stability. This is combined with dynamic loss scaling to avoid gradient underflow in half-precision.

   - Activation Checkpointing: During backpropagation, all intermediate activations are typically saved for gradient computation, occupying a large amount of memory. Activation checkpointing selectively saves some activations and recomputes the rest when needed, trading time for space, which is particularly effective when memory is limited.

2. Supervised Fine-Tuning (SFT): Aligning Instructions and Output Formats

Although pretrained models have acquired rich knowledge, they may not follow human instructions well or output specific formats. The Supervised Fine-Tuning (SFT) stage uses high-quality labeled data to fine-tune the model, aligning its behavior with human expectations. Unlike pretraining, this stage belongs to standard supervised learning—each training sample has a clear, manually annotated target.

Data Format: Uses carefully crafted human-written “instruction-output” pair datasets. For example, in the mathematics domain, the data format might be:

- Instruction example: Solve the equation _x_[2] _−_ 5 _x_ + 6 = 0

- Output example: Factoring gives ( _x −_ 2)( _x −_ 3) = 0, so the solutions are _x_ = 2 or _x_ = 3.

SFT requires extremely high data quality, covering diverse task types, and outputs should include correct reasoning steps. Datasets typically contain tens of thousands to hundreds of thousands of such examples.

Supervised fine-tuning is a standard supervised learning process. The instruction and desired output are concatenated as input, and the model is trained to generate the target sequence in the output part. The loss function is still the next token prediction loss, but typically only the loss on the output part is computed to avoid meaningless modeling of the instruction part.

Mathematically, for an instruction _x_ and target output _y_ , the loss function is:

**==> picture [171 x 34] intentionally omitted <==**

Engineering techniques include:

- Parameter-Efficient Fine-Tuning (PEFT): Large models have enormous parameters; fully fine-tuning all parameters is costly and prone to overfitting. LoRA (Low-Rank Adaptation) is currently the most widely used technique. Its core idea is to assume that the weight update ∆ _W_ has a low-rank property. Therefore, the original weights _W_ 0 are frozen, and two much smaller trainable matrices _A_ and _B_ are introduced, such that ∆ _W_ = _BA_ , and the updated weight is _W_ = _W_ 0 + _BA_ . During fine-tuning, only _A_ and _B_ are updated, reducing trainable parameters to one ten-thousandth or even less of the original, greatly lowering memory usage and overfitting risk.

- High-Quality Data Construction: The quality of SFT data directly determines the upper limit of finetuning effectiveness. Besides manual writing, the following strategies can be employed:

   - Model-Assisted Construction: Use stronger base models to generate candidate answers, which are then screened and corrected by experts.

   - Mining Community Resources: Collect and organize from high-quality resources like math competition solutions, technical Q&A communities, etc.

   - Data Augmentation: Expand the dataset through rewriting, translation, etc., to increase diversity.

3. Reinforcement Learning (RL): Optimization Based on Feedback

After SFT, the model can follow instructions, but output quality can still be improved—such as correctness, conciseness, safety, alignment with human preferences, etc. The Reinforcement Learning (RL) stage introduces a reward signal to further optimize the model, making its outputs better align with higher-order goals. This is a key stage for enhancing the model’s mathematical reasoning ability and aligning with human values. Before delving into specific techniques, let’s review the basic framework of reinforcement learning. In the language model scenario:

- Agent: The language model itself, whose policy _πθ_ ( _a|s_ ) is the probability distribution of choosing the next token _a_ given the context _s_ (the sequence of tokens generated so far).

- Environment: The interactive process of text generation, including the user’s input prompt and the autoregressive generation environment of the model.

- State: The current text context, i.e., all tokens generated so far.

- Action: Choosing the next token.

- Reward: A quality score calculated based on the complete generated sequence, provided by an external evaluation mechanism.

The goal is to optimize the policy parameters _θ_ to maximize the expected cumulative reward:

**==> picture [93 x 12] intentionally omitted <==**

where _τ_ = ( _s_ 0 _, a_ 0 _, s_ 1 _, a_ 1 _, ..._ ) is a complete text generation trajectory, and _R_ ( _τ_ ) is the total reward obtained for that trajectory.

Below are several typical reinforcement learning methods for large models:

##### 2.6.3.1 Reinforcement learning from human feedback (RLHF)

RLHF is the core alignment technology used by models like ChatGPT. It incorporates human preferences into the optimization objective, making model outputs more aligned with human values. RLHF typically consists of three steps:

1. Collect Human Preference Data: Given a prompt, the initial model after SFT generates multiple different answers. Human annotators rank these answers (which is better, which is worse). This process produces a large number of preference pairs ( _x, yw, yl_ ), where _x_ is the prompt, _yw_ is the preferred response, and _yl_ is the less preferred response.

2. Train a Reward Model (RM): Use the collected preference pairs to train an independent reward model _rφ_ ( _y|x_ ), teaching it to assign higher scores to text outputs that better align with human preferences. Preference modeling typically uses the Bradley-Terry model:

**==> picture [183 x 13] intentionally omitted <==**

where _σ_ is the sigmoid function. The training objective of the reward model is to maximize this likelihood probability:

**==> picture [230 x 13] intentionally omitted <==**

After training, the reward model can provide a scalar score for any text output, reflecting its degree of alignment with human preferences.

3. Use Reinforcement Learning to Optimize the Policy Model: Freeze the trained reward model _rφ_ and use the SFT-finetuned policy model _π_ SFT as the starting point for fine-tuning. Given a prompt _x_ , the policy model _πθ_ generates a response _y_ and receives a reward _rφ_ ( _y|x_ ) from the reward model. Simultaneously, to prevent the policy model from deviating too much from the initial _π_ SFT (to avoid losing language capability or producing meaningless output), a KL divergence penalty term is added to the reward. Therefore, the total reward is:

**==> picture [211 x 12] intentionally omitted <==**

where _β_ is a penalty coefficient controlling the degree of deviation. The KL divergence term is calculated as:

**==> picture [179 x 27] intentionally omitted <==**

Then, policy gradient algorithms are used to optimize the policy model _πθ_ to maximize the expected reward _J_ ( _θ_ ). Proximal Policy Optimization (PPO) is currently the most commonly used algorithm. It achieves stable and efficient policy updates by introducing importance sampling and a clipping mechanism.

##### 2.6.3.2 Direct preference optimization (DPO)

The RLHF process is complex, requiring training a separate reward model and using reinforcement learning algorithms, which can be unstable and involve many hyperparameters. Direct Preference Optimization (DPO) provides a more concise alternative, bypassing explicit reward model modeling and directly using human preference data to optimize the policy.

The core insight of DPO is: Under the Bradley-Terry preference model, there exists a closed-form analytical relationship between the optimal policy _π[∗]_ , the reward function _r[∗]_ , and the reference policy _π_ ref:

**==> picture [177 x 27] intentionally omitted <==**

where _Z_ ( _x_ ) is the partition function, independent of _y_ . Substituting this expression into the preference probability formula, a loss function directly based on the policy _πθ_ can be derived:

**==> picture [311 x 27] intentionally omitted <==**

Here, _π_ ref is typically the initial model after SFT. Optimizing this loss function directly drives the policy model to assign higher likelihood (relative to _π_ ref) to the preferred response _yw_ and lower likelihood to the dispreferred response _yl_ . DPO eliminates the need for reward model training and the complex reinforcement learning loop, making implementation simpler and training more stable. It has become a popular alternative to RLHF, achieving comparable or even better results on many tasks.

##### 2.6.3.3 Group relative policy optimization (GRPO) and reinforcement learning for mathematical reasoning

In tasks such as mathematical reasoning, answer quality often lies on a spectrum rather than a simple binary of correct or incorrect. This raises the question of how to effectively use diverse candidate answers to guide model learning. Group Relative Policy Optimization (GRPO) addresses this by modeling the relative quality of different candidate answers under the same input.

The core idea of GRPO is that it does not rely on binary preferences, but instead optimizes based on the relative quality within a group of answers. For the same mathematical problem, the model generates or collects multiple candidate answers, which can be grouped according to criteria such as correctness, completeness of reasoning steps, and conciseness.

For a given problem _x_ , the model generates a set of candidate outputs _{y_ 1 _, y_ 2 _, . . . , yn}_ . Each candidate answer is assigned a quality score _r_ ( _x, yi_ ), for example using a reward model or rule-based evaluation. GRPO does not directly optimize these absolute reward values; instead, it focuses on their relative relationships within the same group.

To this end, we define the _relative advantage_ of each candidate as the difference between its reward and the group mean:

**==> picture [161 x 33] intentionally omitted <==**

This quantity captures how a particular answer compares to others in the same group. If an answer has a score above the average, its advantage is positive; otherwise, it is negative.

Based on this formulation, the optimization objective of GRPO can be written as:

**==> picture [145 x 14] intentionally omitted <==**

Intuitively, this objective increases the probability of answers that are better than the group average, and decreases the probability of those that are worse. In this way, the model gradually learns to prefer higher-quality outputs for the same problem.

From a higher-level perspective, the key idea of GRPO is to replace absolute evaluation with relative comparison. This design has several advantages. First, it reduces dependence on the exact scale of the reward function, making training more robust to reward magnitudes. Second, by comparing answers within the same input, it helps reduce variance and improves training stability. In addition, it naturally leverages ranking information rather than relying only on binary labels, which is particularly useful in tasks such as mathematical reasoning and code generation.

Therefore, GRPO can be understood as a policy optimization method based on within-group relative ranking. By reinforcing the principle that better answers should be more likely to be generated, it guides the model toward more reliable generation behavior.

GRPO is well-suited for mathematical reasoning because:

- Learning _why an answer is wrong_ is as important as learning _how to obtain the correct answer_

- Answer quality often exists at multiple levels, and binary preferences cannot fully capture this information

e Between-group comparison encourages the model to learn more robust and efficient reasoning patterns The idea of GRPO can be flexibly combined with methods such as DPO or reward model-based approaches. For example, a calibrated reward model can be used to score each answer, after which answers are dynamically grouped based on their scores, followed by group-based comparative optimization.

In summary, the training of modern large language models is a multi-stage, progressive process, with three learning paradigms each playing its role. These three stages build upon each other, each with its own focus, collectively shaping the final large language model. Pretraining provides breadth and depth, supervised fine-tuning provides format alignment, and reinforcement learning provides value alignment and fine-grained optimization. It is this meticulously designed training pipeline that enables models to demonstrate near-human-level capabilities in complex tasks such as mathematical reasoning, code generation, and conversational interaction.

**Table 2.1:** Three Reinforcement Learning Paradigms

|**Stage**|**Learning Paradigm**|**Source of Supervision**|**Core Objective**|
|---|---|---|---|
|||**Signal**||
|Pretraining|Self-Supervised Learning|Structure of the data itself|Learn language patterns|
||||and world knowledge, es-|
||||tablish foundational capa-|
||||bilities|
|Supervised Fine-Tuning|Supervised Learning|Annotations|Teach the model to fol-|
||||low instructions and out-|
||||put formats|
|Reinforcement Learning|Reinforcement Learning|Reward signal|Optimize output quality,|
||||align with human prefer-|
||||ences and values|



### 2.7 Engineering techniques

The core idea of machine learning engineering practice can be summarized as “control and guidance”— through a series of carefully designed technical means, control the inherent uncertainty of the optimization process and guide the model parameters to converge to regions with good generalization performance. This is far from a simple accumulation of technical details; it is a profound understanding and comprehensive application of optimization dynamics, generalization theory, and computational resource management.

The final performance of a model depends not only on the algorithm itself but also on the meticulous design and coordinated cooperation of every link in the engineering practice. This section will delve into the key engineering aspects of the machine learning pipeline—data preparation, model initialization, training optimization, and regularization—revealing the mathematical intuition and design principles behind them.

#### 2.7.1 Data preparation: The foundation of model learning

Machine learning models “learn” patterns from data; therefore, the quality, scale, and diversity of the data directly determine the upper limit of model performance. As the computer science adage goes, “Garbage In, Garbage Out.” No matter how sophisticated the algorithm, if the input data is flawed, the model ultimately cannot learn correct knowledge.

##### 2.7.1.1 Data collection: Building a high-quality data source

In machine learning for mathematical tasks, data sources exhibit rich diversity, each with its unique value and challenges.

Symbolic data is the most direct carrier of mathematical knowledge, typically extracted from structured mathematical databases. For example, the On-Line Encyclopedia of Integer Sequences (OEIS) contains hundreds of thousands of integer sequences and their mathematical properties; arXiv’s mathematical papers, textbooks, and theorem-proof documents contain vast amounts of formulas, theorems, and proof steps. The characteristics of such data are clear structure and precise semantics, but they often require complex parsing techniques to restore them from PDF or LaTeX source code into usable structured forms.

Generated data is automatically synthesized according to specific mathematical rules or constraints and plays an increasingly important role in mathematical reasoning tasks. For instance, we can design a random polynomial generator to produce quadratic equations like _ax_[2] + _bx_ + _c_ = 0 and automatically compute their discriminants and roots; or generate adjacency matrices of specific graph structures and their corresponding graph-theoretic properties (such as diameter, chromatic number). The advantages of generated data are scalability, naturally existing labels, and precise control over the coverage of the data distribution. However, generation rules must be carefully designed to avoid producing “pseudo-data” that contradicts real mathematical patterns.

Simulation data is common in machine learning for solving scientific and engineering problems, especially tasks involving differential equations and physical simulations. For example, when solving partial differential equations, we can sample points on the computational domain grid and obtain approximate solutions of the equation through numerical solvers, forming “input-output” pairs. The quality of simulation data depends on the accuracy of the numerical method and the rationality of the sampling strategy. 2. Data Cleaning: Stripping Noise, Preserving Essence

Collected raw data is often “dirty,” especially when sourced from the internet. The goal of data cleaning is to reduce noise in the data, allowing the model to focus on genuine mathematical patterns. For mathematical text, cleaning involves multiple levels:

First is format normalization. Mathematical expressions have multiple representation forms; for example, the multiplication symbol might be “×”, “·”, or “*”, which need to be unified into a standard form; commands in LaTeX source code like “ `\frac{a}{b}` ” need to be correctly parsed into structured fraction representations. Second is noise filtering. Mathematical content crawled from the internet is often mixed with advertisements, navigation bars, irrelevant comments, and other interference, requiring heuristic rules or trained classifiers to filter them out. For scanned literature, errors from Optical Character Recognition (OCR) also need correction— for instance, misidentifying “ _x_[2] ” as “ _x_ 2” is a common problem that requires correction based on context or mathematical grammar.

In the training of large language models, data cleaning is even more massive and crucial. Taking the training of a model with hundreds of billions of parameters as an example, the training data volume typically reaches trillions of tokens. The cleaning process involves deduplication (removing highly similar documents), toxic content filtering, privacy information desensitization, format standardization, and other steps. This process requires designing efficient distributed processing pipelines to ensure data quality while controlling computational costs. 3. Data Representation: Bridging the Mathematical World and Neural Networks

Data representation is the key step of transforming raw mathematical objects into forms processable by models (usually numerical vectors or tensors), and it is also a core challenge in AI for Math. A good representation should preserve the essential structure of mathematical objects while being convenient for neural network processing.

Text and symbolic representation is the most common approach. For mathematical expressions, such as a first-order logic formula _∀x∃y_ ( _x_ + _y_ = 0), we first tokenize it into a discrete token sequence: ‘[“ _∀_ ”, “x”, “ _∃_ ”, “y”, “(”, “x”, “+”, “y”, “=”, “0”, “)”]‘. This requires the tokenizer to understand the grammatical roles of mathematical symbols—for example, distinguishing “x” as a variable from “×” as a multiplication symbol. Current large language models widely adopt subword tokenization algorithms, such as Byte-Pair Encoding (BPE), which can discover frequently occurring subword units from a statistical perspective, effectively handling combinations of rare words and mathematical symbols. The tokenized sequence is then mapped to dense vectors through an embedding layer, where each token is represented as a high-dimensional vector, and semantically similar tokens are close to each other in the vector space.

Graph and combinatorial structure representation is a common way to handle discrete mathematical objects. A graph can be represented by an adjacency matrix, where element _Aij_ = 1 indicates node _i_ is connected to node _j_ , otherwise 0. For weighted graphs, the elements of the adjacency matrix can be real-valued weights. For polyhedra or more complex topological spaces, their combinatorial structure can also be described by similar 0-1 matrices—for example, the face-edge incidence matrix of a polyhedron. The emerging Graph Neural Networks (GNNs) in recent years are specifically designed to handle such structures, learning vector representations for nodes, edges, and even entire graphs through message passing and neighbor aggregation on graphs.

Representation of abstract algebraic structures is more difficult, requiring deep mathematical knowledge to design. For an abstract group, we cannot directly input it into a neural network, but we can compute its numerical invariants—for example, the distribution of element orders, the number of conjugacy classes, the character table, etc., and form these numerical values into a feature vector. For a manifold, we can compute its topological invariants—such as Betti numbers (the ranks of homology groups in various dimensions), homotopy groups, curvature integrals, etc. Another approach is to use coefficients of function spaces on the manifold as representations, such as expansion coefficients of eigenfunctions (harmonic functions) of the Laplace operator on the manifold. The core requirement of these representations is to maintain invariance under transformations— for example, regardless of how we relabel the elements of a group, the representation should remain unchanged. 4. Data Augmentation: Creating Infinite Possibilities from Limited Data

When real data is scarce, data augmentation artificially expands the dataset by applying reasonable transformations to existing data to improve model robustness and generalization ability. Its mathematical essence is to apply a transformation that preserves invariance to the input space without changing the “semantics” of the data labels.

In scenarios where real data is scarce, data augmentation artificially expands the dataset by applying reasonable transformations to existing data to improve model robustness and generalization ability. Its mathematical essence is: without changing the “semantics” of the data labels, apply a transformation to the input space that preserves invariance.

In the field of computer vision, data augmentation is already mature—rotating, flipping, cropping, or adding noise to images, these transformations do not change the image category (a cat rotated is still a cat). In mathematical tasks, data augmentation can also play an important role, with its core being the utilization of symmetry, invariance, and equivalence relations of mathematical objects.

Variable substitution and scaling are the most intuitive augmentation methods. In algebraic expressions, systematically replacing variable names—for example, replacing all _x, y_ in the equation _x_[2] + _y_ = 1 with _a, b_ —keeps the solution set structure unchanged. Multiplying both sides of an equation by a non-zero constant simultaneously, or performing linear combinations on a system of equations, can also generate new equivalent forms. This utilizes the isomorphic relationship of mathematical objects—variable names are just labels; the real mathematical structure lies in the interactions between variables.

Rewriting into equivalent forms utilizes mathematical identities for transformation. For example, rewriting the expression log( _ab_ ) as log _a_ + log _b_ (within the domain), or rewriting sin[2] _x_ + cos[2] _x_ as 1. This type of augmentation teaches the model to focus on the equivalence class of expressions rather than specific syntactic forms, helping the model learn algebraic rules of mathematical operations.

Logical transformations are particularly useful in theorem proving and logical reasoning tasks. Given a theorem “if _A_ then _B_ ”, we can generate its contrapositive “if not _B_ then not _A_ ” as new data; for the equivalence relation “ _A_ if and only if _B_ ”, we can generate four directional implication relationships. This type of augmentation helps the model understand the symmetry of logical structures.

Parameter perturbation is effective in numerical computation and geometric problems. For geometry problems, we can randomly change the dimensions (such as side lengths of a triangle) or angles within a reasonable range while keeping the geometric relationships of the problem unchanged; for algebraic calculation problems, we can perturb equation coefficients within the range allowed by numerical stability to generate new instances.

This forces the model to learn the structural features of the problem rather than specific numerical coincidences.

Data augmentation is an effective, low-cost means of injecting mathematical knowledge (such as symmetry, invariance, equivalence relations), which can significantly improve the model’s generalization ability and data efficiency.

#### 2.7.2 Model initialization: The starting point of the training journey

The initial parameter values determine the starting point of the optimization process. In the vast landscape of non-convex optimization, the choice of this starting point is crucial—a poor starting point may cause the model to converge to a poor local minimum or encounter numerical instability early in training. Just as a climber needs to choose a suitable base camp to start the ascent, model initialization is a key step that lays the foundation for the entire training journey.

##### 2.7.2.1 Avoiding zero initialization

Intuitively, initializing all weights and biases to zero seems like a “neutral” starting point. However, for multi-layer neural networks, this initialization leads to severe symmetry issues, preventing the model from learning effectively.

Consider a fully connected layer as an example. If all weights _wij_ = 0, then the linear input for each neuron in this layer is

**==> picture [112 x 24] intentionally omitted <==**

It can be seen that at this point, the neuron’s output does not depend on the input _x_ at all but is determined solely by the bias.

If we further assume all biases _bj_ are also the same (e.g., all initialized to 0), then the outputs of all neurons in this layer will be completely identical. In this case, each neuron produces the same activation value during forward propagation; during backpropagation, since the error signals and inputs they receive are also identical, their gradient updates will be exactly the same. Therefore, throughout the training process, these neurons always maintain the same parameter values and learn exactly the same features.

Even if the biases _bj_ are different, since the weights are zero, the neuron outputs still contain no information from the input features. The network in the initial stage is equivalent to a model relying only on constant offsets, making it difficult to effectively learn the relationship between input and output.

Therefore, the root of the problem is: when weights are initialized to the same value (especially zero), the model cannot break the symmetry between neurons, causing multiple neurons to degenerate into functionally equivalent units, thereby significantly reducing the model’s expressive power. This phenomenon is called failure to break symmetry, which also explains why in practice, weights must be randomly initialized to introduce differences between parameters.

##### 2.7.2.2 Random initialization: Scale is key

The most direct method to break symmetry is random initialization—sampling each parameter independently from some probability distribution. However, random does not mean arbitrary; the choice of scale becomes the key to success or failure. Suppose we sample weights _W_ from a distribution with zero mean and variance _σ_[2] . Consider a simple forward propagation: _z_ = _Wx_ + _b_ , where _x_ is the input vector. If _σ_ is too large, the weight values may cause the magnitude of _z_ to rapidly inflate, and after multi-layer propagation, activation values tend to infinity, leading to gradient explosion; if _σ_ is too small, activation values rapidly shrink to zero, leading to gradient vanishing. Both scenarios can paralyze training—the former causes numerical overflow, the latter makes parameter updates almost stall.

- So, what scale is “just right”? The answer lies in variance analysis.

- 3. Variance Scaling-Based Initialization

The core idea of this class of initialization methods is: during initialization, try to keep the variance of activation values in forward propagation and the variance of gradients in backpropagation stable. This essentially designs a delicate statistical balance to allow signals to flow smoothly through the network.

Xavier initialization (also known as Glorot initialization) is an early exemplar of this idea. It assumes the activation function is linear and symmetric near the origin (like the tanh function) and derives that the variance of weights should be set to:

**==> picture [96 x 25] intentionally omitted <==**

where _n_ in is the number of input neurons and _n_ out is the number of output neurons. This setting ensures that the variance of activation values in each layer remains equal during forward propagation, while the variance of gradients also remains equal during backpropagation. When sampling from a uniform distribution, the corresponding range is _W ∼U_ [ _−_ ~~�~~ _n_ in+6 _n_ out _[,]_ ~~�~~ _n_ in+6 _n_ out[]][.]

However, Xavier initialization targets linear activation functions. When ReLU became mainstream, researchers found Xavier performed poorly on ReLU networks. The reason is: ReLU sets half of the negative input values to zero, halving the output variance. To compensate for this “information loss,” He initialization (also known as Kaiming initialization) emerged:

**==> picture [66 x 25] intentionally omitted <==**

For a uniform distribution, the corresponding range is _W ∼U_ [ _−_ ~~�~~ _n_ 6in _[,]_ ~~�~~ _n_ 6in[]][; for a normal distribution, it] is _W ∼N_ (0 _, n_[2] in[)][.][The intuition of He initialization is:][since ReLU halves the variance,][double the variance] during initialization to maintain overall variance stability. This simple adjustment made training deep ReLU networks possible.

4. Orthogonal Initialization

Variance scaling methods ensure stable signal propagation from a statistical perspective, while orthogonal initialization provides another elegant idea from a geometric viewpoint.

Consider a linear layer _y_ = _Wx_ . We want to keep the vector norm stable throughout the network—i.e., _∥y∥_ as close as possible to _∥x∥_ . If _W_ is an orthogonal matrix (i.e., _W[T] W_ = _I_ ), then for any vector _x_ , we have _∥Wx∥_ = _∥x∥_ . Orthogonal matrices perfectly preserve vector norms without introducing scaling effects.

Extending this idea to neural network initialization: we initialize the weight matrix as an (approximately) orthogonal matrix. In specific implementation, we can sample a random matrix from a standard normal distribution and then orthogonalize it via QR decomposition or singular value decomposition. Although activation functions and nonlinearities in real networks break this ideal norm-preserving property, orthogonal initialization still greatly alleviates gradient vanishing and explosion problems, especially suitable for Recurrent Neural Networks (RNNs) and scenarios requiring long-term dependency modeling.

The deep charm of orthogonal initialization lies in that it is not merely a numerical trick but embodies a geometric understanding of information flow—we want the input signal to preserve its “energy” as it propagates through the network, avoiding attenuation or explosion due to layer-by-layer scaling. This geometric intuition complements the statistical intuition of variance scaling methods, together forming the theoretical foundation of modern deep learning initialization.

#### 2.7.3 Training process optimization: Navigating non-convex terrain

Training deep neural networks is essentially searching for the lowest point on a high-dimensional nonconvex function landscape—a complex terrain filled with peaks, valleys, saddle points, and flat regions. The core goal of training process optimization is to enable gradient descent and its variants to traverse this complex terrain efficiently and stably, descending quickly while avoiding getting stuck in poor local minima, ultimately reaching parameter regions with good generalization.

##### 2.7.3.1 The family of optimization algorithms: From naive gradient descent to adaptive methods

Stochastic Gradient Descent and Mini-batch Gradient Descent form the foundation of all modern optimization algorithms. Unlike Batch Gradient Descent, which uses all data in each iteration, Mini-batch Gradient Descent randomly samples a small batch of examples and uses the average of their gradients as an estimate of the true gradient. Let the parameters at step _t_ be _θt−_ 1, and a small batch of samples randomly sampled from the training set be _B_ . Then the gradient estimate is:

**==> picture [113 x 30] intentionally omitted <==**

where _|B|_ is the mini-batch size, _Li_ is the loss function value for the _i_ -th sample, and _∇θLi_ is the gradient of the loss function with respect to parameters _θ_ . This approach brings a dual effect: on one hand, computational cost is greatly reduced, making training on large-scale datasets possible; on the other hand, the random noise introduced by mini-batch sampling actually becomes a “beneficial perturbation” for the optimization process—it can help the model escape poor local minima and explore a broader parameter space. The mini-batch size embodies the classic bias-variance trade-off: large batches provide more accurate gradient estimates (low variance) but are computationally expensive and may get stuck in sharp minima; small batches introduce more noise (high variance) but may lead to better generalization performance.

Momentum is inspired by physics—imagine a ball rolling down a hill; it accumulates speed, traverses flat areas, and resists local bumps. Mathematically, momentum maintains a velocity vector _vt_ , which is an exponentially weighted moving average of historical gradients:

**==> picture [159 x 11] intentionally omitted <==**

where _β_ is the momentum decay coefficient, controlling the decay rate of historical information; _η_ is the learning rate; _gt_ is the gradient at the current step. The effect of momentum is: accelerating progress in regions where gradient directions are consistent, smoothing updates in regions where gradient directions oscillate, thereby effectively alleviating ill-conditioned curvature problems and helping the model traverse saddle points and flat regions.

Adaptive learning rate algorithms push optimization to new heights—they assign independent adaptive learning rates to each parameter, dynamically adjusting the update step size based on the parameter’s historical gradient information. The most outstanding representative is the Adam algorithm. Adam maintains two state variables: the first moment estimate of gradients _mt_ (i.e., gradient mean with momentum) and the second moment estimate _vt_ (i.e., mean of squared gradients, reflecting the magnitude of gradient variation):

**==> picture [255 x 13] intentionally omitted <==**

where _β_ 1 and _β_ 2 are decay coefficients; _gt_ is the gradient at the current step; _gt_[2][denotes element-wise square.] Since _mt_ and _vt_ are biased towards zero in the initial stages, Adam also introduces bias correction steps:

**==> picture [130 x 23] intentionally omitted <==**

Finally, parameters are updated as:

**==> picture [107 x 23] intentionally omitted <==**

where _η_ is the global learning rate, and _ϵ_ is a tiny constant to prevent division by zero. The ingenuity of Adam lies in: for parameters with large and frequently changing gradients, _[√] v_ ˆ _t_ is large, effectively reducing the learning rate; for parameters with small and stable gradients, the effective learning rate increases. This adaptive mechanism makes Adam relatively robust to hyperparameter choices, converges quickly, and has become the most popular default optimizer today. Of course, Adam is not a panacea—in some tasks (such as certain areas of computer vision), carefully tuned Stochastic Gradient Descent with momentum can still achieve better generalization performance.

##### 2.7.3.2 Learning rate scheduling

The learning rate is one of the most important hyperparameters in training, and the core idea of learning rate scheduling is simple yet profound: use a larger learning rate in the early stages of training for rapid descent and exploration of the vast parameter space; reduce the learning rate in the later stages for fine-tuning in local regions.

Common learning rate scheduling strategies include:

   - Step decay: Multiply the learning rate by a decay factor (e.g., 0.1) every certain number of epochs. This strategy is simple and effective, especially suitable for long-term training.

   - Cosine annealing: Adjust the learning rate periodically according to a cosine function, causing the learning rate to first decrease slowly, then accelerate, and finally approach zero. Its smooth decay curve sometimes leads to better convergence.

   - Early stopping-style scheduling: Monitor validation set performance and proactively reduce the learning rate when performance stagnates. This adaptive strategy avoids mismatches between manually preset scheduling strategies and training dynamics.

3. Gradient Clipping

When training deep networks, especially Recurrent Neural Networks or Transformers, gradient explosion is a common threat—the gradient norm may grow exponentially, causing parameter update steps to become too large, sending the loss function to infinity instantly and crashing the training.

Gradient clipping provides a simple and effective solution. Let the gradient vector be _g_ , its norm be _∥g∥_ , and the preset threshold be _c_ . Then the clipped gradient ˜ _g_ is:

**==> picture [118 x 41] intentionally omitted <==**

This operation does not change the direction of the gradient, only limiting its norm within the threshold. It can be understood as a fuse in a circuit—when the current (gradient) is too high, the fuse blows but protects the entire system; gradient clipping actively scales the gradient back to a safe range when it is about to go out of control, ensuring training stability.

The beauty of gradient clipping is that it acknowledges the uncertainty in the optimization process and sets up a “safety net.” In training large language models, gradient clipping is almost standard, preventing gradient

explosion without overly interfering with the normal optimization process. 4. Curriculum Learning

The inspiration for curriculum learning comes directly from human teaching processes—we don’t let beginners face the most difficult problems directly but start with simple concepts and gradually increase difficulty. This idea also applies to machine learning: don’t let the model face the most difficult samples from the beginning; start with simple samples and gradually introduce more complex cases.

Curriculum learning can be implemented in various ways:

- Data ordering: Sort training data according to difficulty metrics (e.g., sentence length, number of problem steps), sample simple examples in the early stages, and gradually increase the proportion of difficult examples later.

- Dynamic sampling: Adjust sampling weights based on the model’s current performance—sampling probability can be reduced for sample types the model performs well on and increased for those it performs poorly on.

- Progressive tasks: In reinforcement learning, train in a simplified environment first, then transfer to the full environment.

The mathematical intuition of curriculum learning is: simple samples provide stable gradient signals, helping the model quickly establish correct representations in the early stages; as the model’s capability improves, the challenge of difficult samples matches its current level, avoiding premature entrapment in poor local minima. In mathematical reasoning tasks, curriculum learning is particularly effective—for example, first let the model learn linear equations in one variable, then gradually introduce systems of linear equations in two variables, quadratic equations, and transcendental equations.

#### 2.7.4 Regularization: Combating overfitting, improving generalization

The core goal of regularization is to reduce overfitting and improve the model’s generalization ability on unseen data. Its philosophical essence is: impose constraints or disturbances on the optimization process, guiding the model towards simpler, smoother, more general solutions, rather than merely memorizing the training data.

##### 2.7.41. Explicit Constraints: L1 and L2 Regularization

The most intuitive regularization method is to add a norm penalty term of the parameters to the loss function, directly constraining model complexity. L2 regularization (also known as weight decay) adds the sum of squared weights to the loss function. Let the original loss function be _L_ original( _θ_ ), then the regularized loss is:

**==> picture [137 x 23] intentionally omitted <==**

where _λ_ is the regularization coefficient, controlling the strength of the penalty; _∥θ∥_[2] 2[=] > _i[θ] i_[2][is the squared] L2 norm of the parameter vector. Its gradient update becomes:

**==> picture [121 x 13] intentionally omitted <==**

It can be seen that each update step subtracts a small portion of the weight value ( _ηλθ_ ), driving parameters to shrink towards zero. L2 regularization tends to make all parameter absolute values smaller, making the model output more smooth in response to input changes, thereby reducing overfitting risk. From a Bayesian perspective, L2 regularization is equivalent to introducing a Gaussian prior on the parameters.

L1 regularization adds the sum of absolute values of weights:

 _L_ reg( _θ_ ) = _L_ original( _θ_ ) + _λ∥θ∥_ 1

where _∥θ∥_ 1 = > _i[|][θ][i][|]_[ is the L1 norm of the parameter vector.][The unique aspect of L1 regularization is that] it tends to drive some parameters exactly to zero, achieving feature selection and obtaining a sparse model. This is because the L1 norm is non-differentiable at zero, making the optimization process more likely to push parameters to zero. L1 regularization is equivalent to introducing a Laplace prior on the parameters. 2. Implicit Regularization: Dropout

Dropout is one of the most imaginative regularization techniques in deep learning. It does not directly modify the loss function but randomly interferes with the network structure during training. Operation: During each forward propagation, randomly “drop” a portion of neurons with probability _p_ (usually 0.5)—i.e., temporarily set the outputs of these neurons to zero. This means each iteration trains a different sub-network, and these sub-networks share weights. During testing, all neurons are retained, but outputs need to be multiplied by _p_ to maintain consistency of expected output. Intuition and Effects: The effectiveness of Dropout comes from multiple levels:

- Preventing co-adaptation: It forces each neuron not to overly rely on a few other specific neurons because those neurons might be dropped in the next iteration. Each neuron must learn to work with many random subsets, making the extracted features more robust and independent.

- Approximation of model averaging: Each dropout instance is equivalent to training a different sub-network. During testing, using the full network with weight scaling (multiplying by the retention probability) can be approximately viewed as averaging the outputs of these exponentially many sub-networks (corresponding to geometric mean under specific conditions). This is similar to ensemble learning, which is proven to effectively reduce variance and improve generalization performance.

- Sparse activation: Dropout creates a sparse activation pattern, sharing a similar spirit with L1 regularization— both encourage the network to use fewer features for prediction.

From an information theory perspective, Dropout can be understood as applying random perturbations to the network structure during training, an efficient data-agnostic form of “data augmentation.” 3. Early Stopping

Early stopping might be the simplest and most effective regularization method. Its idea is straightforward yet profound: stop training before the model starts overfitting the training data.

Specific method: Split data into training and validation sets. During training, periodically evaluate model performance (e.g., loss or accuracy) on the validation set. When it is observed that the error on the validation set no longer decreases or even starts to increase—even though the training error may still be decreasing—stop training and revert to the parameter state with the best validation set performance.

Mathematical explanation: In the early stages of optimization, parameters move in a direction that reduces both training error and test error. The model is learning the true patterns in the data, which are consistent across training and test sets. However, as training continues, optimization begins to overfit the noise and specific cases in the training data, which only exist in the training set. At this point, parameters move in a direction that only reduces training error but may increase test error; training error and validation error start to diverge. Early stopping essentially truncates the number of optimization iterations when validation error reaches its minimum, preventing further worsening of this divergence.

From an optimization perspective, early stopping limits the distance parameters move in the parameter space, similar to the constraint L2 regularization imposes on parameter norms. From a Bayesian perspective, it concentrates the parameter prior near the initial values. The elegance of early stopping is that it does not require modifying the loss function or network structure; simply monitoring validation set performance yields a regularization effect.

#### 2.7.5 Engineering practice for large language models on mathematical problems

Applying the above engineering practices to the training of mathematical large language models allows us to more concretely understand how these techniques work together and what special challenges the mathematical domain brings.

   1. Data Preparation: Training mathematical large language models requires massive, high-quality mathematical text—from arXiv papers, mathematics textbooks, Stack Exchange discussions to mathematical implementations in code repositories. This data needs fine-grained cleaning, including normalization of LaTeX expressions, standardization of mathematical symbols, cross-document deduplication, etc. For supervised fine-tuning, mathematical question-answer pairs need to be carefully constructed, not only containing questions and answers but also emphasizing the presentation of reasoning processes—chainof-thought data teaches the model to derive step-by-step rather than jumping directly to conclusions.

   2. Training Pipeline: As mentioned earlier, follow the three-stage pipeline of “pre-training →supervised finetuning →reinforcement learning.” In the reinforcement learning stage, the particularity of mathematical tasks is especially prominent—we can utilize program-assisted execution, letting the model generate executable Python code to solve mathematical problems, then verify results through a code interpreter. This provides a more objective and scalable reward signal than human preference: whether the code runs correctly is deterministic. We can also train specialized verifier models to judge the correctness of generated answers and the rigor of reasoning steps, serving as reward models in reinforcement learning.

   3. Regularization and Stability: In mathematical reasoning, overfitting may manifest as the model memorizing solutions to specific problems rather than learning general problem-solving logic. Dropout and early stopping are equally applicable here. Furthermore, the Transformer architecture’s inherent residual connections and layer normalization already have built-in effects for stabilizing training, reducing reliance on certain explicit regularizations.

4. Curriculum Learning: Mathematical knowledge has a natural hierarchical structure—from arithmetic to algebra, from geometry to calculus. This provides an ideal application scenario for curriculum learning. We can first let the model learn simple arithmetic operations, gradually introduce equations, functions, derivatives, integrals; or in the reinforcement learning stage, first let the model solve simple problems with fewer steps, then gradually increase problem difficulty. This progressive training aligns with the cognitive laws of mathematical learning, guiding the model to establish a solid knowledge foundation.

It is worth pondering that these engineering practices are not isolated tricks but an interconnected system. Good initialization allows the use of larger initial learning rates; residual connections and layer normalization reduce gradient vanishing problems and also lower dependence on complex regularization; early stopping and learning rate scheduling work together—when validation performance stagnates, we can either stop training or lower the learning rate to continue exploration; and the multi-stage training pipeline itself is a macro-level “curriculum learning”—first let the model master basic language abilities (pre-training), then learn to follow instructions (supervised fine-tuning), and finally optimize output quality (reinforcement learning).

In the exploration of AI for Math, combining prior knowledge of specific mathematical problems to design and adjust these practices is key to success. For example, designing mathematics-specific data augmentation strategies (such as variable substitution, equivalent form rewriting), designing special loss functions for physics-informed neural networks, and designing program-verification-based reinforcement learning rewards for mathematical reasoning models. Ultimately, the common goal of all these engineering practices is to achieve “control and guidance” over the optimization process and model behavior—taming complex non-convex optimization with limited resources, guiding the model towards parameter regions with powerful generalization ability, reliable reasoning capability, and mathematical problem-solving ability.

### References

- [1] Léon Bottou. “Large-scale machine learning with stochastic gradient descent”. In: _Proceedings of COMPSTAT’2010_ . Springer. 2010, pp. 177–186.

- [2] Tom Brown et al. “Language models are few-shot learners”. In: _Advances in Neural Information Processing Systems_ . Vol. 33. 2020, pp. 1877–1901.

- [3] Paul F Christiano et al. “Deep reinforcement learning from human preferences”. In: _Advances in Neural Information Processing Systems_ . Vol. 30. 2017.

- [4] Djork-Arné Clevert, Thomas Unterthiner, and Sepp Hochreiter. “Fast and accurate deep network learning by exponential linear units (ELUs)”. In: _arXiv preprint arXiv:1511.07289_ (2015).

- [5] George Cybenko. “Approximation by superpositions of a sigmoidal function”. In: _Mathematics of Control, Signals and Systems_ 2.4 (1989), pp. 303–314.

- [6] Jacob Devlin et al. “BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding”. In: _Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies_ . 2019, pp. 4171–4186.

- [7] Xavier Glorot and Yoshua Bengio. “Understanding the difficulty of training deep feedforward neural networks”. In: _Proceedings of the Thirteenth International Conference on Artificial Intelligence and Statistics_ . JMLR Workshop and Conference Proceedings. 2010, pp. 249–256.

- [8] Ian Goodfellow, Yoshua Bengio, and Aaron Courville. _Deep Learning_ . MIT Press, 2016.

- [9] Ian Goodfellow et al. “Generative adversarial nets”. In: _Advances in Neural Information Processing Systems_ . Vol. 27. 2014.

- [10] Alex Graves. “Generating sequences with recurrent neural networks”. In: _arXiv preprint arXiv:1308.0850_ (2013).

- [11] Jonathan Ho, Ajay Jain, and Pieter Abbeel. “Denoising diffusion probabilistic models”. In: _Advances in Neural Information Processing Systems_ . Vol. 33. 2020, pp. 6840–6851.

- [12] Sepp Hochreiter and Jürgen Schmidhuber. “Long short-term memory”. In: _Neural Computation_ 9.8 (1997), pp. 1735–1780.

- [13] Kurt Hornik, Maxwell Stinchcombe, and Halbert White. “Multilayer feedforward networks are universal approximators”. In: _Neural Networks_ 2.5 (1989), pp. 359–366.

- [14] Phillip Isola et al. “Image-to-image translation with conditional adversarial networks”. In: _Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition_ . 2017, pp. 1125–1134.

- [15] Tero Karras, Samuli Laine, and Timo Aila. “A style-based generator architecture for generative adversarial networks”. In: _Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition_ . 2019, pp. 4401–4410.

- [16] Diederik P Kingma and Jimmy Ba. “Adam: A method for stochastic optimization”. In: _International Conference on Learning Representations_ . 2015.

- [17] Yann LeCun, Yoshua Bengio, and Geoffrey Hinton. “Deep learning”. In: _Nature_ 521.7553 (2015), pp. 436– 444.

- [18] Christian Ledig et al. “Photo-realistic single image super-resolution using a generative adversarial network”. In: _Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition_ . 2017, pp. 4681–4690.

- [19] Andrew L Maas, Awni Y Hannun, and Andrew Y Ng. “Rectifier nonlinearities improve neural network acoustic models”. In: _Proceedings of the International Conference on Machine Learning_ . Vol. 30. 1. 2013, p. 3.

- [20] Vinod Nair and Geoffrey E Hinton. “Rectified linear units improve restricted boltzmann machines”. In: _Proceedings of the 27th International Conference on Machine Learning (ICML-10)_ . 2010, pp. 807–814.

- [21] Arkadi Nemirovski et al. “Robust stochastic approximation approach to stochastic programming”. In: _SIAM Journal on Optimization_ 19.4 (2009), pp. 1574–1609.

- [22] Albert B Novikoff. _On convergence proofs on perceptrons_ . Tech. rep. Stanford Research Institute Menlo Park CA, 1962.

- [23] Long Ouyang et al. “Training language models to follow instructions with human feedback”. In: _Advances in Neural Information Processing Systems_ . Vol. 35. 2022, pp. 27730–27744.

- [24] Xipeng Qiu. _Neural Networks and Deep Learning_ . China Machine Press, 2020.

- [25] Alec Radford et al. _Improving language understanding by generative pre-training_ . Tech. rep. OpenAI, 2018.

- [26] Rafael Rafailov et al. “Direct preference optimization: Your language model is secretly a reward model”. In: _Advances in Neural Information Processing Systems_ . Vol. 36. 2023, pp. 53728–53741.

- [27] Sebastian Ruder. “An overview of gradient descent optimization algorithms”. In: _arXiv preprint arXiv:1609.04747_ (2016).

- [28] David E Rumelhart, Geoffrey E Hinton, and Ronald J Williams. “Learning representations by backpropagating errors”. In: _Nature_ 323.6088 (1986), pp. 533–536.

- [29] Andrew M Saxe, James L McClelland, and Surya Ganguli. “Exact solutions to the nonlinear dynamics of learning in deep linear neural networks”. In: _arXiv preprint arXiv:1312.6120_ (2013).

- [30] Franco Scarselli et al. “The graph neural network model”. In: _IEEE Transactions on Neural Networks_ 20.1 (2009), pp. 61–80.

- [31] Rico Sennrich, Barry Haddow, and Alexandra Birch. “Neural Machine Translation of Rare Words with Subword Units”. In: _Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics_ . 2016, pp. 1715–1725.

- [32] Zhihong Shao et al. “DeepSeekMath: Pushing the limits of mathematical reasoning in open language models”. In: _arXiv preprint arXiv:2402.03300_ (2024).

- [33] Nitish Srivastava et al. “Dropout: a simple way to prevent neural networks from overfitting”. In: _The Journal of Machine Learning Research_ 15.1 (2014), pp. 1929–1958.

- [34] Ilya Sutskever et al. “On the importance of initialization and momentum in deep learning”. In: _International Conference on Machine Learning_ . PMLR. 2013, pp. 1139–1147.

- [35] Richard S Sutton and Andrew G Barto. _Reinforcement learning: An introduction_ . MIT Press, 2018.

- [36] Ashish Vaswani et al. “Attention is all you need”. In: _Advances in Neural Information Processing Systems_ . Vol. 30. 2017, pp. 5998–6008.

- [37] Li-Ping Wang, Song Chen, Li-Nan Jiang, et al. “Parameter-Efficient Fine-Tuning in Large Language Models: A Survey of Methodologies”. In: _Artificial Intelligence Review_ 58.8 (2025), p. 227.

- [38] Daniel M Ziegler et al. “Fine-tuning language models from human preferences”. In: _arXiv preprint arXiv:1909.08593_ (2019).

## Chapter 3: AI for discovering mathematical patterns

### 3.1 Overview

The previous chapter’s introduction to the fundamental techniques of machine learning has laid out a powerful toolkit for us. Neural networks, deep learning, supervised and unsupervised learning—the success of these methods in fields like image recognition and natural language processing has fully demonstrated their ability to extract patterns from complex data. However, when we turn our gaze to mathematical research, a deeper question emerges: Can these techniques transcend the role of “efficient calculators” and truly participate in the core process of mathematical discovery?

To answer this question, we need to re-examine the inherent dilemmas of mathematical research itself. The discovery of mathematical laws has always relied on the interplay of two core capabilities: intuitive insight and logical deduction. Mathematicians, through a profound understanding of known structures, generate conjectures about unknown relationships, which are then verified through rigorous proofs, forming a “conjecture-proof” cycle. However, as the objects of mathematical research become increasingly complex—such as topological invariants on high-dimensional manifolds, algebraic structures in high-degree polynomial rings, or the long-term behavior of nonlinear dynamical systems—the boundaries of human intuition begin to show. We excel at imagining symmetries in three-dimensional space but struggle to intuitively grasp the geometry of fifty-dimensional space; we can derive explicit solutions for low-degree equations but find it difficult to discern hidden connections between high-dimensional algebraic varieties.

It is precisely within this dilemma that artificial intelligence reveals its unique value. But the “artificial intelligence” here is not a generalized concept; rather, it points to an emerging interdisciplinary field taking shape: using machine learning as a cognitive tool, with mathematical structures themselves as the object of study, and mathematical understanding as the core goal. This field has its own distinct methodology, theoretical concerns, and research questions. It is neither a simple application of AI technology nor a passive extension of mathematical theory, but a genuine form of intersection—the birth of a new “cognitive paradigm.”

The core of this new paradigm lies in this: when we face a mathematical problem that lies beyond the boundaries of human intuition, we can leverage AI’s pattern recognition capabilities to “probe” for potential regularities or signals from mathematical data; then, through interpretability techniques, “map” these signals back to concepts understandable by mathematicians, ultimately refining them into testable mathematical conjectures. This is AI-assisted mathematical discovery—the machine is responsible for exploring structures in high-dimensional spaces that are difficult for humans to access directly, while the mathematician is responsible for interpretation, refinement, and proof. The two work in a division of labor, jointly expanding the boundaries of mathematical cognition.

This collaborative logic can be clearly articulated as: Mathematical Problem →Suitable AI Technology →Concrete Implementation Process. We do not start from the technology to find application scenarios—that would lead to a mere piling up of tools; nor do we start from theory to fit in examples—that would obscure the essence of the problem. Instead, we start from the dilemma of the mathematical problem itself and examine what kind of AI technology can provide substantive assistance. For example, faced with the deep problem of “understanding the relationship between geometric and algebraic invariants of knots,” the challenge lies in learning the mapping relationships between different mathematical structures from unstructured data—this is precisely what neural networks excel at. Therefore, we design experiments for AI to find patterns in this data,

3.2 AI Discovers Hidden Relationships Between Knot Invariants: A Supervised Learning Approach

then through interpretability analysis, reveal the key features the model relies on, and finally translate these features into conjectures that mathematicians can test.

This problem-oriented perspective reveals the unique character of AI for Math as an interdisciplinary field. Here, the relationship between AI and mathematics is no longer a one-way “application” or “assistance,” but a deep “collaboration”: AI is responsible for probing, the mathematician is responsible for understanding.

In the following sections, we will present this collaborative paradigm in its entirety through concrete case studies. Each case will follow the narrative thread of “Mathematical Problem →AI Technology →Implementation Process,” demonstrating how AI, as a new methodology, helps us explore deep relationships between knot invariants, discover hidden patterns in algebraic structures, and even predict the existence of certain mathematical conjectures. These cases are not merely demonstrations of technology; they are witnesses to a new research paradigm—an era belonging to AI for Math is quietly unfolding.

### 3.2 AI discovers hidden relationships between knot invariants: A supervised learning approach

Imagine a rope tied into a complex knot in three-dimensional space, with its ends then connected—this is a “knot” in mathematics. How do we precisely describe and study this “knot”? The key lies in finding quantities that remain unchanged no matter how we continuously stretch or twist the rope (as long as we don’t cut it or let it pass through itself). Such quantities are called knot invariants. They are like the “fingerprints” of a knot, helping us distinguish different knots and understand their deep structure.

The main knot invariants can be divided into two broad categories: The first category is geometric (hyperbolic) invariants. For the vast majority of knots, their complement space (the part of three-dimensional space with the knot itself removed) can be endowed with a very elegant geometric structure—hyperbolic geometry. Just as a saddle surface is a two-dimensional hyperbolic space, a knot’s complement can be a three-dimensional hyperbolic space. This leads to a series of refined geometric quantities, such as:

- Volume: Hyperbolic volume, measuring the size of this geometric space, is a fundamental geometric characteristic of a knot.

- Chern-Simons invariant: A topological invariant originating from theoretical physics, related to the “twisting” of the space.

- Cusp geometry: The knot itself can be thought of as an infinitely thin tube. The boundary of its tubular neighborhood is a torus. The geometric information on this torus (such as the meridional translation and longitudinal translation) encodes the structure of the knot “at infinity”.

- Injectivity radius: Measures the scale of the “narrowest point” in the knot complement, reflecting a geometric “bottleneck”.

The second category is algebraic invariants, defined through algebraic or combinatorial methods, such as:

- Jones polynomial: A polynomial invariant discovered in 1984, whose appearance revolutionized knot theory.

- Signature: An integer invariant that encodes many important algebraic properties of a knot, for example, it is closely related to whether a knot can be the boundary of some surface in four-dimensional space (i.e., the minimal genus of such a surface).

For a long time, mathematicians have vaguely felt that there should be profound connections between invariants from these two different worlds. A famous example is the “Volume Conjecture”, which boldly proposes that the hyperbolic volume of a knot might be hidden in the asymptotic behavior of its Jones polynomial. However, discovering new, concretely provable relationships faces enormous challenges. The reason is that the relationships between these invariants can be extremely subtle, involving nonlinear patterns in high-dimensional spaces. From vast, complex data, it is difficult to reliably extract mathematically valuable clues relying solely on human observation and traditional statistical methods. We are good at visualizing in three dimensions, but find it hard to intuitively grasp the structure in the high-dimensional space spanned by multiple invariants.

This is precisely the point where AI can intervene. When the core difficulty of a mathematical problem is “high-dimensional complexity beyond human intuition”, the powerful pattern recognition capabilities of machine learning come into play.

In 2021, the DeepMind team published a breakthrough result in the journal _Nature_ . Their developed AI system could help mathematicians discover new connections between knot invariants. This research demonstrated that AI can guide mathematicians’ intuition to discover mathematical connections that humans might overlook. The entire study follows a clear logical thread, which we can break down into four key steps.

Step 1: Transforming a Mathematical Conjecture into a Machine Learning Problem and Data Generation

Any exploration begins with an initial intuition or hypothesis. In this study, the mathematicians’ initial hypothesis was: “There exists some undiscovered predictable relationship between the geometric (hyperbolic) invariants of a knot and its algebraic invariants (especially the signature).” To test this hypothesis, it needed to be transformed into a machine learning problem. Specifically:

- Define Input (X): We need to select a set of geometric invariants to serve as the feature vector describing each knot. The researchers chose volume, the Chern-Simons invariant, four quantities describing Cusp geometry (real and imaginary parts of the meridional translation, real and imaginary parts of the longitudinal translation), injectivity radius, etc. In this way, each knot _K_ is represented as a numerical vector _X_ ( _K_ ).

- Define Output (Y): We need to choose an algebraic invariant as the prediction target. Here, the signature _σ_ ( _K_ ) was chosen. Choosing the signature was wise: it is an integer, making it easy to model as a classification problem; it is easy to compute; and it contains rich mathematical information, making it a quantity “worth understanding”.

- Build the Dataset: Machine learning requires data. The researchers constructed three complementary datasets to ensure the robustness and generalization ability of subsequent discoveries:

   - Systematic Census Data: From the “Regina” database, containing all knots with crossing number (a measure of knot complexity) up to 16, totaling about 1.7 million samples. This dataset provides “systematic coverage” of small, simple knots.

   - Random Complex Data: Using the professional knot software SnapPy, randomly generated complex knots with about 80 crossings, yielding about 1 million samples after deduplication. This dataset represents a more complex, more “generic” distribution of knots, used to verify the generalization of discoveries.

   - Specially Constructed Data: By controlling braid parameters, constructed tens of thousands of knots with specific algebraic structures (e.g., 4-braids, 5-braids, 6-braids). This dataset was not used for training but specifically for subsequent “stress testing” of conjectures—to see if the discovered patterns still hold on these special knots.

Thus, an abstract mathematical intuition was transformed into a concrete machine learning problem: Given a knot’s geometric feature vector _X_ ( _K_ ), can we train a model to accurately predict the knot’s signature _σ_ ( _K_ )? Step 2: Supervised Learning and Pattern Detection

Next, a neural network was used to train on the prepared dataset. In the knot case, the researchers used a standard fully connected feedforward neural network. This is a multi-class classification problem because the signature is an integer. Model performance was evaluated based on its classification accuracy on an independent test set.

The experimental results were encouraging: The trained model achieved a test accuracy of 78% in predicting the signature, and prediction errors never exceeded ±2. In contrast, a baseline of random guessing had a much lower accuracy (e.g., uniform guessing within the signature’s value range). This result strongly suggests that between a knot’s geometric features and its signature, there exists a robust mathematical pattern that can be captured by the machine learning model. This gave mathematicians confidence to explore further—their intuitive direction was likely valuable.

Step 3: Interpretability Analysis and Clue Extraction

The model’s successful prediction is just the beginning. More importantly: “How” does the model make predictions? Which geometric features does it rely on? How do these features interact? Answering these questions is key to transforming machine learning output into mathematical conjectures.

To this end, the researchers used an interpretability technique called “gradient-based saliency analysis”. Its core idea is very intuitive: We want to know how much each input feature “contributes” to the model’s final prediction. Specifically, for each sample in the dataset, we compute the absolute value of the partial derivative of the model’s loss function with respect to each input feature _|∂L/∂xi|_ . The intuitive meaning of this value is: If we make a small change to a feature _xi_ , how much will the model’s prediction loss change? A larger change indicates the model is more “sensitive” to that feature, meaning the feature is more important in the decision.

For each sample _x_ in dataset _X_ , compute the absolute value of the gradient of the model’s loss function _L_ with respect to the _i_ -th input feature _xi_ , _|∂L/∂xi|_ . This value reflects how much the model’s prediction loss would change if feature _xi_ were slightly altered. A larger change indicates the model is more sensitive to that feature, suggesting it may be more important.

To obtain the overall importance of each feature across the entire dataset, we average the absolute gradient values over all samples:

**==> picture [97 x 30] intentionally omitted <==**

where _ri_ is the average gradient saliency score for the _i_ -th feature, and _|X|_ is the total number of samples in the dataset.

Applying this saliency analysis to the knot model yielded a clear pattern. The analysis indicated that among all geometric invariants, three features stood out, with their _ri_ values significantly higher than others, being crucial for predicting the signature:

- Real part of the meridional translation _Re_ ( _µ_ )

- Imaginary part of the meridional translation _Im_ ( _µ_ )

- Real part of the longitudinal translation _Re_ ( _λ_ )

These three quantities together describe the geometry of the “Cusp” (the boundary torus of the infinitely thin tubular neighborhood) in the knot complement, i.e., the so-called Cusp geometry. In other words, the model told us: To predict the signature, the most important information is almost entirely concentrated in the Cusp geometry.

To verify this discovery, the researchers trained a second model, this time using only these three Cusp geometry features as input. The result was astonishing: The prediction accuracy of this simplified model was almost identical to that of the original model using all dozen geometric features! This was undoubtedly decisive evidence: Information about the signature is almost completely concentrated in these three Cusp geometric quantities. This step sharply focused the mathematicians’ attention from a dozen possible geometric invariants down to three core features. The problem was greatly simplified.

Step 4: Mathematical Refinement and Conjecture/Theorem Formation

Now, the machine learning task was complete. It detected the pattern and located the key features. Next came the moment for mathematicians to exercise their irreplaceable creative wisdom. Armed with the clue provided by AI—“Cusp geometry is key”—they began to apply their deep mathematical intuition and expertise for in-depth analysis and re-creation.

First, they visualized the relationship between these key features and the signature. Observations revealed that the relationship between the signature and these quantities was not a simple linear one but exhibited a complex pattern. After repeatedly examining the data distribution and deeply mining the geometric meaning, the mathematicians creatively defined a new, composite geometric quantity, which they called the natural slope:

**==> picture [97 x 12] intentionally omitted <==**

This newly defined quantity has a clear geometric interpretation: On the Euclidean torus of the Cusp, there is a special curve (a geodesic starting from a meridian). When it travels around the torus and intersects the meridian again, the path it takes is equivalent to some multiple of the meridian plus a longitude. This “multiple” is the natural slope. It is a quantity directly derived from Cusp geometry, with clear geometric meaning.

An even more exciting discovery followed: When plotting the signature _σ_ ( _K_ ) against this newly defined natural slope slope( _K_ ), a strong linear trend emerged between the two! This prompted the mathematicians to propose the first concrete mathematical conjecture:

**Initial Conjecture:** There exist constants _c_ 1 and _c_ 2 such that for all hyperbolic knots _K_ ,

**==> picture [179 x 11] intentionally omitted <==**

This conjecture is concise and elegant, linking an algebraic invariant (signature) with a new geometric invariant (natural slope) and another fundamental geometric quantity (volume). However, the journey of scientific discovery is never smooth sailing. The researchers used the previously constructed “specially constructed data” (those special knots constructed from braids) to stress-test this conjecture. They found that on some special knots, this conjecture did not hold. The appearance of counterexamples did not signal the failure of the exploration but instead guided the mathematicians to a more refined analysis. They noted that in the saliency analysis, another feature—the injectivity radius inj( _K_ )—though not as prominent as the Cusp geometry, also showed some importance. Incorporating this clue, they ultimately proposed a revised conjecture:

**Final Conjecture:** There exists a constant _c_ such that for all hyperbolic knots _K_ ,

**==> picture [201 x 14] intentionally omitted <==**

Subsequently, the researchers rigorously proved the above conjecture in a separate mathematical paper, establishing it as a reliable mathematical theorem. This theorem has direct applications; for example, it implies that the signature controls non-hyperbolic Dehn surgery on the knot, and the natural slope controls the genus of surfaces bounded by the knot in R[+] 4[.][A new mathematical truth, discovered with AI assistance, was thus born.]

Reviewing the entire knot research case, we can clearly see a logical thread running through it, ensuring that AI assistance always serves the core goal of mathematical discovery:

- Object Definition: The core object of study is the hyperbolic knot _K_ . This is the starting point of the entire exploration.

- Representation Learning: Transforming the abstract knot structure, via its geometric invariants, into a numerical vector _X_ ( _K_ ) that machine learning models can process. Simultaneously, the target property of interest is its algebraic invariant, the signature _Y_ ( _K_ ). This step is the bridge connecting the mathematical world and the data world.

- Function Approximation: Transforming the vague goal of “discovering a relationship” into a clear supervised learning problem: finding a function _f_ such that _f_ ( _X_ ( _K_ )) can well predict _Y_ ( _K_ ). The neural network acts as a high-dimensional approximator for this unknown function _f_ .

- Structure Inversion: Using interpretability techniques to “probe” the trained neural network, reverseengineering the key mathematical structure (i.e., Cusp geometry) it relies on for decisions. This is equivalent to “translating” the complex high-dimensional patterns learned by the model back into a subset of features with clear geometric meaning that mathematicians can understand.

- Conjecture Proposal: Based on the identified key structure, mathematicians use domain knowledge to create new composite concepts (natural slope) and construct precise conjectures expressible in traditional mathematical language, ultimately establishing them as theorems through proof. This completes the decisive leap from “patterns in data” to “statements in mathematics”.

- Verification and Refinement: Using specially constructed data and mathematical proof to rigorously verify and refine the conjecture, ultimately forming mathematically sound results.

This thread emphasizes that AI’s role is not to replace mathematicians’ reasoning but to serve as a powerful pattern detector and focusing lens. It handles the analysis of vast, high-dimensional data that humans are not good at, and points to “veins” worth digging deeper. The final “mining” and “smelting” work (i.e., concept creation, conjecture proposal, and theorem proof) is completed by mathematicians relying on their profound professional intuition and strict logical reasoning. More precisely, the clues provided by AI guided the mathematicians to perform the following creative work:

1. Define a New Concept: Based on the key features _µ_ and _λ_ , mathematicians defined a new, geometrically meaningful composite quantity—the natural slope: slope( _K_ ) = _Re_ ( _λ/µ_ ).

2. Propose and Refine a Conjecture: After observing data trends, they first proposed a conjecture that the signature _σ_ ( _K_ ) has an approximately linear relationship with the natural slope and is constrained by volume. Subsequently, using AI’s performance on another dataset, they found counterexamples to this conjecture.

3. Conjecture the Final Conclusion: Incorporating another feature of relatively high importance (the injectivity radius inj( _K_ )), the mathematicians successfully conjectured the following conclusion:

   - _|_ 2 _σ_ ( _K_ ) _−_ slope( _K_ ) _| ≤ c ·_ vol( _K_ ) _·_ inj( _K_ ) _[−]_[3]

In the above research work, the workflow of the AI model can be summarized as follows:

- Data Sources: Building a Multi-Layered Data Foundation

- Any data-driven exploration begins with data. To ensure the comprehensiveness and robustness of subsequent discoveries, the researchers constructed three complementary datasets, each playing a different role:

   - Systematic Census Data: From the “Regina” database, containing all knots with crossing number (a common measure of knot complexity) up to 16, totaling about 1.7 million samples. The value of this dataset lies in its “systematicity”—it covers all structurally relatively simple knots, providing a complete benchmark for the study.

   - Random Complex Data: Using the professional knot software SnapPy, randomly generated complex knots with about 80 crossings, yielding about 1 million samples after deduplication. This dataset represents a more complex, more “generic” distribution of knots, used to verify the generalization of discoveries—i.e., whether the discovered patterns still hold across a broader family of knots.

- ® Specially Constructed Data: By controlling braid parameters, constructed tens of thousands of knots with specific algebraic structures (e.g., 4-braids, 5-braids, 6-braids). This dataset was not used for the initial model training but specifically for subsequent “stress testing” of conjectures—to see if the discovered patterns still hold on these specially constructed knots, or even to find counterexamples.

- These three datasets form an organic complement in terms of scale and distribution: census data provides systematic coverage, random data provides generalization verification, and constructed data is used for targeted boundary testing. This multi-layered data strategy is an important foundation for ensuring that subsequent machine learning discoveries have statistical robustness and mathematical significance.

- Input and Output: Translating the Mathematical Problem into a Machine Learning Task

- With data in hand, the next step is to “translate” the mathematical problem into a language machine learning can understand:

   - Input Features (X): Each knot is represented as a numerical vector composed of multiple geometric invariants. These features include volume, the Chern-Simons invariant, four quantities describing Cusp geometry (real part _Re_ ( _µ_ ) and imaginary part _Im_ ( _µ_ ) of the meridional translation, real part _Re_ ( _λ_ ) and imaginary part _Im_ ( _λ_ ) of the longitudinal translation), injectivity radius, etc. This vector _X_ ( _K_ ) is the perspective through which the model “observes” the knot.

   - Output Label (Y): The model’s prediction target is the knot’s algebraic invariant—the signature _σ_ ( _K_ ). The signature is an integer, so this problem is modeled as a multi-class classification task.

- Network Architecture and Model: Choosing Suitable Tools

- Faced with this prediction task, the researchers chose the most classic and mature tool:

   - Model Type: A standard fully connected feedforward neural network. Although simple in structure, this type of network can theoretically approximate arbitrarily complex functional relationships, sufficient to meet the needs of detecting unknown mathematical patterns.

   - Training Task: Supervised learning with the geometric feature vector as input and the signature category as output. The model’s goal is to learn a mapping function _f_ from geometric features to signature, such that _f_ ( _X_ ( _K_ )) is as close as possible to the true _σ_ ( _K_ ).

- Interpretability Analysis: Opening the Black Box, Locating the Key

- However, the model’s high prediction accuracy is just the beginning. More important is answering “why”— which geometric features does the model actually rely on to make judgments? This step is key to transforming machine learning output into mathematical insight.

   - Analysis Method: The researchers used gradient-based saliency analysis. They computed the absolute value of the gradient of the loss function with respect to each input feature and averaged it over the dataset to obtain an “importance score” for each feature.

   - Key Discovery: The analysis results showed that among all geometric features, three features had saliency scores far higher than the others—they stood out like three prominent peaks: the real part of the meridional translation _Re_ ( _µ_ ), the imaginary part of the meridional translation _Im_ ( _µ_ ), and the real part of the longitudinal translation _Re_ ( _λ_ ). Retraining a model using only these three features yielded accuracy comparable to using all features, confirming the concentration of information.

- Method Boundaries: A Cautious View of AI’s “Discoveries” In the same paper, the researchers also successfully applied this methodology to the field of representation theory, further validating its generality. However, despite the remarkable success of this research, we must also soberly recognize the inherent limitations of this AI-assisted discovery approach:

   - Data Dependence and Representation Bias: All knowledge learned by the model comes from the training data. If the data fails to cover certain important types of knots, or if the chosen feature representation fails to effectively capture the essential properties of knots, the model may draw partial or even misleading conclusions.

   - The Gulf Between Correlation and Causality: Machine learning identifies statistical correlations, not mathematical necessity. A high-accuracy predictive model merely indicates a stable association between certain geometric features and the signature in the observed data, but this does not guarantee that this association is a universal mathematical theorem. Final confirmation must rely on rigorous mathematical proof.

   - The Indirectness of Interpretability Techniques: The “importance” information provided by methods like gradient saliency is essentially an indirect inference based on model behavior, not a direct interpretation of mathematical structure. The clues it provides need to be judged cautiously and cross-validated with domain knowledge; they cannot be accepted blindly.

   - The Creative Leap from Pattern to Conjecture: AI outputs data and feature importance. Transforming this into a mathematically elegant, appropriately conditioned conjecture is a process highly dependent on the mathematician’s creativity and professional expertise. The refinement from the initial conjecture to the final theorem in this study fully demonstrates the complexity and irreplaceability of this creative leap.

   - Computational Cost and Reproducibility: Large-scale data generation and model training require considerable computational resources. A complete study must meticulously document the data generation protocol, model parameters, and random seeds to ensure its discoveries can be reproduced and verified by others.

These limitations do not negate the value of AI but rather delineate a boundary for caution: AI is a powerful assistant, but not yet an omniscient oracle. Its discoveries need to be understood, tested, and proven.

### 3.3 AI discovers new algorithms: Based on reinforcement learning and llms

Matrix multiplication is one of the most fundamental and core computational tasks in computer science and mathematics. From scientific computing, linear algebra, and signal processing to neural networks in modern artificial intelligence, countless complex computations ultimately boil down to large-scale matrix multiplication operations. Therefore, improving the efficiency of matrix multiplication, even by a tiny theoretical or practical margin, can have a huge “multiplier effect” across a wide range of scientific and technological fields.

However, since German mathematician Volker Strassen proposed the famous Strassen algorithm in 1969, substantial improvements to algorithms for fixed-size matrix multiplication have stagnated for decades. The core insight of the Strassen algorithm is: computing the product of two 2 _×_ 2 matrices does not necessarily require 8 scalar multiplications (the standard “dot product” method), but can be accomplished with only 7 multiplications through a clever combination. This algorithmic idea can be applied recursively to larger block matrices, reducing the time complexity of an _N ×N_ matrix multiplication from the classical _O_ ( _N_[3] ) to approximately _O_ ( _N_[log][2][ 7] ) _≈ O_ ( _N_[2] _[.]_[81] ).

This breakthrough inspired an esoteric research direction in computational complexity theory called the “matrix multiplication exponent,” which seeks the smallest exponent _ω_ that can reduce the complexity of matrix multiplication to _O_ ( _N[ω]_ ). After more than half a century of research, the current best theoretical result is _ω <_ 2 _._ 37286, but these asymptotically optimal constructions are often highly complex “existence proofs” or nonexplicit methods, not directly corresponding to explicit algorithms that we can run efficiently on actual hardware.

From a practical perspective, a more fundamental and perplexing question is: For a given fixed-size matrix (e.g., 3 _×_ 3, 4 _×_ 4, 5 _×_ 5), what is the minimum number of multiplications required to complete the multiplication? This question seems basic, but the answer is extremely difficult to determine. For example, for 3 _×_ 3 matrices, the currently known best explicit algorithm was discovered by J. Laderman in 1976 and requires 23 multiplications. Despite nearly 50 years of effort, we still do not know if this is optimal. For 4 _×_ 4 matrices, the best-known method is to recursively apply the Strassen algorithm twice (the so-called Strassen-square algorithm), requiring 7[2] = 49 multiplications, but whether this is optimal is also unknown.

Why is such a seemingly simple, well-defined problem so difficult? The root cause is that finding an efficient matrix multiplication algorithm is essentially equivalent to finding a low-rank decomposition of a specific three-dimensional “tensor” (a multi-dimensional array). This tensor is called the matrix multiplication tensor, which completely encodes the bilinear operation of “multiplication.” Finding a matrix multiplication algorithm is finding a set of simple “primitives” (rank-one tensors) whose sum exactly equals this complex matrix multiplication tensor. Each primitive corresponds to one multiplication operation in the algorithm. Therefore, the number of multiplications required by the algorithm is the rank of that tensor decomposition.

Transforming this mathematical problem into a search problem immediately reveals its difficulty. Taking 4 _×_ 4 matrices as an example, the size of its matrix multiplication tensor _T_ 4 is 16 _×_ 16 _×_ 16. Searching for its rank- _R_ decomposition over a finite set (e.g., _F_ = _{−_ 2 _, −_ 1 _,_ 0 _,_ 1 _,_ 2 _}_ ) results in a combinatorial explosion. Specifically, each decomposition consists of 3 _R_ vectors of length 16. For _T_ 4, its action space (possible combinations of rank-one factors) is 10[10] times larger than that of _T_ 3, far exceeding traditional games like chess or Go. The search space is so vast that it surpasses any human method or computer method based on exhaustive or traditional combinatorial search. Therefore, the discovery of matrix multiplication algorithms has long relied on mathematicians’ ingenious constructions, heuristic searches guided by domain-specific knowledge, or successive numerical optimization followed by manual rounding adjustments. These methods are often highly personal, difficult to generalize, and hard to scale.

This leads to the core question of this section: Can we leverage modern artificial intelligence technology to automatically explore this vast algorithmic space and discover new, efficient, and correct algorithms that surpass human intuition? This question is not only about matrix multiplication itself but also represents a new paradigm—viewing “algorithm discovery” itself as a process that can be explored and optimized by machines.

AlphaTensor and AlphaEvolve are two landmark works under this paradigm. They start from different technical paths—the former based on deep reinforcement learning gamifying the problem, the latter based on large language model-guided program evolution—both demonstrating the enormous potential of artificial intelligence in automatically discovering mathematical algorithms and constructions, and achieving substantial breakthroughs on a classic problem that has puzzled the academic community for decades.

To deeply understand the work of AlphaTensor and AlphaEvolve, we must first grasp the core mathematical idea of “algorithm as tensor decomposition.” This is the bridge connecting specific computational problems with abstract search spaces.

Matrix multiplication **C** = **AB** is a bilinear operation: each element _cij_ in the output **C** is linear with respect to both inputs **A** and **B** . Any bilinear operation can be uniquely determined by a three-dimensional tensor.

Specifically, consider the multiplication of 2 _×_ 2 matrices:

**==> picture [207 x 34] intentionally omitted <==**

Here, _c_ 11 = _a_ 11 _b_ 11 + _a_ 12 _b_ 21, _c_ 12 = _a_ 11 _b_ 12 + _a_ 12 _b_ 22, and so on.

We can flatten the elements of the input matrices **A** and **B** into vectors. For example, in row-major order: **a** = ( _a_ 11 _, a_ 12 _, a_ 21 _, a_ 22) _[T]_ = ( _a_ 1 _, a_ 2 _, a_ 3 _, a_ 4) _[T]_ , similarly **b** = ( _b_ 1 _, b_ 2 _, b_ 3 _, b_ 4) _[T]_ and **c** = ( _c_ 1 _, c_ 2 _, c_ 3 _, c_ 4) _[T]_ .

Then, _c_ 1 = _c_ 11 = _a_ 1 _b_ 1 + _a_ 2 _b_ 3. This relationship can be fully encoded by a 4 _×_ 4 _×_ 4 tensor _T_ 2: define the elements _Ti,j,k_ of _T_ 2 such that

**==> picture [108 x 35] intentionally omitted <==**

For the computation of _c_ 1, we need _T_ 1 _,_ 1 _,_ 1 = 1 and _T_ 1 _,_ 2 _,_ 3 = 1, with all other _T_ 1 _,j,k_ = 0. This tensor _T_ 2 is the matrix multiplication tensor for 2 _×_ 2 matrix multiplication. It is a sparse tensor with elements only 0 or 1, and the positions of its non-zero entries precisely describe which products of input terms contribute to which output term.

More generally, _n × n_ matrix multiplication corresponds to a tensor _Tn_ of size _n_[2] _× n_[2] _× n_[2] . Similarly, the multiplication of an _n × m_ matrix with an _m × p_ matrix corresponds to the tensor _Tn,m,p_ .

Understanding how tensors encode matrix multiplication, the next question is: How to decompose this tensor?

First, we need to define the most basic building block—the rank-one tensor. A three-dimensional tensor is called a rank-one tensor if it can be written as the outer product of three vectors. Specifically, given three vectors **u** _∈_ R _[I]_ , **v** _∈_ R _[J]_ , **w** _∈_ R _[K]_ , their outer product **u** _⊗_ **v** _⊗_ **w** produces a three-dimensional _I × J × K_ tensor whose element at position ( _i, j, k_ ) is _uivjwk_ .

Intuitively, this is the simplest, indecomposable tensor primitive.

If a tensor _T_ can be expressed as the sum of _R_ rank-one tensors:

**==> picture [125 x 33] intentionally omitted <==**

then we say the tensor rank of _T_ is at most _R_ , denoted Rank( _T_ ) _≤ R_ . This is a natural generalization of the concept of matrix rank to higher dimensions. The rank of a matrix is the minimum dimension of the space spanned by its column (or row) vectors, while the rank of a tensor is the minimum number of terms (outer products) required to decompose it into rank-one terms.

Here emerges a profound and elegant connection:

**Theorem 3.1**

_A rank R decomposition of the matrix multiplication tensor Tn directly corresponds to an algorithm for computing the product of two n × n matrices, using exactly R scalar multiplications._

**==> picture [9 x 9] intentionally omitted <==**

How is this correspondence established? Let’s derive it step by step. Given the decomposition _Tn_ =[�] _[R] r_ =1 **[u]**[(] _[r]_[)] _[ ⊗]_ **[v]**[(] _[r]_[)] _[ ⊗]_ **[w]**[(] _[r]_[)][.][By the definition of the tensor, for any inputs]

**a** _,_ **b** , the output **c** satisfies:

**==> picture [442 x 126] intentionally omitted <==**

Here, the expressions in parentheses are linear combinations of input elements (only additions), and then the two are multiplied—this is one scalar multiplication. There are _R_ such multiplications in total.

2. For _i_ = 1 to _n_[2] , compute:

**==> picture [72 x 33] intentionally omitted <==**

This step involves only additions and scalar multiplications (multiplying by coefficients _u_[(] _i[r]_[)][), introducing] no new multiplications.

This algorithm uses exactly _R_ multiplications. The coefficients of the vectors **u**[(] _[r]_[)] , **v**[(] _[r]_[)] , **w**[(] _[r]_[)] define the specific linear combinations in the algorithm. For example, Strassen’s classic algorithm is precisely an _R_ = 7 decomposition of _T_ 2, and its corresponding 7 sets of ( **u**[(] _[r]_[)] _,_ **v**[(] _[r]_[)] _,_ **w**[(] _[r]_[)] ) define those famous intermediate products _M_ 1 _, . . . , M_ 7.

More importantly, a fast algorithm for a small matrix size can be recursively applied to large matrices via the “block matrix” idea. For example, viewing a large _N × N_ matrix as composed of 2 _×_ 2 sub-blocks, applying Strassen’s 2 _×_ 2 algorithm to each sub-block (now viewed as operations on “blocks,” where each block operation requires 7 scalar multiplications) can recursively reduce the overall complexity to _O_ ( _N_[log][2][ 7] ) _≈ O_ ( _N_[2] _[.]_[81] ).

More generally, if an _n × n_ matrix multiplication algorithm uses _R_ multiplications (i.e., Rank( _Tn_ ) _≤ R_ ), then through recursive blocking, the asymptotic complexity for multiplying two _N × N_ matrices is _O_ ( _N_[log] _[n][ R]_ ). Therefore, searching for a lower _R_ directly impacts the theoretical limit of matrix multiplication.

Finding low-rank decompositions of tensors is a notoriously difficult problem. For matrices (two-dimensional tensors), computing their rank can be solved in polynomial time (e.g., via singular value decomposition). But for tensors of three or more dimensions, computing their exact rank is an NP-hard problem and extremely difficult in practice.

Therefore, algorithm discovery has long relied on mathematicians’ flashes of insight, heuristic searches for specific structures, or successive numerical optimization followed by manual rounding adjustments. These methods are inefficient, poorly scalable, and heavily dependent on human-designed heuristic rules that may not be optimal. This is precisely where AI methods can shine: automatically searching this vast space that is difficult for human intuition to reach.

DeepMind’s AlphaTensor work’s core innovation lies in cleverly formalizing the NP-hard problem of tensor decomposition as a single-player game (called TensorGame) and using deep reinforcement learning technology based on AlphaZero to play this game, thereby automating the search for efficient decompositions.

The design of TensorGame ingeniously transforms the mathematical goal of “finding a low-rank decomposition” into a sequential decision-making problem:

- State: The game state _St_ is a three-dimensional tensor. The initial state _S_ 0 is precisely the target tensor _T_ we want to decompose (e.g., the tensor _T_ 4 corresponding to 4 _×_ 4 matrix multiplication).

- Action: At each step _t_ , the player (the AI agent) chooses an action—this action corresponds to a rank-one tensor, formed by the outer product of three vectors ( **u**[(] _[t]_[)] _,_ **v**[(] _[t]_[)] _,_ **w**[(] _[t]_[)] ). The elements of these vectors must come from a predefined discrete set _F_ , e.g., _{−_ 2 _, −_ 1 _,_ 0 _,_ 1 _,_ 2 _}_ . The purpose of discretization is practical: to ensure the coefficients of the ultimately discovered algorithm are concise, interpretable, and avoid issues from floating-point precision.

- State transition: After executing an action, the state is updated to the current tensor minus this rank-one tensor:

**==> picture [140 x 13] intentionally omitted <==**

The intuitive meaning of this operation is: “remove a primitive from the remaining part to be decomposed.” Each step gradually “dissolves” the target tensor.

- Termination and reward: The goal of the game is to reduce the tensor to zero in as few steps as possible,

- i.e., reach _SR_ = **0** . At this point, the sequence of actions constitutes a valid decomposition:

**==> picture [122 x 33] intentionally omitted <==**

The number of steps _R_ here is precisely the rank of the decomposition, corresponding to the number of multiplications in the algorithm.

The reward design directly serves this goal: a reward of _−_ 1 is given for each step. Therefore, the total return for the entire game is _−R_ , and maximizing the return is equivalent to minimizing the number of steps _R_ —that is, finding a decomposition with as low a rank as possible.

If the game fails to reach zero within a preset maximum number of steps _R_ limit, an additional penalty is given based on an upper bound on the rank of the remaining tensor _SR_ limit. This guides the agent to reduce the complexity of the remaining part as much as possible even if it cannot fully decompose it.

A key advantage of this formalization is its flexibility. The reward function can be easily modified to optimize other objectives, not just the theoretical number of multiplications. For example, at the end of the game, the algorithm corresponding to the action sequence can be run on specific hardware, and its negative runtime can be used as an additional reward—thus directly discovering algorithms customized and practically efficient for specific hardware like GPUs and TPUs.

AlphaTensor is built upon the famous AlphaZero framework, whose core is a neural network Monte Carlo Tree Search (MCTS) planner. MCTS is a tree search strategy that combines random simulation with value estimation to efficiently select promising actions in large action spaces.

- Neural network _fθ_ : It takes the current state (tensor _St_ ) as input and outputs two key pieces of information:

   - Policy _π_ : A probability distribution over all possible actions ( **u** _,_ **v** _,_ **w** ). It predicts which actions are more likely to lead to a good decomposition. Due to the huge action space, AlphaTensor adopts the strategy of Sampled AlphaZero, letting the network output a relatively compact set of candidate actions rather than enumerating all of them.

   - Value _z_ : An estimate of the distribution of future returns (cumulative reward). This is essentially the network’s belief about “starting from the current state, how small a rank can be achieved to finish the game.” Using a distribution rather than a single value can better capture uncertainty.

- Monte Carlo Tree Search: At each step, AlphaTensor does not directly use the policy output by the neural network. Instead, it uses that policy and value as guidance to perform multiple rounds of simulation to build a search tree. In the tree, it explores more deeply those action paths that appear promising and synthesizes the simulation results to obtain a search policy superior to the original network policy. This process balances “exploitation” (choosing what currently seems best) and “exploration” (trying new possibilities).

- Training loop: The agent trains through self-play. In each game, it uses MCTS to select actions. After the game ends, the resulting trajectory (states, actions, final reward) is used as training data to update the neural network parameters _θ_ , making its policy and value predictions increasingly accurate. This is a continuously self-improving closed loop.

Directly applying standard AlphaZero to TensorGame faces huge challenges because its action space and state representation complexity far exceed those of board games. AlphaTensor introduces several key innovations for this:

- Specialized neural network architecture: Adopts a Transformer-based architecture but deeply customized for three-dimensional tensor input.

   - Input projection: Projects the _S × S × S_ input tensor onto three _S × S_ two-dimensional grids. Each grid corresponds to a pair of tensor “modes” (e.g., rows and columns correspond to indices of input matrices **A** and **B** , respectively).

   - Generalized axial attention: The core of the model is a series of attention blocks, each operating between pairs of grids. This is more efficient than standard full self-attention and explicitly models the relationships between different slices of the tensor. The architecture design respects the mathematical property of tensor rank invariance under slice permutations—this customized inductive bias enables the network to learn and reason about tensor structure more effectively.

- Synthetic demonstrations and mixed training: Tensor decomposition is hard, but its inverse process— constructing a tensor given a decomposition—is easy. AlphaTensor leverages this to generate a massive amount of “synthetic demonstration” data: randomly generate sets of rank-one tensors _{_ ( **u**[(] _[r]_[)] _,_ **v**[(] _[r]_[)] _,_ **w**[(] _[r]_[)] ) _}_ , then construct the corresponding tensor _D_ = _r_ **[u]**[(] _[r]_[)] _[ ⊗]_ **[v]**[(] _[r]_[)] _[ ⊗]_ **[w]**[(] _[r]_[)][.][This yields (tensor, decomposition)] pairs.

- The neural network is trained on a mixture of two types of data: one is reinforcement learning on the target tensor _Tn_ (via self-play); the other is supervised learning on synthetic demonstration data (imitating known decompositions). This mixed strategy greatly improves performance and sample efficiency, even though randomly generated tensors have different properties from the target matrix multiplication tensor.

- Basis transformation to inject diversity: A tensor has different representations under different bases (coordinate systems), but its rank is invariant. At the start of each game, AlphaTensor applies a random invertible linear transformation (basis change) to the target tensor _Tn_ , then plays the game in the transformed space. After finding a decomposition, it transforms back to the standard basis to obtain the final algorithm.

This strategy offers a dual advantage: First, it provides a powerful exploration mechanism because the same target appears in different “guises” under different bases; Second, the decomposition in the transformed basis may have simpler coefficients (restricted to _F_ ), but when transformed back to the original basis, it may produce coefficients outside _F_ , thus unexpectedly expanding the coverage of the algorithm space.

   - Action normalization: To reduce the network learning redundant representations, equivalent actions (differing only in sign) are normalized. At the same time, additional training data is extracted from completed games by methods like swapping action orders to improve data utilization efficiency.

   - AlphaTensor trained a single model to decompose matrix multiplication tensors of various sizes ( _n, m, p ≤_

- 5) and explored different number systems (standard arithmetic R and modulo-2 arithmetic Z2). Its achievements are fruitful and landmark:

- **Rediscovery of classic algorithms** : AlphaTensor autonomously rediscovered the Strassen algorithm (2 _×_ 2, rank 7) and the Laderman algorithm (3 _×_ 3, rank 23) from scratch, validating the effectiveness of its method on known problems.

- **First algorithm surpassing Strassen for** 4 _×_ 4: This is the most theoretically groundbreaking result.

   - In modulo 2 arithmetic (Z2), AlphaTensor discovered a rank-47 decomposition for _T_ 4, the first improvement over the rank-49 corresponding to the two-level recursive Strassen method.

   - In standard arithmetic (R), it improved the best-known upper bounds for multiple matrix sizes. For example, for _T_ 4 _,_ 5 _,_ 5 (4 _×_ 5 multiplied by 5 _×_ 5 matrix), it reduced the known best multiplication count from 80 to 76; for _T_ 5 _,_ 5 _,_ 5, from 98 to 96.

- **Enriched algorithm database and recursive improvements** : AlphaTensor discovered thousands of inequivalent decompositions (not convertible to each other via simple symmetry operations) for each size. For example, for the rank-49 decomposition of 4 _×_ 4 alone, it discovered over 14,000 non-equivalent forms. This reveals the richness of the algorithm space. By intelligently recursively combining these discovered small-size algorithms, AlphaTensor further improved known upper bounds for over 70 larger sizes ( _n, m, p ≤_ 12) of matrix multiplication.

- **Beyond standard matrix multiplication** : The framework’s generality was validated.

   - Skew-symmetric matrix-vector multiplication: AlphaTensor discovered fast decompositions for small sizes and induced and proved a general algorithm from them: for _n × n_ skew-symmetric matrixvector multiplication, only _∼_[1] 2 _[n]_[2][multiplications are needed, achieving asymptotic optimality and] improving the previous _n_[2] algorithm.

   - Discovery of discrete Fourier transform bases: Over finite fields, AlphaTensor was used to find decompositions of cyclic convolution tensors. As a result, it autonomously discovered factors corresponding to the discrete Fourier transform and its inverse, demonstrating its ability to recognize deep mathematical structures.

- **Hardware-customized algorithm discovery** : By modifying the reward function to include actual runtime on specific hardware (Nvidia V100 GPU and Google TPU v2) as feedback, AlphaTensor successfully discovered matrix multiplication algorithms optimized for hardware. Although the theoretical multiplication count of these algorithms might be the same as Strassen-square (e.g., 4 _×_ 4 block matrix multiplication), because the operation sequences generated by their decompositions better match the hardware’s memory hierarchy, computational units, and compiler optimization strategies, they achieved significant speedups in actual tests. This proves that AI can not only optimize theoretical complexity but also directly optimize key performance metrics in engineering practice.

The success of AlphaTensor shows that deep reinforcement learning can tackle core NP-hard computational mathematical problems like tensor decomposition and systematically produce new knowledge that is provably correct, theoretically valuable, and practically significant. It transforms algorithm discovery from an “art” reliant on inspiration into a scalable, automated “scientific” process.

#### 3.3.1 AlphaEvolve: Program evolution and algorithm discovery based on large language models

If AlphaTensor is a “specialist,” customizing a sophisticated reinforcement learning solution for the tensor decomposition problem, then Google DeepMind’s AlphaEvolve is more like a “generalist.” It is a code evolution agent based on large language models, with a broader design goal: by combining evolutionary computation with the code generation and understanding capabilities of LLMs, to search the program space for better algorithms or constructions that can solve various scientific and engineering problems (especially those that can be automatically evaluated).

Before delving into the technical details, we need to first understand a fundamental question: Why not directly ask a large language model to generate a perfect algorithm based on the problem description? There are three levels of consideration behind this:

- The reliability dilemma: The success rate of “one-shot generation” for complex algorithms is extremely low. The “hallucination” phenomenon of large language models leads to a large number of invalid outputs—they may look plausible but are riddled with errors when run. Pure generative methods lack verification mechanisms, making it difficult to guarantee algorithm correctness.

- The necessity of cumulative innovation: Algorithm discovery is rarely achieved in one step. The working style of human mathematicians is often incremental—making small improvements on an existing algorithm, accumulating to a certain extent before forming a breakthrough. The evolutionary framework perfectly simulates this process of “cumulative innovation”: a small effective modification is retained and becomes the basis for the next, larger improvement. Iterating on code that has already been validated as effective is far more reliable for an LLM than creating from scratch.

- The value of search guidance: Pure code generation is aimless. The database and evaluation feedback in the evolutionary framework provide clear direction for the LLM’s creation—it is not randomly wandering in a sea of possibilities but continuously optimizing towards the goal of performance improvement. This “goal-directed generation” is the core of intelligent search.

Based on these considerations, AlphaEvolve established its core philosophy: represent solutions as programs and leverage LLMs as powerful, domain-knowledgeable “mutation operators” in an evolutionary loop guided by an automatic evaluation function, continuously improving these programs.

The workflow of AlphaEvolve can be clearly decomposed into four key steps:

- Step 1: Task definition and automatic evaluation loop

The user needs to provide the core of the problem: an automatic evaluation function `evaluate(program)` . This function receives a candidate program (algorithm), runs it, and returns one or more scalar scores to measure its performance. Correctness can be ensured by verification during execution—for example, using the discovered matrix multiplication algorithm to compute random instances and compare with standard results; any errors are automatically caught and penalized.

Here, the real results of program execution replace subjective evaluation by humans or LLMs, enabling long-term, stable iterative optimization without fear of LLM “hallucinations” or biases. It is this closed loop that distinguishes AlphaEvolve from purely conversational AI. Step 2: Initialization

The user provides an initial program (which can be very simple, inefficient, or even a naive implementation) and marks the parts of the code allowed to evolve with special comments (e.g., `# EVOLVE-BLOCK-START/END` ). The remaining parts serve as a fixed framework, unchanged. This design ensures both freedom for evolution and stability of the program’s basic structure.

Step 3: Evolutionary loop

- Prompt sampling and construction: Sample a batch of high-performing programs from the “program database” (an archive storing historically explored high-scoring, diverse programs and their scores). Construct an information-rich prompt for the LLM, including: task description and instructions, one or more high-scoring programs and their detailed evaluation results (scores, outputs, etc.), possible additional context (relevant mathematical formulas, paper excerpts, optimization objective descriptions, etc.). Finally,

   - ask the LLM to analyze these programs and propose improvements, presented in the form of code diffs.

   - LLM generation and creative deduction: The LLM (such as the Gemini series models) digests the prompt and generates code modification suggestions. The key here is that the LLM can not only make small syntax-level modifications but also deeply understand program logic and propose profound algorithmic changes—such as introducing new optimization steps, changing data structures, adding heuristic rules, or even changing the entire algorithmic paradigm. It draws not only on information in the current context but also on the vast algorithm knowledge base accumulated during its pre-training on massive amounts of code.

   - Program creation and evaluation: Apply the LLM’s generated results to the parent program to produce new candidate programs. Then, a cascaded evaluation mechanism starts: first run on a small, fast set of test cases to quickly filter out programs with errors or extremely poor performance; after passing the preliminary screening, conduct formal evaluation on a more comprehensive, more time-consuming test set. This layered strategy balances efficiency and accuracy.

   - Database update and evolutionary strategy: New programs and their scores are fed into the program database. The database management strategy draws inspiration from advanced evolutionary algorithms like MAP-Elites, aiming to simultaneously maintain an “elite archive” (the best in each performance region) and overall diversity, balancing “exploitation” (deepening known advantageous regions) and “exploration” (trying entirely new possibilities).

- Step 4: Iteration and convergence

As the loop continues, the performance of algorithms in the program database continuously improves. The evolutionary process can stop after reaching a preset performance threshold, or human researchers can intervene to examine the evolved algorithms and extract new mathematical insights.

AlphaEvolve was applied to the same tensor decomposition problem as AlphaTensor, but it adopts a higherorder “meta-search” strategy. The uniqueness of this strategy lies in changing the fundamental question of “what to search,” including:

- Transition of the search object: In AlphaTensor, the user directly searches for the decomposition factors ( **u** _,_ **v** _,_ **w** ) themselves. But in AlphaEvolve, the user does not ask the LLM to directly output decomposition factors; instead, they ask it to evolve a “program that can find tensor decompositions.”

- The initial program can be very simple—for example, an off-the-shelf gradient descent optimizer using the Adam optimizer to minimize the reconstruction loss _∥T −_ **u** _⊗_ **v** _⊗_ **w** _∥_[2] , with a preset rank _R_ . This program itself may not be efficient, but it is the starting point for evolution.

- Transition of the evaluation object: Correspondingly, the evaluation function no longer directly measures the quality of the decomposition but measures the performance of this “decomposition-finding algorithm.” Specifically, the evaluation function runs the evolved algorithm, attempting it on multiple target tensors (e.g., _T_ 4 _,_ 4 _,_ 4) and multiple random seeds, returning the best rank it can find and the success rate of achieving that rank. This evaluation method incentivizes the evolution of more powerful, robust optimization algorithms—those that can stably and repeatably discover high-quality decompositions.

- The role of the LLM: In this framework, the LLM reads the current best-performing “decompositionfinding algorithms,” understands their structure (e.g., what optimizer is used, what regularization terms are in the loss function, how initialization is done, whether random restarts are included, etc.), and then proposes modifications. These modifications can be very deep, far beyond the scope of daily adjustments by human experts, for example:

   - Changing gradient descent to a quasi-Newton method for faster convergence;

- Adding regularization terms promoting coefficient discretization to the loss function, guiding the algorithm to find decompositions with concise coefficients;

- Designing an alternating projection algorithm iterating between factor space and tensor space;

- Even writing a small search logic mimicking the AlphaTensor style, combining local search with global planning.

The workflow of AlphaEvolve is shown in Figure 3.1 (cited from [alpha evolve paper]).

**Figure 3.1:** AlphaEvolve Workflow

The reason the LLM can make these creative modifications is that it has “read” a vast amount of algorithm code, optimization literature, and mathematical knowledge during its pre-training. It is not imagining out of thin air but performing well-founded combination and innovation within a huge prior knowledge base.

- On the matrix multiplication problem, AlphaEvolve achieved results complementary to AlphaTensor and,

- in some aspects, more historically significant:

   1. **Broad matching and surpassing** : Among the 54 tested matrix multiplication sizes, the programs discovered by AlphaEvolve matched known best results in 38 cases and achieved substantial improvements in 14 sizes. For example, it reduced the multiplication count for _⟨_ 2 _,_ 4 _,_ 5 _⟩_ from 33 to 32, and for _⟨_ 3 _,_ 4 _,_ 7 _⟩_ from 66 to 63. Although these improvements are numerically small, in the field of algorithm optimization, each reduction of “1” may signify a breakthrough in theoretical bounds.

   2. **Historical breakthrough: rank-48 algorithm for** 4 _×_ 4 **complex matrices** : This is AlphaEvolve’s most striking achievement. It discovered the first rank-48 algorithm for computing 4 _×_ 4 matrix multiplication over the complex field (and also the real field). Since the Strassen algorithm was proposed in 1969, the best record for 4 _×_ 4 matrices over general number systems has been rank-49 (the result of two-level Strassen recursion). This record stood for over half a century, attempted by countless mathematicians without success. AlphaEvolve changed this record to 48, leading recursively to an algorithm with complexity approximately _O_ ( _N_[log][4][ 48] ) _≈ O_ ( _N_[2] _[.]_[792] )—a new matrix multiplication method faster than the Strassen algorithm.

The true power of AlphaEvolve lies in its generality. Matrix multiplication is just the first showcase of its capabilities. In broader mathematical and engineering fields, it has also demonstrated astonishing potential.

1. Mathematical construction problems: The research team tested AlphaEvolve on over 50 open problems from analysis, combinatorics, number theory, and geometry. The results are stunning:

   - On about 75% of the problems, it rediscovered known best constructions—this validates the method’s reliability.

   - On about 20% of the problems, it discovered new, provably better constructions—this demonstrates the method’s creativity.

Specific cases include:

- Improved the upper bound for the Erdős minimal overlap problem, slightly improving the previous record. Increased the known lower bound for the kissing number problem in 11-dimensional space from 592 to 593. The kissing number problem studies how many disjoint spheres of equal size can simultaneously touch a central sphere, and is extremely difficult in high-dimensional spaces.

- Improved the best-known densities or sizes for various geometric packing problems (e.g., hexagonal packing, packing circles in a circle, Heilbronn triangle problem).

The key to its methodology is: AlphaEvolve is designed to evolve “heuristic search algorithms,” not directly evolve “mathematical constructions” themselves. Each evolved program is required to perform local search and optimization based on the previous best construction within a fixed time. This multi-stage, adaptive strategy enables it to automatically attack complex optimization problems that are difficult for traditional methods to handle.

2. Critical engineering optimization: This is one of the most astonishing application scenarios of AlphaEvolve: it can optimize complex engineering systems without any prior hardware knowledge, solely through automatic evaluation feedback.

- Data center scheduling: Evolved a simple heuristic function for Google’s Borg cluster management system to evaluate machine fitness during scheduling. This AI-evolved function reclaimed an average of 0.7% of global computing resources—in a hyperscale data center, this means huge cost savings and value creation.

- AI training kernel optimization: Evolved a “tiling strategy” heuristic for the key matrix multiplication kernel training the Gemini large model. Tiling is a core technique for optimizing the runtime speed of matrix multiplication on hardware, but the optimal tiling strategy is highly dependent on hardware architecture. Without being told any hardware details, AlphaEvolve, through automatic feedback from runtime, found tiling strategies superior to those designed by human experts, improving kernel speed by an average of 23% and reducing overall training time.

- Hardware circuit design: In highly optimized TPU arithmetic circuit Verilog code, AlphaEvolve discovered simplification schemes that could remove redundant logic.

- Compiler intermediate code optimization: Directly optimized the intermediate representation code generated by the XLA compiler for the Transformer attention mechanism, improving execution efficiency. This means it not only optimizes at the algorithmic level but can also delve into the compiler level to optimize how code is actually executed.

These cases collectively prove one point: AlphaEvolve is a powerful, general-purpose “scientific discovery and engineering optimization engine” that combines the creativity of cutting-edge large language models with the reliability of automatic evaluation. It is not confined to specific mathematical problems but can be applied to any domain that can be expressed as a program and automatically evaluated.

AlphaTensor and AlphaEvolve represent two different but complementary paradigms for AI-driven algorithm discovery. They start from disparate origins, ultimately converge on solving the same class of core problems, and exhibit their own characteristics and potential.

**Table 3.1:** Methodological Comparison of AlphaTensor and AlphaEvolve

|**Dimension**|**AlphaTensor**|**AlphaEvolve**|
|---|---|---|
|Core Method|Deep Reinforcement Learning (based|Large Language Model-guided pro-|
||on<br>AlphaZero/MCTS),<br>customized|gram evolution, employing a general|
||for a specific problem formalization|problem-solving framework|
||(game)||
|Problem Formalization|Formalizes “finding decomposition” as|Formalizes<br>“solving<br>the<br>problem”|
||a single-player game (TensorGame),|as a code optimization task, state/-|
||state is a tensor, action is a rank-one fac-|knowledge is implicit in the program|
||tor|database, action is code modification|
|Search Space|Directly searches the solution space (de-|Searches the meta-space (programs that|
||composition factors**u**_,_**v**_,_**w**)|can generate or find solutions)|
|Core Technology|Specialized<br>neural<br>network<br>(Trans-|General large language model (e.g.,|
||former variant designed for tensors),|Gemini), its knowledge comes from|
||trained via reinforcement learning|pre-training, invoked via prompt engi-|
|||neering and in-context learning|
|Advantages|Highly targeted, high search efficiency;|Extremely flexible, requires almost no|
||good theoretical guarantees; extreme|modification of the core framework for|
||performance within the target domain|different problems; can handle com-|
|||plex, multi-component codebases; can|
|||seamlessly incorporate rich natural lan-|
|||guage domain knowledge; outputs are|
|||often more interpretable and deploy-|
|||able|
|Limitations|Requires designing specialized game|Heavily reliant on the existence and|
||rules, state representations, and reward|quality of the automatic evaluation|
||functions for each new problem; neural|function; evolutionary process can be|
||network architecture is tightly coupled|slow and depends on LLM generation|
||with the problem, high migration cost|quality; may have high computational|
|||resource requirements|
|Output Nature|Direct mathematical objects (decompo-|Programs that generate those mathe-|
||sition factors), immediately convertible|matical objects, or directly optimized,|
||to an algorithm|runnable code|



These two paradigms are not in competition but constitute two poles of a methodological spectrum. They each capture different aspects of intelligent search—AlphaTensor represents “focused depth,” AlphaEvolve represents “breadth and flexibility.” In the future, these two paradigms are likely to move towards deep integration:

- Complementarity of search levels: AlphaTensor searches at the “object level,” AlphaEvolve searches at the “meta level.” The latter can be seen as a generalization and abstraction of the former. An interesting idea is: using AlphaEvolve to evolve a better AlphaTensor—for example, evolving more effective neural network architectures, cleverer reward function designs, or even new MCTS variants. In this way, metalevel evolution provides better tools for object-level search, and object-level discoveries in turn enrich meta-level knowledge.

- Building hybrid workflows: A powerful human-machine collaborative research paradigm might look like this:

- Exploration phase: Use a system like AlphaEvolve for broad, heuristic exploration, quickly generating a large number of candidate ideas or rough algorithms. The focus of this phase is breadth— covering as many different possibilities as possible, identifying promising directions.

- Deepening and verification phase: For promising candidate directions, use more specialized, powerful methods (like a customized AlphaTensor-style reinforcement learning) for focused, in-depth search and optimization. The focus of this phase is depth—pushing as close to the optimal solution as possible in selected directions. Simultaneously, use formal verification tools to ensure the correctness of final results.

- Interpretation and conjecture phase: From high-performance algorithms or objects discovered by AI, humans and AI collaborate to extract patterns, symmetries, and potential new mathematical conjectures. AI may have discovered a new structure, and human mathematicians are responsible for understanding the mathematical principles behind this structure and formalizing them into provable theorems.

- Feedback and iteration phase: New insights from human mathematicians are formalized into new constraints, heuristics, or evaluation criteria, fed back to the AI system, initiating a new round of more efficient search. Thus, human intuition and AI search capabilities form a positive feedback loop, mutually enhancing each other.

AlphaTensor and AlphaEvolve together depict such a future: algorithm discovery is no longer an occasional flash of inspiration but a systematically advanceable, deeply human-machine intelligent collaborative exploration process. In this future, AI does not replace mathematicians’ thinking but expands the boundaries of mathematicians’ capabilities—they are responsible for probing possibilities in vast spaces difficult for humans to reach, while humans are responsible for understanding, refining, and proving. It is precisely this synergy that constitutes the core appeal of the emerging field of AI for Math.

The work of AI discovering mathematical laws is burgeoning, with achievements emerging one after another. Limited by space, we cannot detail them all. Interested readers can refer to the references at the end of this chapter, which include important recent advances in this field.

### References

- [1] Charles Blundell et al. “Towards combinatorial invariance for Kazhdan-Lusztig polynomials”. In: _Representation Theory of the American Mathematical Society_ 26 (2022), pp. 114–141.

- [2] Peter Bürgisser, Michael Clausen, and Mohammad Amin Shokrollahi. _Algebraic complexity theory_ . Vol. 315. Springer Science & Business Media, 1997.

- [3] Tianlong Chen et al. “Learning to optimize: A primer and a benchmark”. In: _Journal of Machine Learning Research_ 23.189 (2022), pp. 1–59.

- [4] Alexander Chervov et al. “CayleyPy RL: Pathfinding and Reinforcement Learning on Cayley Graphs”. In: _arXiv preprint arXiv:2502.18663_ (2025).

- [5] Alexander Chervov et al. “A Machine Learning Approach That Beats Large Rubik’s Cubes”. In: _arXiv preprint arXiv:2502.13266_ (2025).

- [6] Stephen G Coppola. _An annotated bibliography of fast matrix multiplication_ . Available online. 2024.

- [7] Alex Davies et al. “Advancing mathematics by guiding human intuition with AI”. In: _Nature_ 600.7887 (2021), pp. 70–74.

- [8] Alex Davies et al. “The signature and cusp geometry of hyperbolic knots”. In: _Geometry & Topology_ (2024).

- [9] Bin Dong et al. “Machine Learning Assisted Exploration for Affine Deligne–Lusztig Varieties”. In: _Peking Mathematical Journal_ (2025).

- [10] Alhussein Fawzi et al. “Discovering faster matrix multiplication algorithms with reinforcement learning”. In: _Nature_ 610.7930 (2022), pp. 47–53.

- [11] Julian D Laderman. “A noncommutative algorithm for multiplying 3 _×_ 3 matrices using 23 multiplications”. In: _Bulletin of the American Mathematical Society_ 82.1 (1976), pp. 126–128.

- [12] Robert Lange, Yuki Imajuku, and Edoardo Cetin. “ShinkaEvolve: Towards Open-Ended and SampleEfficient Program Evolution”. In: _arXiv preprint arXiv:2509.19349_ (2025).

- [13] Gang Liu et al. “Scientific Algorithm Discovery by Augmenting AlphaEvolve with Deep Research”. In: _arXiv preprint arXiv:2510.06056_ (2025).

- [14] Alexander Novikov, Ngân Vũ, Martin Eisenberger, et al. “AlphaEvolve: A coding agent for scientific and algorithmic discovery”. In: _arXiv preprint_ (2024).

- [15] Bernardino Romera-Paredes et al. “Mathematical discoveries from program search with large language models”. In: _Nature_ 625.7995 (2024), pp. 468–475.

- [16] Julian Schrittwieser et al. “Mastering Atari, Go, chess and shogi by planning with a learned model”. In: _Nature_ 588.7839 (2020), pp. 604–609.

- [17] David Silver et al. “A general reinforcement learning algorithm that masters chess, shogi, and Go through self-play”. In: _Science_ 362.6419 (2018), pp. 1140–1144.

- [18] Volker Strassen. “Gaussian elimination is not optimal”. In: _Numerische Mathematik_ 13.4 (1969), pp. 354– 356.

## Chapter 4: AI for proving mathematical theorems

### 4.1 Overview

#### 4.1.1 The development history of automated theorem proving

Proving mathematical theorems is the most central activity of the discipline of mathematics. From the axiomatic deduction of Euclid’s _Elements_ , to the logical construction of Whitehead and Russell’s _Principia Mathematica_ , to contemporary mathematicians’ exploration of the Millennium Prize Problems, “proof” has always been the cornerstone of mathematical knowledge—it not only confirms the truth or falsity of a proposition but, more importantly, reveals the profound logical connections between propositions, making mathematics a solid and elegant edifice.

Automated theorem proving is precisely a pursuit in the field of artificial intelligence that has lasted nearly seventy years: enabling machines to derive new conclusions from known axioms and theorems through logical reasoning, much like human mathematicians. The history of this pursuit not only witnesses the evolution of AI technology but also reflects the changing understanding of the fundamental question: “How do machines think?”

The development of automated theorem proving can be roughly divided into three stages, each corresponding to different technical approaches and philosophical reflections on “how machines understand mathematics.” Stage One: Early Exploration and Rule-Based Automation

The fundamental idea of this period originated from the theoretical foundations of computability laid by Turing, Church, and others in the 1930s. Since mathematical reasoning can be formalized as symbolic manipulation, in theory, machines should be able to perform such operations.

In 1956, the “Logic Theorist” program developed by Allen Newell, Herbert Simon, and others became the first realization of this ideal. It successfully proved 38 theorems from Chapter 2 of Russell and Whitehead’s _Principia Mathematica_ —this was the first time a machine demonstrated logical reasoning ability, also marking the birth of artificial intelligence as an independent discipline.

The core methodology of this stage was symbolism and heuristic search. Computers were seen as searchers navigating a “state space” composed of axioms, theorems, and inference rules: the initial state was known facts, the goal state was the theorem to be proved, and each action was the application of an inference rule. However, this method soon encountered a fundamental challenge: combinatorial explosion. Even for moderately complex theorems, the number of possible reasoning paths is astronomical, with the vast majority being dead ends. Early systems heavily relied on carefully designed, domain-specific heuristic rules crafted by mathematicians to guide the search; their “intelligence” was essentially the internalization of human expert knowledge. This dependence meant that the system’s capability boundaries were limited to what humans could foresee and encode in advance, making it difficult to truly break through the human cognitive framework.

Stage Two: The Rise of Interactive Theorem Provers and Formal Mathematics

Faced with the dilemma of combinatorial explosion, the research paradigm underwent a profound shift in the 1970s and 1980s. Researchers gradually realized that, in the foreseeable future, pursuing fully automated proofs might be unrealistic. Instead, they turned to a more pragmatic question: How can computers become guardians of mathematical rigor, rather than replacements for creativity?

This line of thinking gave birth to Interactive Theorem Provers (ITPs), such as Isabelle, HOL Light, Coq, and later Lean. The core design philosophy of these tools is exceptionally elegant: a small, rigorously verified

4.1 Overview

logical “kernel” responsible solely for checking whether each step of a proof conforms to the most basic logical rules, without concern for how those steps were conceived. The mathematician’s work becomes interacting with the prover: using high-level “tactics” to decompose and prove goals, while the prover acts like a tireless proofreader, ensuring every step of reasoning is absolutely rigorous.

This collaborative model had profound implications. On one hand, it allowed mathematicians to focus on high-level insights and strategies, delegating tedious detail-checking to the machine. On the other hand, with the help of ITPs, mathematicians achieved complete formal verification of milestone proofs like the Four Color Theorem and the Kepler conjecture—proofs whose complexity had surpassed the capacity of any human to verify alone.

More importantly, formal mathematics libraries began to be systematically constructed, such as Isabelle’s Archive of Formal Proofs and Lean’s Mathlib. These libraries are high-quality, structured, and absolutely reliable data sources of mathematical knowledge that have been rigorously verified by machines. They provide foundational infrastructure for subsequent AI models—a profoundly significant foundational work that organizes mathematical knowledge in a machine-readable, understandable, and operable form for the first time. Stage Three: The Integration of Large Language Models and Symbolism

The rise of deep learning, particularly the development of large language models and reinforcement learning, has brought new possibilities to automated theorem proving. Researchers realized that the reason human mathematicians can quickly find correct paths in the vast space of reasoning relies not only on logical deduction but also on an ineffable “mathematical intuition”—a vague sense of which proof directions are promising. This intuition might be learnable from data.

Large language models, pre-trained on billions of lines of code and mathematical text, have indeed learned the structure of mathematical language and common reasoning patterns. They can be fine-tuned to take the current proof state as input and predict the next likely effective proof strategy—in other words, they act as heuristic policy networks, providing a sense of direction for the search.

Systems like DeepMind’s AlphaProof have pushed this concept to its extreme. They formalize theorem proving entirely as a reinforcement learning problem:

Environment: Interactive theorem provers like Lean, which provide deterministic state transitions and perfect correctness feedback—an ideal reinforcement learning environment with clear goals (proof completion) and objective rewards (success or failure of the proof).

- Agent: A large neural network that simultaneously learns a policy function (choosing the next tactic) and a value function (evaluating how far the current state is from completing the proof).

- Training: Through self-play on a massive number of automatically generated formal problems, the agent continuously optimizes its proof search strategy, learning to navigate the vast reasoning space efficiently.

This neuro-symbolic integration—combining the reasoning capabilities of neural networks with the absolute rigor of formal systems—represents the current frontier of automated theorem proving.

#### 4.1.2 Core achievements of current AI-assisted theorem proving

The AlphaProof system has achieved remarkable success along this path. At the 2024 International Mathematical Olympiad, it solved three non-geometry problems, including the most difficult Problem 6 of that competition. Combined with its dedicated geometry reasoning system, AlphaGeometry 2, AlphaProof’s overall performance reached a silver medal level. This is the first time artificial intelligence has achieved medal-level performance in a top-tier mathematics competition—and, crucially, every one of its proofs has been fully verified by the Lean kernel, possessing absolute logical reliability.

Behind this breakthrough lies a series of methodological innovations:

- Automated Formalization: Utilizing large language models to transform vast numbers of natural language mathematical problems into formal propositions, constructing a training set containing tens of millions of problems, thereby breaking through the bottleneck of manual formalization. This means the system can “read” and “understand” mathematically described problems in natural language and convert them into a symbolic form it can operate on.

- Neural-Guided Proof Search: Combining the pattern recognition capabilities of neural networks with the lookahead planning capabilities of Monte Carlo Tree Search, significantly improving search efficiency in the vast proof space. The neural network tells the search “where might be worth exploring,” while the tree search is responsible for systematically evaluating and comparing different paths.

- Test-Time Reinforcement Learning: For a single extremely difficult problem, the system can perform targeted reinforcement learning by quickly generating variants of it, enabling “specialized training.” This capability allows the system to dynamically adapt to the characteristics of the problem, demonstrating powerful adaptive ability.

#### 4.1.3 Core limitations and future challenges

Despite significant achievements, current AI theorem proving systems still face fundamental challenges:

Computational cost and accessibility are practical issues. Systems at the level of AlphaProof require enormous computational resources for training and operation (especially test-time reinforcement learning). This makes them more akin to “national laboratory-level” research apparatuses rather than tools that ordinary researchers or students can use daily. How to reduce computational costs and democratize this technology is an urgent problem to solve.

The dependence on formalization infrastructure is equally significant. The system’s capability boundaries are limited by the coverage of formal mathematics libraries. Currently, successes are mainly concentrated in competition mathematics and classical mathematics areas with well-established formalizations. Formalizing new concepts and theories from cutting-edge mathematical research is itself an extremely time-consuming and expertise-intensive endeavor—creating a paradox: AI needs formalized data to learn, but formalized data requires substantial human effort to create.

Perhaps the most profound challenge lies in the gap from “problem-solving” to “theory-building.” Current AI, no matter how powerful, is essentially a super strategy searcher and combinatorial optimizer. It operates within a relatively closed formalized knowledge system to solve given problems, rather than engaging in pioneering exploration. The work of human mathematicians extends far beyond solving given problems—they also pose new questions, identify meaningful patterns, evaluate the value of different mathematical directions (socalled “mathematical taste”), and even create entirely new concepts and theoretical frameworks. These activities require a level of metacognitive ability that current technology is far from achieving.

The history of automated theorem proving is an evolution from symbolic search to neural learning, from independent verification to human-machine collaboration. Systems represented by AlphaProof, through the deep integration of the “intuition” of large language models with the “rigor” of formal systems, have for the first time enabled machines to reach a level of high-quality mathematical reasoning close to that of human experts. Although the road ahead remains long, especially in terms of high-level creativity and theory-building, it has already opened a new door for mathematical research.

### 4.2 Mathematical capabilities of large language models: Technical implementation

The mathematical reasoning capabilities exhibited by large language models do not stem from some mysterious “mathematical intuition,” but are the result of a rigorous, engineerable training pipeline. This pipeline begins with the infusion of vast knowledge, guides the model to understand task formats, and ultimately achieves precise alignment with specific objectives through reinforcement learning. Understanding this pipeline is to understand the source and boundaries of current AI mathematical capabilities. The mathematical capabilities of modern large language models are typically acquired through a carefully designed three-stage training pipeline. Each stage has its unique data composition, algorithmic objectives, and focus on capability shaping.

Stage One: Large-scale Pre-training – Building the “Knowledge Foundation”

The starting point for any capability is knowledge. The goal of the pre-training stage is to make the model a “knowledgeable” general learner.

- Data: Massive unlabeled corpora. The model is exposed to text data on the scale of trillions of tokens, covering high-quality web pages, books, academic papers, open-source code, etc. Scale is key – only with sufficient data can the breadth and depth of human knowledge be covered.

- Algorithm: Next-token prediction and the Transformer architecture. The core task of pre-training appears simple: given the preceding context, predict the next most likely token. However, this “simple” task, with sufficiently large models and data, gives rise to astonishing emergent capabilities. The engine powering this process is the Transformer architecture, whose self-attention mechanism allows the model to dynamically evaluate relationships between all tokens in a sequence, efficiently capturing long-range dependencies and complex patterns. Through distributed training on large-scale clusters, the model’s hundreds of millions or even hundreds of billions of parameters gradually learn the ability to map text into a high-dimensional semantic space.

This stage produces a “knowledgeable but undisciplined” base model. It possesses a rich reservoir of knowledge, knowing a vast number of facts, formulas, and reasoning patterns about mathematics, but it does not yet understand specific task formats – you can ask it any question, and its response might be factual, fictional, or completely irrelevant. It needs further “disciplining.”

Stage Two: Supervised Fine-tuning – Teaching “Task Format” and “Chain-of-Thought”

If pre-training is about instilling knowledge, then supervised fine-tuning is about teaching the model how to “use” this knowledge to respond to human instructions.

   - Data: High-quality instruction-response pairs. Researchers construct tens of thousands to hundreds of thousands of carefully crafted (instruction, input, expected output) data pairs. For example, the instruction is “Solve the equation: 2 _x_ + 5 = 13”, and the expected output is “ _x_ = 4”. These data demonstrate how the model should respond to different types of tasks.

   - Algorithm: Supervised instruction fine-tuning. The base model is fine-tuned in a supervised manner using this instruction data. This process essentially teaches the model a new conditional probability distribution: _P_ (output _|_ instruction _,_ input). The model gradually learns that when it sees the instruction “solve the equation,” it should output a numerical answer; when it sees the instruction “prove,” it should output a sequence of logical derivations.

- Chain-of-thought fine-tuning is a key innovation for eliciting the model’s explicit reasoning capabilities. Standard instruction fine-tuning only requires the model to output the final answer, whereas chain-of-thought finetuning requires the model to output a complete solution including step-by-step reasoning. For example, for the same equation problem:

- Standard fine-tuning output: _x_ = 4

- Chain-of-thought fine-tuning output: First, subtract 5 from both sides of the equation to get 2 _x_ = 8. Then, divide both sides by 2 to get _x_ = 4. Therefore, the answer is 4.

By learning from a large amount of such chain-of-thought data, the model internalizes the paradigm that “for complex problems, logical derivation steps should be shown before the final answer.” This does not grant the model a new reasoning ability but guides the logical abilities already implicitly learned during pre-training to be expressed explicitly through demonstration data. This explicit reasoning process not only makes the model’s decisions more interpretable but also provides intermediate steps that can be evaluated for subsequent reinforcement learning.

After this stage, the model transforms into a “student who follows instructions and can show its thought process.” However, the optimization objectives for its output – such as conciseness, rigor, or innovativeness – are not yet precisely defined. It knows how to answer, but not yet what constitutes the best answer.

Stage Three: Reinforcement Learning – Achieving “Precise Task Alignment”

The goal of the third stage is to strongly align the model’s output with specific, objectively evaluable task objectives. Its core is designing a rule-based reward function and then optimizing the model via reinforcement learning so that its behavior becomes highly consistent with these rules.

**Design of the Reward Function** : The reward function _R_ needs to automatically score the model’s output based on a set of clear rules. The design of the reward function directly determines the behavior the model ultimately learns.

- **For computational problems** : The reward function is usually very simple and deterministic. The rule is: _R_ (output) = 1 if the final numerical answer is correct, otherwise _R_ (output) = 0. The system can automatically extract the final numerical answer from the model’s output and compare it with the standard answer.

- **For logical proof problems** : The design of the reward function is much more complex, representing the current technological frontier.

   - **Formal verification** : In formal mathematics settings, the strictest rule is to submit the entire proof process output by the model (e.g., Lean or Coq code) to a theorem prover kernel for verification. The rule is: _R_ (output) = 1 if the prover fully accepts the proof, otherwise _R_ (output) = 0. This is the core method used by systems like AlphaProof, providing an absolutely reliable correctness signal.

   - **Challenges with natural language proofs** : For informal natural language proofs, automatically judging the validity of each reasoning step is extremely difficult. A compromise method is to check whether key reasoning steps appear in the proof (e.g., “used induction,” “applied the Cauchy-Schwarz inequality”), or to use another verification model to check the logical consistency between steps. However, the completeness and reliability of such rules are limited.

- **The dilemma of judging innovativeness** : It is currently almost impossible to effectively evaluate innovativeness through automated rules. Innovativeness involves the degree of “difference” from known proofs, the “cleverness” of conception, etc. These are high-level, fuzzy semantic concepts difficult to quantify as deterministic reward signals.

- **Reinforcement Learning Algorithm** : Policy gradient algorithms like Proximal Policy Optimization (PPO) are typically used. The process is: treat the supervised fine-tuned model as the policy to be optimized; for a task prompt, the policy model generates an output; the rule-based reward function automatically scores this output; the PPO algorithm uses this reward signal to update the model parameters, making it more likely to generate outputs that receive high scores in the future.

This method is direct and efficient, particularly suitable for tasks where objectives can be clearly quantified. It strongly binds the model’s behavior to the objective metric of “correctness,” achieving a leap from “knowing how to answer” to “knowing how to answer correctly.”

Although rule-based reinforcement learning provides a clear alignment direction for the model, its limitations are fully exposed in complex reasoning tasks. Understanding these limitations helps us accurately grasp the boundaries of current AI mathematical capabilities.

1. Ambiguity and Complexity of Proof Process Judgment Natural language proofs are full of ambiguity for machines. When a model outputs “it obviously follows” or “by a standard lemma,” these expressions may be clear enough for human readers but difficult for machines to verify. The “jumps” common in human proofs – omitting intermediate steps considered “obvious” – need to be fully expanded for machine verification. Automatically judging whether a jump is acceptable requires nearly complete background knowledge, which is itself an AI-complete problem.

2. The Non-computability of Innovativeness Evaluation What is the “innovation” of a proof? Is it using a novel combination of lemmas? Simplifying a known proof? These definitions themselves cannot be fully formalized. To judge whether a proof is novel requires semantic-level comparison with the entire database of existing proofs, which is infeasible in practice. At best, the reward function can reward outputs that are “different from common proof methods in the training data,” but this may be far from genuine mathematical innovation and could even reward incorrect or more verbose proofs.

3. Sparsity of Reward Function and Exploration Challenges In proof tasks, the reward function returns a positive signal (+1) only when the final proof is completely correct; all intermediate steps before that receive a reward of 0. This sparse reward is like searching for a specific planet in the vast universe – the guiding signal is extremely weak, leading to low training efficiency.

A more subtle problem is the trap of local optima. The model may learn to generate safe, verbose proofs that mimic known ones to ensure correctness rewards, but this strategy strongly discourages its motivation to explore more concise, clever new proofs. This runs counter to the “creativity” we desire – the model is guided by the reward mechanism towards conservatism, not innovation.

Surveying the entire training pipeline, we can clearly see the source and boundaries of the mathematical capabilities of current large language models. It is an extremely diligent polymath. Through pre-training, it absorbs the vast mathematical knowledge accumulated by humanity; through supervised fine-tuning, it learns how to respond to mathematical problems in standard formats; through reinforcement learning, it optimizes its behavior to maximize correctness.

However, there remains an essential gap from becoming a pioneering creator with intuition and inspiration. The core of this gap lies in the fact that what we can define and optimize are objectives that can be quantified by clear rules – answer correctness, proof acceptance. But the qualities required for high-level mathematical creation – deep insight, ingenious conception, theoretical taste – are precisely those that cannot be reduced to clear rules.

When we define the reward function as “answer correct,” we optimize for reliability and rigor; but how to define, quantify, and set “creativity” and “deep insight” as optimization objectives remains an unsolved mystery.

This reveals the boundaries of current AI capabilities in mathematical reasoning and general scientific discovery: it excels in closed, rule-defined problem spaces, but to play a role in open, creative work requiring value judgments, fundamental methodological breakthroughs are still needed.

Future progress may depend on how more abstract, higher-order meta-cognitive objectives – such as “elegance of explanation,” “unification of theories,” “depth of concepts” – can be modeled as learnable signals. This is not only a technical challenge but also a rethinking of the fundamental question: “What is mathematical creativity?”

### 4.3 Current success case 1: AlphaProof

After understanding the development history of automated theorem proving and the technical implementation of large language models, we can finally delve into a specific, milestone system: AlphaProof developed by DeepMind. It is not only a top achievement in the current field of AI theorem proving but also a deep integration of many concepts we previously discussed—formalized mathematics, neural-guided search, reinforcement learning—within a unified framework.

AlphaProof solved three high-difficulty problems from the 2024 International Mathematical Olympiad, including the hardest Problem 6 of that competition. Combined with its dedicated geometry system AlphaGeometry2, its overall performance reached a silver medal level. This is the first time artificial intelligence has achieved medal-level performance in a top-tier mathematical competition, and each of its proofs has been rigorously verified by the Lean theorem prover, ensuring absolute logical reliability.

Behind this achievement lies a meticulously designed technical architecture. We will use AlphaProof as the main case study to dissect in detail how it transforms abstract mathematical reasoning into a computable, optimizable problem.

#### 4.3.1 Mathematical model: Viewing theorem proving as a Markov decision process

The starting point for any reinforcement learning system is to formalize a real-world problem into an environment with which an agent can interact. AlphaProof defines theorem proving as the following Markov Decision Process:

- State ( _S_ ): The state _st_ is the “tactic state” of the Lean proof assistant at time _t_ . It is a text string that clearly lists all current goals to be proven and the available hypotheses for each goal. For example, when proving “for all natural numbers _n_ , _n_ is either even or odd”, the initial state might be the goal “ _⊢∀n ∈_ N _,_ Even( _n_ ) _∨_ Odd( _n_ )”. After applying a tactic like “intro _n_ ”, the state becomes “ _n_ : N _⊢_ Even( _n_ ) _∨_ Odd( _n_ )”. This textual representation contains all information about the problem structure—it tells the agent: what you have (hypotheses) and what you need to prove (goals).

- Action ( _A_ ): An action _at_ is a Lean tactic that can be executed in the current state _st_ , also represented as a text string. Tactics can be basic (such as `intro` , `apply` , `have` , `exact` ) or complex combined automated strategies (such as `linarith` , `ring` ), or even user-defined ones. The action space is open and vast—this is precisely the richness of mathematical proof.

- State Transition ( _P_ ): The transition function _P_ ( _st_ +1 _|st, at_ ) is defined by Lean’s proof assistant execution engine and is deterministic. Given the current state and a tactic string, Lean attempts to execute it. If the tactic is legal and successful, the environment transitions to a new proof state _st_ +1; if the tactic is inapplicable or results in an error, the current attempt fails—meaning the agent needs to learn to choose “feasible” actions.

- Reward ( _R_ ): The design of the reward function needs to guide the agent to find proofs that are as short as

- possible. The system assigns a small negative reward for each non-terminal step (e.g., _rt_ = _−_ 1). When the agent successfully completes the proof of the entire theorem, the reduction in cumulative negative reward itself reflects the optimization goal—the fewer steps required to find a proof, the higher the total return. A more sophisticated design handles the case of “subgoals”: if a tactic decomposes a goal into multiple independent subgoals (e.g., proving _P ∧Q_ decomposes into proving _P_ and proving _Q_ ), its return is defined as the sum of the negative step counts of the longest branch among all subgoal proof paths. This encourages the agent to balance the difficulty of each subgoal rather than just optimizing the total number of steps.

- Discount Factor ( _γ_ ): Typically set to 1, because proving is a finite-horizon episodic task, and there is no need for exponential discounting of the future.

The agent’s goal is to learn a policy _π_ ( _a|s_ ) that maximizes the expected cumulative reward (return) over the entire proof episode, which is equivalent to minimizing the average number of steps required to find a proof.

Core Component One: The Proof Network—Understanding State and Generating Intuition

To learn the policy _π_ , the agent needs a model capable of understanding and representing proof states. AlphaProof uses a massive, 30-billion-parameter encoder-decoder Transformer model as its “proof network”. This network plays two key roles, analogous to the two capabilities of a human mathematician:

1. Policy Network: Corresponds to the intuition of “what to do next”. The decoder part of the network, receiving the state representation produced by the encoder, outputs a probability distribution _π_ ( _a|s_ ) over possible tactics. This distribution is not uniform; rather, based on patterns learned from millions of training runs, the network “ranks” the tactics most likely to be effective in the current state. It tells the agent: in this proof state, which tactics are more worth trying.

2. Value Network: Corresponds to the evaluation of “how good/difficult is this situation”. Another output head of the network estimates the expected return _V_ ( _s_ ) _≈ E_ [ _Gt|st_ = _s_ ] from the current state _s_ to the final completion of the proof. Intuitively, _V_ ( _s_ ) reflects the “difficulty estimate” of completing the remaining proof. A _V_ value close to 0 means nearing completion; a large negative value means there is still a long way to go, or perhaps a dead end has been reached.

The training of this network is divided into three stages. First is large-scale pre-training on hundreds of billions of tokens of code and mathematical text corpora using standard language modeling, enabling it to grasp the basic syntax of mathematical language and logical structure. Next is supervised fine-tuning on paired data of “state-next tactic” from human-written formal proof libraries like Mathlib, allowing the network to initially learn to imitate common steps of human provers. But the most crucial stage is the subsequent reinforcement learning, which is key for the agent to form its own “intuition”—through millions of trials and errors in self-play, the network gradually learns to distinguish promising proof paths from dead ends.

Core Component Two: Interaction with the Environment and Search—Planning and Trial-and-Error

Having just the proof network is not enough; the policy and value estimates it provides are immediate and local. To find a complete proof, this local intuition needs to be combined with forward-looking search. AlphaProof adopts a Monte Carlo Tree Search algorithm inspired by AlphaZero but with key adaptations for the proving task.

The search process constructs a tree where nodes are proof states and edges are tactic actions. Starting from the initial theorem state (root node), the following cycle is repeated:

Selection: Starting from the root node, recursively select child nodes until reaching a leaf node that is not fully expanded. The selection criterion balances “exploitation” (choosing branches with high value estimates) and “exploration” (choosing branches with few visits but potential), using a formula similar to PUCT, where the prior probability _π_ ( _a|s_ ) from the policy network guides exploration. This mechanism ensures the agent neither rigidly sticks to known good paths nor blindly tries all possibilities.

- Expansion and Evaluation: When a leaf node _sL_ is reached, the proof network is called to generate _K_ candidate tactics for it (sampled according to the policy distribution), and their execution is attempted in the Lean environment. Each successful tactic produces a new child node (a new proof state). Then the value network evaluates this new state _sL_ , producing an estimate _V_ ( _sL_ ).

- Backpropagation: The leaf node’s value estimate _V_ ( _sL_ ) is propagated back along the selected path, updating the visit counts and average value estimates for each node-action pair on the path.

A key adaptation is for the common case of “subgoals” in proofs. For example, a tactic might decompose the goal “prove _A ∧ B_ ” into two independent subgoals “prove _A_ ” and “prove _B_ ”. In the search tree, this creates a special “AND node”. From this node, the agent needs to choose which subgoal to tackle first. The search algorithm prioritizes the subgoal with the worst value estimate (i.e., the one that appears most difficult), because the completion time of the entire proof depends on the longest branch—this embodies the proof strategy of “tackling the hardest part first”, consistent with the intuition of human mathematicians.

At the end of the search, based on the visit counts of actions under the root node, an improved policy refined by forward-looking search can be obtained. The agent can then choose its next action accordingly or directly use the proof path found by the entire search tree.

AlphaProof’s exceptional capability stems not only from its sophisticated network and search algorithms but also from its revolutionary training paradigm, particularly two core ideas: building a large-scale training curriculum through automated formalization, and test-time reinforcement learning.

#### 4.3.2 Core innovation one: Automated formalization and large-scale curriculum learning

To make a reinforcement learning agent powerful, it needs to be “well-informed”—to practice on an extremely diverse and massive set of problems. However, manually formalizing mathematical problems into Lean is an extremely time-consuming task. AlphaProof’s method to break this bottleneck is automated formalization. It uses a fine-tuned large language model (based on Gemini) to automatically translate approximately 1 million natural language mathematical problems (from a wide range of sources, from middle school math to Olympiad problems) into Lean statements. This process does not require 100% accuracy, because even if the translation is biased, the generated Lean statement itself is a syntactically correct, verifiable new mathematical proposition. This system ultimately generated about 80 million formalized problems, constituting an unprecedented, massive-scale training dataset.

A central “matcher” system dynamically selects problems from this database and assigns them to distributed “executor” agents to attempt to prove or disprove. Problem selection priority is based on “interestingness”— problems that are unsolved, or sometimes solvable and sometimes not, are prioritized. For problems that fail after multiple attempts, the system allocates more computational resources (search simulations) to tackle them. The successful proof/disproof data (state-tactic sequences) generated by agents during attempts are collected and used to continuously update the parameters of the proof network. This process forms a positive feedback loop: the stronger the agent’s problem-solving ability, the more diverse and difficult problems it can solve, thereby generating higher-quality training data, which further improves the network. This learning from large-scale, autonomously generated experience is key to AlphaProof surpassing previous supervised learning methods based on fixed datasets.

**Core Innovation Two: Test-Time Reinforcement Learning**

Even after large-scale training, when facing a brand-new, extremely difficult Olympiad problem, a generalpurpose agent may still fail to find a proof within a limited search budget. Another breakthrough of AlphaProof is the introduction of Test-Time Reinforcement Learning (TTRL). The idea is simple yet powerful: since general training gives the agent broad mathematical capabilities, can we conduct a brief, intensive “special training” for a single “hard nut” problem?

The specific process is as follows: When presented with a target difficult problem _T_ , the system first automatically generates a large, related set of “variant problems” _{VT }_ around _T_ . These variants are generated by a large language model and could be simplified versions of _T_ (e.g., removing a condition), analogical versions (e.g., replacing an algebraic structure with a topological one), generalized versions, or those obtained by programmatically making minor perturbations to the assumptions of _T_ . These variants, together with _T_ itself, constitute a tailored training curriculum for that specific problem.

Then, AlphaProof initiates a focused reinforcement learning loop, but this time the training data is no longer the 80 million general problems, but only the set of _T_ and its variants. The agent (initialized from a trained general model) rapidly performs self-play and learning on this small-scale, highly relevant curriculum. This process may last for several days, consuming significant computational resources.

The result is that the agent can deeply adapt to the specific mathematical structures and difficulties involved in _T_ , often discovering proof strategies that the general model could not find even after searching for days. This mimics the behavior of human mathematicians working on a difficult problem: trying various special cases, searching for lemmas, generalizing from simple cases. Test-time reinforcement learning successfully automates this mechanism of “problem-specific” deep exploration.

AlphaProof demonstrates its powerful capabilities in multiple dimensions:

- Solving High-Difficulty Problems: In the 2024 International Mathematical Olympiad, it solved three nongeometry problems, including the hardest Problem 6 of the competition. Combined with its dedicated geometry system AlphaGeometry 2, its total score reached a silver medal level. This is the first time artificial intelligence has achieved medal-level performance in a top-tier mathematical competition.

- Verified Reliability: All outputs are formal proofs verified by the Lean kernel; their reliability is equivalent to the mathematical axiomatic system itself, completely eliminating “hallucinations” or specious reasoning.

- Discovering Novel Proofs: Through reinforcement learning and self-play, the agent sometimes finds proof paths that are different from known human proofs but equally correct and potentially more concise. This capability goes beyond mere imitation, exhibiting a certain sense of “creativity”.

- Efficiency Improves with Experience: As training progresses, the agent not only becomes more capable of solving problems but also requires fewer search steps to solve the same problems, indicating that its value and policy networks indeed learn more effective heuristics. It is not only “doing it right” but also “doing it better”.

However, while appreciating these achievements, we must also be soberly aware of AlphaProof’s current limitations:

- Massive Computational Cost: Both the training phase (tens of thousands of TPU-days) and the test-time reinforcement learning for a single problem (several TPU-days) require enormous computational resources, far exceeding the typical budgets of academic institutions. This makes AlphaProof more akin to a “national laboratory-level” research apparatus rather than a tool usable by ordinary researchers, raising concerns about accessibility and reproducibility.

- Domain Still Limited: Current successes are mainly concentrated within the scope of Olympiad mathematics and lower-division undergraduate competition mathematics. Although these problems are difficult, they belong to a “closed world”—all necessary concepts and theorems are already well-formalized in libraries like Mathlib. Extending the system to the frontiers of mathematical research faces significant challenges, as that involves defining new concepts and proposing new conjectures, not merely solving already formalized problems.

- Shortcomings in Geometry Handling: Due to insufficient support for Olympiad-style plane geometry in current formal geometry libraries (Mathlib), AlphaProof had to delegate geometry problems to the specialized AlphaGeometry 2 system. While this “division of labor” solves the problem, it also exposes that the development of formal mathematical libraries itself is a major challenge: if knowledge in a certain domain has not yet been formalized, AI cannot access it.

- The Nature of “Creativity” is Debated: AlphaProof’s “creativity” is mainly manifested in searching and combining existing knowledge to find new paths. This is still fundamentally different from the “high-level creativity” of human mathematicians who propose entirely new concepts and construct new theoretical frameworks. As revealed by benchmarks like DeepMath-Creative, current large language models still frequently exhibit directional errors, logical flaws, or ineffective lengthy reasoning when faced with tasks requiring truly constructive thinking (such as constructing specific counterexamples) or open-ended problems. Their performance heavily relies on memorizing and recombining patterns in the training data, rather than deep conceptual understanding or genuine inspiration. Is this “creativity” a new form of intelligence or merely clever recombination of existing knowledge? This question will likely accompany the entire development journey of AI for Math.

The success of AlphaProof marks a key leap for automated theorem proving from “toy problems” to “competition-level difficult problems”. It proves that the path of neuro-symbolic integration is feasible—the intuition guidance of neural networks, combined with the rigorous verification of formal systems, can yield superior performance. However, the road ahead from Olympiad problems to research frontiers, from problemsolving to theory-building, remains long. Nonetheless, a new door has undoubtedly been opened.

### 4.4 Current success case 2: LLM-based agents

Mathematical research has long relied on the intuition, reasoning, and creativity of individual mathematicians. However, with the rapid advancement in the capabilities of large language models (LLMs), a new research paradigm is emerging, where AI agents are deeply involved or even lead mathematical discovery. This section briefly introduces Aletheia: a mathematical research agent built upon Gemini Deep Think. It can perform iterative generation, verification, and correction for research-level mathematical problems and has successfully produced mathematical papers entirely generated by AI.

An agent based on a large language model refers to a system that uses a large language model as its core, integrated with mechanisms such as planning, memory, and tool usage, enabling it to perceive its environment, make autonomous decisions, and execute complex tasks. Aletheia is precisely an agent designed following this concept. Its architecture revolves around three core pillars, allowing it to handle high-difficulty reasoning while leveraging external tools to ensure the accuracy and verifiability of results.

First, Aletheia is equipped with Gemini Deep Think as its deep reasoning engine. This is an advanced language model optimized for complex mathematical and logical reasoning, possessing powerful multi-step deduction capabilities and long-context understanding. It can handle Olympiad-level challenging problems and doctoral-level specialized questions while remembering and relating multiple intermediate results. Second, it implements reasoning-time extended computation, continuously deepening through multiple rounds of “thinkverify-correct” loops until reliable conclusions are reached. Furthermore, Aletheia deeply integrates Google Search and web browsing functionalities, enabling it to verify theorems in real-time, search literature, avoid fabrication errors, and check complex expressions using external computational tools. This tool-calling mechanism liberates the model from closed knowledge recall, allowing it to explore based on the latest information, thereby effectively ending “hallucinations” and literature errors.

Aletheia’s workflow is a typical iterative generate-verify-correct closed loop, applicable to various tasks from specific calculations to theoretical construction:

1. Problem Input: The researcher poses a problem in natural language. For example, “Calculate the eigenweights in the arithmetic Hirzebruch proportionality principle” or “Analyze the current status of Conjecture No. 47 in the Erdős problem database.”

2. Generate Multi-round Reasoning: Based on the input problem, the model first generates a preliminary solution idea or proof sketch. Then, using reasoning-time extended computation, the model deeply deduces each step. If encountering an obstacle, it backtracks and tries a new path. During generation, the model can call search tools at any time to check for known results or verify whether a certain intermediate lemma has already been proven.

3. Verification and Correction: After completing the preliminary result, the model performs self-verification: checking logical consistency and computational correctness. If errors or inconsistencies are found, it returns to the reasoning stage for correction, repeating the iteration until satisfied.

4. Output Solution: Finally, it outputs the complete problem solution, accompanied by the reasoning process and literature citations.

This process may seem simple, but the “autonomous iteration” capability it embodies is a key step in transforming large language models from “question-answering tools” to “research partners.” Aletheia has demonstrated powerful capabilities on several cutting-edge mathematical problems, with the following two cases being the most representative.

Case One: A Fully Autonomously Generated Mathematical Paper

Aletheia’s most striking achievement is that it completely autonomously generated the mathematical content of a mathematical paper, from problem understanding and theory construction to final calculations, without any human intervention.

- Problem Background: Feng, Yun, and Zhang established the (higher) arithmetic Hirzebruch proportionality principle in previous work. This is a profound result linking the arithmetic volume of shtukas moduli stacks to differential operators of L-functions. The formula involves certain structural constants called “eigenweights,” but the original authors only calculated these weights in simple cases; the general case remained unsolved.

- Aletheia’s Contribution: The research team tasked Aletheia with calculating the eigenweights for all classical groups. During exploration, the agent autonomously discovered a profound connection between these weights and the representation theory of symmetric groups. It then used algebraic combinatorics tools (such as Young diagrams, Schur functors) to derive a closed formula for the general case. The entire research process, from problem understanding and theory construction to final calculations, was completed entirely independently by Aletheia.

The significance of this case lies not only in solving a specific problem but also in demonstrating that AI can make conceptual discoveries—it recognized the connection between eigenweights and representation theory and proactively invoked relevant theoretical tools to construct a solution. This goes beyond simple pattern matching or computational execution, entering the core realm of mathematical research.

Case Two: Semi-autonomously Tackling an Open Erdős Problem

If the first case demonstrates the “depth” of AI, the second case demonstrates its “breadth” and “systematicity.”

- Problem Background: The Erdős problem database, compiled by mathematician Bloom, contains about 700 conjectures marked as “open.” These problems vary in difficulty, and many have remained unsolved for a long time due to scattered literature or ambiguous formulation. For human mathematicians, examining these 700 problems one by one is a time-consuming and tedious task.

- Research Strategy: The research team adopted a hybrid approach: AI first performed natural language verification and literature retrieval to narrow the search space, followed by human expert evaluation for correctness and novelty. This collaborative model of “AI preliminary screening + human confirmation” leverages the strengths of both sides: AI is tireless and reads extensively, while humans possess deep judgment and creative understanding.

- Aletheia’s Contribution: Aletheia systematically evaluated all 700 open problems, with remarkable results:

   - Autonomously solved 4 problems: The solutions generated by AI appeared novel and were confirmed correct and previously unrecorded by human experts. These problems themselves may not be extremely difficult, but their “open” status meant no one had successfully solved them before; AI filled this gap.

   - Assisted in identifying existing solutions for 9 problems: Through literature retrieval, AI assisted in discovering that these problems had actually been solved in some obscure papers, which might have been published in niche journals or written in obscure language, thus missed by mainstream databases. Their status was updated from “open” to “solved.”

- The research team noted that the “open” status of many of these problems stemmed more from the obscurity of the literature than from their inherent difficulty. In other words, some problems remained unsolved for a long time not because they were too hard, but because their solutions were buried in the vast ocean of literature. AI, with its powerful search and reasoning capabilities, effectively overcomes this. It can not only read and understand but also bridge language and journal barriers to establish connections in knowledge.

The success of the Aletheia agent marks AI’s leap from a “problem-solving tool” to a “research partner.” It combines a deep reasoning engine, reasoning-time extended computation, and tool-calling capabilities to jointly construct an autonomous system capable of handling cutting-edge mathematical problems.

From fully autonomously generating papers to systematically tackling Erdős problems, Aletheia demonstrates that large language models can play a substantive role in mathematical discovery. In the future, with further improvements in model reasoning capabilities and the refinement of tool ecosystems, we can reasonably expect more agents to deeply participate in mathematical research.

### 4.5 Creativity in Large Language Models**

Currently, research on the application of large language models in the field of mathematics is experiencing explosive growth. Mainstream evaluation benchmarks (such as GSM8K, MATH, etc.) and model optimization directions are almost entirely focused on the model’s reasoning ability—that is, whether the model can derive the correct answer step-by-step and solve standardized mathematical problems. The achievements in this direction are exciting, with AlphaProof’s performance on the IMO being the best proof.

However, mathematics is not merely a mechanical combination of logical deduction. The soul of mathematics lies in creativity—proposing unprecedented concepts, inventing ingenious methods, constructing counterexamples that overturn cognition. From the leap from Euclidean geometry to non-Euclidean geometry, from the conceptual extension of integers to complex numbers, from Fermat’s Last Theorem to the final proof of the Poincaré conjecture, every major breakthrough in the history of mathematics has essentially been a victory of creativity. If reasoning ability makes AI an excellent “problem solver,” then creativity is the key to making it a true “mathematician.”

But what is creativity? Can it be evaluated? Do current AI models possess this ability? These questions are becoming the next frontier in the exploration of the AI for Math field.

Currently, academic research on the mathematical creativity of LLMs receives very little attention, lacking systematic evaluation standards and specialized datasets. To scientifically evaluate creativity, we need an operational analytical framework. Drawing on research in the history and philosophy of mathematics, the paper DeepMath-Creative proposes an evaluation model based on three key dimensions:

#### 4.5.1 Dimension one: Generation of new concepts

This is the highest level of creativity, manifested in the introduction of unprecedented mathematical concepts or ideas, thereby opening up entirely new research fields. Concepts are the language of mathematics; the birth of a new concept often signifies a restructuring of the entire discipline.

The emergence of the Riemannian metric laid the foundation for modern differential geometry. It not only defined curvature at an abstract level but, more importantly, provided the precise mathematical language for Einstein’s theory of general relativity—matter tells spacetime how to curve, spacetime tells matter how to move. Without Riemannian geometry, general relativity might have remained at the level of philosophical speculation.

The concept of a differentiable manifold perfectly combines local feasibility of calculus with global complex topological structures. It allows us to perform calculus on curved spaces like spheres and tori, becoming a cornerstone of theoretical physics and geometric modeling. Today, from the manifold hypothesis in machine learning to spacetime models in cosmology, manifolds are ubiquitous.

Group theory was born from Galois’s exploration of the solvability of algebraic equations. This mathematician, only in his twenties at the time, pioneered a completely new structural way of thinking in the manuscripts written on the eve of his duel. Today, group theory unifies the study of symmetry in geometry, algebra, and number theory, with applications everywhere from crystal structures to quantum mechanics.

Topological spaces transcend the traditional concept of distance (metric spaces), defining continuity and proximity solely through “open sets.” This extreme abstraction elevates mathematical analysis to a more fundamental level—it turns out that the essence of continuity lies not in distance, but in the concept of “neighborhood” itself.

#### 4.5.2 Dimension two: Invention of new methods

Another form of creativity is inventing entirely new techniques or tools to solve complex problems that were previously difficult to overcome. New methods often do not directly provide the answer but rather open a path towards it.

For example, the invention of the theory of generalized functions originated from the confusion caused by Dirac’s _δ_ function in quantum mechanics. This function is infinite at one point and zero elsewhere, yet its integral is 1—within the framework of classical function theory, it simply could not be defined. Mathematicians had to break through the inherent notion that “a function is a point-to-point mapping,” viewing functions instead as functional actions on test functions. This breakthrough not only provided a rigorous mathematical foundation for quantum mechanics but also became a core tool in the modern theory of partial differential equations.

The Bochner technique is a milestone in geometric analysis. It cleverly links geometry (curvature) with analysis (the Laplace operator), using curvature conditions to constrain the topological properties of manifolds. This method of “attacking geometry with analysis” provides an elegant pathway for proving many profound geometric theorems.

#### 4.5.3 Dimension three: Creation of new examples

Testing the boundaries of propositions by constructing concrete examples (especially counterexamples) is an important driver for theoretical development. A clever counterexample often deepens our understanding of a concept more than ten positive examples.

In 1956, John Milnor constructed a seven-dimensional manifold that is topologically equivalent to the standard seven-dimensional sphere (homeomorphic) but different in its differential structure (not diffeomorphic). This “exotic sphere” overturned people’s intuitive understanding of high-dimensional spaces—it turns out that different smooth structures can exist on the same topological space. This discovery directly initiated the theory of exotic manifolds and the entirely new field of differential topology.

Earlier, in 1872, Weierstrass constructed a function that is continuous everywhere but differentiable nowhere. Before this, mathematicians generally believed that continuous functions were always differentiable, at least at most points. This counterexample directly challenged the foundations of analysis at the time, forcing mathematicians to re-examine basic concepts like function, continuity, and differentiability, and promoting the rigorization of real analysis theory. It reminds us: intuition may deceive us; only strict logic can guide us to truth.

These three dimensions—new concepts, new methods, new examples—together constitute the complete spectrum of mathematical creativity. They exist at different levels but are equally important. A new concept may open up a field, a new method may solve a batch of problems, and a new example may correct the direction of an era.

The process by which human mathematicians create new concepts and methods (such as drafts, failed attempts, moments of inspiration) is often chaotic, unstructured, and full of chance. It is difficult for us to reconstruct these complex cognitive trajectories into large-scale, standardized datasets suitable for training large language models. More importantly, when a model generates a “novel” concept or method, it is difficult for us to judge: is this genuine originality, or merely a clever recombination of training data? Existing automatic evaluation mechanisms can hardly distinguish between these two situations.

Unlike abstract concepts and methods, concrete, constructible mathematical examples are “tangible.” Whether an example is correct or constitutes a counterexample can be judged through rigorous mathematical verification, which is a unique advantage of the discipline of mathematics. This verifiability provides a relatively objective and feasible standard for evaluating machine creativity.

The value of mathematical creativity extends far beyond solving known problems. Looking back at every leap in the development of mathematics—from the birth of non-Euclidean geometry to the rise of topology, from the proposal of Galois theory to Wiles’s proof of Fermat’s Last Theorem—each is a crystallization of creativity. It is precisely the introduction of new concepts, the invention of new methods, and the construction of new examples that continuously reshape the landscape of mathematics and expand the boundaries of human reason. In the era of artificial intelligence, endowing large language models with mathematical creativity will have even more profound significance: it is not only a touchstone for testing whether machines possess true intelligence, but it may also give rise to an “AI mathematician” or “AI collaborator” capable of exploring mathematical conjectures, generating proof ideas at unprecedented speeds, and even discovering hidden patterns and connections within complex structures beyond human reach, thereby accelerating the process of scientific discovery and driving transformative breakthroughs in mathematics and related disciplines (such as theoretical physics, cryptography, computational biology).

However, on the path to this vision lie major core technical challenges. Among them, the most central problem is the difficulty of defining and designing reward functions that can effectively evaluate mathematical creativity within the reinforcement learning framework. The effectiveness of reinforcement learning highly depends on a clear, quantifiable reward signal that can guide the model to gradually approach the goal. But in the context of mathematical creativity, this requirement encounters fundamental dilemmas:

1. The subjectivity and context-dependence of novelty: What is “novel”? A construction may be unknown to the model itself, but perhaps it is common knowledge to the entire mathematical community. True creativity requires stepping outside the distribution of training data to produce entirely new knowledge with “historical” significance, and the judgment of this novelty often requires deep mathematical insight and cannot be measured by simple statistical indicators (such as dissimilarity from training data). Whether a construction is “clever” or “profound” is a higher-order aesthetic judgment, difficult to formalize into a scalar reward.

2. The unpredictability of long-term impact: Just as the value of the Riemannian metric or exotic spheres was fully recognized only decades later, the true impact of mathematical creation often only becomes apparent in the distant future. At each step of reinforcement learning, the model cannot predict what chain reaction its current construction fragment might produce in the future. This delayed and sparse reward makes traditional optimization methods based on short-term returns (such as policy gradient) almost ineffective.

3. The exponential sparsity of the exploration space: The construction space of mathematical objects (such as manifolds, groups, functions) is infinite and highly unstructured. Truly creative constructions (like the Weierstrass function) are like a drop in the ocean. For a model to randomly wander in such a vast space, it is almost impossible to stumble upon a valuable example by mere “trial and error.” Without effective intrinsic motivation or heuristic guidance, reinforcement learning will fall into endless ineffective exploration.

4. The tension between correctness and creativity: Mathematical creativity must be built on a foundation of logical rigor. A “novel” but self-contradictory counterexample is worthless. Therefore, the reward function must achieve a delicate balance between encouraging novelty and enforcing correctness. Overemphasizing correctness will make the model tend to conservatively replicate known knowledge; overemphasizing novelty may lead the model to generate a large number of meaningless, logically broken constructions. How to design a reward mechanism that can tolerate errors during exploration while ultimately guiding the model towards logical closure is a blind spot in current technology.

5. The evaluation dilemma of process vs. result: The value of mathematical creation is often embedded in the thinking process itself—from vague intuition to rigorous construction, from failed attempts to moments of insight. However, existing reinforcement learning primarily focuses on the final output result (e.g., whether the counterexample is correct). A reward signal capable of capturing the “insight,” “analogical transfer ability,” or “handling of contradictions” demonstrated by the model during the construction process almost does not exist.

These challenges collectively point to a deeper issue: we still lack a computational theory capable of understanding and evaluating mathematical creation. Creativity is not a simple quantifiable metric but a complex, multi-dimensional phenomenon deeply bound to context. To make it a computable, optimizable goal, we need a deeper understanding of creativity itself.

Future research may need to go beyond a single, external reward function, exploring instead composite paradigms such as intrinsic motivation mechanisms (e.g., rewards based on curiosity or information gain), metacognitive mechanisms (allowing the model to learn to evaluate its own thinking paths), and human-machine collaborative evaluation (involving human mathematicians in reward shaping).

Regardless, facing and overcoming this core technical challenge will be the necessary path towards intelligent systems with genuine mathematical creativity. Because ultimately, what we anticipate is not just a machine that can solve problems, but a partner that can think, create, and explore the unknown realms of mathematics with us. This partner may not have moments of inspiration like human mathematicians, but it may discover mathematical truths that are difficult for humans to see alone—through massive exploration, precise pattern recognition, and tireless combination—in a completely different way.

### References

- [1] Mohammed Abouzaid, Andrew J Blumberg, Martin Hairer, et al. “First Proof”. In: _arXiv preprint arXiv:2602.05192_ (2026).

- [2] Josh Achiam et al. _GPT-4 technical report_ . Tech. rep. arXiv preprint arXiv:2303.08774, 2023.

- [3] Zhangir Azerbayev et al. “Llemma: An open language model for mathematics”. In: _The Twelfth International Conference on Learning Representations_ . 2024.

- [4] Maissam Barkeshli, Michael R Douglas, and Michael H Freedman. “Artificial intelligence and the structure of mathematics”. In: _arXiv preprint arXiv:2604.06107_ (2026).

- [5] Xiaoyang Chen and Xiang Jiang. “Can LLM Generate Interesting Mathematical Research Problems?” In: _arXiv preprint arXiv:2603.18813_ (2026).

- [6] Xiaoyang Chen et al. “DeepMath-Creative: A Benchmark for Evaluating Mathematical Creativity of Large Language Models”. In: _arXiv preprint arXiv:2505.08744_ (2025).

- [7] Ziru Chen et al. “Seed-Prover 1.5: Mastering Undergraduate-Level Theorem Proving via Learning from Experience”. In: _arXiv preprint arXiv:2512.17260_ (2025).

- [8] Yuri Chervonyi, Trieu H Trinh, Miroslav Olšák, et al. “Gold-medalist performance in solving olympiad geometry with AlphaGeometry2”. In: _Journal of Machine Learning Research_ 26.241 (2025), pp. 1–39.

- [9] Katherine M Collins, Albert Q Jiang, Simon Frieder, et al. “Evaluating language models for mathematics through interactions”. In: _Proceedings of the National Academy of Sciences_ 121.36 (2024).

- [10] Yihong Dong and X Ma. “STP: Self-play LLM Theorem Provers with Iterative Conjecturing and Proving”. In: _International Conference on Machine Learning_ . 2025.

- [11] Tony Feng. “Eigenweights for arithmetic Hirzebruch Proportionality”. In: _arXiv preprint arXiv:2601.23245_ (2026).

- [12] Tony Feng et al. “Semi-Autonomous Mathematics Discovery with Gemini: A Case Study on the Erdős Problems”. In: _arXiv preprint arXiv:2601.22401_ (2026).

- [13] Tony Feng, Trieu H Trinh, G Bingham, et al. “Towards Autonomous Mathematics Research”. In: _arXiv preprint arXiv:2602.10177_ (2026).

- [14] Simon Frieder et al. “Mathematical capabilities of ChatGPT”. In: _Advances in Neural Information Processing Systems_ . Vol. 36. 2023, pp. 73421–73445.

- [15] K Georgiev et al. “Mathematical Exploration and Discovery at Scale”. In: _arXiv preprint_ (2025).

- [16] Thomas Hubert, R Mehta, L Sartran, et al. “Olympiad-level formal mathematical reasoning with reinforcement learning”. In: _Nature_ 651 (2026), pp. 607–613.

- [17] Yong Lin, Shange Tang, Chi Jin, et al. “Goedel-Prover: A Frontier Model for Open-Source Automated Theorem Proving”. In: _arXiv preprint arXiv:2502.07922_ (2025).

- [18] Jiawei Liu et al. “Numina-Lean-Agent: An Open and General Agentic Reasoning System for Formal Mathematics”. In: _arXiv preprint arXiv:2601.14027_ (2026).

- [19] Filip Marić. “A survey of interactive theorem proving”. In: _Logic in Computer Science II_ . Belgrade: Matematički institut SANU, 2015, pp. 173–223.

- [20] Jason Wei et al. “Chain-of-thought prompting elicits reasoning in large language models”. In: _Advances in Neural Information Processing Systems_ . Vol. 35. 2022, pp. 24824–24837.

- [21] Y Xin et al. “Scaling up Multi-Turn Off-Policy RL and Multi-Agent Tree Search for LLM Step-Provers”. In: _arXiv preprint arXiv:2509.06493_ (2025).

## Chapter 5: AI for constructing counterexamples

### 5.1 Overview

The core driving force of mathematics is not only to prove theorems, but also to delineate their boundaries. Constructing counterexamples is precisely the art of revealing “where a conjecture fails.” A beautiful proof tells us “truth ends here,” while a brilliant counterexample tells us “falsehood begins there.”

Constructing counterexamples is the most subversive art in mathematical logic—it not only declares the end of a path but also delineates the insurmountable boundaries of truth. In the history of mathematics, an ingenious counterexample often reveals the inherent fissures within a concept more powerfully than ten conventional proofs, forcing the revision of axiomatic systems, the reconstruction of definitions, and even giving rise to entirely new research paradigms. Artificial intelligence, through brute-force traversal and intelligent pruning via deep search, reinforcement learning, or generative models, can quietly infiltrate the sparse corners beyond human imagination. This approach does not attempt to replace the mathematician’s stroke of genius that ignites a counterexample with inspiration. Instead, it transforms the discovery of counterexamples from a personal art reliant on serendipitous insight into an engineering process that is scalable and systematically reproducible.

### 5.2 AI constructs counterexamples in graph theory: Based on reinforcement learning

Combinatorics and graph theory are fascinating and challenging branches of mathematics. The objects they study are often discrete, finite, and structured. In these fields, mathematicians have proposed numerous conjectures concerning the relationships between extremal combinatorial and graph parameters. These conjectures typically arise from observations in numerical experiments, inductions from specific instances, or generalizations of known results. They serve as beacons, guiding the direction of exploration.

However, the history of mathematical conjectures tells us: not all seemingly plausible propositions are correct. Determining whether a conjecture holds, especially finding a counterexample to refute it, is often an extremely arduous task. The essence of the problem lies in the vastness of the search space, where the target (a structure violating the conjecture’s conditions) might be just a “needle in a haystack”.

Take graph theory as an example. For a simple undirected graph with _n_ vertices, the number of all possible graphs is 2[(] _[n]_ 2[)] , a number that grows exponentially with _n_ . When _n_ = 20, the number of possible graphs already exceeds 10[57] . Clearly, it is completely infeasible to examine all possibilities through manual enumeration or traditional exhaustive algorithms.

For a long time, mathematicians have relied on intuition, structural insights, and theoretical deduction to guess the possible forms of counterexamples. They also use algorithmic tools such as heuristic search and linear programming for assistance. For instance, for certain problems that can be expressed as linear programs, commercial solvers can find optimal solutions or counterexamples very efficiently. However, many combinatorial problems cannot be concisely expressed as linear programs, or the structure of their search space is very complex, making it difficult for traditional optimization methods to explore effectively.

Thus, we face a core question: when confronted with a vast, discrete, and structurally complex search space where we need to find a “rare” structure satisfying specific (often “pathological” or non-intuitive) conditions,

5.2 AI Constructs Counterexamples in Graph Theory: Based on Reinforcement Learning

does there exist a systematic method that can effectively explore and discover in a “black-box” manner, without relying on deep problem-specific insights?

Such a method should possess the following characteristics: generality (able to handle a wide range of problem formulations), minimal reliance on domain knowledge (reducing dependence on problem-specific heuristics), effective exploration of high-dimensional discrete spaces, and some “learning” ability to accumulate experience from failed attempts. This is precisely the stage where reinforcement learning, especially policy search methods, can play a role.

The core idea of reinforcement learning is to let an agent learn how to perform a sequence of actions through interaction with an environment to maximize cumulative reward. This paradigm can be mapped very intuitively to our mathematical construction problem:

- Agent: An algorithm attempting to construct a mathematical object (e.g., a graph, matrix, set family).

- Environment: Defines the rules for constructing the object (e.g., constructing a simple graph of order _n_ ) and the metric for evaluating the quality of the final object.

- State: At a certain point in the construction process, the partial decisions made so far (e.g., some edges already determined).

- Action: A specific decision the agent can make in the current state (e.g., adding a specific edge next, or not adding it).

- Reward: A score calculated after the entire object is constructed, based on whether it violates the conjecture (or the degree of violation). Our goal is to minimize this score (for lower-bound conjectures) or maximize it (for upper-bound conjectures) to find a counterexample.

Specifically, the process of constructing a combinatorial object can be viewed as generating a string in a certain order. For example, to construct a graph with _n_ vertices, we can consider all possible _n_ 2[edges in a fixed] order, deciding for each edge to “keep” (encoded as 1) or “delete” (encoded as 0). Thus, any graph uniquely corresponds to a binary string of length _n_ 2[.][The agent’s task is to generate this string step by step.]

The key idea is that the agent knows nothing about the “mathematical problem” it is solving. It merely learns a policy—a mapping from the “current generated string fragment” to a probability distribution over the “next character”. This policy is adjusted through trial and error: it generates many complete strings (i.e., constructs many graphs), each receiving a score based on the reward function. Then, the agent analyzes those constructions with high (or low, depending on the goal) scores and adjusts its policy to make decisions more similar to these successful constructions in the future.

To better understand the above method, we introduce Wagner’s work. Wagner chose the deep cross-entropy method as the foundational tool.

The cross-entropy method is essentially an evolutionary algorithm based on policy search. Its core is to maintain a parameterized policy network (typically a neural network) and improve the policy through iterative “generate-evaluate-evolve” steps. We break down its workflow in the context of combinatorial construction.

Suppose we want to construct a discrete object _x_ , generated by a series of decisions _a_ 1 _, a_ 2 _, . . . , aT_ , where _n_ each decision _at_ belongs to a finite action set _A_ . For example, in constructing a graph, _T_ = 2[,] _[ A]_[=] _[{]_[0] _[,]_[ 1] _[}]_[.] There exists a reward function _R_ ( _x_ ) evaluating the quality of the final object _x_ . Our goal is to find the object _x[∗]_ that maximizes (or minimizes) _R_ ( _x_ ).

A policy _πθ_ is a function with parameters _θ_ , which gives the probability distribution over actions given the current partial sequence (state _st_ ): _πθ_ ( _a|st_ ). In the sequential generation setting, the state _st_ is typically the sequence of decisions made so far ( _a_ 1 _, . . . , at−_ 1).

We wish to learn parameters _θ_ such that objects _x_ generated according to policy _πθ_ have high expected reward E _x∼πθ_ [ _R_ ( _x_ )].

The deep cross-entropy method approximates the optimal policy through the following iterative steps:

1. Sampling Phase: Generate _N_ complete objects _x_ 1 _, x_ 2 _, . . . , xN_ independently according to the current policy _πθ_ , and compute the reward _ri_ = _R_ ( _xi_ ) for each object.

2. Selection Phase: Sort all samples by reward, retaining only the top _K_ = _⌈ρN ⌉_ elite samples, where _ρ_ is the elite retention ratio (typically 5% to 20%).

3. Update Phase: Analyze the generation trajectories of these elite samples, i.e., the decision sequences at each step. For each elite sample’s generation sequence ( _a_ 1 _, . . . , aT_ ), construct training data: for each step _t_ , state _st_ = ( _a_ 1 _, . . . , at−_ 1), action _at_ . Then, update the policy by minimizing the cross-entropy loss:

**==> picture [172 x 25] intentionally omitted <==**

The cross-entropy form of the loss function _L_ ( _θ_ ) is the core. For a given (state, action) pair ( _s, a_ ), we want the policy network’s output probability _πθ_ ( _a|s_ ) for action _a_ in that state to be as large as possible. _−_ log _πθ_ ( _a|s_ ) measures the difference between the predicted probability and the perfect prediction (probability 1). Minimizing the sum of these differences over all elite trajectories is “stretching” the policy network, aligning its decision distribution closer to the empirical distribution of the elite samples.

This process repeats until a satisfactory construction is found or a preset number of iterations is reached. Algorithm5.1 is the pseudocode for this deep cross-entropy method.

To put the above algorithm into practice, we need to encode the partial construction sequence _st_ into a fixeddimensional vector that the neural network can process. Wagner adopted a simple yet general encoding scheme, particularly suitable for tasks generating binary strings (e.g., the upper triangular part of a graph’s adjacency matrix).

The input is the concatenation of two vectors:

- **Decision Vector** : Length _T_ , where the _i_ -th component indicates whether a decision has been made at the _i_ -th position. If decided, the component is the actual value (0 or 1); if not yet decided, the component is 0. This vector records the “history” so far.

- **Position Indicator Vector** : This is a one-hot vector, with only the _t_ -th component being 1 and the rest 0. It explicitly tells the network which position it is currently making a decision for.

Why are two vectors needed? The decision vector provides context, and the position vector provides focus. The network needs to combine them to understand: “Based on the decisions I have already made (decision vector), what is the higher probability I should choose 0 or 1 for this specific position (position vector)?”

Regarding the neural network architecture, Wagner used a simple Multi-Layer Perceptron (MLP):

- Input Layer: Size 2 _T_ (concatenation of two vectors)

- Hidden Layers: Typically 2-3 fully connected layers with ReLU activation function. For example, the paper mentions a three-layer structure with 128, 64, and 4 neurons.

- Output Layer: Size _|A|_ , with two neurons for binary decisions, converted into a probability distribution _πθ_ (0 _|st_ ) and _πθ_ (1 _|st_ ) via the softmax function.

[State _st_ ]

_↓_

[Decision Vector _⊕_ Position Vector]

_↓_

[Fully Connected Layer (128) + ReLU]

_↓_

[Fully Connected Layer (64) + ReLU]

_↓_

[Fully Connected Layer (4) + ReLU]

_↓ ↓_

[Output Layer (2) + Softmax]

[Probability Distribution ( _P_ (0) _, P_ (1))]

This architecture, though simple, is sufficient to capture dependencies between decisions in many combinatorial problems. For objects like graphs with strong structural relationships, Graph Neural Networks (GNNs) might be a more natural choice, as they can directly take the graph structure (vertices, edges) as input and utilize message-passing mechanisms to aggregate neighborhood information. However, the generality of a simple MLP allows it to be quickly applied to various problems without designing specialized network structures for each new problem.

Wagner’s paper demonstrates the successful application of this method to several graph theory and combinatorial conjectures. Below, we select two typical examples to elaborate on how AI works and what mathematical insights it reveals.

Example One: Conjecture on the Sum of Eigenvalue and Matching Number

**Conjecture:** For any connected graph _G_ with _n ≥_ 3, the sum of its largest eigenvalue _λ_ 1 and matching number _µ_ satisfies _λ_ 1 + _µ ≥[√] n −_ 1 + 1.

AI Setup Details:

      - _n_

      - Object Representation: Graph with _n_ vertices, encoded as a binary string of length _T_ = () 2[.] Reward Function: _R_ ( _G_ ) = _−_ ( _λ_ 1( _G_ )+ _µ_ ( _G_ )), aiming to minimize this sum to find a potential counterexample.

      - Task Scale: Search for _n_ = 19.

      - Computational Details: Each reward evaluation requires computing the largest eigenvalue of the graph’s adjacency matrix and the maximum matching. Total training iterations approximately 5000 rounds.

- AI’s Discovery Process:

   1. Initial Phase: Random policy, generating various dense and sparse graphs.

   2. Learning Trend: The network quickly (within a few hundred iterations) “learns” from reward feedback that sparse graphs tend to have smaller _λ_ 1. Simultaneously, to maintain connectivity (which the reward function may not explicitly require, but sparsity easily leads to disconnection), it discovers trees are a good candidate category: they are minimally connected graphs.

   3. Structural Evolution: From random graphs, to sparse disconnected graphs, to trees, and finally focusing on a specific tree structure—“balanced double star”: a central edge connecting the centers of two stars,

#### 5.2.1 Algorithm 5.1: Deep cross-entropy method

**Input:** Reward function _R_ ( _·_ ), Action space _A_ , sequence length _T_ , Policy network _πθ_ , initial parameters _θ_ 0, Samples per round _N_ , elite retention ratio _ρ ∈_ (0 _,_ 1) (elite count _K_ = _⌈ρN ⌉_ ), Learning rate _α_ , stopping condition **Output:** Best construction found during training _x[∗]_ = arg max _x R_ ( _x_ ) **1** Initialize policy network parameters _θ ← θ_ 0 **2 while** _stopping condition not met (e.g., counterexample found or max iterations reached)_ **do 3 Sampling Phase** : 1. Initialize sample set _S ←∅_ **for** _i_ = 1 _**to** N_ **do** Initialize empty sequence _s ← ϵ_ **for** _t_ = 1 _**to** T_ **do** Sample action _at_ according to _πθ_ ( _·|s_ ) _s ← s ⊕ at_ Decode complete object _xi_ from _s_ , compute reward _ri_ = _R_ ( _xi_ ) Add ( _xi, ri, s_ ) to _S_ **Selection Phase** : Sort samples in _S_ by reward _ri_ Let _E_ be the set of top _K_ elite samples **Update Phase** : Initialize training set _D ←∅_ **foreach** _generation sequence_ ( _a_ 1 _, . . . , aT_ ) _∈E of an elite sample_ **do for** _t_ = 1 _**to** T_ **do** _st ←_ ( _a_ 1 _, . . . , at−_ 1) _D ←D ∪{_ ( _st, at_ ) _}_ Compute cross-entropy loss: _L_ ( _θ_ ) = _−_ � log _πθ_ ( _a|s_ ) ( _s,a_ ) _∈D_ Gradient descent update: _θ ← θ − α · ∇θL_ ( _θ_ )

**4 return** Best construction found during training _x[∗]_ = arg max _x R_ ( _x_ )

   - each star having a similar number of leaves. This structure effectively keeps the largest eigenvalue low while also having a small matching number, all while maintaining connectivity.

4. Successful Counterexample: When _n_ = 19, the finally found graph satisfies _λ_ 1 = _√_ 10 _≈_ 3 _._ 162, _µ_ = 2, sum approximately 5.162, which is less than _√_ 18 + 1 _≈_ 5 _._ 243, successfully refuting the conjecture.

This case demonstrates how AI, starting from scratch, through pure trial-and-error learning, discovered a

graph structure that human mathematicians might not have considered and successfully used it to overturn the conjecture.

#### 5.2.2 Example two: Conjecture on distance spectrum and proximity

**Conjecture:** Concerning the distance matrix eigenvalues _∂i_ and the proximity parameter _π_ of a graph, they satisfy _π_ + _∂⌊_ 2 _D/_ 3 _⌋ >_ 0, where _D_ is the diameter.

AI Setup Details:

      - Reward Function: _R_ ( _G_ ) = _−_ ( _π_ ( _G_ ) + _∂⌊_ 2 _D/_ 3 _⌋_ ( _G_ )), aiming to find graphs making this sum as small as possible (even negative).

      - Task Scale: Initial search for _n_ = 30.

      - Computational Challenge: Computing distance matrix eigenvalues and proximity is more time-consuming than for adjacency matrices, especially for non-tree graphs requiring all-pairs shortest path algorithms. This limits the number of samples _N_ that can be evaluated per round.

- AI’s Discovery Process:

   1. Failed to directly find a counterexample: After several days of training, the best graph found by AI for _n_ = 30 had a sum value of about 0 _._ 4, still positive, not a counterexample.

   2. Key Insight—Structural Convergence: Although not a counterexample, a strong pattern emerged: among all elite samples, the graph structures were highly consistent. They all consisted of a long path, connected near its midpoint to a large star, whose neighbors themselves formed small cliques. The only variation was the sizes of these small cliques, as shown in Figure5.1 (cited from the original paper).

   - **Figure 5.1:** Reinforcement Learning Constructing Counterexamples

   - 3. From Pattern to Counterexample: This pattern provided human researchers with a clear “design blueprint”. Based on this, Wagner et al. manually constructed a parameterized family of graphs: a path of length _d_ , with _m_ leaves attached (i.e., a star) to a vertex near the midpoint. Through analysis, they found that when _d_ = 12 (diameter _D_ = 12, _⌊_ 2 _D/_ 3 _⌋_ = 8) and _n_ is sufficiently large ( _≥_ 190), this “double-tailed comet” graph indeed satisfies _π_ + _∂_ 8 _<_ 0, thus becoming a counterexample.[-]

This case highlights another role of AI in mathematical discovery—a super pattern detector. When directly searching for a counterexample is computationally difficult, AI can reveal the topological features that potential extremal structures must satisfy by outputting a series of “near-optimal”, structurally similar candidate solutions. This greatly reduces the human search space, transforming the problem from “searching among all graphs” to “optimizing parameters within a graph family of a specific pattern”.

Based on the above examples, the general workflow of using reinforcement learning for mathematical construction can be seen as follows:

Step 1: Problem Formulation

Transform the specific mathematical construction problem into a reinforcement learning framework, defining state representation, action space, reward function, and termination conditions. This is the most critical step, requiring a deep understanding of the nature of the mathematical problem. A good formulation should allow the reward function to accurately reflect the problem’s objective while ensuring the state representation contains sufficient information for decision-making.

Step 2: Algorithm Selection and Implementation

Choose an appropriate reinforcement learning algorithm. For mathematical construction problems with sparse rewards and discrete action spaces, policy-based methods like policy gradient methods and the crossentropy method often perform well. These methods directly optimize the policy without needing to learn complex value functions, making them more suitable for combinatorial problems with huge exploration spaces. Step 3: Training Process

The agent learns through interaction with the environment (i.e., the construction process). In each training cycle, the agent uses the current policy to generate multiple complete constructions, computes the reward for each, and then uses this information to update the policy. This process repeats until the policy converges or a satisfactory construction is found.

Step 4: Result Extraction and Analysis

After training, use the learned policy to generate constructions and perform mathematical verification. If a counterexample or extremal construction is found, further analyze its structure to gain mathematical insights. Sometimes, even if no counterexample is found, the “near-optimal” constructions discovered by AI can provide valuable clues for human researchers.

The essential points of the method can be summarized as:

1. General Framework: The same reinforcement learning code can be used to attack different mathematical conjectures, requiring only a change of the reward function. This generality is difficult to match with traditional methods.

2. Learning from Experience: The reinforcement learning agent accumulates experience through extensive trial and error, gradually learning which decision patterns are more likely to produce high-reward constructions. This is similar to how human mathematicians guide research by accumulating intuition and experience, but reinforcement learning can explore possibilities more systematically and extensively.

3. Handling High-Dimensional Combinatorial Spaces: Reinforcement learning methods, especially when combined with neural networks, can handle extremely high-dimensional state and action spaces, which is unattainable for traditional exhaustive methods.

4. Exploring Unconventional Structures: Since reinforcement learning algorithms do not rely on human prior intuition, they have the potential to discover counterintuitive, unconventional constructions that human researchers might easily overlook.

5. Sparse Reward Challenge: Mathematical construction problems typically have only final rewards, making

   - learning very difficult. Specialized techniques, such as curriculum learning (starting from simple problems and gradually increasing difficulty) or intrinsic rewards (encouraging exploration of new states), are needed to assist the learning process.

6. Scalability: Once a policy is trained, it can quickly generate a large number of high-quality constructions, which is valuable for studying the distribution of constructions or finding multiple different counterexamples.

It is worth noting that while reinforcement learning provides powerful search capabilities, it does not guarantee finding the optimal solution or a counterexample. The algorithm’s success depends on various factors, including the quality of problem formulation, the design of the reward function, the choice of algorithm, and the tuning of hyperparameters.

From a broader perspective, the application of reinforcement learning in discovering graph theory counterexamples represents an important paradigm in AI for Math: when human intuition and traditional algorithms struggle to reach the problem space, AI can discover hidden, counterintuitive structures through systematic exploration and learning. These discoveries not only verify or refute conjectures but, more importantly, enrich our understanding of mathematical structures and inspire new theoretical directions.

### 5.3 The PatternBoost method

In the previous section, we explored how to leverage reinforcement learning and heuristic search for efficient construction within discrete combinatorial spaces. We saw the great potential of pure reinforcement learning methods (such as the cross-entropy method), while also recognizing their limitations: when the size of the constructed object (e.g., sequence length) becomes large (for instance, several hundred symbols), a naive neural network struggles to effectively learn and predict the entire structure. This difficulty is fundamentally rooted in the inherent conflict between “exploration” and “exploitation,” which is particularly pronounced in the vast, discrete, and structurally complex space of mathematical constructions.

Specifically, we can view the mathematical construction task from two perspectives:

1. Local Perspective: Starting from a given construction (such as a graph or a matrix), attempt to improve the degree to which it satisfies the target constraints through a series of “small-step” modifications (e.g., adding or deleting an edge, an element). This is a “fine-tuning” style of optimization. Its advantage lies in the ability to conduct detailed exploration near known “good solutions,” but its drawback is the tendency to get stuck in local optima, lacking the ability to break out of the current structural pattern. For example, for a triangle-free graph, local search can try adding new edges to existing non-triangle edges, but it struggles to conceive an entirely new, structurally distinct bipartite graph layout.

2. Global Perspective: Grasping the overall patterns and structural characteristics of “good constructions” from a macro level. For instance, by analyzing hundreds of excellent triangle-free graphs, a human mathematician might discern that most exhibit a “bipartite graph” structure. The global perspective can provide novel ideas to escape local patterns, but its disadvantage is the difficulty in precisely generating concrete instances that satisfy all micro-level constraints. A pure generative model might learn the pattern of “bipartiteness,” but the graphs it randomly generates may still contain some triangles.

In mathematical research, this “local adjustment” (e.g., trying to modify a known counterexample) and “global conception” (e.g., conjecturing a new structural framework based on symmetry or extremal principles) are typically alternated. A method purely based on reinforcement learning or local search often lacks effective global conception capability. Conversely, a pure generative model (e.g., directly training a Transformer to output constructions) may generate a large number of invalid outputs due to its inability to precisely satisfy complex, combinatorial constraints.

Therefore, a natural question arises: Can we design a hybrid method that allows machines, like mathematicians, to effectively iterate between local fine-tuning and global pattern learning? This method needs to leverage both the precision of local search and the creativity of global learning. This is precisely the core motivation behind the PatternBoost method. It aims not to replace humans, but to build an automated system that can simulate the cycle of “hands-on experimentation” and “reflective abstraction” in human mathematical research. Its target mathematical problems are clear: in those structurally complex combinatorial spaces, find constructions that satisfy specific constraints, possess extremal properties (e.g., maximum number of edges, maximum size), or serve as counterexamples to conjectures.

The essence of PatternBoost lies in its simple yet powerful iterative framework. It decomposes the entire construction search process into two alternating phases: local search and global learning. This cycle can be understood through a clear analogy: imagine a community of bicycle designers (local phase) each fine-tuning and optimizing their own bicycle designs to make them more comfortable and efficient. These excellent bicycles are put into use, filling the streets. A new generation of designers (global phase) observes the various optimized bicycles on the streets, abstracts the common features and patterns of successful designs, and conceives new bicycle designs based on these patterns, yet in a similar style. These new designs are then taken back by the designers for fine-tuning optimization, and a new round of the cycle begins.

In the mathematical context, this cycle is formalized into a repeatable algorithmic process:

1. Local Phase (Producing Good Solutions): Use a (typically simple) local search algorithm, starting from one or more “seed” constructions, to explore the nearby space through a series of allowed local operations (e.g., adding/deleting elements, swapping positions). The goal is to obtain one or more “high-quality” constructions. Here, “high-quality” is quantified by a scoring function that measures how well the construction satisfies our objective (e.g., for the problem of maximizing edges in a triangle-free graph, the score is the number of edges; to guide the search, a scoring function that penalizes the existence of triangles can also be designed).

2. Global Phase (Learning Patterns): Collect a batch of optimal constructions produced in the local phase, using them as training data. Use a machine learning model capable of capturing sequential or structural patterns (in PatternBoost, primarily Transformer-based generative models) to learn the implicit “construction patterns” within these good solutions. After training, let this model generate a batch of new constructions “similar” to the training data, serving as new “seeds.”

3. Iteration: Feed the new seeds generated in the global phase back into the local search algorithm, starting a new round of the cycle. As the cycle progresses, the starting points for local search become increasingly better (because they come from a model that has already learned “good patterns”), and the quality of the dataset used to train the model also improves (because they are the results of continuously optimized local search). Ideally, this process forms a positive feedback loop, continuously approaching or even discovering optimal or groundbreaking constructions.

The beauty of this framework lies in its modularity and generality. The local search algorithm and the global learning model can be customized or replaced according to the specific problem. The authors of the PatternBoost paper specifically emphasize their desire to provide a mathematician-friendly tool that does not require deep machine learning expertise. Therefore, in their experiments, they extensively used very simple local search and a lightweight Transformer implementation to demonstrate that the method remains effective even in this “naive” setting.

Next, we will delve into each key component of the PatternBoost workflow, using the paper’s core example— “constructing the graph with the maximum number of edges among graphs on n vertices that contains no triangles (i.e., verifying/discovering the extremal graph of Mantel’s theorem)”—as a running case study.

#### 5.3.1 Core component one: Local search – from seeds to good solutions

Local search is the foundational engine of PatternBoost. It needs to accomplish two tasks: produce a feasible, improved construction from a starting point; and define what constitutes a “local” move.

Let’s understand this using the paper’s core example: constructing the graph with the maximum number of edges among graphs on _n_ vertices that contains no triangles—this is precisely the problem described by the famous Mantel’s theorem in graph theory, whose extremal structure is the complete bipartite graph _K⌊n/_ 2 _⌋,⌈n/_ 2 _⌉_ . For this problem, the paper adopts an extremely simple two-stage greedy strategy as the local search:

1. Eliminate Violations: If the input graph contains triangles, repeatedly delete a random edge that participates in the most triangles until the graph contains no triangles. This operation is greedy, aiming to quickly reduce the “violation” degree.

2. Expand and Optimize: After obtaining a triangle-free graph, repeatedly attempt to add a new random edge. If adding this edge does not create a new triangle, keep it; otherwise, reject the addition. Repeat this process until no more edges can be added without creating a triangle.

This algorithm is very simple; it does not utilize any deep knowledge about graph structure (such as bipartiteness), relying purely on random attempts. Its scoring function is also straightforward: in the final triangle-free graph, the score is the number of edges. The authors use this simple setup to highlight the improvement brought by the subsequent Transformer’s global learning, rather than the intelligence of the local search itself.

Why is local search needed? Because the constructions directly output by generative models (like Transformers) may not be perfect in terms of micro-level constraints. For example, a graph generated by a Transformer that has learned the “rough structure of a bipartite graph” might still contain a few sporadic triangles. Local search acts like a “proofreader” or “polisher,” responsible for refining these rough, potentially flawed conceptions into mathematical objects that strictly satisfy all constraints and can be precisely evaluated. Without this step, a large number of generated results would be invalid and unable to enter subsequent evaluation and iteration.

#### 5.3.2 Core component two: Global learning – capturing construction “patterns” with transformers

After collecting a batch of high-quality constructions (e.g., those graphs with the highest edge counts selected from numerous local search runs), PatternBoost enters the global learning phase. The core idea is: these good solutions must contain some generalizable “success pattern,” and the task of the machine learning model is to discover and learn this pattern.

Why choose Transformers? The Transformer architecture excels at processing sequential data, particularly in capturing long-range dependencies. A mathematical construction (such as a graph’s adjacency matrix, a matrix’s entry sequence, a point set’s coordinate list) can be “serialized” into a string of symbols. Through its self-attention mechanism, the Transformer can learn the relationships between elements at any two positions in the sequence, which is crucial for understanding the overall layout of combinatorial structures (e.g., the connection pattern between two parts of a graph). Compared to simple feedforward neural networks used in prior work, Transformers can handle longer sequences, thus enabling modeling of larger-scale constructions.

To input a mathematical object into a Transformer, it first needs to be represented as a series of discrete symbols. Taking a triangle-free graph on 20 vertices as an example:

1. Matrix Representation: The graph can be represented by a 20 _×_ 20 symmetric adjacency matrix, with zeros on the diagonal. Due to symmetry, we only need the 190 0 _/_ 1 elements in the upper triangular part.

2. Flattening: Concatenate these 190 elements row-wise into a one-dimensional binary sequence, e.g., 010010110...

3. Tokenization: Directly using a length-190 sequence of 0s and 1s is inefficient because the vocabulary has only two symbols, and overly long sequences increase the model’s learning difficulty. PatternBoost employs Byte Pair Encoding (BPE)—a common compression technique in natural language processing. BPE automatically analyzes all sequences in the training data, identifies frequently occurring substrings, and assigns a new, unique Token ID to each such substring. After BPE processing, the original long binary sequence is compressed into a shorter sequence composed of multiple tokens, where each token may represent 2, 3, or more original bits. This not only shortens the sequence length, improving training and generation efficiency, but these tokens themselves may correspond to meaningful local patterns.

In practice, the size of the BPE vocabulary (i.e., the number of tokens) is a hyperparameter that needs tuning. Typically, a balance must be struck between model capacity (a larger vocabulary means shorter sequences but a larger token embedding layer) and the informativeness of the sequence representation. A common rule of thumb is that vocabulary size can be related to the size of the training dataset and the model’s embedding dimension. For mathematical construction datasets, due to potentially stronger regularity in patterns, a relatively small vocabulary (e.g., 100-500) may sometimes be sufficiently efficient. Another practical issue is dynamism: when the dataset of good solutions is updated during iteration, should the BPE dictionary be retrained? In principle, for consistency, it’s best to use a fixed tokenization scheme throughout the PatternBoost cycle. If new data introduces entirely new high-frequency patterns, retraining BPE might be more optimal, but this makes it harder to compare model outputs across different iterations. A compromise is to train BPE on a larger initial training set and keep it fixed in subsequent iterations.

The training process is standard language model training: given a token sequence (representing a good solution graph), train the Transformer model to predict the next token in the sequence. By minimizing the prediction error (cross-entropy loss) over all good solution sequences, the model gradually learns the probability distribution of “what a good construction sequence should look like.”

After training, generating a new construction is like letting the model “continue the story”: starting from an initial token, let the model predict the probability distribution for the next token based on the already generated tokens, then sample the next token from this distribution, and repeat until a complete sequence (ending with an end-of-sequence token) is generated. Finally, decode this token sequence back to the original binary representation (adjacency matrix), yielding a new graph “conceived” by the model.

The key point is: the new graph generated by the model has sequence patterns “similar” to the good solution graphs in the training set, but it is not a simple copy. It is a new sample from the learned probability distribution, thus potentially producing new constructions that are structurally similar but differ in specific details. This embodies the creativity of “global learning”—it can generate new starting points that follow successful patterns yet are entirely novel.

Connecting the two phases above forms the main loop of PatternBoost. The experiments in the paper clearly demonstrate the effect of iteration:

- Generation Zero (Initialization): Starting from empty graphs, run 40,000 simple local searches. The resulting distribution peaks around 66 edges, with the best result being 99 edges—appearing only twice. The known theoretical optimum is 100 edges, i.e., the complete bipartite graph _K_ 10 _,_ 10.

- Generation One: Take the top 25% of good solutions to train a small Transformer. Let the Transformer generate 100,000 new sequences, of which about 37,000 can be correctly decoded into valid 20-vertex adjacency matrices. Use these 37,000 graphs as seeds, each undergoing local search. The result is surprising: 46 graphs reach the theoretical optimum, and 47 graphs have 99 edges. In contrast, the local search baseline found only two 99-edge graphs in 40,000 attempts. Moreover, these 46 optimal graphs are structurally isomorphic—all are the complete bipartite graph _K_ 10 _,_ 10 or its isomorphic variants. Subsequent Iterations: Add the newly found good solutions to the training set, continue fine-tuning the Transformer, and repeat generation and search. After several rounds of iteration, the model almost exclusively generates complete bipartite graphs and quickly learns to generate the optimal structure with two equal-sized parts.

This example perfectly illustrates the power of PatternBoost: a very simple local search, paired with a lightweight Transformer, through a few iterations, automatically “discovers” the extremal structure of the problem (the complete bipartite graph) starting from complete ignorance (random search from empty graphs). The Transformer successfully abstracts the global pattern of “bipartiteness” from a collection of successful cases and uses it to dramatically improve the starting point quality for local search.

The PatternBoost paper does not only showcase successful cases; it carefully selects a series of problems, forming a spectrum from “method effective but not surpassing human” to “method makes breakthrough discoveries.” This helps us objectively assess its capabilities and scope of applicability. 1. Difficult Problem: Maximum Number of Edges in Graphs Without 4-Cycles

This problem requires constructing a graph on _n_ vertices that contains no cycles of length 4 and has as many edges as possible. This problem is mathematically much more difficult than the triangle-free graph problem. Using the same simple local search, after running 50 million local searches, the lowest score obtained was 68, the highest was 89, the distribution peak was at 81, while for _n_ = 33, the maximum possible score is 96. After applying PatternBoost, performance improved significantly; the best result was a graph with 91 edges. By using a larger Transformer model and an improved tokenization strategy (adding separators after each matrix row), the method eventually found the theoretically optimal 96-edge graph after 116.5 million local searches. However, the search volume required to reach the optimum was enormous, and for larger _n_ , even with PatternBoost, the found solutions still lag behind known lower bounds. This indicates that for some problems with extremely complex, hard-to-capture structures, even the enhanced PatternBoost faces challenges, though its performance is still far superior to pure local search.

2. Well-Performing Problem: Maximizing the Permanent of Matrices Avoiding the “312” Pattern

In this problem, the goal is to find 0-1 matrices that avoid a specific “312” pattern and have the maximum permanent. PatternBoost used a setup similar to before and was compared against a carefully designed, problemspecific search algorithm crafted by human experts. The result was that the specialized human algorithm won only by a narrow margin (found matrix permanent 5.2e6, PatternBoost 5.1e6). This is a highly instructive result: a general, almost domain-knowledge-free ML method can perform close to a specialized algorithm painstakingly designed by humans. More importantly, the optimal solution sets found by the two methods were almost disjoint, meaning they explored different regions of the search space. When the good solutions found by the human algorithm were added to PatternBoost’s training set, PatternBoost was able to discover a series of new highquality constructions. This demonstrates the potential of human-machine collaboration: human intuition can provide high-value seeds, and machines can conduct large-scale, tireless exploration and generalization based on them.

### 5.3 Breakthrough problem: Minimum number of edges in spanning subgraphs of hypercubes

This is a 30-year-old problem: concerning how many edges must be retained in a _d_ -dimensional hypercube so that its spanning subgraph still has diameter _d_ . A conjecture estimates that such a subgraph must have at least 2 _[d]_ + _d/d_ 2 _[−]_[2][edges.][For] _[d]_[=][5][,][the][conjectured][construction][appears][optimal.][But][when][the][authors] applied PatternBoost to _d_ = 6, the method successfully found a construction with only 81 edges, better than the conjectured construction with 2[6] + �63� _−_ 2 = 82 edges, thereby disproving the conjecture. This is one of PatternBoost’s most striking achievements: it not only optimized known bounds but genuinely solved an open mathematical problem, making a new discovery. The process of discovering this counterexample fully demonstrates the closed loop from automated construction to mathematical discovery: the machine proposes candidate counterexamples, and humans verify and theorize.

Furthermore, the paper demonstrates PatternBoost’s application on multiple other problems, including “point sets in grids with no isosceles triangles,” “point sets in space with no 5 points on a sphere,” and “saturated Sperner families,” some of which improved known best constructions. These cases collectively indicate that PatternBoost is a general framework applicable to various combinatorial extremal problems, and its effectiveness largely depends on whether the problem itself possesses “implicit patterns” that can be captured by machine learning models.

Although PatternBoost has achieved impressive results, it is not a universal key. Its successful application relies on a set of conditions and faces numerous challenges:

1. Problem Suitability: The method is best suited for problems where “optimal constructions have clear but complex patterns.” If the optimal construction is highly disordered or random (e.g., constructions for lower bounds of certain Ramsey numbers), or if the scoring function is extremely rugged and lacks gradients, PatternBoost may struggle to learn effective patterns. The “no 4-cycle” problem in the paper is much harder than the “no triangle” problem, partly because the structure of the extremal graph is more complex and harder to encode and learn.

2. Quality of Local Search: The overall performance of PatternBoost heavily depends on the effectiveness of the local search component. The simple greedy search used in the paper proves the concept, but in practical applications, designing more intelligent local search for specific problems (e.g., leveraging problem symmetry, designing finer neighborhood operations) can greatly enhance loop efficiency. A poor local search may fail to fully optimize the good starting points generated by the Transformer, thereby hindering the entire process.

3. The Art of Representation and Tokenization: How to effectively represent a mathematical object as a sequence is crucial for the Transformer’s learning. Different flattening orders (row-wise, column-wise, diagonal), whether to add separators, the size of the BPE vocabulary, etc., all significantly affect the proportion of valid sequences generated by the model and the learning speed. Currently, choices in this area rely more on experience and experimentation, lacking systematic theoretical guidance. This constitutes an important direction for engineering and theoretical research.

4. Interpretability and Mathematical Insight: PatternBoost is a powerful “discovery engine,” but it is essentially an optimization tool. Does the counterexample or extremal construction it finds reveal deeper mathematical principles? Can the “patterns” learned by the model be translated into human-understandable mathematical concepts or conjectures? For example, in the case of disproving the hypercube conjecture, can the specific graph structure with 81 edges inspire mathematicians to propose new theorems about extremal graph structures? At present, the transition from machine-generated constructions to their elevation into human mathematical knowledge still demands substantial involvement from mathematicians. Enabling models not only to generate constructions, but also to offer explanations or formulate hypotheses about them, remains an open and frontier challenge.

5. Computational Cost and Stopping Criteria: Although the models used in PatternBoost are relatively lightweight, large-scale iteration still requires considerable GPU computational resources, especially when dealing with large-scale problems (large _n_ ). The local search phase may involve millions or even hundreds of millions of evaluations of candidate solutions, which itself can be computationally intensive. In practice, clear stopping criteria need to be set to avoid infinite computation. Common stopping conditions include: model performance on a validation set (e.g., the proportion of valid samples generated) no longer improves; learning curves (e.g., training loss) plateau; the quality of the best solution found does not improve significantly over several consecutive iterations; or a predetermined computation time or resource budget is reached. When these conditions are met, iteration should stop, and the current best construction should be analyzed.

### 5.4 AI constructing counterexamples: Based on LLM agents

In the previous sections, we explored two methods for constructing counterexamples: one based on reinforcement learning, which systematically searches the vast combinatorial space through a policy network; and another based on the iterative fusion of local search and global learning, enabling the machine to learn the implicit patterns of “good constructions.” Both methods have their merits, but they share a common prerequisite: a well-defined formal environment—whether it’s an explicit action space, a reward function, or an executable scoring criterion.

This subsection systematically explains how to build an LLM agent system capable of autonomously constructing counterexamples to mathematical conjectures, incorporating verification mechanisms to ensure the correctness of the constructions.

A complete counterexample construction agent system can be abstracted into the following three-layer architecture:

- Core Engine Layer: Includes the generative model used to produce counterexamples. This layer provides the agent’s fundamental capabilities: understanding mathematical language, performing reasoning, and generating constructions.

- Agent Layer: Implements the core logic for intelligent decision-making, including how to decompose complex problems, how to learn from mistakes, how to retrieve relevant knowledge, etc. This layer determines whether the agent can, like a human researcher, strategically adjust its approach when facing difficulties, rather than blindly trying.

- Application Layer: The goal-oriented layer for specific tasks, responsible for translating the high-level goal of “refuting this conjecture” into an executable action plan and ultimately outputting a verified counterexample.

In the above architecture, a key design choice is to separate the generation and verification of counterexamples: a large language model is responsible for generating candidate counterexamples, which are then submitted to an independent verification module for correctness judgment. The core advantages of this design are:

- No need for a complete formal environment: It is not necessary to fully formalize the entire conjecture and its background theory in advance. The agent can directly handle problems described in natural language, relying on formal tools or human checks only in the final verification stage.

- Relatively simple verification target: It only needs to judge whether the construction satisfies the conditions and conclusion of the proposition, without verifying complex intermediate reasoning steps. This “final result check” is simpler than verifying a complete proof chain.

- Fast iteration speed: After generation, it is immediately judged by the verification module, forming a “generate-verify-correct” closed loop, allowing a large number of attempts in a short time.

In this architecture, the design of the verification module is crucial. It can be a formal verification tool (such as Lean, Coq), a symbolic computation system (such as Mathematica, SageMath), or involve human expert intervention. Regardless of the form, the verification module needs to output a clear judgment result and provide specific feedback information when an error is determined—for example, “this construction does not satisfy condition A” or “it actually does not negate conclusion B.” This interpretable output not only allows the generation module to make targeted corrections but also provides a basis for subsequent human review.

#### 5.4.1 Core mechanism one: Iterative verification and repair

Iterative verification and repair is the core mechanism for interaction between the agent and the LLM verifier. Its basic workflow is as follows:

1. Initial Generation: The agent generates a candidate counterexample construction and a brief explanation based on the given mathematical conjecture.

2. Verification: Submit the candidate counterexample to the verifier, requesting it to judge its correctness. The verifier outputs the judgment result along with detailed reasoning.

3. Error Feedback: If the verifier judges it as incorrect, it outputs the specific reason for the error—for example, “this construction does not satisfy condition A” or “it actually does not negate conclusion B.”

4. Reflection and Correction: The generation module receives the error feedback, combines it with the problem context and previous attempt history, and generates a corrected candidate counterexample. This process is not a simple “try again,” but a targeted improvement based on feedback.

5. Loop Iteration: Repeat steps 2-4 until verification passes or the maximum number of attempts is reached. The technical key point here is: the quality of error feedback is crucial. If the verifier only outputs “incorrect,” the generation module does not know how to correct it. Therefore, prompts need to be designed to make the verifier output detailed, actionable feedback. Meanwhile, the correction process needs to retain historical context to avoid repeating the same mistakes—the agent should “remember” which approaches have been tried and failed. **Core Mechanism Two: Reflection and Decomposition**

For complex counterexample construction tasks, directly generating a complete counterexample often exceeds the LLM’s capability. The reflective decomposition mechanism gradually breaks down complex problems into manageable subproblems:

1. Planning: The agent first understands the original problem and generates a general construction idea. This step is similar to a human mathematician’s “thinking about the general direction” when facing a difficult problem.

2. Subgoal Decomposition: Decompose the construction process into multiple subtasks. For example, “first construct a function satisfying condition A, then adjust it to satisfy condition B, and finally verify that it breaks conclusion C.” Each subgoal is relatively simple and easier to achieve.

3. Recursive Solving: For each subgoal, the iterative verification and repair mechanism can be applied again—or the subgoal can be further decomposed. This recursive decomposition enables the agent to handle problems whose complexity far exceeds its single-generation capability.

4. Result Synthesis: After all subgoals are verified, the system combines them into a complete counterexample description and performs a final overall verification.

The quality of subgoal decomposition directly affects the final success rate. Decomposition that is too coarse leaves subgoals still difficult to solve; decomposition that is too fine may introduce excessive combinatorial complexity. The dependencies between subgoals also need to be properly managed—some subgoals may need to be completed sequentially, while others can be explored in parallel.

#### 5.4.2 Case study – Successful counterexample construction practice

To understand how the above mechanisms operate in practice, let’s examine a successful case: the handling of the Anderson conjecture in commutative ring theory by the AI4Math team at Peking University.

The Anderson conjecture was proposed by American mathematician David F. Anderson in 2014, concerning a profound property of “quasi-complete local rings” in commutative algebra, a rather deep problem in commutative ring theory. For over a decade after its proposal, no substantial breakthrough was made. The AI4Math team, formed by Professor Bin Dong’s group at the Beijing International Center for Mathematical Research, Peking University, and collaborators, decided to use this difficult problem as a touchstone to test their agent’s capabilities. They independently built a dual-agent collaboration framework—consisting of the natural language reasoning agent Rethlas and the formal verification agent Archon. The two agents have clear division of labor: Rethlas is responsible for literature retrieval and mathematical reasoning, while Archon is responsible for translating the reasoning results into rigorous formal proofs.

The mathematical reasoning agent Rethlas did not attempt to directly prove the conjecture. Instead, through cross-domain retrieval, it connected the theory of “integral domain completion” with the Anderson conjecture and constructed a counterexample, thereby refuting the conjecture. This means the Anderson conjecture was negated rather than proven—in mathematical research, negating a conjecture is as valuable as proving one, as it delineates the boundaries of theory.

Subsequently, the formal verification agent Archon transformed this counterexample construction into approximately 19,000 lines of Lean formalization code. During the formalization process, it autonomously discovered and corrected logical flaws in the initial plan. When a required mathematical concept was not yet included in Lean’s current formalized mathematics library, Archon, through retrieval and comparison, autonomously found an equivalent alternative path. Finally, Archon completed the generation of all the code.

This case clearly demonstrates the core advantages of the “generate-verify” paradigm in counterexample construction tasks. In the generation phase, the agent dares to propose a negative construction rather than solely seeking a proof—Rethlas, through cross-domain association, linked the seemingly unrelated theory of “integral domain completion” with the Anderson conjecture. This kind of analogy and transfer belongs to the “conceptual leap” traditionally considered the core of human intelligence. In the verification phase, the formal verification step provided rigorous final assurance for this seemingly bold construction—Archon not only completed the generation of tens of thousands of lines of code but also autonomously discovered and repaired logical flaws during the process. The two agents collaborated, jointly solving a problem that human mathematicians had failed to resolve for over a decade.

- Counterexample construction agents based on large language models represent a new paradigm for AI for

- Math. Compared to traditional methods requiring a complete formal environment, it has significant advantages:

   - Low Barrier to Entry: It does not require pre-formalizing the entire conjecture and its background theory; it can directly handle conjectures described in natural language. This enables AI exploration of a large number of mathematical problems that have not yet been formalized.

   - High Flexibility: It can handle various types of mathematical objects—from sets of integers in number theory, to functions in analysis, to constructions in geometry. As long as it can be described in language, it can be attempted to be constructed in language.

   - Interactivity: The agent’s output is human-readable natural language, which mathematicians can understand, evaluate, and correct. This human-machine readability makes collaboration possible.

   - Fast Iteration: The closed loop of generate-verify-correct allows a large number of attempts in a short time, exploring avenues that human researchers might overlook.

However, this method also has inherent limitations. The generation module (the large language model) may still make mistakes or get stuck in loops when dealing with problems requiring multi-step complex reasoning. The reflective decomposition mechanism can alleviate this issue but cannot eliminate it completely. The model’s capabilities are limited by its training data; for extremely cutting-edge or niche mathematical fields, the model may lack the necessary background knowledge.

Constructing counterexamples to mathematical conjectures is a touchstone for testing the mathematical creativity of LLMs. By combining the generative capabilities of LLMs with external verification mechanisms, we can build an efficient paradigm for counterexample discovery. This paradigm does not require pre-formalizing the entire problem, has a lower barrier to entry, iterates faster, and is expected to benefit more mathematical researchers. The successful handling of the Anderson conjecture by the AI4Math team at Peking University is strong proof of the effectiveness of this paradigm: the agents not only constructed a counterexample that human mathematicians had failed to find for over a decade but also ensured its correctness through formal verification, with both steps completed autonomously by AI agents. Although the reliability of large language models themselves still needs improvement, by positioning them in the role of “generating candidates” rather than “verifying conclusions,” we can fully leverage their exploratory advantages while entrusting the responsibility of rigor to specialized verification modules. This division of labor and collaboration model makes counterexample construction tasks an ideal testing ground for the mathematical creativity of LLMs.

### References

- [1] Boris Alexeev and Dustin G Mixon. “Forbidden Sidon subsets of perfect difference sets, featuring a human-assisted proof”. In: _arXiv preprint arXiv:2510.19804_ (2025).

- [2] Pieter-Tjerk de Boer et al. “A tutorial on the cross-entropy method”. In: _Annals of Operations Research_ 134.1 (2005), pp. 19–67.

- [3] François Charton et al. “PatternBoost: Constructions in Mathematics with a Little Help from AI”. In: _arXiv preprint arXiv:2411.00566_ (2024).

- [4] Richard S Sutton and Andrew G Barto. _Reinforcement learning: An introduction_ . 2nd. MIT Press, 2018.

- [5] Adam Zsolt Wagner. “Constructions in combinatorics via neural networks”. In: _arXiv preprint arXiv:2104.14516_ (2021).

## Chapter 6: AI for PDEs (numerical computation)

### 6.1 Overview of PDE problems and traditional numerical methods

Partial differential equations (PDEs) are the core mathematical tools for describing the evolution of continuous media systems in fields such as physics, chemistry, biology, engineering, and even socio-economics. From heat conduction and fluid motion to quantum mechanics and financial option pricing, PDEs model the laws governing how variables change with space and time in the real world. Traditionally, solving these equations relies on well-developed numerical methods, such as finite difference methods, finite element methods, and spectral methods, which form the cornerstone of scientific and engineering computation. However, as the complexity of problems continues to increase—whether due to high-dimensional spaces, complex geometric boundaries, strong nonlinearities, or data-scarce inverse problems—the limitations of traditional methods are becoming increasingly apparent. This chapter will delve into the basic classification of PDE problems, the mathematical ideas, implementation details, theoretical limits, and computational challenges of traditional numerical methods. Using this as a starting point, it will reveal why artificial intelligence-based solution methods in recent years, particularly Physics-Informed Neural Networks (PINNs), are seen as a promising new paradigm for addressing these challenges. Through detailed mathematical examples, algorithmic pseudocode, complexity analysis, and visual comparisons, we will construct a comprehensive and in-depth framework for understanding.

To understand how AI can intervene, we must first understand the nature of the problem. A partial differential equation establishes a relationship between an unknown function (usually a function of space and time) and its partial derivatives with respect to the independent variables. It is typically formulated as:

**==> picture [263 x 28] intentionally omitted <==**

where _u_ = _u_ ( **x** ) is the unknown function, **x** = ( _x_ 1 _, . . . , xn_ ) are the independent variables (typically spatial and temporal coordinates) defined in the domain Ω _⊂_ R _[n]_ , and _F_ is a given operator. This equation acts like a “syntactic rule,” specifying the local constraints that the function _u_ must satisfy at every point in its domain. However, this rule alone is usually insufficient to uniquely determine a solution; we need additional “contextual” information, namely boundary conditions and (for time-dependent problems) initial conditions. A complete PDE problem, consisting of the governing equation, initial conditions, and boundary conditions together, is called a well-posed problem. Mathematically, one needs to study the existence, uniqueness, and stability (well-posedness) of its solution. In computational practice, our goal is to construct a numerical solution that approximates the true solution as closely as possible when an analytical solution is unavailable.

From a mathematical structure perspective, PDEs can be classified based on the characteristics of their highestorder derivatives. This classification profoundly influences the behavior of the equation’s solutions and the properties of the numerical methods used to solve them. For second-order linear PDEs, they can generally be categorized into the following three classic types:

1. Elliptic Equations (Elliptic PDEs) Elliptic equations typically describe steady-state (time-independent) equilibrium or distribution problems, and their solutions possess “smoothing” and “global dependence” properties. A classic example is Poisson’s equation, which describes the steady state of a potential field (such as electrostatic or gravitational potential) under a given source distribution:

6.1 Overview of PDE Problems and Traditional Numerical Methods

 _−∇_[2] _u_ = _f_ ( **x** ) _,_ **x** _∈_ Ω

where _∇_[2] is the Laplacian operator and _f_ is a known source term. In particular, when _f_ = 0, it is called Laplace’s equation. Elliptic equations have no time dimension; their solution is determined simultaneously across the entire domain, and any disturbance on the boundary instantly affects all interior points (though the influence strength decays with distance). Typical boundary conditions are Dirichlet conditions (specifying the function value _u_ on the boundary), Neumann conditions (specifying the normal derivative _∂u/∂n_ on the boundary), or a mixture of both (Robin conditions). Elliptic problems mathematically correspond to finding the minimizer of an energy functional.

2. Parabolic Equations (Parabolic PDEs) Parabolic equations introduce a time variable and describe dissipative processes such as diffusion and heat conduction. The most famous representative is the heat equation:

**==> picture [175 x 24] intentionally omitted <==**

where _α >_ 0 is the diffusion coefficient. This type of equation evolves unidirectionally in time (irreversible) and has the property of “smoothing” initial disturbances. Solving them requires initial conditions _u_ ( **x** _,_ 0) = _u_ 0( **x** ) and boundary conditions. Information propagates inward from the initial time and the boundaries, making time-stepping a natural solution strategy.

3. Hyperbolic Equations (Hyperbolic PDEs) Hyperbolic equations also describe time evolution processes, but their characteristics are wave-like and non-dissipative, such as the propagation of sound waves, light waves, and elastic waves. The standard form is the wave equation:

**==> picture [182 x 25] intentionally omitted <==**

where _c_ is the wave speed. These equations possess characteristic lines; disturbances propagate along these lines at finite speeds and may maintain discontinuities (such as shocks). They require initial conditions (including initial displacement and initial velocity) and boundary conditions.

In addition to the three classic types mentioned above, the real world contains a large number of nonlinear PDEs (such as the Navier-Stokes equations describing fluids, the Allen-Cahn equation describing phase transitions) and systems of equations (coupling multiple unknown functions). These complexities pose significant challenges for both analytical and numerical solutions.

The core idea of traditional numerical methods is to discretize the continuous PDE problem, transforming it into a discrete, finite-dimensional algebraic problem (usually a system of linear or nonlinear equations), which is then solved using a computer. This process can be viewed as finding an approximation to the original PDE solution within a finite-dimensional space spanned by a grid or a set of basis functions. Different discretization strategies give rise to different families of numerical methods, each with its own mathematical principles, advantages, and applicable scenarios. Table 6.1 summarizes the core concepts and typical application scenarios of these four mainstream methods:

**Table 6.1:** Comparison of Four Mainstream Numerical Methods

|**Method**|**Name**|**Core Discretization**|**Typical Application**|**Typical Application**|**Key Advantages**|**Key Advantages**|**Main Challenges**|
|---|---|---|---|---|---|---|---|
|||**Idea**|**Fields**|||||
|Finite Diference||Approximate deriva-|Fluids, heat conduc-||Simple concept, easy||Poor adaptation to|
|Method|(FDM)|tives<br>using<br>difer-|tion on regular do-||implementation, ma-||complex<br>geometry,|
|||ence<br>quotients<br>of|mains||ture theory||curse of dimension-|
|||function<br>values<br>at|||||ality|
|||grid points||||||
|Finite|Element|Partition<br>domain|Structural|mechan-|Strong<br>geometric||Complex mesh gen-|
|Method|(FEM)|into<br>elements,<br>ap-|ics,<br>fuids<br>with||adaptability,|rigor-|eration, high compu-|
|||proximate<br>solution|complex|geometry,|ous theory,|widest|tational cost in high|
|||using local polyno-|electromagnetics||application||dimensions|
|||mial basis functions,||||||
|||based on variational||||||
|||principles||||||
|Finite|Volume|Divide control vol-|Computational fuid||Strictly<br>maintains||Complex high-order|
|Method|(FVM)|umes, integrate con-|dynamics,|combus-|physical|conser-|schemes,<br>difcult|
|||servation laws, main-|tion,<br>multiphase||vation,|strong|theoretical analysis|
|||tain physical fux bal-|fow||robustness|||
|||ance||||||
|Spectral|Method|Expand<br>solution|Turbulence|sim-|Exponential|conver-|Requires<br>smooth|
|||using global smooth|ulation,|quantum|gence accuracy for||solution, poor geo-|
|||basis<br>functions|chemistry,|weather|smooth solutions||metric<br>adaptability,|
|||(e.g., Fourier series,|forecasting||||dense matrices|
|||Chebyshev<br>polyno-||||||
|||mials)||||||



Next, we will delve into the mathematical details, implementation examples, and analyze the computational complexity and error characteristics of each method.

#### 6.1.1 Finite difference method (FDM)

Imagine laying a regular grid with nodes over the solution domain, like a sheet of graph paper. The PDE tells us the relationship between the rate of change (derivative) of the function at each point and the function value at that point. The core of FDM is to use the difference (difference quotient) of function values at adjacent nodes to approximate the derivative at that point. This is the most direct numerical implementation of the fundamental definition of calculus: “the derivative is the limit of the difference quotient.”

Mathematical formulation and example: Consider a simple but classic two-dimensional Poisson equation with Dirichlet boundary conditions on a unit square domain:

**==> picture [243 x 60] intentionally omitted <==**

We discretize uniformly in the _x_ and _y_ directions with step size ∆ _x_ = ∆ _y_ = _h_ = 1 _/_ ( _N_ + 1), obtaining grid points ( _xi, yj_ ) = ( _ih, jh_ ), where _i, j_ = 0 _,_ 1 _, ..., N_ + 1. The function values at boundary points ( _i_ = 0 _, N_ + 1 or _j_ = 0 _, N_ + 1) are given by the boundary condition _g_ . For interior points ( _i, j_ ), we approximate the second derivatives using central differences:

**==> picture [349 x 30] intentionally omitted <==**

where _ui,j ≈ u_ ( _xi, yj_ ). Substituting these approximations into the Poisson equation yields an equation for each interior point:

**==> picture [222 x 24] intentionally omitted <==**

Rearranging:

**==> picture [222 x 14] intentionally omitted <==**

This forms a large system of linear equations for all interior unknowns _ui,j_ . This system has a sparse, banded coefficient matrix (each equation involves only 5 unknowns) and can be solved using efficient iterative methods (such as the conjugate gradient method, multigrid method).

**Algorithm 6.1:** Finite Difference Method for Solving the 2D Poisson Equation

**Input:** Number of grid divisions _N_ (number of interior points in each direction), Source term function _f_ ( _x, y_ ), Boundary condition function _g_ ( _x, y_ ), Solver parameters (iteration count, convergence tolerance, etc., optional) **Output:** Numerical solution matrix _U ∈_ R[(] _[N]_[+2)] _[×]_[(] _[N]_[+2)] (including boundary points)

- **1** Initialize step size _h_ = 1 _/_ ( _N_ + 1), create solution matrix _U_ of dimension ( _N_ + 2) _×_ ( _N_ + 2)

#### 6.1.2 Apply boundary conditions :

- **3 for** _all boundary points_ ( _i, j_ ) _(i_ = 0 _or i_ = _N_ + 1 _or j_ = 0 _or j_ = _N_ + 1 _)_ **do**

- **4** _U_ [ _i_ ][ _j_ ] _← g_ ( _xi, yj_ )

 **5 Assemble linear system** _A_ **u** = **b** :

- **6 for** _each interior point_ ( _i, j_ ) _(i_ = 1 _, . . . , N , j_ = 1 _, . . . , N )_ **do**

- **7** Construct equation: 4 _ui,j − ui_ +1 _,j − ui−_ 1 _,j − ui,j_ +1 _− ui,j−_ 1 = _−h_[2] _fi,j_

- **8 if** _neighboring point is on boundary_ **then 9** Move its value (known quantity) to the right-hand side **b**

- **10** _Note: The coefficient matrix A is a sparse, symmetric positive definite block tridiagonal matrix (under natural ordering), with at most about_ 5 _non-zero entries per row, dimension N_[2] _× N_[2]

 **11 Solve sparse linear system** :

- **12** Choose a solver (e.g., conjugate gradient method, multigrid method)

- **13** Solve _A_ **u** vec = **b** , obtaining interior solution vector **u** vec

 **14 Reconstruct solution matrix** :

- **15** Map solution vector **u** vec back to interior point positions in _U_

- **16 return** numerical solution matrix _U_

For a problem in _d_ -dimensional space, if discretized into _N_ interior points in each dimension, the total number of degrees of freedom (number of unknowns) is:

_N_ dof = _N[d]_

This relationship reveals the fundamental challenge of the finite difference method: the number of unknowns grows exponentially as the dimension _d_ increases. For example, when _N_ = 100, a two-dimensional problem has 10[4] unknowns, a three-dimensional problem increases to 10[6] , and a four-dimensional problem reaches 10[8] . This “Curse of Dimensionality” imposes enormous computational and storage pressure on traditional numerical methods when dealing with high-dimensional PDE problems.

The computational cost of the finite difference method mainly comes from two stages: system assembly and system solution.

The system assembly stage requires generating the corresponding discrete equation for each interior node. Since the total number of interior nodes is _N[d]_ , and the discrete stencil for each node (e.g., five-point difference) involves only a constant number of neighboring nodes, the time complexity of the assembly stage is

**==> picture [83 x 14] intentionally omitted <==**

The system solution stage is the main bottleneck of the entire computational process. For the resulting sparse linear system _A_ **u** = **b** , different solution strategies exhibit markedly different complexity characteristics.

Direct methods like Gaussian elimination, while theoretically general-purpose, can lead to significant fill-in during the elimination process for sparse matrices, dramatically increasing the density of the coefficient matrix. For general two-dimensional problems, the computational complexity can be as high as _O_ (( _N[d]_ )[3] ) = _O_ ( _N_[3] _[d]_ ), which is usually unacceptable in practice.

Classical iterative methods like Jacobi require only _O_ ( _N[d]_ ) operations per iteration. The convergence rate of such methods is typically linear, meaning the error decays by a fixed ratio each iteration. For elliptic problems, the convergence rate is determined by the spectral radius of the coefficient matrix, and the required number of iterations is inversely proportional to the square of the mesh size _h_ , i.e., _O_ ( _h[−]_[2] ) = _O_ ( _N_[2] ). Therefore, the total complexity of classical iterative methods is

**==> picture [161 x 14] intentionally omitted <==**

Modern iterative methods like the conjugate gradient method can significantly improve convergence efficiency. For the symmetric positive definite system resulting from discretizing the Poisson equation, its condition number satisfies _κ_ ( _A_ ) = _O_ ( _h[−]_[2] ) = _O_ ( _N_[2] ). The number of iterations for the conjugate gradient method is approximately _O_ ( ~~�~~ _κ_ ( _A_ )) = _O_ ( _N_ ), resulting in a total complexity of

**==> picture [141 x 13] intentionally omitted <==**

Optimal methods like the multigrid method, by alternating error correction on grids of different scales, can achieve solution efficiency proportional to the number of unknowns. For sufficiently smooth problems, the computational complexity of the multigrid method can reach

**==> picture [71 x 14] intentionally omitted <==**

This is the theoretically optimal complexity achievable by the finite difference method, keeping the overall computational complexity at the _O_ ( _N[d]_ ) level.

Although the linear system _A_ is sparse—each equation involves only a constant number of unknowns— storage requirements still need careful handling.

If using sparse storage formats like compressed row storage or compressed column storage, only the non-zero elements and their corresponding row and column indices need to be recorded. For the five-point stencil, each interior point corresponds to 5 non-zero elements, so the total storage is _O_ ( _N[d]_ ).

If using a dense storage strategy, i.e., retaining all elements of the matrix (including many zeros), the storage would be as high as _O_ ( _N_[2] _[d]_ ). This approach is completely infeasible for most practical problems, so practical applications must adopt sparse storage strategies to control space complexity at _O_ ( _N[d]_ ).

The error of the finite difference method originates from approximating derivatives with difference quotients. Taking central differences as an example, Taylor expansion yields

**==> picture [232 x 25] intentionally omitted <==**

For the second derivative, its central difference approximation is

**==> picture [278 x 25] intentionally omitted <==**

Thus, the local approximation error (i.e., truncation error) of the central difference scheme is of order _O_ ( _h_[2] ). This means that as the grid is refined, the local error at each discrete point tends to zero at a rate of _h_[2] .

The discretization error refers to the overall difference between the numerical solution and the true solution. When the true solution is sufficiently smooth, the discretization error has the same order as the truncation error. Specifically, there exists a positive constant _C_ independent of _h_ such that

**==> picture [77 x 13] intentionally omitted <==**

where _∥·∥_ can be the _L_[2] norm or the _L[∞]_ norm. This relationship indicates that when the grid step size is halved, the error is reduced to about one-quarter of its original value. Therefore, the above central difference scheme is said to have second-order convergence accuracy.

More generally, if a difference scheme of order _p_ is used, its discretization error satisfies

**==> picture [86 x 11] intentionally omitted <==**

where _p_ is determined by the construction of the difference scheme. It should be noted that the actual convergence order is limited by the smoothness of the true solution: if the true solution lacks sufficient high-order derivatives, the actual convergence rate may be lower than the theoretical value.

The core advantage of the finite difference method lies in its intuitive concept and simple implementation. The method directly constructs discrete schemes based on the definition of derivatives, making the physical meaning clear and easy for beginners to understand and master. For problems on regular domains (such as rectangles, cubes), the finite difference method can efficiently generate sparse linear systems, and its theoretical framework—including stability analysis, convergence proofs, and error estimation—is well-developed, providing solid theoretical guarantees for the reliability of numerical solutions.

However, the finite difference method also faces significant limitations. First, the method has poor adaptability to the geometric shape of the computational domain. When dealing with complex or irregular boundaries, constructing high-accuracy difference schemes that satisfy boundary conditions is often very difficult, usually requiring complex techniques like coordinate transformations or immersed boundary methods. Second, as the spatial dimension increases, the degrees of freedom grow exponentially, leading to a sharp increase in computational cost and storage requirements. This “curse of dimensionality” makes the traditional finite difference method difficult to apply directly to high-dimensional problems.

**2. Finite Element Method (FEM)**

If the finite difference method (FDM) imposes rules “point by point,” then the finite element method (FEM) constructs the solution “piece by piece.” Its core idea is: partition the complex solution domain into many nonoverlapping small pieces, such as triangles or quadrilaterals; these small pieces are called “elements.” On each element, we use a simple function (e.g., a low-degree polynomial) to approximate the true solution, much like using many small polygonal tiles to mosaic a floor of complex shape, drawing simple patterns on each tile. By cleverly combining these “local approximations,” we can obtain a global approximate solution over the entire domain.

Unlike the finite difference method, which directly discretizes the partial differential equation, the finite element method deals with the “weak form” (integral form) of the original equation. The weak form, through “averaging” over the integration domain, reduces the smoothness requirements on the solution—allowing the solution to have discontinuous derivatives in some places, which provides convenience for handling complex problems. Meanwhile, certain boundary conditions (like natural boundary conditions) are automatically incorporated into the weak form without needing extra treatment. The core of the finite element method is the Galerkin method: we seek an approximate solution within a finite-dimensional function space spanned by piecewise polynomial basis functions, and require the residual of the partial differential equation to be orthogonal to all “test functions” in that space, thereby ensuring the approximate solution is as close as possible to the true solution in an overall sense.

**Figure 6.1:** Schematic of the 2D finite element method: Left figure shows triangular element mesh, node _i_ connected to several elements; Right figure illustrates the corresponding linear basis function _ϕi_ ( _x, y_ ) as a “tent function,” taking value 1 at node _i_ , 0 on the support boundary, and varying linearly on each adjacent triangular element.

**==> picture [118 x 79] intentionally omitted <==**

**----- Start of picture text -----**<br>
i<br>K 1 K 2<br>2D triangular mesh<br>**----- End of picture text -----**<br>


**==> picture [183 x 143] intentionally omitted <==**

**----- Start of picture text -----**<br>
ϕi = 1 ϕi ( x, y )<br>i<br>ϕi = 0 (adjacent boundary)<br>Linear basis function (tent function)<br>**----- End of picture text -----**<br>


Next, using the two-dimensional Poisson equation as an example, we introduce the four main steps of the finite element method:

**==> picture [215 x 28] intentionally omitted <==**

**==> picture [147 x 12] intentionally omitted <==**

The finite element solution process can be divided into the following four main steps.

Step 1: Domain Discretization

Partition the solution domain Ω into many small triangular (or quadrilateral) elements, forming a triangular mesh. Unlike the finite difference method, finite element elements can flexibly conform to complex geometric

126

6.1 Overview of PDE Problems and Traditional Numerical Methods

boundaries. Denote the mesh as _Th_ = _{K}_ , where _h_ represents the characteristic size of the elements (usually taken as the diameter of the circumscribed circle of the largest element). The set of all element vertices constitutes the node set.

Step 2: Construct Finite Element Space

On each element _K_ , we need a “local blueprint” to describe the shape of the solution on that element. This blueprint is the shape function. Taking linear elements on triangular elements as an example, define three shape functions _N_ 1 _[K]_[(] _[x, y]_[)][,] _[ N]_ 2 _[K]_[(] _[x, y]_[)][,] _[ N]_ 3 _[K]_[(] _[x, y]_[)][ on element] _[ K]_[, which satisfy:]

On each element, the shape functions are linear functions of _x_ and _y_ , simple in form, easy to integrate and differentiate

Take value 1 at the corresponding vertex (node) and 0 at the other two vertices

This means that if we know the function values _ci_ 1 _, ci_ 2 _, ci_ 3 at the three vertices of element _K_ , we can uniquely construct the approximate solution on the element via the shape functions:

**==> picture [257 x 14] intentionally omitted <==**

Here, the shape functions act as “interpolators,” smoothly extending the discrete nodal values to the entire interior of the element.

Next, we need to piece these “local blueprints” together into a global approximate function. To do this, we define a global basis function _ϕi_ ( _x, y_ ) for each global node _i_ . Its construction is very intuitive: “stitch together” the shape function corresponding to node _i_ from all elements containing node _i_ , and set it to 0 on all other elements. The global basis function _ϕi_ has the following key properties:

Local support: _ϕi_ is non-zero only on the ring of elements surrounding node _i_ , and zero elsewhere. This ensures sparsity in subsequent computations.

Nodal interpolation property: _ϕi_ takes value 1 at node _i_ and 0 at all other nodes.

The approximate solution _uh_ ( _x, y_ ) over the entire domain can be expressed as a linear combination of all nodal basis functions:

**==> picture [113 x 33] intentionally omitted <==**

where _M_ is the total number of nodes, and _ci_ are the unknown coefficients to be determined, whose physical meaning is the approximate solution value at the node. In this way, shape functions provide the “local description” on each element, while global basis functions are responsible for “seamlessly stitching” these local descriptions into a continuous function over the entire domain (for linear elements, the solution is automatically continuous across element boundaries).

Step 3: Form Weak Form and Discrete System

To obtain the finite element equations, we first derive the weak form of the Poisson equation. Multiply the original equation by a “test function” _v_ and integrate over the domain Ω. Using the divergence theorem (integration by parts in higher dimensions) to transform second derivatives into first derivatives:

**==> picture [215 x 26] intentionally omitted <==**

For Dirichlet boundary conditions (given function values on the boundary), we enforce the approximate solution to equal the known value _g_ on the boundary, so the test function _v_ is taken as 0 on the boundary, and the boundary integral term automatically vanishes. Thus, the problem transforms into: find _u_ satisfying the boundary conditions such that the above integral equality holds for all admissible test functions.

_M_ Now, substitute the approximate solution _uh_ = _i_ =1 _[c][i][ϕ][i]_[and][take][the][test][function] _[v]_[to][be][each][basis] function _ϕj_ (i.e., the Galerkin method). This yields _M_ equations:

Denote

**==> picture [251 x 76] intentionally omitted <==**

Then the above system can be written in concise matrix form:

**==> picture [36 x 9] intentionally omitted <==**

where _A_ is called the stiffness matrix, **b** is the load vector, and **c** is the vector of unknown coefficients. Step 4: Assembly and Solution

The computation of the stiffness matrix and load vector does not need to be performed directly over the global domain; instead, we utilize the local support property of the basis functions: each _ϕi_ is non-zero only on a few elements. Therefore, we can compute local contributions on each element separately, then “assemble” the contributions from all elements into the global matrix and vector. Specifically:

On each element _K_ , compute the element stiffness matrix and element load vector;

According to the node numbering, accumulate the element contributions to the corresponding positions in the global matrix _A_ and global vector **b** .

Since each basis function only overlaps with basis functions of adjacent nodes, the stiffness matrix _A_ is sparse— the proportion of non-zero entries is low, and it is usually symmetric positive definite (for the Poisson equation). This sparsity allows us to solve the linear system using efficient iterative solvers (like the conjugate gradient method) or direct solvers (like sparse LU decomposition), completing the solution in reasonable time even when the number of nodes reaches millions.

After solving for the coefficient vector **c** , substitute it into _uh_ ( _x, y_ ) = _ciϕi_ ( _x, y_ ) to obtain the finite element approximate solution of the original problem over the entire domain.

For a two-dimensional triangular mesh, the number of nodes _M_ is roughly proportional to the number of elements. More generally, in _d_ -dimensional space, to achieve discretization accuracy with characteristic size _h_ , the required degrees of freedom (number of nodes) is approximately _O_ ( _h[−][d]_ ). This relationship is identical to that of the finite difference method, again revealing the essence of the curse of dimensionality—as the spatial dimension increases, degrees of freedom grow exponentially, directly leading to a sharp increase in computational cost and storage requirements.

The stiffness matrix _A_ resulting from finite element discretization has three important properties: sparsity, symmetry, and positive definiteness (for elliptic problems). Sparsity arises because each basis function is nonzero only on a finite number of elements in its support, so each node couples only with adjacent nodes, and the vast majority of matrix entries are zero. When using sparse storage formats, the storage requirement is only _O_ ( _M_ ), i.e., linear in the number of degrees of freedom. Symmetry and positive definiteness allow efficient iterative algorithms like the conjugate gradient method to be applied.

The computational complexity of the finite element method consists of two stages: assembly and solution. The assembly stage requires integral calculations for each element; since the computation per element is constant, the total complexity of assembly is _O_ ( _M_ ). The complexity of the solution stage depends on the linear solver used. If using sparse direct methods (e.g., solvers based on multifrontal elimination), for two-dimensional problems, the complexity typically ranges between _O_ ( _M_[1] _[.]_[5] ) and _O_ ( _M_[2] ); if using optimal iterative solvers like the multigrid method, the solution complexity can be reduced to _O_ ( _M_ ), achieving optimal efficiency linear in the number of degrees of freedom.

**Algorithm 6.2:** Finite Element Method for Solving 2D Poisson Equation (Triangular Linear Elements)

**Input:** Node coordinate array **nodes** , dimension _M ×_ 2, Element connectivity array **elements** , each element contains 3 node indices, Right-hand side function _f_ ( _x, y_ ), Dirichlet boundary node list **dirichlet** _ **nodes** and corresponding boundary values **Output:** Nodal solution vector **u** , where _ui ≈ u_ ( **x** _i_ )

**1** Initialize global stiffness matrix **A** (using sparse storage format) and load vector **b** to zero

**2 for** _each triangular element K ∈_ **elements do 3** Get coordinates of the element’s three nodes **x** 1 _,_ **x** 2 _,_ **x** 3 **4** Compute element stiffness matrix **A** _K ∈_ R[3] _[×]_[3] : ( _AK_ ) _ij_ = _∇ϕi · ∇ϕj d_ Ω � _K_ **5** Compute element load vector **b** _K ∈_ R[3] : ( _bK_ ) _i_ = _fϕi d_ Ω � _K_ **6** Assemble **A** _K_ into corresponding positions of global matrix **A** (according to element’s local-to-global node mapping) **7** Assemble **b** _K_ into corresponding positions of global vector **b 8 Handle Dirichlet boundary conditions** : **9 for** _each boundary node i ∈_ **dirichlet** ___ **nodes do 10** Enforce _ui_ = _g_ ( **x** _i_ ) **11** Modify row _i_ and column _i_ of matrix **A** (typically set row _i_ , column _i_ to 1, adjust right-hand side accordingly)

- **12** Solve sparse linear system **Au** = **b** (using sparse direct method like UMFPACK, or iterative method like conjugate gradient)

- **13 return** nodal solution vector **u**

Regarding the convergence accuracy of the finite element method, for linear elements (i.e., using firstdegree polynomial approximation), when the true solution is sufficiently smooth, the error satisfies the following estimates:

**==> picture [215 x 13] intentionally omitted <==**

where the _L_[2] norm measures the error in the function values themselves, and the _H_[1] energy norm measures the overall error in function values and their first derivatives. This means that when the mesh is refined by a factor of two, the function value error is reduced to about one-quarter, and the derivative error is reduced to about one-half.

More generally, if using elements of polynomial degree _p_ , the convergence order can be improved to

 _∥u − uh∥L_ 2 = _O_ ( _h[p]_[+1] )

This property reveals the intrinsic relationship between accuracy and element order in the finite element method: increasing the polynomial degree can significantly accelerate convergence speed. However, this improvement in accuracy is not without cost—higher-order elements require more integration points and degrees of freedom per element, and the complexity of program implementation also increases accordingly. Therefore, in practical applications, a trade-off must be made between accuracy, efficiency, and implementation difficulty: linear elements ( _p_ = 1) are widely popular due to their simplicity, quadratic elements ( _p_ = 2) offer a good balance between accuracy and efficiency, while higher-order elements are typically used for special problems requiring extremely high accuracy.

The core advantage of the finite element method lies in its strong adaptability to complex geometric shapes. Through unstructured meshes (e.g., triangular, tetrahedral meshes), the finite element method can precisely conform to arbitrarily complex boundaries, giving it unparalleled flexibility when dealing with practical engineering problems. Furthermore, the finite element method has a rigorous mathematical theoretical foundation—based on Sobolev spaces and variational principles—and its stability analysis and error estimation framework are welldeveloped. For these reasons, the finite element method has become the most mainstream numerical method in engineering fields such as structural mechanics, fluid mechanics, and heat conduction.

However, the finite element method also faces non-negligible challenges. First, the curse of dimensionality in high-dimensional problems still exists—as the spatial dimension increases, the number of elements and nodes grows exponentially, causing computational costs to rise sharply. Second, generating high-quality computational meshes (especially three-dimensional unstructured meshes) is itself a highly challenging task, often requiring specialized pre-processing software and significant manual intervention, and mesh quality directly affects the accuracy and stability of the numerical solution. For dynamic problems involving moving boundaries, free surfaces, or large deformations, the mesh may need frequent regeneration, further increasing computational complexity and implementation difficulty.

 **3. Finite Volume Method (FVM)**

The idea of the finite volume method is rooted in the most fundamental conservation laws of the physical world. It divides the solution domain into many non-overlapping control volumes (usually the grid cells themselves), then directly applies the conservation law to each control volume: the rate of change of a physical quantity (such as mass, momentum, energy) equals the net flux entering through its boundaries plus internal source terms. This naive idea of “from local conservation to global conservation” makes FVM inherently conservative at the discrete level, which is its most distinctive feature compared to finite difference and finite element methods.

Unlike the finite difference method, which directly approximates derivatives, FVM discretizes the conservation law equation in integral form. Using the divergence theorem, it transforms volume integrals over a control volume into flux integrals over its boundary, thereby converting the continuous equation into a set of discrete balance equations. This approach makes FVM particularly suitable for handling flow problems with strong nonlinear phenomena like shocks and discontinuities—in these problems, derivatives of the solution may not exist, but the integral form of the conservation law still holds. Figure 6.2 illustrates the division of control volumes and the physical picture of flux exchange for a one-dimensional case:

In one dimension, each control volume is centered at node _xi_ , with left and right boundaries at _xi−_ 1 _/_ 2 and _xi_ +1 _/_ 2 respectively. The conservation law requires:

**Figure 6.2:** Schematic of 1D finite volume method: Each control volume is centered at node _xi_ , _ui_ is the solution value at node _xi_ , _Fi±_ 1 _/_ 2 are the fluxes at interfaces _xi±_ 1 _/_ 2, flux exchange occurs at interfaces _xi−_ 1 _/_ 2 and _xi_ +1 _/_ 2

**==> picture [280 x 136] intentionally omitted <==**

**----- Start of picture text -----**<br>
Fi− 1 / 2 Fi +1 / 2<br>Control volume  i<br>x<br>xi− 1 xi− 1 / 2 xi xi +1 / 2 xi +1<br>ui− 1 ui ui +1<br>∆ xi<br>———<br>Control volume boundary<br>→ Flux direction<br>• Node position<br>|<br>**----- End of picture text -----**<br>


**==> picture [347 x 41] intentionally omitted <==**

where _F_ denotes the flux through the boundary (physical quantity transferred per unit time per unit area). This equation forms the physical basis for finite volume discretization.

Consider the one-dimensional steady-state convection-diffusion equation:

**==> picture [160 x 100] intentionally omitted <==**

where _a_ is the convection velocity (constant), _ν >_ 0 is the diffusion coefficient, and _f_ is the source term. This equation is already written in conservation form _[dF] dx_[=] _[f]_[,][where][the][total][flux] _[F]_[consists][of][convection][and] diffusion terms:

Integrate over control volume _Vi_ = [ _xi−_ 1 _/_ 2 _, xi_ +1 _/_ 2]:

**==> picture [242 x 29] intentionally omitted <==**

This integral form does not involve derivatives, allowing for discontinuous solutions, reflecting FVM’s adaptability to weak solutions.

Next, discretize. Denote _Fi_ +1 _/_ 2 as the flux approximation at interface _xi_ +1 _/_ 2, i.e., _Fi_ +1 _/_ 2 _≈ F_ ( _ui, ui_ +1), and approximate the right-hand side source term as _fi_ ∆ _xi_ (∆ _xi_ is the control volume width). Then the discrete equation is:

**==> picture [115 x 13] intentionally omitted <==**

The core of the problem lies in how to construct the interface flux _Fi_ +1 _/_ 2, i.e., approximate the physical flux at that interface based on neighboring node values _ui, ui_ +1. Different reconstruction methods are used for different physical mechanisms:

Diffusion term _−ν[du]_[Usually][central][differencing][is][used,][because][diffusion][is][an][isotropic][physical] _dx_[:] process:

**==> picture [129 x 28] intentionally omitted <==**

where ∆ _x_ = _xi_ +1 _− xi_ (assuming uniform grid).

Convection term _au_ : Convection has directionality; information propagates along the flow direction, so it is necessary to choose the “upwind” value based on the flow velocity direction to ensure numerical stability:

**==> picture [243 x 40] intentionally omitted <==**

This upwind scheme is physically reasonable: the convective flux at the interface is determined by the physical quantity upstream. The upwind scheme is unconditionally stable but only first-order accurate. Combining the two parts above gives the discrete form of the total flux:

**==> picture [316 x 40] intentionally omitted <==**

Substituting into the discrete equation and rearranging yields a linear system for the node values _ui_ :

**==> picture [381 x 27] intentionally omitted <==**

This is a tridiagonal system that can be solved directly using the efficient Thomas algorithm.

The greatest advantage of the finite volume method is its inherent conservation property. Since the method starts directly from the integral form of the conservation law, the discrete equation on each control volume precisely satisfies the balance of physical quantities; fluxes on internal interfaces cancel each other during global assembly, thus strictly maintaining overall conservation at the discrete level. This characteristic makes the finite volume method particularly suitable for handling multi-physics problems involving conservation of mass, momentum, and energy, such as fluid dynamics and heat transfer, ensuring physical reasonability of the solution even on coarse grids. Furthermore, the finite volume method has good adaptability to complex geometry, can handle complex computational domains in engineering using unstructured meshes, and coupled with its strong numerical stability (especially with upwind schemes), it has become the mainstream method in commercial software for computational fluid dynamics (CFD).

However, the finite volume method also has certain limitations. Constructing high-order accurate schemes is more complex than in the finite element method, requiring flux reconstruction at element interfaces and often introducing limiters to suppress unphysical oscillations, which imposes higher demands on scheme design and program implementation. At the same time, rigorous mathematical error analysis (such as a priori and a posteriori error estimates) is not as systematic and complete within the finite volume framework as it is for the finite element method, leaving its theoretical foundation somewhat less comprehensive. For high-dimensional problems on unstructured meshes, balancing accuracy, stability, and computational efficiency remains an ongoing research topic and challenge in finite volume method applications.

**Algorithm 6.3:** Finite Volume Method for Solving 1D Steady Convection-Diffusion Equation (Upwind Scheme)

**Input:** Grid node coordinate array _x_ [0 _..N_ ], where _N_ is number of elements (number of nodes is _N_ + 1),

Convection velocity _a_ (constant), diffusion coefficient _ν >_ 0, Source term function _f_ ( _x_ ), Boundary values _u_ 0 = _u_ ( _x_ 0), _uN_ = _u_ ( _xN_ ) (Dirichlet boundary conditions) **Output:** Nodal solution vector **u** = [ _u_ 0 _, u_ 1 _, . . . , uN_ ][T] , where _ui ≈ u_ ( _xi_ )

- **1** Compute lengths of each control volume ∆ _xi_ = _xi_ +1 _− xi_ , _i_ = 0 _,_ 1 _, . . . , N −_ 1

- **2** Initialize tridiagonal coefficient matrix **A** _∈_ R[(] _[N]_[+1)] _[×]_[(] _[N]_[+1)] and right-hand side vector **b** _∈_ R _[N]_[+1] to zero

 **3 for** _each interior control volume i_ = 1 _,_ 2 _, . . . , N −_ 1 **do**

**==> picture [327 x 268] intentionally omitted <==**

**6** Assemble into tridiagonal matrix: _Ai,i−_ 1 = _−_ � _d_[left] + max(0 _, −a_ )� _Ai,i_ = _d_[left] + _d_[right] + _|a| Ai,i_ +1 = _−_ � _d_[right] + max(0 _, a_ )� **7** Compute source term contribution (midpoint integration approximation):

 **8 Handle Dirichlet boundary conditions** :

_A_ 0 _,_ 0 = 1, _b_ 0 = _u_ 0 (left boundary) _AN,N_ = 1, _bN_ = _uN_ (right boundary)

Set other elements in boundary rows to zero (maintain matrix structure)

- **9** Solve tridiagonal linear system **Au** = **b** (using Thomas algorithm, time complexity _O_ ( _N_ ))

- **10 return** nodal solution vector **u**

 **4. Spectral Methods**

Spectral methods adopt a “global” strategy fundamentally different from the finite element method. While the finite element method uses locally supported “small tent” basis functions, each affecting only a small surrounding region, spectral methods use smooth, oscillatory global functions defined over the entire domain as basis functions, such as sine functions, cosine functions, Chebyshev polynomials, Legendre polynomials, etc.

The idea is to expand the unknown solution as a series of these global basis functions, then determine the expansion coefficients through some criterion (e.g., requiring the residual of the partial differential equation to be zero at collocation points, or orthogonal to all basis functions).

Behind this global approximation strategy lies a profound trade-off: if the solution to the problem is itself smooth (i.e., infinitely differentiable), then approximating it with equally smooth global basis functions can be extremely efficient. Unlike the algebraic convergence of finite difference or finite element methods (error decreases as a power law with increasing degrees of freedom), spectral methods can achieve exponential convergence—meaning adding a few basis functions can cause the error to drop dramatically, achieving very high accuracy with very few degrees of freedom.

Taking Fourier basis functions sin( _kπx_ ), cos( _kπx_ ) defined on interval [0 _,_ 1] and Chebyshev basis functions _Tk_ ( _x_ ) = cos( _k_ arccos _x_ ) defined on [ _−_ 1 _,_ 1] as examples, low-order basis functions (small _k_ ) have smooth waveforms and long wavelengths, while high-order basis functions (large _k_ ) exhibit rapid oscillations and shorter wavelengths. In numerical implementation, Chebyshev-Gauss collocation points are often used; such nodes are densely distributed near the boundaries and become sparser towards the middle of the interval. This node distribution helps suppress the Runge phenomenon (i.e., violent oscillatory distortion near the ends of the interval when using equidistant nodes for high-degree polynomial interpolation), thereby improving the stability of highorder interpolation.

Spectral methods use oscillatory basis functions over the entire interval; low-order basis functions describe large-scale features of the solution, while high-order basis functions capture fine structures.

Consider the one-dimensional Poisson equation defined on interval [ _−_ 1 _,_ 1]:

**==> picture [131 x 13] intentionally omitted <==**

with Dirichlet boundary conditions _u_ ( _−_ 1) = _a_ , _u_ (1) = _b_ . We choose Chebyshev polynomials as basis functions:

**==> picture [190 x 12] intentionally omitted <==**

Chebyshev polynomials are orthogonal on interval [ _−_ 1 _,_ 1] with respect to the weight function 1 _/√_ 1 _− x_[2] , and naturally form denser node distributions near the boundaries, making them particularly suitable for handling boundary layer problems. The approximate solution is expressed as a truncated expansion:

**==> picture [99 x 34] intentionally omitted <==**

where _u_ ˆ _k_ are the unknown expansion coefficients.

Spectral methods mainly have two implementation approaches:

Galerkin spectral method: Substitute the approximate solution into the differential equation and require the residual to be orthogonal to all test functions _Tj_ ( _x_ ) ( _j_ = 0 _,_ 1 _, . . . , N_ ) in the weighted inner product sense:

**==> picture [181 x 28] intentionally omitted <==**

This leads to an algebraic system for the coefficients _u_ ˆ _k_ . Due to the orthogonality of Chebyshev polynomials and the special structure of derivative relationships, for some linear equations with constant coefficients, the stiffness matrix can be diagonal or nearly diagonal, making computation relatively efficient. Collocation method (pseudospectral method): This is the more common form in engineering applications.

We choose a special set of collocation points—Chebyshev-Gauss-Lobatto nodes:

**==> picture [159 x 28] intentionally omitted <==**

These nodes are exactly _−_ 1 and 1 at the interval endpoints, and become denser closer to the boundaries. The collocation method requires the approximate solution _uN_ ( _x_ ) to satisfy the differential equation exactly at each interior collocation point:

**==> picture [179 x 13] intentionally omitted <==**

while boundary conditions are directly enforced at the endpoint nodes:

**==> picture [127 x 11] intentionally omitted <==**

To compute _u[′′] N_[(] _[x][j]_[)][, a differentiation matrix is introduced.][Denote] _[ u][j]_[=] _[u][N]_[(] _[x][j]_[)][ as the function values] at the nodes; then derivatives can be computed via matrix multiplication:

**==> picture [208 x 33] intentionally omitted <==**

where _D_ is the first-order differentiation matrix, and _D_[(2)] = _D · D_ is the second-order differentiation matrix. Both matrices are dense, and their elements can be given explicitly via analytical formulas for Chebyshev polynomials. Thus, the discretized equation at interior collocation points is written as:

**==> picture [195 x 34] intentionally omitted <==**

Combined with boundary conditions, this yields a system of linear algebraic equations for the node values _{uk}_ .

Algorithm 6.4 shows the complete process of the collocation spectral method for solving the one-dimensional Poisson equation.

**Algorithm 6.4:** Collocation Spectral Method for Solving 1D Poisson Equation (Chebyshev Basis Functions)

**Input:** Truncation order _N_ (highest polynomial degree), Right-hand side function _f_ ( _x_ ), Boundary values _a_ = _u_ ( _−_ 1), _b_ = _u_ (1)

**Output:** Solution vector **u** at collocation points, where _uj ≈ u_ ( _xj_ )

- **1** Generate Chebyshev-Gauss-Lobatto nodes:

**==> picture [159 x 27] intentionally omitted <==**

- **2** Construct first-order differentiation matrix **D** _∈_ R[(] _[N]_[+1)] _[×]_[(] _[N]_[+1)] (standard formula, dense matrix)

- **3** Compute second-order differentiation matrix **D**[(2)] = **D** _·_ **D**

- **4 Extract submatrix and right-hand side corresponding to interior nodes** : Interior node indices: _j_ = 1 _,_ 2 _, . . . , N −_ 1

**A** int = **D**[(2)] [1 : _N,_ 1 : _N_ ] (size ( _N −_ 1) _×_ ( _N −_ 1))

**b** int = _f_ ( _x_ 1: _N_ ) _−_ **D**[(2)] [1 : _N,_ 0] _· a −_ **D**[(2)] [1 : _N, N_ ] _· b_

- **5** Solve dense linear system **A** int **u** int = **b** int (using LU decomposition, time complexity _O_ ( _N_[3] ))

- **6** Combine full solution vector: **u** = [ _a,_ **u** int _, b_ ][T]

- **7 return** solution vector **u** at collocation points

Spectral methods are extremely efficient in their use of degrees of freedom. In one-dimensional problems, the degrees of freedom of the solution are determined by the truncation order _N_ , merely _O_ ( _N_ ), independent of grid step size. Extending to _d_ -dimensional space, if using tensor product basis functions, the degrees of freedom become _O_ ( _N[d]_ ). This means that to achieve the same resolution, spectral methods require far fewer degrees of freedom than finite difference or finite element methods.

However, the cost of this efficiency is reflected in the structure of the algebraic system. The differentiation matrix produced by the collocation method is dense—the derivative calculation at each collocation point depends on function values at all nodes, so the discrete algebraic system matrix is also dense. In one-dimensional problems, the storage cost is _O_ ( _N_[2] ), and direct solution (e.g., LU decomposition) computational cost is _O_ ( _N_[3] ). For two-dimensional problems, if using _N_[2] collocation points, the matrix size becomes _N_[2] _× N_[2] , with storage and solution costs rising to _O_ ( _N_[4] ) and _O_ ( _N_[6] ) respectively, a growth trend that becomes unbearable in highdimensional cases. Therefore, practical high-dimensional spectral methods often need to rely on fast transforms (like the Fast Fourier Transform) or iterative solution techniques to avoid directly handling dense matrices. The most striking feature of spectral methods is their convergence rate. If the true solution is infinitely smooth (i.e., all derivatives exist and are continuous), then as the truncation order _N_ increases, the approximation error decays exponentially:

**==> picture [101 x 13] intentionally omitted <==**

where _c >_ 0 is a constant. This means that adding a few basis functions reduces the error by an order of magnitude. To achieve 10 _[−]_[6] accuracy, the finite element method may require tens of thousands of degrees of freedom, while spectral methods often need only a few dozen. This exponential convergence rate is much faster than the algebraic convergence _O_ ( _N[−][p]_ ) of finite difference or finite element methods, making spectral methods an ideal tool for high-precision computation.

However, this remarkable convergence speed has a key prerequisite: the solution must be smooth. If the true solution has discontinuities or sharp corners, the situation is completely different. Approximating a nonsmooth function with smooth global basis functions leads to the famous Gibbs phenomenon—violent unphysical oscillations near the discontinuity, which do not disappear as _N_ increases, only making the oscillation frequency higher. From a convergence perspective, when the solution is not smooth, the convergence rate of spectral methods deteriorates sharply to algebraic convergence _O_ ( _N[−]_[1] ) or worse. This sensitivity constitutes the main application limitation of spectral methods.

The greatest advantage of spectral methods lies in their unparalleled accuracy and efficiency for smooth problems. Exponential convergence means that extremely high-precision numerical solutions can be obtained with very few degrees of freedom, making spectral methods the method of choice in fields requiring highprecision computation, such as direct numerical simulation (DNS) of turbulence, quantum chemistry calculations, and spectral models in weather forecasting. At the same time, for periodic problems and problems on regular domains, spectral methods can fully utilize techniques like the Fast Fourier Transform to achieve efficient computation.

However, the limitations of spectral methods are equally apparent. They have extremely stringent requirements on the smoothness of the solution; once the solution has discontinuities or local sharp variations, convergence deteriorates drastically, and even unphysical oscillations may appear. Furthermore, spectral methods have poor adaptability to complex geometric shapes—traditional spectral methods require the computational domain to be regular shapes like rectangles, annuli, etc., making it difficult to handle irregular domains common in engineering. Although variants like the spectral element method combine the geometric flexibility of finite elements with the high accuracy of spectral methods by partitioning the computational domain into multiple subdomains and using spectral approximation on each, the implementation complexity and computational cost increase significantly. Finally, the dense matrix nature of spectral methods causes computational costs to rise sharply for high-dimensional problems, limiting their widespread application in problems beyond three dimensions.

### 6.2 Basic framework and mathematical principles of PINNs

Although traditional numerical methods have achieved great success and form the backbone of modern scientific computing, they reveal inherent limitations when facing the following emerging challenges. These limitations precisely constitute the core motivation for AI methods represented by PINNs to intervene in the field of PDE solving.

#### 6.2.1 Challenge 1: The “curse of dimensionality” in high-dimensional problems

This is the most fundamental challenge. The degrees of freedom (number of grid points, elements, basis functions) of traditional grid-based methods grow exponentially with the spatial dimension _d_ . For example, in a _d_ -dimensional unit hypercube, if each dimension is discretized into _N_ points, then the degrees of freedom for FDM and FEM (on quasi-uniform grids) are approximately _N[d]_ . For a moderate dimension _d_ = 10, even with only _N_ = 10 points per dimension, the total degrees of freedom reach as high as 10[10] , which already exceeds conventional computing capabilities. While spectral methods also have degrees of freedom of _O_ ( _N[d]_ ), the storage and computational costs of their dense matrices _O_ ( _N_[2] _[d]_ ) are even more catastrophic. As a function approximator, the number of parameters (weights and biases) of a neural network mainly depends on the width and depth of the network, and not directly on the dimension of the input space. PINNs take spatial and temporal coordinates as input and directly output the value of the solution at that point. This “point-to-point” solving approach bypasses the need for global discretization of the entire high-dimensional space. Although the training process also requires computing the loss at many points, these points are randomly or adaptively sampled, and their number can be controlled independently of the dimension, offering a potential pathway to alleviate the curse of dimensionality.

#### 6.2.2 Challenge 2: Complicated geometry, inverse problems, and automation

For complex and irregular solution domains, although FEM and FVM can adapt through mesh generation, generating high-quality meshes itself is computationally expensive. Moreover, for scenarios involving topological changes (e.g., crack propagation), moving boundaries (e.g., free surfaces), or inferring geometry (inverse problems), the mesh may need dynamic adjustment, which is cumbersome and requires expertise. PINNs are inherently meshless methods. The network input is merely coordinate points ( _x, y, z, t_ ). As long as points can be sampled within the domain (including boundaries), the loss function can be constructed for training, making it highly insensitive to geometric complexity. This advantage is particularly evident when solving inverse problems: for example, in problems where only partial internal observation data (e.g., readings from several sensors) are known, and physical parameters, unknown source terms, or even boundary shapes need to be inferred simultaneously. PINNs can naturally formulate this as a unified optimization problem by incorporating the PDE residual, boundary conditions (if known), and data fitting terms into the loss function. The neural network parameters simultaneously encode the solution and the parameters to be inverted, and both can be obtained through a single training process, without the need to regenerate meshes and solve the forward problem for each possible parameter or geometric hypothesis.

#### 6.2.3 Challenge 3: Integrating multi-source heterogeneous data and uncertainty quantification

Traditional numerical solvers are typically “purely physics-driven”: given complete governing equations and well-posed conditions, they output a deterministic solution. However, in practical applications, we often have sparse, noisy data from experiments or observations, and there may also be epistemic uncertainty about certain physical parameters or boundary conditions. Traditional methods struggle to seamlessly and naturally integrate these data and uncertainties into the solving process, often requiring complex data assimilation (e.g., 4D-Var) or stochastic PDE frameworks. The PINN loss function has a natural capacity for fusion and potential for probabilistic interpretation extension. It can sum the PDE residual loss, boundary/initial condition loss, and data fitting loss with weights. By minimizing this total loss, the solution learned by the neural network simultaneously satisfies physical laws and actual observation data, becoming a “physics-driven + data-driven” hybrid model. Furthermore, by employing a Bayesian framework or introducing random variables, PINNs can quantify prediction uncertainty, which is crucial for simulation-based decision-making.

**Challenge 4: Automation and Generality of the Solving Process**

Implementing traditional numerical methods typically requires significant intervention from domain experts: selecting appropriate methods based on problem type (FEM vs. FVM), generating high-quality meshes, designing stable discretization schemes, handling complex boundary conditions, selecting and tuning solver parameters (e.g., iteration tolerance, preconditioners), etc. This process is highly specialized, difficult to automate, and has poor portability. PINNs provide a relatively unified framework: for a large class of PDE problems, the workflow can be abstracted as “define network architecture, construct physics-informed loss (using automatic differentiation), sample coordinate points within the domain and on boundaries, train the network to optimize the loss.” The automatic differentiation (Autograd) functionality provided by modern deep learning frameworks (e.g., PyTorch, TensorFlow) makes computing PDE residuals (often involving high-order partial derivatives) exceptionally simple—one only needs to code the original equation without manually deriving complex discretization schemes. This greatly lowers the barrier to entry for PDE solving and facilitates the construction of general-purpose solving tools and code libraries.

Next, we detail the basic framework and mathematical principles of PINNs.

From a mathematical perspective, solving a PDE problem essentially involves finding a function that satisfies specific equations and boundary/initial conditions. This is a classic function approximation problem: we wish to find a specific function satisfying complex constraints within an infinite-dimensional function space. Traditional numerical methods solve the continuous problem by discretizing it, transforming the infinitedimensional problem into a finite-dimensional linear or nonlinear system. Although this discretization process is effective, it also, to some extent, “solidifies” our representation of the solution (e.g., a linear combination of basis functions) and tightly couples computational complexity with mesh resolution.

It is in this context that Physics-Informed Neural Networks emerged. The core idea is: Can we leverage the powerful function approximation capability of neural networks to directly approximate the solution function that satisfies the PDE constraints? This idea did not arise out of thin air. As early as the 1990s, researchers explored using neural networks to solve differential equations. However, its true revival and widespread application benefited from the revolutionary progress in deep learning in the 2010s: the emergence of efficient automatic differentiation frameworks, the proliferation of large-scale parallel computing hardware, and the deepening theoretical understanding of neural networks. The “Physics-Informed Neural Networks” framework proposed by Raissi et al. in 2019 clearly outlined the mathematical contours of this paradigm, making it a unified and flexible solver.

The fundamental motivation of PINNs lies in transforming PDE solving from a purely numerical discretization problem into a machine learning problem constrained by physical laws. The neural network is no longer merely a black-box fitting tool but becomes a “white-box” or “gray-box” model embedded with physical prior knowledge. This shift in perspective offers new possibilities for solving complex problems that are difficult for traditional methods to handle (e.g., high-dimensional, inverse problems, data assimilation).

##### 6.2.3.1 Core idea: The loss function as the “guardian” of physical laws

The basic idea of PINNs is intuitive and powerful. We can summarize it into the following key steps:

Step 1: Parameterize the unknown solution. Use a neural network to approximate the PDE solution. The neural network input is the spatial coordinates **x** and time _t_ , and the output is the approximate solution value _u_ ˜( **x** _, t_ ; _**θ**_ ), where _**θ**_ represents all adjustable parameters (weights and biases) of the network. Unlike traditional numerical methods, there is no concept of a grid here—the neural network itself is a global function approximator.

Step 2: Encode physical laws into the loss function. The PDE itself, initial conditions, and boundary conditions are no longer treated as “hard constraints” that must be strictly satisfied but are transformed into “soft constraints” that can be optimized, i.e., parts of a loss function. The goal of network training is to minimize this loss function. This approach reflects a profound shift in perspective: instead of satisfying the equation exactly at discrete points, we seek a function that “as much as possible” satisfies all constraints over the entire domain.

Step 3: Solve via optimization. Use gradient-based optimization algorithms (e.g., Adam, L-BFGS) to adjust the network parameters _**θ**_ so that the loss function continuously decreases. When the loss is sufficiently small, we consider the neural network output _u_ ˜ to be an acceptable approximate solution to the original PDE.

The cleverness of this framework lies in its full utilization of automatic differentiation technology in modern deep learning frameworks. To compute the PDE residual (i.e., the difference between the left and right sides of the equation), we need to compute the partial derivatives of the approximate solution _u_ ˜ with respect to input variables (e.g., _x, t_ ). In traditional programming, this requires manual derivation or symbolic computation, which is cumbersome and error-prone. However, in modern frameworks like TensorFlow and PyTorch, automatic differentiation can accurately compute derivatives of arbitrary order with computational efficiency comparable to network forward propagation. This makes embedding complex differential operators into the loss function exceptionally simple.

Therefore, the core mathematical principle of PINNs can be summarized as: transforming a PDE solving problem into a nonlinear optimization problem with neural network parameters as optimization variables and the weighted sum of physical law (PDE, initial/boundary conditions) and data fitting errors as the objective.

##### 6.2.3.2 Mathematical formulation: A unified loss function framework

Now, let us formally describe a typical PDE problem and how a PINN models it.

Consider a PDE problem defined on a spatial domain Ω _⊂_ R _[d]_ and time interval [0 _, T_ ]. We seek a function _u_ ( **x** _, t_ ) that satisfies:

Governing equation (PDE):

**==> picture [366 x 48] intentionally omitted <==**

**==> picture [112 x 12] intentionally omitted <==**

Boundary condition (BC):

**==> picture [194 x 12] intentionally omitted <==**

where _B_ is a boundary operator (e.g., Dirichlet condition _B_ [ _u_ ] = _u_ , or Neumann condition _B_ [ _u_ ] = _∇u·_ **n** ).

Additionally, sometimes we have some observation data points _{_ ( **x** _[i] d[, t][i] d_[)] _[, u][i] d[}] i[N]_ =1 _[d]_[, which may come from exper-] imental measurements or incomplete numerical solutions.

The PINN method approximates the true solution _u_ ( **x** _, t_ ) using a parameterized neural network _u_ ˜( **x** _, t_ ; _**θ**_ ). Next, we construct a composite loss function to simultaneously encode all these constraints:

**==> picture [229 x 12] intentionally omitted <==**

The meanings of each term are as follows:

1. PDE residual loss _Lf_ : Measures how well the approximate solution satisfies the governing equation inside the domain. By sampling a set of “residual points” or “collocation points” _Tf_ = _{_ ( **x** _[i] f[, t][i] f_[)] _[}][N] i_ =1 _[f]_[within the] domain, compute:

**==> picture [214 x 35] intentionally omitted <==**

This is the core of the entire loss function, forcing the neural network to learn the physical laws hidden in the PDE.

2. Boundary condition loss _Lb_ : Forces the approximate solution to satisfy given conditions on the boundary. Sample a set of points _Tb_ = _{_ ( **x** _[i] b[, t][i] b_[)] _[}] i[N]_ =1 _[b]_[on the boundary, compute:]

**==> picture [202 x 34] intentionally omitted <==**

3. Initial condition loss _Li_ : Forces the approximate solution to satisfy given conditions at the initial time. Sample points _Ti_ = _{_ ( **x** _[i] i[,]_[ 0)] _[}][N] i_ =1 _[i]_[on the initial time surface, compute:]

**==> picture [172 x 33] intentionally omitted <==**

4. Data loss _Ld_ (optional): If observation data exist, used to force the approximate solution to match the data:

**==> picture [166 x 33] intentionally omitted <==**

In the formula, _λf , λb, λi, λd_ are positive weighting coefficients used to balance the magnitude and importance of different loss terms. Setting these weights is crucial for successful training—they determine the network’s priority between fitting the PDE residual, boundary conditions, initial conditions, and observation data.

Ultimately, solving the PDE is transformed into an optimization problem:

**==> picture [87 x 17] intentionally omitted <==**

By iteratively updating _**θ**_ using gradient descent or its variants (e.g., Adam), the final network _u_ ˜( **x** _, t_ ; _**θ**[∗]_ ) is the desired approximate solution.

In practice, setting the weighting coefficients _λ_ in the loss function is often an empirical challenge. The PDE residual loss _Lf_ involves high-order derivatives, and its numerical value is usually much smaller than the boundary/initial condition losses _Lb, Li_ . If all weights are simply set to 1, the optimization process may be dominated by _Lb_ and _Li_ , causing the network to quickly satisfy boundary/initial conditions while the PDE residual remains large, resulting in a trivial solution that does not satisfy physical laws.

In practice, setting the weighting coefficients _λ_ in the loss function is often an empirical challenge. The PDE residual loss _Lf_ involves high-order derivatives, and its numerical value is usually much smaller than the boundary/initial condition losses _Lb, Li_ . If all weights are simply set to 1, the optimization process may be dominated by _Lb_ and _Li_ , causing the network to quickly satisfy boundary/initial conditions while the PDE residual remains large, resulting in a trivial solution that does not satisfy physical laws. Common tuning strategies include:

- Empirical trial and error: Manually set weights based on the initial magnitude ratio of loss terms, e.g., making _λf Lf_ (0) _≈ λbLb_ (0) _≈ λiLi_ (0). This method is simple and intuitive but requires multiple attempts.

- Learning rate annealing: Dynamically adjust weights during training, e.g., adaptively adjusting based on the descent speed or current value of each loss term. A common practice is to make the weights inversely proportional to the average of the corresponding loss term, keeping the contribution of each loss to the total loss balanced.

- Gradient-based balancing: Adjust weights by monitoring the relative contribution of different loss terms to parameter updates (i.e., gradient norms), making the impact of each term on optimization roughly balanced. The basic idea is: if a loss term produces too large a gradient norm, reduce its weight; otherwise, increase it.

- Adaptive probabilistic models: Treat each loss term as the negative log-likelihood of a Gaussian distribution, with its variance (i.e., the reciprocal of the weight) as a trainable parameter, optimized simultaneously via maximum likelihood estimation. This method transforms the weight selection problem into an automatic learning process but is relatively complex to implement.

The computation of the loss function relies on discrete point sets sampled within the domain, on boundaries, and at the initial time. The distribution strategy of these points directly affects training efficiency and final solution accuracy. Commonly used sampling strategies include:

- Uniform random sampling: The simplest method, uniformly random sampling within the domain. Suitable for problems with smooth solution variations.

- Latin hypercube sampling: A stratified random sampling method that divides each dimension into equiprobable intervals and then takes one sample from each interval. This method ensures uniform distribution of points projected onto each coordinate axis and has better coverage than pure random sampling in moderate dimensions.

- Quasi-Monte Carlo sequences: Low-discrepancy sequences such as Sobol sequences, Halton sequences, etc., can generate point sets with more uniform distribution than random sampling, often accelerating convergence and providing more stable training.

- Adaptive importance sampling: Dynamically adjust the distribution of sampling points during training based on the magnitude of the current PDE residual, collecting more points in regions with large residuals. This method can allocate computational resources more effectively, focusing on difficult regions.

The number and distribution of initial sampling points are hyperparameters that need tuning. Typically, boundary and initial condition points need to be dense enough to ensure constraints are accurately imposed, while the number of internal collocation points determines the sufficiency of the network’s learning of the PDE. Empirically, the number of collocation points is usually much larger than that of boundary and initial points.

The PINN training process is shown in Figure6.3. PINN training includes training point sampling, forward propagation and automatic differentiation, loss construction, and parameter update, iteratively optimized until convergence.

**Figure 6.3:** PINN Training Process

##### 6.2.3.3. Network architecture: Why choose fully connected networks?

In early and most PINN works, the foundational architecture chosen is the Multilayer Perceptron (MLP), also known as a fully connected feedforward neural network. This choice is not accidental but is jointly determined by the mathematical properties of MLPs and the characteristics of PDE problems.

Mathematically, MLPs are supported by the Universal Approximation Theorem. This theorem states that as long as there are enough neurons in a single hidden layer, an MLP can approximate any continuous function defined on a compact set to arbitrary accuracy. For deeper networks, their expressive power is even stronger. The solutions of PDEs are typically smooth functions we expect (at least inside the domain), so MLPs theoretically have the ability to approximate them.

**Theorem 6.1 (Universal Approximation Theorem)**

_Let φ_ ( _·_ ) _be a non-constant, bounded, monotonically increasing continuous function, Id be a d- dimensional unit hypercube_ [0 _,_ 1] _[d] , and C_ ( _Id_ ) _be the set of continuous functions defined on Id. For any function f ∈ C_ ( _Id_ ) _, there exists an integer m, and sets of real numbers vi, bi ∈_ R _and real vectors_ **w** _i ∈_ R _[d] (i_ = 1 _, . . . , m), such that the function F defined by_

**==> picture [464 x 95] intentionally omitted <==**

The Universal Approximation Theorem guarantees the ability of MLPs as universal function approximators: as long as the network is wide enough, it can approximate any continuous function to arbitrary accuracy. This theoretical cornerstone provides rigorous mathematical support for the feasibility of PINNs.

From the problem structure perspective, the input of a PDE is usually spatial coordinates and time, with low dimensionality (1D, 2D, 3D plus time), and the output is the solution value, usually a scalar or low-dimensional vector. MLPs are naturally suited for handling this “coordinates-to-value” mapping relationship. Unlike convolutional neural networks (CNNs), which assume input has local spatial structure, or recurrent neural networks (RNNs), which assume input has temporal structure, MLPs make no prior assumptions about data structure, making them truly universal function approximators that can handle various geometric shapes and equation types equally.

A typical MLP used for PINNs can be expressed as:

**==> picture [291 x 53] intentionally omitted <==**

where _σ_ is a nonlinear activation function, such as tanh, sin, or ReLU. In PINNs, tanh is particularly commonly used due to its smoothness (infinitely differentiable) and boundedness (output range [ _−_ 1 _,_ 1]), because smoothness ensures stability in computing high-order derivatives via automatic differentiation, and boundedness helps stabilize training convergence.

However, MLPs are not the only choice. Depending on specific problem characteristics, researchers have also explored other architectures. Table6.2 compares several common architectures in terms of their applicable scenarios and advantages/disadvantages in PINNs.

The choice of architecture should depend on the specific problem. For most standard, low-to-mediumdimensional forward PDE problems, a sufficiently deep and wide MLP is usually a reliable and convenient starting point. When the problem has obvious structural characteristics (e.g., spatiotemporal sequences, image data on regular domains), choosing corresponding specialized architectures (RNN, CNN) may improve efficiency and solution quality. Emerging architectures like Transformer and KAN represent frontier exploration directions, suitable for complex scenarios where traditional architectures perform poorly.

##### 6.2.3.4. The triad of error sources: Approximation, optimization, and generalization

Understanding the sources of error in PINNs is crucial for evaluating their performance and reliability. Unlike traditional numerical methods, PINN error consists of three interrelated components, which we can call the “error triad”:

1. Approximation error: Even if there exists an optimal set of network parameters _**θ**[∗]_ , the neural network ˜

function space _{u_ ( _·_ ; _**θ**_ ) _}_ may not perfectly represent the true solution _u_ . This is determined by the limited expressive capacity of the network architecture (e.g., depth, width, choice of activation function). The Universal Approximation Theorem guarantees that error can be arbitrarily small with infinite width or depth, but in practice networks are finite in size, so their expressive capacity is necessarily limited. For solutions with singularities, boundary layers, or high-frequency oscillations, approximation error may be particularly significant—because these complex features require sufficient network capacity to accurately capture. Furthermore, the smoothness of the activation function also affects approximation ability: for example, ReLU networks can only represent piecewise linear functions, while tanh networks can approximate smooth functions.

2. Optimization error: The training process may fail to find the global optimum _**θ**[∗]_ , instead converging to a local optimum _**θ**_[˜] such that _L_ ( _**θ**_[˜] ) _> L_ ( _**θ**[∗]_ ). Neural network loss functions are typically non-convex, with numerous saddle points and local minima in high-dimensional parameter spaces. The choice of optimization algorithm (Adam or L-BFGS?), learning rate scheduling strategy, and network parameter initialization all significantly affect the final converged parameter point. Moreover, differences in numerical magnitude between different terms in the loss function (as mentioned earlier) can also cause optimization difficulties, causing certain constraints to be ignored. Therefore, even if the network can theoretically

**Table 6.2:** Comparison of Commonly Used Neural Network Architectures in PINNs

|**Architecture**|**Core Idea**||**Applicable Scenarios**|**Applicable Scenarios**|**Applicable Scenarios**|**Advantages**|**Disadvantages and**|
|---|---|---|---|---|---|---|---|
|**Type**|||||||**Challenges**|
|MLP|Fully<br>connected,||General,||low-|Solid<br>theoretical|Sufers from “spec-|
||universal<br>function||dimensional problems,|||guarantee<br>(Univer-|tral<br>bias”,<br>low|
||approximator||irregular geometry|||sal<br>Approximation|parameter efciency|
|||||||Theorem),<br>simple|for high-dimensional|
|||||||implementation,|problems|
|||||||naturally compatible||
|||||||with automatic dif-||
|||||||ferentiation||
|CNN|Local connectivity,||Regular grid data||(e.g.,|High<br>parameter|Complex to handle|
||weight<br>sharing,||image-like|physical||efciency,<br>efective|irregular<br>geometry,|
||translation<br>invari-||felds), problems||with|at<br>extracting<br>local|requires<br>projecting|
||ance||local correlations|||features, suitable for|input<br>onto<br>regular|
|||||||high-dimensional|grids|
|||||||spatial processing||
|RNN/LSTM|Recurrent<br>connec-||Strongly||time-|Naturally suited for|Training<br>prone<br>to|
||tions, memory|of|dependent|problems,||temporal<br>modeling,|gradient<br>vanish-|
||historical states||sequence prediction|||can<br>capture<br>long-|ing/explosion,<br>low|
|||||||term dependencies|parallelization|
|Transformer|Self-attention||Complex|geometry,||Can<br>model<br>depen-|High computational|
||mechanism, global||long-range interactions,|||dencies at arbitrary|and<br>memory<br>cost,|
||dependency model-||point cloud|data||distances, high fexi-|training<br>requires|
||ing|||||bility|large<br>amounts<br>of|
||||||||data|
|KAN|Learnable|ac-|Function|approxi-||Fewer<br>parameters,|Still in exploratory|
||tivation<br>func-||mation,|scenarios||potentially<br>better|stage,<br>theory<br>and|
||tions,<br>based|on|requiring|high|inter-|interpretability|methods<br>are<br>still|
||Kolmogorov-||pretability||||developing|
||Arnold theorem|||||||

represent the exact solution, inappropriate optimization may fail to find it.

3. Generalization/Discretization error: Even if we find a network with low loss on the training sample points, we cannot guarantee it satisfies the PDE over the entire continuous domain. This is because the loss function is computed on a finite set of points _{Tf , Tb, Ti}_ , not over the entire continuous domain. If these sampling points are distributed unreasonably—for example, insufficient sampling in regions where the solution changes rapidly, or sparse sampling near boundaries—the network may produce large errors in unsampled regions. This is similar to discretization error in traditional numerical methods, but in PINNs, the selection and distribution of sampling points are more flexible, allowing both uniform random sampling and adaptive strategies to refine in difficult regions. However, this flexibility also brings new challenges: how to design sampling strategies to ensure accuracy over the entire domain remains an open research question.

These three types of error are coupled, making the theoretical analysis of PINNs far more complex than that of traditional numerical methods. For example, a network with sufficient capacity (small approximation error) may be more difficult to optimize (large optimization error), and a network that fits training points perfectly may perform poorly at unsampled points (large generalization error). In practice, we rely more on posterior error assessment to judge solution quality: after training, evaluate the loss on an independent, dense set of test points, check the physical plausibility of the solution (e.g., symmetry, conservation laws), and compare it with known analytical solutions or high-precision numerical solutions. Furthermore, many physical systems satisfy conservation laws (e.g., mass, energy, momentum conservation). We can compute these conserved quantities corresponding to the PINN solution and check if they are physically reasonable (e.g., whether they remain constant over time in a closed system), which is an effective means of physical consistency verification.

##### 6.2.3.5. Theoretical credibility: When can we trust PINNs?

Given the above challenges, a natural question arises: Under what circumstances can we have high confidence in PINN solutions? Although a complete theory is still under development, based on existing research and experience, we can outline some guiding principles:

- Smoothness of the solution: When the PDE solution is sufficiently smooth (no singularities, discontinuities, or strong boundary layers), MLPs can approximate it more easily, the impact of spectral bias is smaller, and PINNs typically perform well. Elliptic equations (e.g., Poisson equation) under smooth domains and smooth boundary conditions are typical representatives of such problems. Conversely, for fluid problems containing shocks or singular perturbation problems with boundary layers, standard PINNs often struggle to capture these local sharp variations, requiring special treatments (e.g., adaptive sampling, domain decomposition, or shock-capturing techniques).

- Problem dimensionality: For problems with spatial dimensions not exceeding 3 (plus time), sampling and training for PINNs are relatively manageable, and satisfactory accuracy can be achieved with reasonable computational cost. For higher-dimensional problems (e.g., high-dimensional PDEs, stochastic PDEs in uncertainty quantification), standard PINNs face the “curse of dimensionality”—exponentially increasing sampling points are needed to cover the entire space as dimension increases. Special architectures (e.g., tensor decomposition networks) or sampling strategies (e.g., sparse grids, low-discrepancy sequences) are then required to address this challenge.

- Well-posedness of the problem: PINNs are most suitable for solving well-posed forward problems— i.e., where the complete equation form, all parameters, and complete boundary and initial conditions are known. For inverse problems (requiring simultaneous inference of equation parameters or boundary conditions) or data-scarce situations, although PINNs can also handle them, the risk of failure increases significantly due to increased uncertainty in the solution space. In such cases, introducing additional regularization or leveraging physical prior knowledge becomes particularly important.

- Sufficient training and validation: Decreasing training loss does not equate to high solution accuracy. It is essential to validate solution accuracy using an independent, dense set of test points, not just relying on training loss. Checking the physical plausibility of the solution (e.g., symmetry, monotonicity, conservation laws) is also an important validation means. For time-dependent problems, one can check if the solution satisfies physical properties like energy dissipation or mass conservation.

- Consistency with traditional methods: Whenever possible, compare the PINN solution with high-precision traditional numerical solutions (e.g., spectral methods or fine-grid finite element solutions). Consistency is strong evidence for building confidence. Even if a global exact solution is unavailable, comparative validation in local regions or simplified cases is a beneficial practice.

When facing problems that do not meet the above conditions (e.g., fluid problems with shocks, high-dimensional stochastic PDEs, extremely complex geometries), one must resort to more advanced PINN variants or hybrid methods, such as domain decomposition, adaptive sampling, multi-scale network structures, etc.

However, we must clearly recognize that PINNs are not intended to completely replace traditional numerical methods. In domains where traditional methods excel (e.g., linear PDEs on regular domains, large-scale industrial steady-state simulations), they still hold overwhelming advantages in accuracy, efficiency, reliability, and maturity. The emergence of PINNs is more like adding a brand new, complementary set of tools to our PDE solving toolbox. They are particularly suitable for scenarios that are difficult or cumbersome for traditional methods to handle: high-dimensional problems, complex geometry and inverse problems, and scenarios requiring flexible integration of physical models with multi-source data.

### 6.3 Applications

In the previous sections, we systematically introduced the basic framework, training techniques, and robustification methods of Physics-Informed Neural Networks. Understanding these theories and techniques is foundational, while learning how they are applied to solve real scientific computing problems is the final step in mastering the PINN approach. In this section, we will demonstrate, through a series of representative application cases, how PINNs leverage their unique advantages when facing complex partial differential equation problems across multiple scientific and engineering fields.

This section will delve into the mathematical essence behind each case, explain the design motivation and core ideas of the PINN method, and outline the application boundaries and potential of PINNs through discussions on results and limitations. We will structure each case as follows: Problem Background and Mathematical Formulation, Limitations of Traditional Methods and Motivation for PINNs, Specific Design of the PINN Model, Result Analysis and Comparison, Summary and Insights. This structure aims to clearly reveal how PINNs intervene for a specific mathematical problem (PDE) and what new possibilities they offer at the methodological level.

**Example One: Solving Poisson’s Equation with Complex Source Terms and Geometry (Forward Problem)**

- Problem Background and Mathematical Formulation

Poisson’s equation is one of the most fundamental elliptic partial differential equations in mathematical physics, describing the distribution of potential fields (such as electrostatic fields, gravitational fields, steady-state temperature fields). Its general form is:

**==> picture [124 x 14] intentionally omitted <==**

- with appropriate boundary conditions, for example, Dirichlet boundary conditions _u_ ( **x** ) = _g_ ( **x** ) _,_ **x** _∈ ∂_ Ω. Limitations of Traditional Methods and Motivation for PINNs

- Solving Poisson’s equation is a classic problem in computational science, and traditional numerical methods like the Finite Element Method are very mature. However, when the source term _f_ ( **x** ) exhibits sharp variations, singularities, or highly oscillatory characteristics, or when the computational domain Ω has a very complex geometry (such as multiply connected domains, domains with sharp re-entrant corners), traditional methods can face severe challenges. For instance, to capture the influence of a highly oscillatory source term, the FEM requires extremely fine local meshing, leading to a dramatic increase in computational cost; for complex geometries, generating high-quality meshes itself is a difficult problem, often requiring significant manual intervention.

As a mesh-free method, PINNs have the advantage of naturally handling complex geometries—simply sampling coordinate points within the domain as input, without the need for explicit mesh generation. For complex source terms, PINNs can theoretically fit them using the universal approximation capability of neural networks, without requiring pre-refinement of the mesh in regions where the source term varies rapidly.

- Specific Design of the PINN Model

- For the above problem, the PINN model is designed as follows:

   1. Network Architecture: A Multilayer Perceptron (MLP) is used, with spatial coordinates **x** as input and the scalar field _u_ ˆ( **x** ; _θ_ ) as output. Hidden layers typically use the tanh activation function to ensure smoothness.

   2. Loss Function: The loss function consists of two parts:

      - Physics Loss (PDE Residual): Sample _Nf_ “residual points” _{_ **x** _[i] f[}][N] i_ =1 _[f]_[within the computational] domain Ω, and compute:

**==> picture [197 x 35] intentionally omitted <==**

Here, _∇_[2] _u_ ˆ is computed via Automatic Differentiation (AutoDiff).

Boundary Loss: Sample _Nb_ points _{_ **x** _[i] b[}] i[N]_ =1 _[b]_[on the boundary] _[ ∂]_[Ω][, and compute:]

**==> picture [163 x 33] intentionally omitted <==**

The total loss is _L_ ( _θ_ ) = _λf Lf_ + _λbLb_ . The weights _λf , λb_ can be set manually or adjusted using an adaptive weighting strategy.

   3. Training: Minimize the total loss _L_ ( _θ_ ) via gradient descent.

- Result Analysis and Comparison

On a square domain with a highly oscillatory source term _f_ ( _x_ ) = 50 sin(20 _πx_ ) sin(20 _πy_ ), PINNs can achieve accuracy comparable to the FEM on a million-element mesh using very few sample points (typically a few thousand). More importantly, for problems with complex geometries (such as star-shaped

domains, domains with holes), PINNs can solve them directly by random sampling within the domain without mesh generation. Experiments show that when the geometric boundary is complex, the training convergence speed and final accuracy of PINNs are mainly limited by how the boundary condition loss is handled—hard constraint embedding (directly encoding the boundary condition into the network output) usually performs better than soft constraints (penalizing via a loss term).

- Summary and Insights

- This case demonstrates that PINNs exhibit unique flexibility in handling forward problems with complex geometries and complex source terms. Their mesh-free nature eliminates the time-consuming mesh generation process, while automatic differentiation simplifies the computation of high-order derivatives. However, it is important to note that for problems with singularities (such as point sources), standard PINNs may struggle to capture local sharp variations, requiring techniques like adaptive sampling or domain decomposition to improve local accuracy.

#### 6.3.1 Example two: Burgers’ equation and forward problems in fluid dynamics

- Problem Background and Mathematical Formulation

- Burgers’ equation is a nonlinear parabolic partial differential equation, a simplified model of the NavierStokes equations in fluid mechanics, used to describe the motion of one-dimensional viscous fluids, combining convection and nonlinear effects. Its form is:

**==> picture [216 x 25] intentionally omitted <==**

where _u_ ( _x, t_ ) is the fluid velocity, and _ν_ is the viscosity coefficient. Initial conditions _u_ ( _x,_ 0) = _u_ 0( _x_ ) and boundary conditions (typically Dirichlet or periodic) must be specified.

- Limitations of Traditional Methods and Motivation for PINNs

- Although Burgers’ equation has a relatively simple form, its nonlinear nature gives rise to rich physical phenomena, such as shock wave formation and propagation. When the viscosity coefficient _ν_ is small, the equation tends towards hyperbolic type, and the solution may develop steep gradients (approximate discontinuities). When solving with traditional spectral methods or finite difference methods, carefully designed schemes (such as upwind schemes, TVD schemes) are needed to capture shocks stably and avoid non-physical oscillations. Furthermore, traditional methods typically require discretization on a space-time grid, with time step sizes constrained by the CFL condition.

- Solving Burgers’ equation with PINNs essentially involves using space-time coordinates ( _x, t_ ) as input to directly learn the solution field _u_ ˆ( _x, t_ ; _θ_ ) over the entire space-time domain. Its appeal lies in:

   1. No need to solve discrete algebraic systems, avoiding the hassle of designing stable schemes;

   2. Obtaining the solution over the entire space-time in a single training run, facilitating subsequent analysis and visualization;

   3. Ease of handling parametric problems, e.g., by also taking _ν_ as input to learn how the solution varies with the viscosity coefficient.

- Specific Design of the PINN Model

The loss function is designed as follows:

**==> picture [130 x 12] intentionally omitted <==**

where:

_Lf_ : PDE residual loss, computed at sampled points in the space-time domain as _∂∂tu_ ˆ[+ ˆ] _[u][∂] ∂x[u]_[ˆ] _[−][ν][∂] ∂x_[2] _[u]_[ˆ][2] . ~~—|~~

2

- ˆ

- _Li_ : Initial condition loss, computed on the line _t_ = 0 as _|u_ ( _x,_ 0; _θ_ ) _− u_ 0( _x_ ) _|_[2] .

- ˆ

- _Lb_ : Boundary condition loss, computed on the boundaries _x_ = _−L_ and _x_ = _L_ as _|u_ ( _±L, t_ ; _θ_ ) _− g_ ( _t_ ) _|_[2] .

For problems with small viscosity (e.g., _ν_ = 0 _._ 01 _/π_ ), the solution can develop steep gradients in a short time. To capture this feature, denser sampling near the shock region or adaptive sampling strategies are typically required.

- Result Analysis and Comparison

In the standard test problem for Burgers’ equation with small viscosity (initial condition _u_ 0( _x_ ) = _−_ sin( _πx_ ), periodic boundary conditions), PINNs can accurately capture the position and shape of the shock. Compared to traditional finite difference methods (e.g., upwind schemes), PINNs do not produce overshoot or non-physical oscillations near the shock, but the trade-off is that the shock region may be somewhat “smoothed out” due to the global smoothness of the neural network. Research shows that increasing sampling point density or introducing adaptive sampling can significantly improve shock resolution.

- Summary and Insights

The Burgers’ equation case demonstrates PINNs’ capability in handling nonlinear PDEs. Notably, PINNs can stably capture shocks without special design, avoiding the complex choice of numerical schemes in traditional methods. However, for near-hyperbolic cases with extremely low viscosity, standard PINNs still face challenges—shocks may be overly smoothed, or training may fail to converge. Solving this problem typically requires combining adaptive sampling, shock detection techniques, or domain decomposition methods.

#### 6.3.2 Example three: Parameter inversion (inverse problem)

- Problem Background and Mathematical Formulation

Inverse problems are extremely common in practical engineering and scientific experiments: we obtain partial data of a system through observations (e.g., measurements at certain points) and need to infer unknown equation parameters based on this. Traditional methods for solving such problems usually involve complex optimization iterations and multiple forward solves, resulting in high computational costs. PINNs are naturally suited for handling such problems because they can seamlessly incorporate observational data as soft constraints into the loss function.

Consider a diffusion equation with an unknown parameter:

**==> picture [190 x 26] intentionally omitted <==**

with initial condition _u_ ( _x,_ 0) = _h_ ( _x_ ), boundary conditions _u_ (0 _, t_ ) = _g_ 1( _t_ ), _u_ ( _L, t_ ) = _g_ 2( _t_ ), where the diffusion coefficient _κ_ is unknown. We observe field values _u[i] d_[at][certain][points][(] _[x][i] d[, t][i] d_[)][in][the][space-] time domain, possibly with noise. The goal is to simultaneously recover the entire field _u_ ( _x, t_ ) and the parameter _κ_ from these sparse data.

- Limitations of Traditional Methods and Motivation for PINNs

- Traditional methods for handling such parameter inversion problems typically adopt a two-step iterative strategy of “forward solve first, then optimize parameters”: in each iteration, the forward problem is solved using the current parameter estimate, and then the parameters are updated based on the discrepancy between observed and computed data. This method requires multiple complete forward solves, is computationally expensive, and is highly sensitive to the accuracy and stability of the forward solver. PINNs adopt an end-to-end joint learning approach, integrating parameter inversion and forward solving within the same optimization framework. This allows us to leverage automatic differentiation to compute gradients with respect to both network parameters and physical parameters simultaneously, avoiding the loop of multiple forward solves.

- Specific Design of the PINN Model

   1. Network Architecture: Input is ( _x, t_ ), output is _u_ ˆ( _x, t_ ; _θ_ ).

   2. Parameters to Learn: Network weights _θ_ and physical parameter _κ_ . Treat _κ_ as a trainable tensor (scalar).

   3. Loss Function:

**==> picture [246 x 13] intentionally omitted <==**

The first three terms are the same as in the forward problem, with _Lf_ now involving the unknown parameter _κ_ . The newly added **data loss term** is:

**==> picture [162 x 34] intentionally omitted <==**

4. Joint Optimization: Simultaneously update _θ_ and _κ_ via gradient descent to minimize the total loss.

Result Analysis and Comparison

In standard tests, assuming we have only a few observation points in the space-time domain (e.g., _Nd_ = 20) with some noise, PINNs can simultaneously recover the complete solution field and the unknown parameter _κ_ with relatively high accuracy. Research shows that the inversion accuracy of parameter _κ_ is sensitive to the number and distribution of observation points—placing more observation points in regions where the solution changes rapidly usually yields better inversion results. Compared to traditional adjointbased methods, PINN implementation is more concise and does not require deriving adjoint equations.

- Summary and Insights

The parameter inversion case demonstrates the unique advantages of PINNs in handling inverse problems: they unify forward solving and parameter optimization within a single framework, allowing efficient gradient computation with respect to all unknowns via automatic differentiation. This end-to-end learning approach simplifies the inverse problem solving process, making it particularly suitable for situations with sparse, noisy observational data. However, caution is needed: when observational data is too sparse or the parameter space has multiple solutions, the inversion problem may be ill-posed, requiring additional regularization terms or prior knowledge to ensure solution plausibility.

#### 6.3.3 Example four: Source term inversion and data assimilation (inverse problem)

- Problem Background and Mathematical Formulation

- Another important type of inverse problem is source term inversion, where the right-hand side term _f_ ( **x** ) of the PDE or the initial condition is unknown and needs to be inferred from observational data. This has wide applications in fields such as biomedical imaging, pollution source localization, and heat source identification.

Consider the steady-state Poisson equation with an unknown source term _f_ ( **x** ):

**==> picture [247 x 13] intentionally omitted <==**

We observe solution values _u[i] d_[at some points] _[ {]_ **[x]** _[i] d[}]_[ within the domain.][The goal is to invert the source] term _f_ ( **x** ) and the full field _u_ ( **x** ) based on these data.

Limitations of Traditional Methods and Motivation for PINNs

Unlike parameter inversion, source term inversion requires inverting a function rather than a single parameter, significantly increasing the problem’s complexity. Traditional methods typically discretize the source term into a finite-dimensional parameter set (e.g., expanding it with a set of basis functions) and then perform parameter optimization. However, errors introduced by discretization can affect inversion accuracy, and the choice of basis functions itself is a challenge.

PINNs offer an elegant solution: parameterize the unknown source term also with a neural network, thus transforming the function inversion problem into a joint optimization problem of two networks. This approach avoids explicit discretization assumptions, allowing the source term to be represented in a continuous function space.

- Specific Design of the PINN Model

The joint-solving PINN architecture involves two networks:

- Solution Network: _u_ ˆ( **x** ; _θ_ ), outputs the approximate solution.

Source Term Network: _f_[ˆ] ( **x** ; _ϕ_ ), outputs the approximate source term.

The loss function must constrain both networks:

**==> picture [199 x 13] intentionally omitted <==**

where the PDE residual loss becomes:

**==> picture [212 x 35] intentionally omitted <==**

The boundary loss _Lb_ and data loss _Ld_ remain unchanged. By jointly optimizing _θ_ and _ϕ_ , both the solution field and the source term can be recovered.

- Result Analysis and Comparison

- In a 2D problem, assuming the true source term is a localized Gaussian distribution (e.g., _f_ ( _x, y_ ) = exp( _−_ ( _x−_ 0 _._ 5)[2] _−_ ( _y −_ 0 _._ 5)[2] )), and observational data consists of sparse 20 points, PINNs can accurately recover the location and shape of the source term, even if the observation points do not cover the core region of the source. Compared to traditional Tikhonov regularization methods, PINNs do not require prior assumptions about the smoothness or form of the source term, offering stronger expressive power. Summary and Insights

- The source term inversion case demonstrates PINNs’ capability in handling functional inverse problems. By introducing an additional source term network, PINNs transform the function inversion problem into a differentiable joint optimization problem, allowing efficient solution via automatic differentiation. However, it is important to note that source term inversion problems often suffer from severe non-uniqueness— different source terms may produce nearly identical solution fields. Therefore, in applications, prior knowledge (such as non-negativity or sparsity of the source term) must be incorporated to constrain the solution space, or additional observational data is needed to resolve ambiguity.

#### 6.3.4 Example five: Solving high-dimensional partial differential equations

- Problem Background and Mathematical Formulation Many important physical and financial models involve partial differential equations in high-dimensional spaces. For example, the Schrödinger equation for quantum many-body problems, the Black-Scholes equation for pricing financial derivatives (when considering multiple underlying assets), and the FokkerPlanck equation describing stochastic processes. The dimensionality _d_ of these equations can range from tens to hundreds, making them completely intractable for traditional methods. Consider a European basket option pricing problem based on _d_ underlying assets, where the pricing function _u_ ( **s** _, t_ ) satisfies the high-dimensional Black-Scholes equation:

**==> picture [252 x 35] intentionally omitted <==**

**==> picture [427 x 30] intentionally omitted <==**

- Traditional grid-based numerical methods (such as finite difference, finite element) completely fail in high dimensions because the number of required grid points grows exponentially with dimension _d_ ( _O_ ( _N[d]_ )), the so-called “curse of dimensionality.” Even probabilistic algorithms like Monte Carlo methods may face slow convergence when integrating or solving high-dimensional PDEs.

- Neural networks, particularly MLPs, have a number of parameters that grows linearly or polynomially with input dimension, not exponentially. Therefore, PINNs are seen as a promising tool to break the curse of dimensionality and solve high-dimensional PDEs. The basic form remains: take high-dimensional coordinates **x** _∈_ R _[d]_ as input, output the scalar field _u_ ( **x** ; _θ_ ), with the loss function composed of the high-dimensional PDE residual and boundary conditions.

- Specific Design of the PINN Model and Improvement Schemes

- Directly applying standard PINNs to high-dimensional problems faces significant challenges: inefficient sampling in high-dimensional space, complex loss function landscapes, and high computational cost for computing high-dimensional mixed partial derivatives. To address these, researchers have proposed various improvement schemes:

   1. Separable PINNs (SPINNs): The core idea is to approximate the high-dimensional solution function as a sum of products of lower-dimensional functions (separable structure), drastically reducing computational complexity. Specifically, assume the solution can be represented as:

**==> picture [106 x 34] intentionally omitted <==**

   - where each _ψi,k_ is a one-dimensional function represented by a sub-network. This decomposition decouples forward propagation and gradient computation from full-dimensional dot products, reducing computational complexity from _O_ ( _N[d]_ ) to _O_ ( _dNr_ ).

2. Domain Decomposition (cPINNs/XPINNs): Partition the high-dimensional computational domain into several subdomains, train an independent PINN on each subdomain, and enforce continuity conditions (as additional loss terms) on the interfaces between subdomains to ensure global solution continuity. The total loss function takes the form:

**==> picture [153 x 33] intentionally omitted <==**

   - where _L_ Γ penalizes discontinuity of the solution or flux across interfaces. Domain decomposition can break down a high-dimensional problem into multiple lower-dimensional sub-problems, reducing training difficulty.

3. Adaptive Sampling and Feature Mapping: Use residual-based adaptive sampling in high-dimensional space to concentrate computational resources in regions with large residuals. Simultaneously, using mappings like random Fourier features to project inputs into a higher-dimensional feature space can alleviate the “spectral bias” problem of neural networks, improving learning capability for highfrequency components.

- Result Analysis and Comparison

- For an option pricing problem with _d_ = 50, standard PINNs can achieve results within 1% relative error compared to Monte Carlo reference solutions within reasonable training time (a few hours). Traditional grid-based methods are completely infeasible at such high dimensions. SPINNs further reduce training time by an order of magnitude while maintaining comparable accuracy.

- Summary and Insights

- The high-dimensional case demonstrates the great potential of PINNs in breaking the curse of dimensionality. However, we must also be soberly aware that when dimensionality exceeds several hundred, even PINNs face severe challenges in sampling efficiency and training stability. Currently, successful cases of high-dimensional PINNs are mainly concentrated on problems with special structures (e.g., separable, low-rank). For general high-dimensional PDEs, deeper theoretical and methodological innovations are still needed. Many important physical and financial models involve partial differential equations in high-dimensional spaces. For example, the Schrödinger equation for quantum many-body problems, the Black-Scholes equation for pricing financial derivatives (when considering multiple underlying assets), and the Fokker-Planck equation describing stochastic processes. The dimensionality _d_ of these equations can range from tens to hundreds.

#### 6.3.5 Example six: Complex multiphysics coupling problems

- Problem Background and Mathematical Formulation

- Many cutting-edge scientific and engineering problems involve the interaction of multiple physical fields, such as Fluid-Structure Interaction (FSI), thermal-fluid-solid coupling, etc. The governing equations for these problems are typically a set of coupled nonlinear PDEs, making their solution extremely challenging. Consider a simplified 2D fluid-structure interaction problem as an example:

   - Fluid Domain Ω _f_ : The motion of an incompressible fluid is described by the Navier-Stokes equations:

**==> picture [206 x 23] intentionally omitted <==**

- Solid Domain Ω _s_ : The deformation of an elastic body is described by the linear elastodynamic equations:

**==> picture [108 x 26] intentionally omitted <==**

   - Interface Conditions: On the fluid-solid interface Γ, the following must be satisfied:

      - Kinematic Condition (velocity continuity): **u** = ~~—_~~ _[∂] ∂t_ **[d]**

      - Dynamic Condition (stress continuity): _**σ** f ·_ **n** = _**σ** s ·_ **n**

- Limitations of Traditional Methods and Motivation for PINNs

- Traditional partitioned iterative solvers require repeatedly exchanging data between the fluid solver and solid solver at each time step until convergence. This decoupled strategy is not only computationally expensive but also suffers from numerical stability issues (e.g., “added mass” instability). Furthermore, for complex geometries and deformations, mesh updating and regeneration pose significant challenges. PINNs offer the possibility of a monolithic solution. One can construct a unified neural network whose input is space-time coordinates ( **x** _, t_ ) along with a domain identifier, and whose output includes all relevant physical fields (e.g., fluid velocity **u** , pressure _p_ , solid displacement **d** ). The loss function then encom- passes PDE residuals in all domains, boundary conditions for each domain, and coupling conditions on the interface. This “monolithic solving” approach avoids the uncertainty and stability issues associated with partitioned iteration.

Specific Design of the PINN Model

1. Network Architecture: A multi-head output network with a shared backbone, input is ( **x** _, t_ ), outputs are fluid velocity **u** , pressure _p_ , and solid displacement **d** . Different regions can be distinguished via a domain identifier or directly within the loss function.

2. Loss Function:

**==> picture [246 x 12] intentionally omitted <==**

where the coupling condition loss is:

**==> picture [220 x 36] intentionally omitted <==**

3. Training Strategy: All field quantities and their derivatives can be obtained via automatic differentiation of the network outputs.

Multi-physics coupling problems pose significant challenges for PINN training, with the core issue being loss term scale imbalance. Fluid and solid equations differ greatly in dimensions, numerical scales, and physical characteristics, leading to gradients of vastly different magnitudes for the various terms in the loss function. Training may be dominated by one physical field while neglecting others. Coping strategies include:

   - Adaptive Loss Weighting: Methods based on Neural Tangent Kernel (NTK) analysis, for example, automatically adjust loss weights by analyzing the convergence rate differences of different loss terms during early PINN training, balancing the training progress across physical fields.

   - Phased Training: First independently train sub-problems satisfying some strong constraints (e.g., steady flow field or static solid deformation), then use the pre-trained models as initialization for joint fine-tuning with coupling conditions added.

   - Non-dimensionalization: Non-dimensionalize all physical quantities so that the numerical scales of different physical fields are similar, fundamentally alleviating scale imbalance.

- Result Analysis and Comparison

In the classic 1D piston fluid-structure interaction problem, PINNs can accurately capture the coupled evolution of fluid pressure and solid displacement, matching well with analytical or high-precision numerical solutions. For 2D problems, PINNs satisfy stress continuity at the coupling interface reasonably well, but training time increases significantly and sensitivity to hyperparameters (such as network depth, loss weights) becomes more pronounced.

- Summary and Insights

- The multi-physics coupling case demonstrates PINNs’ capability in holistic modeling of complex systems. Through a unified network and loss function, PINNs can simultaneously learn multiple interacting physical fields, avoiding the complexity and stability issues of traditional partitioned iteration. However, the training difficulty for multi-physics problems increases significantly, requiring careful design of network architecture, loss weights, and training strategies. Currently, the application of PINNs to complex multi-physics problems is still in the exploratory stage. For complex problems with strong coupling, large deformations, or turbulent features, reliable results still require combining physical constraints and numerical techniques.

This section, through a series of application cases ranging from simple to complex, demonstrates how PhysicsInformed Neural Networks have evolved from a novel mathematical idea into a powerful tool for solving practical scientific computing problems. Each case revolves around a core mathematical problem, explaining how the PINN design responds to the specific needs and challenges of these problems.

We see that the charm of PINNs lies in their simplicity and flexibility: they transform complex PDE solving problems into neural network optimization problems, encoding all physical knowledge, boundary conditions, and observational data through the design of the loss function. This paradigm allows researchers to explore diverse problems—forward, inverse, high-dimensional, multi-physics—using a relatively unified code framework.

However, we must also soberly recognize that PINNs are not a “universal key.” Their limitations in handling discontinuities and ultra-high-dimensional problems, as well as the black-box nature of their training process and sensitivity to hyperparameters, are all active research areas. The successful application of PINNs often relies on a deep understanding of the physical essence of the problem and proficient mastery of neural network training techniques. They are more like a “specialist” that needs to complement traditional numerical methods and can work wonders in specific scenarios, rather than an all-around “replacement.” When applying PINNs to any serious scientific or engineering research, cross-validation is crucial. This includes:

1. Comparison with traditional high-precision numerical solutions (where feasible).

2. Mesh convergence analysis: Increase the density of residual points and observe if the solution converges.

3. Physical plausibility checks: Verify that the solution satisfies basic physical intuition or secondary conservation laws.

### References

- [1] Simon Arridge et al. “Solving inverse problems using data-driven models”. In: _Acta Numerica_ 28 (2019), pp. 1–174.

- [2] Peter Benner et al. _Model reduction and approximation_ . SIAM, 2017.

- [3] Steven L Brunton and J Nathan Kutz. “Promising directions of machine learning for partial differential equations”. In: _Nature Computational Science_ 4.7 (2024), pp. 483–494.

- [4] Claudio Canuto et al. _Spectral methods: Fundamentals in single domains_ . Springer, 2006.

- [5] Junwoo Cho et al. “Separable physics-informed neural networks”. In: _Advances in Neural Information Processing Systems_ . Vol. 36. 2023.

- [6] Jean Donea and Antonio Huerta. _Finite element methods for flow problems_ . John Wiley & Sons, 2003.

- [7] Lawrence C Evans. _Partial differential equations_ . American Mathematical Society, 2010.

- [8] Joel H Ferziger and Milovan Perić. _Computational methods for fluid dynamics_ . Springer, 2012.

- [9] Jacob Fish and Ted Belytschko. _A first course in finite elements_ . John Wiley & Sons, 2007.

- [10] Jochen Garcke and Michael Griebel. _Sparse grids and applications_ . Springer, 2012.

- [11] Jian Guan et al. “DaPINN: Dimension-augmented physics-informed neural networks”. In: _arXiv preprint_ (2023).

- [12] Ehsan Haghighat et al. “A physics-informed deep learning framework for inversion and surrogate modeling in solid mechanics”. In: _Computer Methods in Applied Mechanics and Engineering_ 379 (2021), p. 113741.

- [13] Ameya D Jagtap and George Em Karniadakis. “Extended physics-informed neural networks (XPINNs): A generalized space-time domain decomposition based deep learning framework for nonlinear partial differential equations”. In: _Communications in Computational Physics_ 28.5 (2020), pp. 2002–2041.

- [14] Ameya D Jagtap, Ehsan Kharazmi, and George Em Karniadakis. “Conservative physics-informed neural networks on discrete domains for conservation laws: Applications to forward and inverse problems”. In: _Computer Methods in Applied Mechanics and Engineering_ 365 (2020), p. 113028.

- [15] George Em Karniadakis et al. “Physics-informed machine learning”. In: _Nature Reviews Physics_ 3.6 (2021), pp. 422–440.

- [16] Aditi Krishnapriyan et al. “Characterizing possible failure modes in physics-informed neural networks”. In: _Advances in Neural Information Processing Systems_ . Vol. 34. 2021, pp. 26548–26560.

- [17] Randall J LeVeque. _Finite difference methods for ordinary and partial differential equations_ . SIAM, 2007.

- [18] Randall J LeVeque. _Finite volume methods for hyperbolic problems_ . Cambridge University Press, 2002.

- [19] S Liao et al. “Physics-informed neural networks for PDE problems: A comprehensive review”. In: _arXiv preprint_ (2025).

- [20] J David Logan. _Applied partial differential equations_ . Springer, 2015.

- [21] Lu Lu et al. “DeepXDE: A deep learning library for solving differential equations”. In: _SIAM Review_ 63.1 (2021), pp. 208–228.

- [22] Lu Lu et al. “Learning nonlinear operators via DeepONet based on the universal approximation theorem of operators”. In: _Nature Machine Intelligence_ 3.3 (2021), pp. 218–229.

- [23] K W Morton and D F Mayers. _Numerical solution of partial differential equations_ . Cambridge University Press, 2005.

- [24] Nasim Rahaman et al. “On the spectral bias of neural networks”. In: _International Conference on Machine Learning_ . PMLR. 2019, pp. 5301–5310.

- [25] Maziar Raissi, Paris Perdikaris, and George Em Karniadakis. “Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations”. In: _Journal of Computational Physics_ 378 (2019), pp. 686–707.

- [26] Justin Sirignano and Konstantinos Spiliopoulos. “DGM: A deep learning algorithm for solving partial differential equations”. In: _Journal of Computational Physics_ 375 (2018), pp. 1339–1364.

- [27] Matthew Tancik et al. “Fourier features let networks learn high frequency functions in low dimensional domains”. In: _Advances in Neural Information Processing Systems_ . Vol. 33. 2020, pp. 7537–7547.

- [28] Lloyd N Trefethen. _Spectral methods in MATLAB_ . SIAM, 2000.

- [29] Rui Wang et al. “Physics-informed neural networks for fluid-structure interaction”. In: _arXiv preprint_ (2023).

- [30] Sifan Wang, Yujun Teng, and Paris Perdikaris. “On the eigenvector bias of Fourier feature networks: From regression to solving multi-scale PDEs with physics-informed neural networks”. In: _Computer Methods in Applied Mechanics and Engineering_ 393 (2022), p. 114823.

6.3 Applications

- [31] Sifan Wang, Yujun Teng, and Paris Perdikaris. “Understanding and mitigating gradient flow pathologies in physics-informed neural networks”. In: _SIAM Journal on Scientific Computing_ 43.5 (2021), A3055– A3081.

- [32] Olek C Zienkiewicz, Robert L Taylor, and Jian Z Zhu. _The finite element method: Its basis and fundamentals_ . Elsevier, 2013.
