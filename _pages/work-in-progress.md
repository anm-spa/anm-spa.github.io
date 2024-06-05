---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
**Static Slicing in Probabilistic Programming: Disentangling Observation Failure and Nontermination**
**[Past title: Non-termination (in)sensitive slicing for probabilistic programs]**

Abu Naser Masud, Mälardalen University, Sweden, abu.naser.masud@mdu.se
and
Federico Olmedo, University of Chile, Chile, federico.olmedo@dcc.uchile.cl

**Abstract.** The probabilistic programming language offers a high degree of flexibility through its expressive syntax and semantics. 
It includes specialized programming primitives for random assignments and “observe” statements, crucial for conditioning the model 
on observed data. This study delves into several aspects of slicing probabilistic programs (PP), spanning slice semantics, different
static slicing types, slicing algorithms, and proof of correctness. Previous research on slicing PP adopt a program semantics that 
conflates observation failure with non-termination, yielding nontermination insensitive slices. However, observation failure and 
nontermination are distinct phenomena. By disentangling them in the semantics, we have identified several variants of static slicing, 
namely nontermination sensitive and nontermination in-sensitive slicing. The latter is further categorized into distribution 
sensitive and distribution insensitive, based on whether the slice strictly preserves the original program’s outcome distribution, even in 
nonterminating scenarios, or weakly considers only terminating executions. We have provided semantic characterization of all the variants
and devised novel algorithms to compute them by introducing a new concept called observe-nontermination dependence. Additionally, we have 
developed (bi) simulation-based proof techniques to verify the correctness of computing all slice variants. Our contributions deepen the
understanding of static slicing in probabilistic programming, potentially impacting various application domains.

[Preprint](../files/main.pdf)
