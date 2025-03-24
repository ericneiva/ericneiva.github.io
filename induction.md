---
layout: page
title: Welcome manual
permalink: /welcome/
---

## Introduction to Gridap

### Github

  * Create a [Github](https://github.com/) account (use an e-mail account that will be active for some time, e.g., your personal e-mail or your University e-mail).
  * Ask EN to invite you to this repository. Write an e-mail to him with your Github user.
  * Generate a pair of ssh keys on your local computer, and install the public key in Github. See instructions [here](https://www.inmotionhosting.com/support/server/ssh/how-to-add-ssh-keys-to-your-github-account/) for more details.
  * Follow basic introductions (_if not familiarised_):
    * [Unix Shell tutorial](https://github.com/MonashMath/SCI1022/blob/master/Unix-CLI.md)
    * [Git tutorial](https://github.com/MonashMath/SCI1022/blob/master/Git.md)

### Julia. Download and install.
  
  * Why Julia? 
    * Read [Introduction to Julia](https://ericneiva.com/slides/intro-to-julia-lang/intro-to-julia-lang.html).
    * Read [Motivation and comparison to other languages](https://indico.cern.ch/event/1074269/contributions/4539601/attachments/2317518/3945412/why-julia%20slides.pdf).
  * Download and install Julia. Follow the instructions [here](https://julialang.org/downloads/).

### Visual Studio Code as Julia IDE.

  * To set up VS Code as your Integrated Development Environment, follow the instructions [here](https://github.com/gridap/Gridap.jl/wiki/Visual-Studio-Code-as-Julia-IDE).
    * They might need to be updated. Ask EN for help, if needed.
  
### Introduction to Julia

  * There are plenty of introductory courses to the Julia programming language around. A few recommendations, follow the one(s) that you prefer:
    * [Julia academy](https://juliaacademy.com/p/intro-to-julia)
    * [Julia2925](https://github.com/Beramos/DS-Julia2925)
  * Take a look at the sections of [the Julia manual](https://docs.julialang.org/en/v1/) that cover the fundamentals of the language (Getting Started, Variables, Integers..., Mathematical Operations..., Strings, Functions, Scope of Variables, Types and Methods).
  * Join the Julia [mailing list](https://listes.services.cnrs.fr/wws/subscribe/julia) from CNRS.

### Finite elements

  * If you get to this point, let Eric know to review together what have you learned so far about FEs.
  * Basic references:
    * _A gentle introduction to the Finite Element Method._ [Lecture notes](https://team-pancho.github.io/documents/anIntro2FEM_2015.pdf) (Chapters 1-5)
    * _Finite elements, analysis and implementation._ [Course of the Imperial College London](https://finite-element.github.io/)
    * _Numerical Methods for Partial Differential Equations._ Lecture notes by Prof. Santiago Badia uploaded to this repo.
      * See also the [slides](https://ericneiva.com/intro-to-fem.html) of EN's group meeting in March 2022 _Introduction to Finite Elements._ which are a summary of Prof. Badia's notes.
    * _Numerical Solution of Partial Differential Equations by the Finite Element Method._ Book by Claes Johnson. [Online version](https://cimec.org.ar/foswiki/pub/Main/Cimec/CursoFEM/johnson_numerical_solutions_of_pde_by_fem.pdf)
  * Advanced references:
    * _Theory and Practice of Finite Elements._ Alexander Ern and Jean-Luc Guermond.
  * See also books in the repo:
    * [2004, Ern and Guermond, Theory and Practice of Finite Elements]
    * [2014, Quarteroni, Numerical Models for Differential Problems]

### Gridap tutorials

  * Tutorials for beginners:
    * [1D tutorials](https://github.com/MonashMath/MTH3340/blob/main/TUTORIALS.md) from Prof. Santiago Badia's course in Numerical Methods for Partial Differential Equations
    * [Gridap tutorials 1, 2 and 3.](https://gridap.github.io/Tutorials/dev/)
  * More tutorials and exercises:
    * [Tutorials 1-4 and Exercises 1-3](https://gridap.github.io/GridapWorkshopNCI2023/) from the _Introduction to Gridap_ workshop at ANU, Canberra, Nov 2023.
    * [Scientific project management](https://github.com/BadiaLab/induction?tab=readme-ov-file#scientific-project-management). Learn about points 1, 2 and 4.

### Unfitted FEs

  * [Blog post](https://ericneiva.com/unfitted-fem-tutorial-and-more.html) with plenty of resources:
    * a detailed unfitted Poisson [tutorial](https://gridap.github.io/Tutorials/dev/pages/t019_unfitted_poisson/#Tutorial-19:-Unfitted-Poisson-1),
    * other examples and tutorials  in [GridapEmbedded.jl](https://github.com/gridap/GridapEmbedded.jl)
    * EN's [slides](https://ericneiva.com/slides/unfitted-fem/unfitted-fem.html#1)
    * [Severo Ochoa Seminars by Santiago Badia](https://www.youtube.com/watch?v=W3w2agqX6KM)
    * [Journal article](https://arxiv.org/pdf/2208.08538) [2022, de Prenter et al] _Stability and conditioning of immersed finite element methods: analysis and remedies_
  * [Scaling of the condition number with "naive" unfitted methods:](https://pdf.sciencedirectassets.com/271868/1-s2.0-S0045782517X00029/1-s2.0-S00457825163072[…]3QuY29t&ua=03165c555e505c035a&rr=87868a8b2a55632b&cc=fr) [2017, de Prenter et al] _Condition number analysis and preconditioning of the finite cell method_
  * [AgFEM for mixed dimensional problems:](https://arxiv.org/pdf/1805.01727.pdf) [2018, Badia et al] _MIXED AGGREGATED FINITE ELEMENT METHODS FOR THE UNFITTED DISCRETIZATION OF THE STOKES PROBLEM_ 
  * See also in the repo:
    * EN's hand-written notes with an introduction session to unfitted FEs
    * ALE method
    * [2003, Fernandez-Mendez et al] _Imposing essential boundary conditions in mesh-free methods_
    * [2017, de Prenter et al] _A note on the penalty parameter in Nitsche’s method for unfitted boundary value problems_
    * On Trace FEM and narrow band method:
      [2018, Lehrenfeld] Stabilised Trace FEM on evolving surfaces, Fig.1 and 2
    * [2021, Badia, Neiva, Verdugo] _Linking ghost penalty and aggregated unfitted methods_
    * [2021, Neiva, Badia] _Robust and scalable h adaptive aggregated unfitted FEs for interface elliptic problems_
    * [2021, Saye] _Domains implicitly defined by multivariate polynomials_
    * [2022, Badia, Martorell, Verdugo] _GEOMETRICAL DISCRETISATIONS FOR UNFITTED FINITE ELEMENTS ON EXPLICIT BOUNDARY REPRESENTATION_
    * [2022, Badia, Neiva, Verdugo] _Robust high order unfitted FEs by interpolation based discrete extension_
  * Upcoming talks on unfitted FEs by EN:
    * _Apr 19_ at [Olot Cultura](https://www.olotcultura.cat/agenda/acte/podem-descobrir-com-es-desenvolupen-els-essers-vius-amb-la-matematica-computacional/) (in Catalan, uploaded to [Youtube](https://youtu.be/28msrMwiwkM?feature=shared))
    * _May 13_ at [COMMEDIA seminar](https://team.inria.fr/commedia/) in INRIA Paris Centre
    * _June 20_ at ChaDoc lunch seminar in CdF
