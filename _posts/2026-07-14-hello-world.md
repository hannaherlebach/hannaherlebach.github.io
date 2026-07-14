---
layout: post
title: "Hello world"
date: 2026-07-14
---

This is the first post on this blog. I'm a first-year DPhil student at Oxford working on machine learning and I plan to write up things I'm reading and thinking about here.

A test of math rendering to make sure things work. The variational free energy can be written as:

$$F = \mathbb{E}_{q(\mathbf{s})}[\ln q(\mathbf{s}) - \ln p(\mathbf{o}, \mathbf{s})]$$

which decomposes into a complexity term minus an accuracy term, or equivalently as a KL divergence minus log model evidence:

$$F = D_{\mathrm{KL}}[q(\mathbf{s}) \| p(\mathbf{s} \mid \mathbf{o})] - \ln p(\mathbf{o})$$

Inline math also works: minimising $F$ is equivalent to maximising the ELBO.
