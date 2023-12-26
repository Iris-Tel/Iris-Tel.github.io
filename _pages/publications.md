---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<h2>Journals:</h2>

<ul>
  <li>Mazloum, T., <em><strong>Wang, S.</strong></em>, and Wiart, J., "Impact of Indoor Distributed Antenna System on RF-EMF Global Exposure." IEEE Access (2023).
    <ul><li><em><strong>Abstract</strong></em>: In this paper, we analyze the impact of the installation of indoor DAS on the global human exposure, considering both DL exposure, and UL exposure. Measurement campaigns are carried out with DAS on and off. The global exposure is evaluated using the ‘Exposure Index’ metric is analyzed. The results have shown that DAS implies a reduction in the global EMF exposure while improving the quality of network connectivity.</li></ul>
  </li>
  
  <newline>  
  <newline>
  <li>Chikha, W., <em><strong>Wang, S.</strong></em>, and Wiart, J., "An Extrapolation Approach for RF-EMF Exposure Prediction in an Urban Area using Artificial Neural Network", Accepted by IEEE Access.
    <ul><li><em><strong>Abstract</strong></em>: In this paper, we present an approach to extrapolate the E field in an urban area using artificial neural network. Using public accessed datasets, i.e., cartoradio and OpenStreetMap, we then extract relevant features, including the ones that have a relation with the number of active antennas and those used by Bertoni-Walfisch propagation model.</li></ul>
  </li>
  
  <newline>  
  <newline>
  <li>Mulugeta. B., <em><strong>Wang, S.</strong></em>, Chikha, W., Liu, J., Roblin, C., and Wiart, J., "Statistical characterization and modelling of indoor RF-EMF down-link exposure", accepted by MDPI Sensors.
    <ul><li><em><strong>Abstract</strong></em>: In this study, a statistical approach is utilized to characterize and model indoor RF-EMF DL exposure, where the variation of RF-EMF DL exposure is mainly influenced by the local indoor environment. Measurements were conducted in three buildings within a few hundred meters vicinity of two BS.</li></ul>
  </li>

  <newline>  
  <newline>
  <li><em><strong>Wang, S.</strong></em>, Mazloum, T., and Wiart, J. (2022, June). "Prediction of RF-EMF exposure by outdoor drive test measurements", Telecom (Vol. 3, No. 3, pp. 396-406). MDPI.
    <ul><li><em><strong>Abstract</strong></em>: In this work, we exploit the ANN model for the spatial reconstruction of RF-EMF exposure in an outdoor urban environment. Drive test measurement campaign was done to collect E-field strength information along the route. We compared the prediction performance using two ANN models.</li></ul>
  </li>

  <newline>  
  <newline>
  <li>Mazloum, T., <em><strong>Wang, S.</strong></em>, Hamdi, M., Mulugeta, B.A., and Wiart J. "Artificial neural network-based uplink power prediction from multi-floor indoor measurement campaigns in 4G networks", Frontiers in Public Health 9 (2021): 777798.
    <ul><li><em><strong>Abstract</strong></em>: In this work, we conduct measurements in a multi-floor indoor environment using a handheld device, i.e., Nemo Handy, to record both DL and UL parameters for LTE networks. We build a feed-forward ANN model with RSRP, as input together with other parameters influencing the TX power and related to the measurement environment.</li></ul>
  </li>

  <newline>  
  <newline>
  <li>Hajj M.A., <em><strong>Wang, S.</strong></em>, Lam T. T, Azzi, S., and Wiart J. ``A statistical estimation of 5G massive MIMO networks' exposure using stochastic geometry in mm-wave bands'', Applied Sciences, 10.23 (2020): 8753.
    <ul><li><em><strong>Abstract</strong></em>: We use stochastic geometry to explore the downlink exposure in 5G massive MIMO antenna networks. The distributions of antenna gain and channel gain were obtained by fitting simulation results, then implemented into an analytical framework. We obtained the closed-form expression of the MGF for the total exposure in the network and validate it by numerical simulations.
</li></ul>
  </li>

  <newline>  
  <newline>
  <li><em><strong>Wang, S.</strong></em> and Wiart J. "Sensor-added EMF exposure assessments in an urban environment using artificial neural networks", IJERPH 17.9 (2020): 3052.
    <ul><li><em><strong>Abstract</strong></em>: The time and spatial mapping of EMF exposure induced by outdoor BS using ANN are studied. The reconstructed EMF exposure map in urban environments is obtained by using data from EMF sensor networks, drive testing, and information accessible publicly, e.g., locations and orientations of BSA. We proposed a new efficient hybrid ANN structure and the results show it outperforms the conventional ANN.
</li></ul>
  </li>

  <newline>  
  <newline>
  <li><em><strong>Wang, S.</strong></em> and Di Renzo, M. "On the mean interference-to-signal ratio in spatially correlated cellular networks", IEEE Wireless Communications Letters, 9.3 (2019): 358-362. 
    <ul><li><em><strong>Abstract</strong></em>: In this work, we focus on spatially repulsive cellular networks and introduce a new parameterization for the IDT approach that is suitable for analysis of the Mean Interference-to-Signal Ratio (MISR). We prove that MISR, as well as the difference between the MISRs of Poisson and non-Poisson cellular networks, monotonically decreases as the PLE increases and the density of the BSs decreases.
</li></ul>
  </li>

  <newline>  
  <newline>
  <li><em><strong>Wang, S.</strong></em> and Di Renzo, M. (2019). On the meta distribution in spatially correlated non-Poisson cellular networks. EURASIP Journal on Wireless Communications and Networking, 2019(1), 161.
    <ul><li><em><strong>Abstract</strong></em>: In this work, we introduce an analytical framework for computing the distribution of the conditional coverage probability given the point process. Then, we have proved that the IDT approach for modeling and analyzing non-Poisson cellular networks can be successfully employed for studying the meta distribution. It is proved that these latter moments can be formulated in terms of a single integral expression. </li></ul>
  </li>

  <newline>  
  <newline>
  <li>Di Renzo, M., <em><strong>Wang, S.</strong></em>, and Xi, X. (2018) "Inhomogeneous double thinning – Modeling and analysis of cellular networks by using inhomogeneous Poisson point processes", IEEE Transactions on Wireless Communications, 17.8 (2018): 5162-5182.
    <ul><li><em><strong>Abstract</strong></em>: In this work, we introduce a new methodology for modeling and analyzing downlink cellular networks, where the BSs constitute a motion-invariant PP that exhibits some degree of interactions among the points, i.e., spatial repulsion or spatial clustering. The accuracy of the IDT approach is substantiated with the aid of empirical data for the spatial distribution of the BSs.
  </li>
</ul>


<h2>Conferences:</h2>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
