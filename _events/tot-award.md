---
layout: default
title: TOT AWARD
permalink: events/tot-award
---

# CONCUR Test of Time Award

The award is jointly organized by CONCUR and the IFIP WG 1.8. Its purpose is to recognize important achievements in Concurrency Theory that were published at the CONCUR conference and have stood the test of time.

The Test of Time award takes place biennially. Eligible papers for the award are those published in CONCUR within 17 and 20 years before the awarding edition. This frequency will be only reached by 2024 while the transitional period has a higher frequency to get up to date with older periods.

The award can recognize up to two of the eligible papers. The awardees are selected by a jury consisting of three members. The jury is renewed every year. Two of the members are appointed by the CONCUR Steering Committee. The third member is appointed by the president of the IFIP 1.8 Group on Concurrency Theory.

Each Test of Time award is announced in the corresponding CONCUR event by the jury or, in their absence, by the PC chair.

Past editions:

* [2024](#concur-test-of-time-award-2024)
* [2023](#concur-test-of-time-award-2023)
* [2022](#concur-test-of-time-award-2022)
* [2021](#concur-test-of-time-award-2021)
* [2020](#concur-test-of-time-award-2020)

## [CONCUR Test of Time Award 2024](https://confest2024.github.io/CONCUR_awards.html)

The award winners have been selected by a Jury composed of Frits Vaandrager (chair), Christel Baier, and Luis Caires. In 2023, one paper was chosen to receive the CONCUR Test of Time Award for the period 2004–2007.

### Period 2004–2007

**Stephen D. Brookes. A semantics for concurrent separation logic** (in [CONCUR 2004](https://doi.org/10.1007/978-3-540-28644-8_2))

**Peter W. O’Hearn. Resources, concurrency and local reasoning** (in [CONCUR 2004](https://doi.org/10.1007/978-3-540-28644-8_4))

At the turn of the millennium, the quest for Hoare-style logics for imperative programs with pointers and aliasing was considered to be one of the most difficult challenges for program verification. The proposals available by then were often too complex to handle even simple examples, much less the kind of software routinely found in industrial code bases. This state of affairs changed when Reynolds, O’Hearn, Istiaq and Yang invented Separation Logic (SL). In his LICS 2002 paper, Reynolds cites unpublished preliminary work by O’Hearn aiming to extend SL to shared state concurrent programs. The key idea was that “as program variables are syntactically partitioned into groups owned by different processes and resources, so the heap should be similarly partitioned by separating conjunctions in the proof of the program”. He also adds: “Unfortunately, at this writing, there is no proof that O’Hearn’s inference rules are sound”.

These difficulties were elegantly overcome by the two invited Concur 2004 papers introducing Concurrent Separation Logic (CSL), authored respectively by O’Hearn and Brookes. In his Concur 2004 paper “Resources, Concurrency, and Local Reasoning”, O’Hearn eloquently expounds how the underlying principles of separation logic would naturally embrace the world of concurrent programs with shared state and basic synchronization primitives. While introducing CSL and its proof rules, O’Hearn presents remarkably simple proofs for numerous challenging examples, highlighting the practicality of the logic’s abstractions. Moreover, he motivates and details a general method for designing CSL proofs based on the intuitive concepts of separation, resource ownership, and resource ownership transfer.

The soundness of CSL was at the time solved after a key suggestion of Brookes, by requiring shared resource invariants to be “precise”, that is, expressed by assertions that uniquely identify a well-delimited part of the heap. In his Concur 2004 paper, “A Semantics for Concurrent Separation Logic”, Brookes develops a novel action-trace semantics for the basic concurrent programming language of CSL, which permits the first proof of soundness for CSL. Brookes’ semantics was also the first race-sensitive denotational model for concurrent programs, a construction of independent interest, and essential to proving the famous “no races” theorem for CSL. This collection of contributions was crucial to establish CSL as the most prominent approach for reasoning about concurrent shared state programs until today.

The Concur 2004 papers by O’Hearn and Brookes frequently refer to each other, and are delightful to read as a whole; it is very fortunate that they appeared in the same edition of Concur. Since then, CSL has been a constant source of inspiration for the scientific community, motivating many theoretical and practical developments important to tackle increasingly sophisticated real-world concurrent shared state programming scenarios including higher-order languages, storable locks, expressive permissions mechanisms, fine-grained concurrency, weak memory concurrency, verification of type systems (e.g., Rust), linearizability, program refinement, crash safety, non-interference, and incorrectness logic. CSL has been adapted as part of mature research tools such as Verifast, Viper, Iris, VST, and F*, and it has been used in an industrial setting for among others the verification of concurrent data structures and micro-kernels/hypervisors.

[Interview with the authors]() (Not yet available)

## [CONCUR Test of Time Award 2023](https://www.uantwerpen.be/en/conferences/confest-2023/concur/awards/)

The award winners have been selected by a Jury composed of Marta Kwiatkowska (chair), Bengt Jonsson, and Igor Walukiewicz. In 2023, one paper was chosen to receive the CONCUR Test of Time Award for the period 2002–2005.

### Period 2002–2005

**Vincent Danos, Jean Krivine. Reversible Communicating Systems** (in [CONCUR 2004](https://doi.org/10.1007/978-3-540-28644-8_19))

This paper represents the first exploration of the reversibility of concurrent computation within process algebra. The notion of reversible computation expands the conventional forward computation by incorporating the ability to roll back a computation. The roots of this concept can be traced back to the 1970s, where it was studied by Landauer and Bennett in the context of thermodynamics and Turing machines. They established that any deterministic computation could be simulated by a logically reversible Turing machine.The challenge in applying reversibility to concurrent systems arises from the fact that actions are not linearly organized by execution time but are partially ordered by a causal relationship. The authors put forward the fundamental notion of causally-consistent reversibility capturing the concept that an action can only be undone if all its subsequent effects have been reversed. The introduced notion has direct applicability to reversibility in distributed settings.This paper has since served as a source of inspiration, either directly or indirectly, for numerous studies on reversible concurrent systems modelled through (higher-order) process algebras, Petri nets, event structures, as well as reversible logic circuits made of DNA. The principle of reversibility has a wide range of applications in distributed systems, including debugging, rollback, and error recovery. These applications will undoubtedly continue to benefit from the pioneering and elegant formalization introduced by Danos and Krivine.

[Interview with the authors](https://www.uantwerpen.be/en/conferences/confest-2023/concur/awards/) by Marta Kwiatkowska.

## [CONCUR Test of Time Award 2022](https://concur2022.mimuw.edu.pl/tot-award/)

The award winners have been selected by a Jury composed of Ilaria Castellani (chair), Paul Gastin, Orna Kupferman, Mickael Randour, and Davide Sangiorgi. In 2022, four papers were chosen to receive the CONCUR Test of Time Award for the periods 1998–2001 and 2000–2003.

### Period 2000–2003

**James J. Leifer, Robin Milner. Deriving Bisimulation Congruences for Reactive Systems** (in [CONCUR 2000](https://doi.org/10.1007/3-540-44618-4_19))

The paper presents a uniform approach for deriving a Labelled Transition System (LTS) semantics from a reduction semantics, in such a way that the resulting bisimilarity is a congruence. LTS semantics, inspired by automata theory, specifies the interactive behaviour of systems, while reduction semantics specifies their internal evolution and is closer to the operational semantics of sequential programs. LTS semantics has been favoured in early work on process calculi, as it lends itself to the definition of a variety of behavioural equivalences that are easy to work with. Subsequently, a wealth of process calculi have been proposed, tailored to specific features (mobility, locations, security, sessions, etc). In these more complex calculi, it became more debatable what to adopt as labels or “observables” for the LTS semantics, and this motivated the shift towards a reduction semantics in conjunction with a structural congruence, allowing for a compact semantic description.

The thrust to retrieve an LTS semantics from a reduction semantics is an important one, and this paper is a milestone in this line of work. The solution proposed is robust, i.e., broadly applicable. It is also mathematically elegant, formulated using the categorical notion of relative pushout (RPO). The paper has spurred a whole trend of research on congruence properties for bisimilarity in which RPOs constitute the key notion. Good examples are applications to bigraphs, graph rewriting and name calculi.

[Interview with James Leifer](https://processalgebra.blogspot.com/2022/07/davide-sangiorgis-interview-with-james.html) by Davide Sangiorgi.

**Luca de Alfaro, Marco Faella, Thomas A. Henzinger, Rupak Majumdar, Mariëlle Stoelinga. The Element of Surprise in Timed Games** (in [CONCUR 2003](https://doi.org/10.1007/978-3-540-45187-7_9))

The paper studies concurrent two-player games played on timed game structures, and in particular the ones arising from playing on timed automata. A key contribution of the paper is the definition of an elegant timed game model, allowing both the representation of moves that can take the opponent by surprise as they are played "faster", and the definition of natural concepts of winning conditions for the two players -- ensuring that players can win only by playing according to a physically meaningful strategy. This approach provides a clean answer to the problem of time convergence, and the responsibility of the players in it. For this reason, it has since been the basis of numerous works on timed games. The algorithm established in the paper to study omega-regular conditions in this neat model of timed games is also enticing, resorting to mu-calculus on a cleverly enriched structure.

[Interview with  Luca de Alfaro, Marco Faella, Thomas A. Henzinger, Rupak Majumdar and Mariëlle Stoelinga](https://processalgebra.blogspot.com/2022/06/interview-with-luca-de-alfaro-marco.html) by Mickael Randour and Luca Aceto.

### Period 1998–2001

**Christel Baier, Joost-Pieter Katoen, Holger Hermanns. Approximate symbolic model checking of continuous-time Markov chains** (in [CONCUR 1999](https://doi.org/10.1007/3-540-48320-9_12))

The paper presented the first symbolic model-checking algorithm for systems that combine probabilistic and real-time behaviors. Specifically, the model-checking algorithm handles real-time probabilistic systems, modeled by continuous-time Markov chains systems, and specifications in CSL -- a branching and continuous-time stochastic logic. This setting significantly extends the scope of systems to which automatic model-checking can be applied. Beyond the new model-checking algorithm, the paper introduces several ideas which have been extensively used since their introduction in the paper. This includes a reduction from a quantitative model-checking problem to the problem of solving a system of equations, as well as a generalization of BDDs, to MTDDs (multi-terminal decision diagrams), which allow both Boolean and real-valued variables, and which enables symbolic reasoning.

[Interview with Christel Baier, Holger Hermanns and Joost-Pieter Katoen](https://processalgebra.blogspot.com/2022/05/orna-kupfermans-interview-with-christel.html) by Orna Kupferman.

**Franck Cassez, Kim Larsen. The Impressive Power of Stopwatches** (in [CONCUR 1999](https://doi.org/10.1007/3-540-44618-4_12))

The paper studies the expressive power of timed automata enriched with stopwatches and unobservable behaviours. Surprisingly, it is proved with smart constructions that this seemingly mild extension already reaches the full expressive power of linear hybrid automata, a very powerful model using a finite discrete control together with continuous variables, linear guards and linear updates. An important consequence is the reduction of the reachability analysis of linear hybrid automata to that of stopwatch automata. Even though both problems are undecidable, approximate reachability for stopwatch automata is easier to develop and implement. Stopwatch automata find another very important application in the field of scheduling problems for timed pre-emptive systems.

[Interview with Kim G. Larsen](https://processalgebra.blogspot.com/2022/08/interview-with-kim-g-larsen-concur-2022.html) by Luca Aceto.


## [CONCUR Test of Time Award 2021](https://qonfest2021.lacl.fr/test-of-time.php)

The award winners have been selected by a Jury composed of Rob van Glabbeek (chair), Luca de Alfaro, Nathalie Bertrand, Catuscia Palamidessi, and Nobuko Yoshida. In 2021, four papers were chosen to receive the CONCUR Test of Time Award for the periods 1994–1997 and 1996–1999.

### Period 1996–1999

**Ahmed Bouajjani, Javier Esparza, and Oded Maler. Reachability Analysis of Pushdown Automata: Application to Model-checking** (in [CONCUR 1997](https://doi.org/10.1007/3-540-63141-0_10))

Citation: This is a breakthrough paper that opened the way for the analysis of pushdown automata via model-checking techniques. The paper proposes a general class of alternating pushdown systems and defines new model checking algorithms for these systems against both linear and branching-time properties. The basic idea is simple, yet extremely elegant: using (regular) automata as representations for sets of states of pushdown automata. The paper proceeds to show that the representation is closed with respect to Boolean operators, makes membership of states decidable, and crucially, makes the predecessor operator easily computable. The approach proposed in this paper is so neat and natural that it has become a standard reference in the field of verification of infinite-state systems.

[Interview with Ahmed Bouajjani and Javier Esparza](https://processalgebra.blogspot.com/2021/08/interview-with-concur-2021-tot-award_23.html) by Nathalie Bertrand.

**Rajeev Alur, Thomas A. Henzinger, Orna Kupferman, and Moshe Y. Vardi. Alternating Refinement Relations** (in [CONCUR 1998](https://doi.org/10.1007/BFb0055622))

Citation: This paper introduces refinement relations, based on simulation and trace containment, for games, modeled as alternating transition systems. Refinement relations had been a foundational notion in formal methods, and much more broadly, in the theory of computation. In the years leading up to this paper, it had become evident that games provided the natural model for open systems, which communicate and are reactive to their environment; this paper extends the notion of simulation and trace containment to games. While conceived in a formal-methods and verification setting, the paper turned out to have broad implications, as these game refinement relations have implications for strategies in general games, and are closely related to notions of subtyping in game theory and in dynamic typing. The extension of refinement relations to games was thus a fundamental tassel in the understanding of dynamic systems, finally being put into place.

[Interview with Rajeev Alur, Thomas A. Henzinger, Orna Kupferman and Moshe Y. Vardi](https://processalgebra.blogspot.com/2021/06/interview-with-concur-2021-tot-award.html) by Luca Aceto.

### Period 1994–1997

**David Janin and Igor Walukiewicz. On the Expressive Completeness of the Propositional mu-Calculus with spect to Monadic Second Order Logic** (in [CONCUR 1996](https://doi.org/10.1007/3-540-61604-7_60))

Citation: This seminal paper relates the expressive power of monadic second-order logic and the mu-calculus, showing that the bisimulation-closed formulas monadic second-order logic are equivalent to the mu-calculus. This is a very deep and insightful result, providing a contribution of undational nature to the field of logic and computation. The paper's insight was one of the central factors contributing to the role of the mu-calculus in model checking, where it provides the computational counterpart to gics for expressing system properties. The relation between logics and the mu-calculus, which can in great part be traced to this paper, has been an extremely fruitful one, with implications in algorithms for the verification and analysis of transition systems, probabilistic systems, timed systems, games, and more.

[Interview with David Janin and Igor Walukiewicz](https://processalgebra.blogspot.com/2021/08/nterview-with-concur-2021-tot-award.html) by Luca Aceto.

**Uwe Nestmann and Benjamin C. Pierce. Decoding Choice Encodings** (in [CONCUR 1996](https://doi.org/10.1007/3-540-61604-7_55))

Citation: This paper makes major strides in the study of the expressiveness of process calculi. It shows that, in a completely distributed and asynchronous setting, input-guarded choice can be simulated by parallel composition. More precisely, the paper constructs a fully distributed and divergence-free encoding from the input-choice pi-calculus into the asynchronous pi-calculus. The correctness of this encoding is demonstrated by establishing a semantic equivalence between a process and its encoding, thereby satisfying and strengthening the common quality criterion of full abstraction. As semantic equivalence it employs the asynchronous version of coupled simulation, and illuminates the surprising versatility of this notion by showing how it avoids the introduction of divergence in the encoding. This work formalizes ideas stemming from the programming language Pict, and has been very influential in the area of expressiveness in concurrency.

[Interview with Uwe Nestmann and Benjamin Pierce](http://mrg.doc.ic.ac.uk/concur-tot/) by Nobuko Yoshida.


## [CONCUR Test of Time Award 2020](https://concur2020.forsyte.at/test-of-time.html)

The award winners have been selected by a Jury composed of Luca Aceto (Chair), Jos Baeten, Patricia Bouyer-Decitre, Holger Hermanns, and Alexandra Silva. In 2020, four papers were chosen to receive the CONCUR Test of Time Award for the periods 1990–1993 and 1992–1995.

### Period 1992-1995

**Roberto Segala and Nancy Lynch. Probabilistic simulations for probabilistic processes** (in [CONCUR 1994](https://doi.org/10.1007/978-3-540-48654-1_35))

The paper “Probabilistic simulations for probabilistic processes”, published by Roberto Segala and Nancy Lynch at CONCUR 1994, receives one award for introducing the ‘simple’ probabilistic automata model. Unlike earlier attempts to embrace probabilities, transition targets here are probability distributions over states, and this makes it possible to lift core process algebraic results in a very elegant manner. Probabilistic automata have quickly been recognised as the pivotal link between classical concurrency theory and the theory of discrete-state Markov processes. They have become the central subjects of probabilistic model checking, and are echoed in a range of very influential modelling formalisms including probabilistic timed automata, probabilistic hybrid automata, and Markov automata.

[Interview with Roberto Segala and Nancy Lynch](https://processalgebra.blogspot.com/2020/04/an-interview-with-nancy-lynch-and.html) by Luca Aceto.

**Davide Sangiorgi. A Theory of Bisimulation for the pi-Calculus** (in [CONCUR 1993](https://doi.org/10.1007/3-540-57208-2_10))

The paper “A Theory of Bisimulation for the pi-Calculus”, published by Davide Sangiorgi in CONCUR 1993, receives one award for introducing the notion of open bisimilarity, which, unlike early and late bisimilarity, is a congruence for the pi-calculus. Open bisimilarity makes it possible to view most names as uninstantiated variables, and this allows for the development of efficient tools based on a kind of symbolic state-space exploration. Open bisimilarity and tools based on it have, for instance, played an important role in research on cryptographic protocols modelled using extensions of the pi-calculus. For a recent example, Horne has used open bisimilarity as the appropriate way to model the capabilities of an attacker trying to get confidential information, with a real-world application to finding and fixing a privacy flaw in e-passports presented by Filimonov et al. at ESORICS 2019.

[Interview with Davide Sangiorgi](https://processalgebra.blogspot.com/2020/04/an-interview-with-davide-sangiorgi.html) by Luca Aceto.

### Period 1990-1993

**Rob van Glabbeek. The Linear Time-Branching Time Spectrum** (in [CONCUR 1990](https://doi.org/10.1007/BFb0039066) and in [CONCUR 1993](https://doi.org/10.1007/3-540-57208-2_6))

The companion papers on “The Linear Time-Branching Time Spectrum”, published by Rob van Glabbeek at CONCUR 1990 and 1993, jointly receive one award for offering a highly influential taxonomy of the menagerie of process semantics, both in a setting where every system action is observable and in the presence of silent moves. Each of the plethora of studied semantics comes equipped with a variety of elegant characterisations in terms of modal logics, testing scenarios, relations, and complete axiomatisations. The encyclopedic nature of the above-mentioned papers has made them a must read for researchers in concurrency theory for nearly 30 years.

[Interview with Rob van Glabbeek](https://processalgebra.blogspot.com/2020/04/an-interview-with-rob-van-glabbeek.html) by Luca Aceto.

**Søren Christensen, Hans Hüttel and Colin Stirling. Bisimulation Equivalence is Decidable for all Context-Free Processes** (in [CONCUR 1992](https://doi.org/10.1007/BFb0084788))

The paper “Bisimulation Equivalence is Decidable for all Context-Free Processes”, published by Søren Christensen, Hans Hüttel and Colin Stirling at CONCUR 1992, receives one award for extending and simplifying the seminal result by Baeten, Bergstra and Klop, who proved the decidability of bisimilarity over normed context-free processes. The CONCUR’92 paper has paved the way to further decidability and complexity results for a variety of classes of infinite-state processes. This includes the 2-EXPTIME algorithm for bisimilarity over BPA presented by Burkart, Caucal and Steffen in a paper published at MFCS 1995, and the work by Senizergues in papers at FOCS 1998 and in the SIAM Journal on Computing in 2005, presenting decidability results for all “equational graphs” with finite out-degree.

[Interview with Hans Hüttel](https://processalgebra.blogspot.com/2020/06/an-interview-with-hans-huttel-concur.html) by Luca Aceto.
