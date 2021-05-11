---
title: "A new perspective on Catastrophic Forgetting"
layout: post
---

# {{ page.title }}

by Fabian Fritz

## Introduction

During the summer of 2020 I had a lot of time to think about some of my favorite problems in machine learning (ML). When I read an article about Catastrophic Interference (CF) by the people at Google Brain, I came across the following statement:

> Despite the ubiquity of catastrophic forgetting, there is limited understanding of the underlying process and its causes.

[[1]](##References)

I was surprised by this, because I was aware that this problem has been around since the mid-eighties and numerous attempts have been made at solving CF. I had been vaguely following the research and had a rough understanding of the proposed solutions. Still, it made me question my own understanding of the problem again and I had a look at the paper by McCloskey & Cohen [[2]](##References) that introduced CF.

That's when I realized that we might have approached the problem, and therefore any attempt at solving it, in the wrong way. Considering CF in the larger context of our quest in the ML research community to make progress towards artificial general intelligence (AGI), it might be that, due to the constraints the fundamental assumptions of connectionism put upon our models, there is no meaningful way to *solve* catastrophic interference, because even an ideal solution would not lead to more powerful models.

In this article I will try to explain how I came to this hypothesis and why I now believe that once we move outside connectionist, regressive models we might be able to solve not only CF but other longstanding issues that have proven challenging for ML and pattern recognition. Even more exciting, the solution that I am envisioning would require us to think about learning and memory in a completely new way, not only in ML but also in neuroscience.

## The mechanics behind Catastrophic Forgetting

## The bigger picture

## References

- [1] Ramasesh, V., Dyer, E., & Raghu, M. (2020). Anatomy of Catastrophic Forgetting: Hidden Representations and Task Semantics. ArXiv, abs/2007.07400.
- [2] McCloskey, M., & Cohen, N. J. (1989). Catastrophic interference in connectionist networks: The sequential learning problem. In Psychology of learning and motivation (Vol. 24, pp. 109-165). Academic Press.
