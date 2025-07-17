---
title: "All-atom inverse protein folding through discrete flow matching"
collection: publications
permalink: /publication/adflip
excerpt: ''
date: 2025-05-01
paperurl: 'https://openreview.net/pdf?id=8tQdwSCJmA'
venue: ICML 2025
---
**Authors**: Kai Yi*, Kiarash Jamali*, and Sjors H.W. Scheres

The recent breakthrough of AlphaFold3 in modeling complex biomolecular interactions, including those between proteins and ligands, nucleotides, or metal ions, creates new opportunities for protein design. In so-called inverse protein folding, the objective is to find a sequence of amino acids that adopts a target protein structure. Many inverse folding methods struggle to predict sequences for complexes that contain non-protein components, and perform poorly with complexes that adopt multiple structural states. To address these challenges, we present ADFLIP (All-atom Discrete FLow matching Inverse Protein folding), a generative model based on discrete flow-matching for designing protein sequences conditioned on all-atom structural contexts. ADFLIP progressively incorporates predicted amino acid side chains as structural context during sequence generation and enables the design of dynamic protein complexes through ensemble sampling across multiple structural states. Furthermore, ADFLIP implements training-free classifier guidance sampling, which allows the incorporation of arbitrary pre-trained models to optimise the designed sequence for desired protein properties. We evaluated the performance of ADFLIP on protein complexes with small-molecule ligands, nucleotides, or metal ions, including dynamic complexes for which structure ensembles were determined by nuclear magnetic resonance (NMR). Our model achieves state-of-the-art performance in single-structure and multi-structure inverse folding tasks, demonstrating excellent potential for all-atom protein design. The code is available (here)[https://github.com/ykiiiiii/ADFLIP].

[Find paper here](https://openreview.net/pdf?id=8tQdwSCJmA)
