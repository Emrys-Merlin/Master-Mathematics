A boundary map to the Roller boundary of a CAT(0) cube complex
====================================================================

I wrote this thesis at Heidelberg University at the Department of Mathematics & Computer Science. I was adviced by Professor Anna Wienhard. 

Abstract
---------


In this thesis we will present the construction of a so-called boundary map between the
strong Γ-boundary B of a discrete, countable group Γ and the Roller boundary ∂X of a
CAT(0) cube complex X on which Γ acts by automorphisms:

φ : B → ∂X.

We will see that this boundary map is measurable and Γ-equivariant almost everywhere.
The existence was first proven by Chatterji, Fernós, and Iozzi under the further
assumption that X is connected, locally countable and finite-dimensional and that Γ acts
non-elementary on X.
This thesis has an expository nature. We will give a brief introduction to CAT(0) cube
complexes and then turn towards the Roller duality, which will lead us immediately to the
Roller boundary. Additionally, we will explore group actions on CAT(0) cube complexes
introducing the notions of non-elementarity and essentiality. Lastly, we will define ergodic
group actions (with coefficients) and strong Γ-boundaries.

Building the thesis
-------------------

This thesis was built on a linux system using the `tex-live-full` package. The packages I used make it necessary to use `xelatex` to build it (`pdflatex` will fail). The following commands should build the thesis:
```bash
git clone git@github.com:Emrys-Merlin/Master-Mathematics.git .
cd Master-Mathematics
xelatex Master.tex
biber Master
xelatex Master.tex
```
Afterwards you should find a `Master.pdf` file in your working directory.
