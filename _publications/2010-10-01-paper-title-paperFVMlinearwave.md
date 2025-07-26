---
title: "Analysis of dissipation operators that damp spurious modes while maintaining discrete approximate geostrophic equilibriums for the B-grid staggered scheme on triangular meshes"
collection: publications
category: manuscripts
permalink: /publication/2010-10-01-paper-title-paperFVMlinearwave
excerpt: ''
date: 2023-09-15
venue: 'Journal of Computational Physics'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'http://vanthanh74.github.io/files/paperFVMlinearwave.pdf'
citation: 'M.-H. Do, V.-T. Nguyen, P. Omnes. &quot;Analysis of dissipation operators that damp spurious modes while maintaining discrete approximate geostrophic equilibriums for the B-grid staggered scheme on triangular meshes.&quot; <i>Journal of Computational Physics
</i>. Volume 489. 2023. 112261. ISSN 0021-9991. https://doi.org/10.1016/j.jcp.2023.112261.'
---

Abstract: We consider the lowest order - so called B-grid - discretization on triangular cells which is common in the ocean or atmosphere simulation science, with pressure field at the vertices of the triangles and the velocity field at the cell centers. It is known that this discretization presents spurious modes due to a too large number of velocities unknowns and that these modes should be damped; since preservation of approximate geostrophic equilibrium (GE) may be of primary importance in the simulations, we propose and analyze damping operators that, when applied to the linearized constant coefficient configuration, exactly preserve discrete versions of the GEs. We also analyze their effects in more general configurations and their possible coupling with more standard damping operators. These strategies cover triangular variants of the Low Froude (LF) scheme [1], the Apparent Topography (AT) scheme [2], [3], as well as a new modification of it. The LF scheme has no numerical diffusion terms in the pressure equation and damps the normal velocity jumps between adjacent cells in the momentum equation. In the AT scheme, numerical diffusion is added in the pressure equation in such a way that it does not impact the discrete GE. However, since the AT scheme alone cannot be proved to be damping through energy estimates and does not preserve the space which is orthogonal to the discrete GE, we also study what we call the Modified Apparent Topography (MAT) that satisfies these important properties. We also suggest semi-implicit time discretizations that preserve these properties. Extensions to the full non-linear equations are also provided. Numerical experiments illustrate the performance of the new schemes.

Keywords: Shallow water equation with Coriolis source term; Low Froude number; Hodge decomposition; Staggered schemes; Spurious mode damping; Geostrophic equilibrium.
