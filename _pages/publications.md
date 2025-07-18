---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- You can also find my articles on <a href="https://scholar.google.com/citations?user=WUwMZtIAAAAJ&hl=fr">my Google Scholar profile</a>. -->

<details>
<summary>Click here for an overview of my PhD research.</summary>
<hr style="height: 3px; background-color: black;">

Through my objective of solving optimization problems under uncertainty in energy management, I explore, leverage, and enhance techniques in <strong>optimal transport</strong>, <strong>machine learning</strong> (mostly <strong>RL</strong>), <strong>convex optimization</strong>, and <strong>stochastic optimization algorithms</strong>.<br><br>

I have thoroughly worked on the <strong>Wasserstein barycenter</strong> problem and proposed several <strong>extensions</strong> to the original formulation. I developed state-of-the-art algorithms to solve these problems and established rigorous mathematical guarantees for each of them.<br><br>

Additionally, I tackled <strong>dimension reduction</strong> in the context of the nested distance—a generalization of the Wasserstein distance—to enable the application of classical methods to large-scale multistage problems.<br><br>

Finally, I investigated the integration of reinforcement learning and stochastic optimization in <strong>a real-world industrial setting</strong>. <br><br>

All of my research is supported by <a href="https://github.com/dan-mim">open-source code</a>, and several contributions have been incorporated into industrial software.

<hr style="height: 3px; background-color: black;">
</details>


## Journal papers

<table>
  <tr>
    <td>
      <b>Mimouni, D., Malisani, P., Zhu, J., & de Oliveira, W. (2024). Computing Wasserstein Barycenter via operator splitting: the method of averaged marginals. DOI: 10.1137/23M1584228.</b><br><br>
      In <a href="https://epubs.siam.org/doi/abs/10.1137/23M1584228">SIAM Journal on Mathematics of Data Science (SIMODS)</a>. (We have made, using AI, a song describing the method (MAM). You may check it <a href="/files/MAM.mp3">here</a>.)<br><br>
      This work introduces a new algorithm for computing exact Wasserstein barycenters — for both free and fixed support — in balanced and unbalanced settings. The approach leverages the Douglas-Rachford operator splitting scheme, demonstrating that the iterative steps are computationally efficient. <br><br>
      Link: <a href="https://epubs.siam.org/doi/abs/10.1137/23M1584228">Paper</a> / <a href="https://www.researchgate.net/publication/373838665_Computing_Wasserstein_Barycenter_via_operator_splitting_the_method_of_averaged_marginals">ResearchGate</a> / <a href="/files/Computing_Wasserstein_Barycenters_via_operator_splitting.pdf">paper PDF</a> / <a href="https://github.com/dan-mim/Computing-Wasserstein-Barycenters-MAM">github</a>.
      <a href="https://github.com/dan-mim/Computing-Wasserstein-Barycenters-MAM">
        <img src="/files/MAM.PNG" alt="plot" width="700"/>
      </a>

    </td>
  </tr>


  <tr>
    <td>
      <b>Mimouni, D., de Oliveira, W., Sempere, G. M. (2025). On the Computation of Constrained Wasserstein Barycenters.</b><br><br>
      Accepted in Pacific Journal of Optimization for a special issue dedicated to Professor R. Tyrrell Rockafellar on the occasion of his 90th birthday.<br><br>
      This work extends my previous method for computing the Wasserstein barycenter using the Douglas-Rachford splitting scheme. In this study, a constraint is imposed on the barycenter in the original problem, and efficient methods are developed to solve it in both convex and non-convex settings.<br><br> 
      Link: <a href="/files/constrained_Wasserstein.pdf">paper PDF</a> / <a href="https://github.com/dan-mim/Constrained-Optimal-Transport">github</a>,  <a href="https://github.com/dan-mim/wasserstein-morphing-mamGAN">also visit</a>.
      <a href="https://github.com/dan-mim/Constrained-Optimal-Transport">
        <img src="/files/mamGAN.PNG" alt="plot" width="700"/>
      </a>
    </td>
  </tr>

  <tr>
    <td>
      <b>Mimouni, D., Malisani, P., Zhu, J., & de Oliveira, W. (2024). Scenario Tree Reduction via Wasserstein Barycenters.</b><br><br>
      Submitted to <a href="https://link.springer.com/journal/10479">Annals of Operations Research</a>.<br><br>
      The method, based on the nested distance, proposed by Kovacevic and Pichler is the most accurate for reducing scenario trees, but its slow execution has limited its practical use. In this work, we show that the method can be significantly accelerated by reformulating one of its steps as an optimal transport problem, solvable with state-of-the-art algorithms. The resulting algorithm is nearly ten times faster, making it suitable for industrial applications.<br><br>
      Link: <a href="https://www.researchgate.net/publication/">website</a> / <a href="/files/reduction_tree.pdf">paper PDF</a> / <a href="https://github.com/dan-mim/Nested_tree_reduction">github</a>.
      <a href="https://github.com/dan-mim/Nested_tree_reduction">
        <img src="/files/KPalgo.PNG" alt="plot" width="700"/>
      </a>
    </td>
  </tr>
  
  <tr>
    <td>
      <b>Currently working on Reinforcement Learning (RL) and Distributionally Robust Optimization (DRO) to tackle multi-stage stochastic optimization problems.</b><br><br>
      This work will be submitted to IEEE Transaction journal. <br><br>
      The goal of this work is to develop a concrete solution for an Energy Management System requiring multistage decision-making. This project will soon be integrated into IFPEN's EMS-lab@ifpen solver.<br><br>
      Link: <a href="https://github.com/dan-mim/EMS-RL-DRO">github</a>.
    </td>
  </tr>

</table>



## International Conferences
<table>
  <tr>
    <td>
      <b>Mimouni, D., Malisani, P., Zhu, J., & de Oliveira, W.: How Optimal Transport can make multi-stage decisions sharper : Boosting scenario tree algorithms (2025). </b><br><br>
      Presentation during the <a href="https://icsp2025.org/">XIIth Conference on Stochastic Programming (ICSP 2025)</a><br><br>
      Link: <a href="">slides to come</a> / Presentation (video) on demand.
    </td>
  </tr>

  <tr>
    <td>
      <b>Mimouni, D., Malisani, P., Zhu, J., & de Oliveira, W. (July 2025). Optimization framework to solve Energy Management System problems: Reinforcement Learning vs Stochastic Programming.</b><br><br>
      Presentation during the <a href="https://sites.google.com/view/iccopt2025/home">2025 International Conference on Continuous Optimization (ICCOPT 2025)</a><br><br>
      Link: <a href="">slides to come</a> / Presentation (video) on demand.
    </td>
  </tr>

  <tr>
    <td>
      <b>Mimouni, D.(2023). Advances in Variational Analysis and Nonsmooth Optimization: Computing Wasserstein Barycenter via Operator Splitting: the Method of Averaged Marginals, July 2024.</b><br><br>
      Presentation during the <a href="https://ismp2024.gerad.ca/">25th International Symposium on Mathematical Programming (ISMP 2025)</a><br><br>
      Link: <a href="/files/ISMP.pdf">slides</a> / Presentation (video) on demand.
    </td>
  </tr>
  
  <tr>
    <td>
      <b>de Oliveira, W., Mimouni, D.(2024). New Approach to Optimal Transport problems, 2024</b><br><br>
      Presentation at <a href="https://europt2024.event.lu.se/">EUROPT 2024</a><br><br>
      Link: <a href="/files/Europt_wlo.pdf">slides</a>.
    </td>
  </tr>


</table>

## French Conferences
<table>
  <tr>
    <td>
      <b>Mimouni, D.(2024). Scenarios methods in stochastic control and applications: Boosting Scenario Tree Reduction, November 2024.</b><br><br>
      Presentation during the <a href="https://www.fondation-hadamard.fr/fr/programmes/les-programmes-thematiques/home/pgmo-days/">The Gaspard Monge Program for Optimization, Operations Research and their interactions with Data Sciences (PGMO)</a><br><br>
      Link: <a href="/files/PGMO_reduction_tree.pdf">slides</a> / Presentation (video) on demand.
    </td>
  </tr>


  <tr>
    <td>
      <b>Mimouni, D.(2023). A new approach for computing Wasserstein Barycenter via operator splitting in the classical balanced setting, Nov 2023.</b><br><br>
      Presentation during the <a href="https://smf.emath.fr/evenements-smf/pgmo-days-2023">PGMO days</a><br><br>
      Link: <a href="/files/PGMOdays.pdf">slides</a> / Presentation (video) on demand.
    </td>
  </tr>

  <tr>
    <td>
      <b>Mimouni, D.(2023). About the Computation of Wasserstein Barycenters, April 2023.</b><br><br>
      Presentation during the <a href="https://ciroquo.ec-lyon.fr/evenements.html">CIROQUO conference</a><br><br>
      Links: <a href="/files/CIROQUO_Wasserstein.pdf">Poster</a>.
    </td>
  </tr>
</table>

## PhD Mid-term Report
<table>
  <tr>
    <td>
      <b>Mimouni, D.(2023). Scenario Tree Reduction and Operator Splitting Method for Stochastic Optimization of Energy Systems.</b><br><br>
      This report corresponds to the research I have carried on up to April 2024. I also presented my research at the industrial annual meeting for PhD students in IFP énergie nouvelles.<br><br>
      Links: <a href="/files/MIMOUNI_Daniel_R11.pdf">Report</a> / <a href="/files/mid-phd_Mimouni_Daniel_R11.pdf">Slides</a>.
    </td>
  </tr>
</table>


<!-- ## Journal papers

<table>
  <tr>
    <td rowspan="3" style="width: 50px;"><b>J1</b></td>
    <td>S. W. Combettes, P. Boniol, A. Mazarguil, D. Wang, D. Vaquero-Ramos, M. Chauveau, L. Oudre, N. Vayatis, P.-P. Vidal, A. Roren, and M.-M. Lefèvre-Colau. "Arm-CODA: A Data Set of Upper-limb Human Movement During Routine Examination." <i>Image Processing On Line (IPOL)</i>, 14:1-13, 2024.</td>
  </tr>
  <tr>
    <td>Data set name: Arm-CODA.</td>
  </tr>
  <tr>
    <td>Links: <a href="https://www.ipol.im/pub/art/2024/494/">website</a> / <a href="https://www.ipol.im/pub/art/2024/494/article.pdf">paper PDF</a> / <a href="https://ipolcore.ipol.im/demo/clientApp/demo.html?id=494">demo</a>.</td>
  </tr>
</table>


## International conference papers

<table>
  <tr>
    <td rowspan="3" style="width: 50px;"><b>IC3</b></td>
    <td>S. W. Combettes, C. Truong, and L. Oudre. "Symbolic representation for time series." To appear in <i>Proceedings of the European Signal Processing Conference (EUSIPCO)</i>, Lyon, France, 2024.</td>
  </tr>
  <tr>
    <td>Method name: ASTRIDE.</td>
  </tr>
  <tr>
    <td>Links: <a href="http://www.laurentoudre.fr/publis/EUSIPCO2024symb.pdf">paper PDF</a> / <a href="https://eusipcolyon.sciencesconf.org/">EUSIPCO 2024</a>.</td>
  </tr>

  <tr>
    <td rowspan="3" style="width: 50px;"><b>IC2</b></td>
    <td>S. W. Combettes, P. Boniol, C. Truong, and L. Oudre. "d_{symb} playground: an interactive tool to explore large multivariate time series datasets." In <i>Proceedings of the International Conference on Data Engineering (ICDE)</i>, Utrecht, Netherlands, 2024.</td>
  </tr>
  <tr>
    <td>Method name: $d_{symb}$ playground.</td>
  </tr>
  <tr>
    <td>Links: <a href="https://icde2024.github.io/demos.html">website</a> / <a href="http://www.laurentoudre.fr/publis/dsymb_demo.pdf">paper PDF</a> / <a href="/files/2024_05_15_dsymb_playground_poster.pdf">poster PDF</a> / <a href="https://github.com/boniolp/dsymb-playground">GitHub</a> / <a href="https://dsymb-playground.streamlit.app/">Streamlit app</a> / <a href="https://youtu.be/4verma-Aqo8">4 min YouTube video</a> / <a href="https://icde2024.github.io/">ICDE 2024</a>.</td>
  </tr>

  <tr>
    <td rowspan="3" style="width: 50px;"><b>IC1</b></td>
    <td>S. W. Combettes, C. Truong, and L. Oudre. "An Interpretable Distance Measure for Multivariate Non-Stationary Physiological Signals." In <i>Proceedings of the International Conference on Data Mining Workshops (ICDMW)</i>, Shanghai, China, 2023.</td>
  </tr>
  <tr>
    <td>Method name: $d_{symb}$.</td>
  </tr>
  <tr>
    <td>Links: <a href="https://ieeexplore.ieee.org/abstract/document/10411636">website</a> / <a href="http://www.laurentoudre.fr/publis/ICDM2023.pdf">paper PDF</a> / <a href="/files/2023_12_01_dsymb_icdm_slides.pdf">slides PDF</a> / <a href="/files/2023_12_01_dsymb_icdm_poster.pdf">poster PDF</a> / <a href="https://github.com/sylvaincom/d-symb">GitHub</a> / <a href="https://www.cloud-conf.net/icdm2023/index.html">ICDM 2023</a> / <a href="https://ai4ts.github.io/icdm2023">AI4TS workshop</a>.</td>
  </tr>
</table>

## Preprints

<table>
  <tr>
    <td rowspan="3" style="width: 50px;"><b>PR1</b></td>
    <td>S. W. Combettes, C. Truong, and L. Oudre. "ASTRIDE: Adaptive Symbolization for Time Series Databases." <i>arXiv</i>, abs/2302.04097, 2023.</td>
  </tr>
  <tr>
    <td>Method name: ASTRIDE.</td>
  </tr>
  <tr>
    <td>Links: <a href="https://arxiv.org/abs/2302.04097">website</a> / <a href="https://arxiv.org/pdf/2302.04097.pdf">paper PDF</a> / <a href="https://github.com/sylvaincom/astride">GitHub</a>.</td>
  </tr>
</table> -->

<!-- <table>
  <tr>
    <th>Year</th>
    <th>Authors</th>
    <th>Title</th>
    <th>Conference / journal</th>
    <th>Status</th>
  </tr>
  <tr>
    <td>2024</td>
    <td>S. W. Combettes, P. Boniol, C. Truong, and L. Oudre</td>
    <td>$d_{symb}$ playground: an interactive tool to explore large multivariate time series datasets</td>
    <td>Proceedings of the International Conference on Data Engineering (ICDE)</td>
    <td>accepted</td>
  </tr>
  <tr>
    <td>2024</td>
    <td>S. W. Combettes, C. Truong, and L. Oudre</td>
    <td>Arm-CODA: A Dataset of Upper-limb Human Movement during Routine Examination</td>
    <td>Image Processing On Line</td>
    <td>published</td>
  </tr>
  <tr>
    <td>2023</td>
    <td>S. W. Combettes, C. Truong, and L. Oudre</td>
    <td>An Interpretable Distance Measure for Multivariate Non-Stationary Physiological Signals</td>
    <td>Proceedings of the Proceedings of the International Conference on Data Mining Workshops (ICDMW)</td>
    <td>published</td>
  </tr>
  <tr>
    <td>2023</td>
    <td>S. W. Combettes, C. Truong, and L. Oudre</td>
    <td>ASTRIDE: Adaptive Symbolization for Time Series Databases </td>
    <td>arXiv</td>
    <td>preprint</td>
  </tr>
</table> -->


{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
