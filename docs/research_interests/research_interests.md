# :material-flask: Research Interests

![Quantum Chemistry](https://img.shields.io/badge/Quantum%20Chemistry-1565C0?style=for-the-badge)
![Electronic Structure Theory](https://img.shields.io/badge/Electronic%20Structure%20Theory-00897B?style=for-the-badge)
![Computational Chemistry](https://img.shields.io/badge/Computational%20Chemistry-00695C?style=for-the-badge)
![Ab Initio Methods](https://img.shields.io/badge/Ab%20Initio%20Methods-7E57C2?style=for-the-badge)
![Transition Metal Chemistry](https://img.shields.io/badge/Transition%20Metal%20Chemistry-4527A0?style=for-the-badge)
![Molecular Magnetism](https://img.shields.io/badge/Molecular%20Magnetism-0288D1?style=for-the-badge)

<!-- My research interests lie at the intersection of electronic structure theory and transition metal chemistry.
I am broadly interested in developing and applying ab initio methods to learn the behaviour and properties of transition metal complexes.

--- -->

## Current Research Interests

My current research interests lie at the intersection of electronic structure theory and transition metal chemistry.

My doctoral thesis is focused on using multireference methods to study electronic structure and molecular magnetism in transition metal complexes.

[**:material-file-pdf-box: View PhD Thesis Summary**](Gurjot_Singh_thesis_summary.pdf){target=_blank  .md-button .md-button--primary } | [**:material-download: Download**](Gurjot_Singh_thesis_summary.pdf){target=_blank download="Gurjot_Singh_thesis_summary.pdf" .md-button .md-button--primary }

### Multireference Electronic Structure Methods

I apply multireference methods to study challenging transition metal complexes with open-shell configurations, near-degenerate excited states, and strong (static) and dynamic correlation effects.
My work includes use of the following methods:

- CASSCF and NEVPT2: Standard tools for treating static and dynamic correlation.  
- QD-NEVPT2: Accurately treats near-degenerate states.  
- Approximate Full CI solvers: Large active spaces handled with DMRG or selected CI solvers.

### Molecular Magnetism

I investigate magnetic properties of transition metal complexes, including exchange interactions, spin-orbit coupling, and EPR parameters using ab initio methods.

#### Exchange Interactions

Studied exchange coupling in copper dimers[^1], using the following methods:

[^1]: **Singh, G.**; Gamboa, S.; Orio, M.; Pantazis, D. A.; Roemelt, M. Magnetic Exchange Coupling in Cu Dimers Studied with Modern Multireference Methods and Broken-Symmetry Coupled Cluster Theory. *Theor. Chem. Acc.* **2021**, *140* (10). [https://doi.org/10.1007/s00214-021-02830-0](https://doi.org/10.1007/s00214-021-02830-0){:target="_blank"}

- CASSCF/DMRGSCF for static correlation and NEVPT2 for dynamic correlation.
- DDCI method as an alternative for treating dynamic correlation.
- A new BS-LPNO-CCSD approach, combining broken-symmetry theory with local coupled-cluster method, as an alternative to the standard BS-DFT.

#### Spin-Orbit Coupling and *g*-tensors

Studied electronic structure of a cobalt-oxo intermediate.[^2]

[^2]: Malik, D. D.; Ryu, W.; Kim, Y.; **Singh, G.**; Kim, J.-H.; Sankaralingam, M.; Lee, Y.-M.; Seo, M. S.; Sundararajan, M.; Ocampo, D.; Roemelt, M.; Park, K.; Kim, S. H.; Baik, M.-H.; Shearer, J.; Ray, K.; Fukuzumi, S.; Nam, W. Identification, Characterization, and Electronic Structures of Interconvertible Cobalt–Oxygen TAML Intermediates. *J. Am. Chem. Soc.* **2024**, *146* (20), 13817–13835. [https://doi.org/10.1021/jacs.3c14346](https://doi.org/10.1021/jacs.3c14346){:target="_blank"}

- Collaborated with experimentalists, where we resolved the ambiguity of the intermediate by proposing two interconvertible tautomers.
- Calculated $g$-tensors using CASSCF + NEVPT2 to probe the electronic structure.

Developed a new framework combining QD-NEVPT2 with selected CI references (based on Ugandi and Roemelt's spin-pure heatbath CI[^3]) for calculating spin-orbit coupling and $g$-tensors.

[^3]: Ugandi, M.; Roemelt, M. A Configuration-Based Heatbath-CI for Spin-Adapted Multireference Electronic Structure Calculations with Large Active Spaces. *J. Comput. Chem.* **2023**, *44* (31), 2374–2390. [https://doi.org/10.1002/jcc.27203](https://doi.org/10.1002/jcc.27203){:target="_blank"}

- Implemented the methodology in the [HUMMR program](https://hummr-dev-team.pages.cms.hu-berlin.de/hummr/){:target="_blank"}.[^4]

[^4]: HUMMR Source code: [https://scm.cms.hu-berlin.de/hummr-dev-team/hummr](https://scm.cms.hu-berlin.de/hummr-dev-team/hummr){:target="_blank"}

- Tested and validated on benchmark systems.
- Manuscript in preparation.
