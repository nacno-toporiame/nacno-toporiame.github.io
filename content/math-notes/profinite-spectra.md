---
title: Some investigations on profinite equivariant spectra
date: '2026-10-18T10:17:39+02:00'
draft: false
math: true
toc: true
tags:
  - Math
description: A very mundane master thesis project
---
This is a post about [my master thesis](/files/MSc-thesis-spellchecked.pdf), which investigates equivariant spectra (as spectral Mackey functors) for profinite groups
and surveys the construction of endomorphism \\(\mathrm{K}\\)-theory in the modern world.

On the Queer Math Day at MPI Leipzig in June 2026, I gave an 8-minute lightning talk when much of the work was ongoing,
from a tt-geometric perspective which I omitted from the thesis proper.
[You can find the slides here](/files/leipzig-20260622.pdf)

The investigation of \\(\mathrm{Sp}_G\\) for profinite \\(G\\) have historically been motivated
by the appearance of Morava stabiliser groups in chromatic homotopy theory. More recently,
Krause--McCandless--Nikolaus investigated the case of \\(\widehat{\mathbb{Z}}\\), in search for the
natural habitat of integral \\(\mathrm{TR}\\) with bimodule coefficients.
To this end, they invented the notion of *quasifinitely genuine \\(G\\)-spectra*,
or *spectral Mackey profunctors*, as well as *polygonic spectra*,
the "Nikolaus--Scholze-style" \\(\widehat{\mathbb{Z}}\\)-spectra.
They proved the equivalence of the two constructions on uniformly bounded below objects,
just as in the original Nikolaus--Scholze result on cyclotomic spectra.

In my master thesis, I've considered analogous constructions using the (usual finitary) Mackey functor model,
for more general profinite groups \\(G\\). I've considered the category of *geometric \\(G\\)-spectra*,
defined as the limit of \\(G/N\\)-spectra along geometric fixed points for all open normal subgroups \\(N \trianglelefteq G\\).

For finitely generated profinite groups satisfying a particular finiteness condition on the lattice of open subgroups,
it turns out that uniformly bounded below geometric \\(G\\)-spectra is a Bousfield localisation of uniformly bounded below \\(G\\)-spectra.
I've also included a short survey on Krause--McCandless--Nikolaus' version, and sketched an argument
that the extra finiteness condition is redundant in their variant, and their theorem holds for finitely generated profinite groups in general.

As a preparation, the thesis' first chapter provides a user's guide of spectral Mackey functors as a model of \\(G\\)-spectra, and
proves the important structural properties, from which one can deduce a lot results in a model-agnostic manner.
Most notably, one gets quite far with just the Segal--tom Dieck splitting, Adams isomorphism and the identification of
geometric fixed points as a smashing localisation.
The general tom Dieck splitting theorem has also been obtained by McCandless in the [Curves in \\(\mathrm{K}\\)-theory paper](https://doi.org/10.4171/jems/1347).

The last chapter surveys the construction of endomorphism \\(\mathrm{K}\\)-theory as \\(\widehat{\mathbb{Z}}\\)-Mackey functors,
and in the case **without coefficients**, a (partial) Mackey functor on the epicyclic category \\(\widetilde{\Lambda}\\), with
transfers along "regular coverings".
Epicyclic Mackey functors have geometric realisations which naturally land in McCandless' category
of integral topological Cartier modules.
