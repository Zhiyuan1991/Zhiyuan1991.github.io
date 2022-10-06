---
layout: archive
# title: "Publications"
permalink: /publications/
author_profile: true
---

M Toloubidokhti, N Kumar, Z Li, PK Gyawali, B Zenger, WW Good, RS MacLeod, and L Wang. Interpretable Modeling and Reduction of Unknown Errors in Mechanistic Operators, International Conference on Medical Image Computing and Computer-Assisted Intervention, (2022)
X Jiang, Z Li, R Missel, MS Zaman, B Zenger, WW Good, RS MacLeod, JL Sapp, L Wang, Few-Shot Generation of Personalized Neural Surrogates for Cardiac Simulation via Bayesian Meta-learning, International Conference on Medical Image Computing and Computer-Assisted Intervention, (2022)
X Jiang, R Missel, M Toloubidokhti, Z Li, O Gharbia, JL Sapp, L Wang, Label-Free Physics-Informed Image Sequence Reconstruction with Disentangled Spatial-Temporal Modeling, International Conference on Medical Image Computing and Computer-Assisted Intervention, (2021)
R Missel, PK Gyawali, JV Murkute, Z Li, S Zhou, A AbdelWahab, J Davis, J Warren, J L Sapp, L Wang, A hybrid machine learning approach to localizing the origin of ventricular tachycardia using 12-lead electrocardiograms, International Conference on Medical Image Computing and Computer-Assisted Intervention, (2020)
X Jiang, S Ghimire, J Dhamala, Z Li, PK Gyawali, L Wang, Learning Geometry-Dependent and Physics-Based Inverse Image Reconstruction, International Conference on Medical Image Computing and Computer-Assisted Intervention, (2020)
PK Gyawali, S Ghimire, P Bajracharya, Z Li, L Wang, Semi-supervised Medical Image Classification with Global Latent Mixing, International Conference on Medical Image Computing and Computer-Assisted Intervention, (2020)
Z Li, JV Murkute, PK Gyawali, L Wang, Progressive Learning and Disentanglement of Hierarchical Representations, International Conference on Learning Representations, (2020)
R Ballagas, J Wei, M Vankipuram, Z Li, K Spies, H Horii, Exploring Pervasive Making Using Generative Modeling and Speech Input, IEEE Pervasive Computing, (2019)
Z Li, PK Gyawali, S Ghimire, L Wang, Semi-supervised Learning by Disentangling and Self-ensembling over Stochastic Latent Space, International Conference on Medical Image Computing and Computer-Assisted Intervention, (2019)
PK Gyawali, Z Li, C Knight, S Ghimire, BM Horacek, J Sapp, L Wang, Improving Disentangled Representation Learning with the Beta Bernoulli Process, IEEE International Conference on Data Mining, (2019)
AK Yung, Z Li, D Ashbrook, Printy3D: in-situ tangible three-dimensional design for augmented fabrication, ACM Conference on Interaction Design and Children, (2018)
C Tejada, O Fujimoto, Z Li, D Ashbrook. Blowhole: Blowing-Activated Tags for Interactive 3D-Printed Models, Graphics Interface Conference, (2018)
Z Huang, Z Xu, Z Li, Z Zhao, D Tao, 'Depth and Skeleton Information Model for Kinect Based Hand Segmentation', International Conference on Advanced ICT and Education (2013)
Z Xu, Z Huang, Z Zhao, Z Li, P Huang, 'Sparse Representation for Kinect Based Hand Gesture Recognition System', International Conference on Advanced ICT and Education (2013)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
