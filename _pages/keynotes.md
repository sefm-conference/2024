---
layout: page_plain
title: Keynotes
permalink: /keynotes/
order: 3
published: true
---

## [Luís Soares Barbosa](https://www.di.uminho.pt/~lsb/), INESC TEC and University of Minho, PT

<img src="{{ site.baseurl }}{% link assets/images/people/barbosa.png %}" class="imageSpeaker" align="right"/>

<!-- <p style="min-height: 170px;">


<br/>

</p>

-->

**Paraconsistency for the working software engineer** 

Modelling complex information systems often entails the need for dealing with scenarios of inconsistency in which several requirements either reinforce or contradict each other. This lecture summarises recent joint work with Juliana Cunha, Alexandre Madeira and Ana Cruz on  a variant of transition systems endowed with positive and negative accessibility relations, and a metric space over the lattice of truth values. Such structures are called *paraconsistent* transition systems, the qualifier stressing a connection to paraconsistent logic, a logic taking inconsistent information as potentially informative.  A coalgebraic perspective on this family of structures is also discussed.




## [Paula Herber](https://www.uni-muenster.de/EmbSys/team/herber/), Universitat Munster, DE

<img src="{{ site.baseurl }}{% link assets/images/people/herber.png %}" class="imageSpeaker" align="right"/>

<!-- <p style="min-height: 170px;">
	TBD
</p>
 -->

**Formal Verification of Cyber-physical Systems using Domain-specific Abstractions**

Cyber-physical systems have become ubiquitous in our daily lives, and their complexity continually evolves to unprecedented levels. In addition to their heterogeneity and interaction with a physical environment, we see a tremendous increase in the use of learning to make autonomous decisions in dynamic environments. These developments pose significant challenges for ensuring the safety and reliability of cyber-physical systems. Formal methods have the potential to guarantee crucial safety properties under all circumstances, but are incredibly expensive and severely suffer from scalability issues. In this talk, I will summarize some of our recent efforts towards reusable specification and more scalable verification of cyber-physical systems using domain-specific abstractions. 

<!--
Bio: Paula Herber is a full professor and head of the Embedded Systems group at the Computer Science Department at the University of Münster, Germany, and a part-time full professor at the University of Twente in the Formal Methods and Tools (FMT) group in the Netherlands. She has received her Ph.D. from TU Berlin in 2010, and worked as a postdoc at the International Computer Science Institute (ICSI) in Berkeley, California, as a substitute professor at the University of Potsdam, and as a postdoc and independent research group leader at TU Berlin. Her main research interests are quality assurance for embedded systems, test automation, and formal methods. She is best known for her contributions to the formalization of industrially used system design languages such as SystemC and Simulink, and highly interested in new techniques to increase the applicability of formal methods for embedded and cyber-physical systems.
-->


## [John van de Wetering](https://vdwetering.name), University of Amsterdam, the Netherlands

<img src="{{ site.baseurl }}{% link assets/images/people/vandewetering.jpg %}" class="imageSpeaker" align="right"/>

**Picturing Quantum Software**

Quantum software is the code that runs on a quantum computer. I'll give a brief overview of what this means, as well as a trifecta of important challenges in this area: efficient compilation, verification, and classical simulation of quantum programs. Then, I'll discuss some of the ways we've been attacking these problems in recent years, using a number of techniques based on graph rewriting and the ZX calculus.





<!--
	962 × 1039 
	512 x 553	

	512 × 982

## [Burcu Kulahcioglu Ozkan](https://burcuku.github.io/home/), TU Delft

<img src="{{ site.baseurl }}{% link assets/images/UA1.png %}" class="imageSpeaker" align="right"/>

**Randomized Testing of Distributed Systems**

Distributed systems are prone to concurrency bugs due to the nondeterminism in the interleavings of the concurrent events in an execution. Detecting and diagnosing concurrency bugs in distributed systems is critical since unforeseen interleavings of concurrent messages, network, or process faults can result in unexpected, erroneous system behavior. However, concurrency bugs are hard to detect as they are triggered only in some subtle interleavings of the events.

Random testing is a practical way of searching for bugs in large distributed systems. While naïve random stress testing is unlikely to discover bugs that rarely occur, recent randomized testing algorithms offer effective testing methods. They provide theoretical guarantees on detecting bugs based on combinatorial results and borrowing ideas from formal methods and verification. In this talk, we will overview the key ideas in randomized testing techniques for detecting concurrency bugs in distributed systems.

## [Reiner Hähnle](https://www.informatik.tu-darmstadt.de/se/gruppenmitglieder/groupmembers_detailseite_30784.en.jsp), TU Darmstadt

<img src="{{ site.baseurl }}{% link assets/images/UA1.png %}" class="imageSpeaker" align="right"/>

**Context-aware Trace Contracts**

The behavior of concurrent, asynchronous procedures depends in general on the call context, because of the global protocol that governs scheduling. This context cannot be specified with the state-based Hoare-style contracts common in deductive verification. Recent work generalized state-based to trace contracts, which permit to specify internal behavior of a procedure, such as calls or state changes, but not its call context. In this talk we discuss a program logic of context-aware trace contracts for specifying global behavior of asynchronous programs. We also provide a sound proof system that addresses two challenges: To observe the program state not merely at the end points of a procedure, we introduce the novel concept of an observation quantifier. And to combat combinatorial explosion of possible call sequences of procedures, we transfer Liskov's principle of behavioral subtyping to the analysis of asynchronous procedures.

Joint work with: Eduard Kamburjan (U Oslo), Marco Scaletta (TU Darmstadt)

## [Mira Mezini](https://www.stg.tu-darmstadt.de/main_stg/staff_stg/mira_mezini_1.en.jsp), TU Darmstadt

<img src="{{ site.baseurl }}{% link assets/images/UA1.png %}" class="imageSpeaker" align="right"/>

**Safe and Secure Programming Abstractions for Decentralized Software**

Today’s computing infrastructure is massively distributed across geo-replicated clouds in the back-end and millions of increasingly powerful devices in the front-end. Applications running on this massively distributed infrastructure are different from traditional distributed applications – they often interact with their surroundingsand their execution flow is not determined by these unpredictable interactions. While today’s software architecture is centralized with data and computations mostly hosted in back-end clouds and front-end devices merely interfacing to the world, there is a call for decentralization, motivated by requirements for privacy, latency, availability (even for deployments with intermittent connectivity in the front-end), and made possible by increased resources in the front-end. But decentralization brings back long-standing challenges of distributed software on the table of application developers, which are amplified due to global distribution, the quest for decentralization, and the interactive nature of applications. At the same time, our programming methods are not up to these challenges, leaving complexity on the shoulders of application developers to manage. 

In this talk, I will present ongoing work on the REScala project, which aims to close this gap. REScala – a library-based extension of the Scala language - advances the state of scientific knowledge in the area of programming foundations for distributed interactive learning applications. It makes decentralization and interactivity first-class programming principles. Computations running on individual nodes of the computing infrastructure have their local view on data and execution, but these views are composable by-design with guaranteed safety and security properties. Moreover, the views have native time-changing capabilities, whichenables them to jointly evolve in time and space.
-->
