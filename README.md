# Fast confidence bounds for the false discovery proportion over a path of hypotheses
Guillermo Durand
2025-10-09

### Citation

Guillermo Durand (October 2025). Fast confidence bounds for the false discovery proportion over a path of hypotheses. Computo.
<https://doi.org/10.57750/efbs-ef14>

### Badges

[![build and
publish](https://github.com/computorg/published-202510-durand-fast/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202510-durand-fast/actions/workflows/build.yml)
[![reviews](https://img.shields.io/badge/review-report-blue)](https://github.com/computorg/published-202510-durand-fast/issues?q=is%3Aopen+is%3Aissue+label%3Areview)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/computorg/published-202510-durand-fast)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/computorg/published-202510-durand-fast)
[![DOI:10.57750/efbs-ef14](https://img.shields.io/badge/DOI-10.57750%2Fefbs--ef14-034E79.svg)](https://doi.org/10.57750/efbs-ef14)
[![Creative Commons
License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

### Authors’ affiliations

- [Guillermo Durand](https://durandg12.github.io/) (Université Paris-Saclay, CNRS, Inria, Laboratoire de Mathématiques d’Orsay, 91405, Orsay, France)

### Abstract

This paper presents a new algorithm (and an additional trick) that
allows to compute fastly an entire curve of post hoc bounds for the
False Discovery Proportion when the underlying bound
$V_{\mathfrak{R}}^{\ast}$ construction is based on a reference family
$\mathfrak{R}$ with a forest structure à la Durand et al. (2020). By an
entire curve, we mean the values
$V_{\mathfrak{R}}^{\ast}(S_1),\dotsc,V_{\mathfrak{R}}^{\ast}(S_m)$
computed on a path of increasing selection sets
$S_1\subsetneq\dotsb\subsetneq S_m$, $|S_t|=t$. The new algorithm
leverages the fact that going from $S_t$ to $S_{t+1}$ is done by adding
only one hypothesis. Compared to a more naive approach, the new
algorithm has a complexity in $O(|\mathcal K|m)$ instead of
$O(|\mathcal K|m^2)$, where $|\mathcal K|$ is the cardinality of the
family.

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-MR4178188" class="csl-entry">

Durand, Guillermo, Gilles Blanchard, Pierre Neuvial, and Etienne
Roquain. 2020. “Post Hoc False Positive Control for Structured
Hypotheses.” *Scand. J. Stat.* 47 (4): 1114–48.
<https://doi.org/10.1111/sjos.12453>.

</div>

</div>
