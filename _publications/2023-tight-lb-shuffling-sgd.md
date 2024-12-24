---
title: "Tighter Lower Bounds for Shuffling SGD: Random Permutations and Beyond"
collection: publications
category: conferences
permalink: /publication/tight-lb-shuffling-sgd
excerpt: '**Jaeyoung Cha**, Jaewook Lee, Chulhee Yun'
date: 2023-04-25
venue: 'ICML'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://proceedings.mlr.press/v202/cha23a.html'
# citation: 'Jaeyoung Cha, Jaewook Lee, Chulhee Yun.&quot;Tighter Lower Bounds for Shuffling SGD: Random Permutations and Beyond.&quot; <i>ICML 2023.</i>.'
---

We study convergence lower bounds of without-replacement stochastic gradient descent (SGD) for solving smooth (strongly-)convex finite-sum minimization problems. Unlike most existing results focusing on final iterate lower bounds in terms of the number of components n and the number of epochs K, we seek bounds for arbitrary weighted average iterates that are tight in all factors including the condition number κ. For SGD with Random Reshuffling, we present lower bounds that have tighter κ dependencies than existing bounds. Our results are the first to perfectly close the gap between lower and upper bounds for weighted average iterates in both strongly-convex and convex cases. We also prove weighted average iterate lower bounds for arbitrary permutation-based SGD, which apply to all variants that carefully choose the best permutation. Our bounds improve the existing bounds in factors of n and κ and thereby match the upper bounds shown for a recently proposed algorithm called GraB.