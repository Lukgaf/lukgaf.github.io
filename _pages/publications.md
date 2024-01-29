---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
JOURNAL PUBLICATIONS (from Ph.D. projects)

1.  Lukumon, G., & Klein, M. (2023). Crowd-sourced idea filtering with Bag of Lemons: the impact of the token budget size. Decision, 50(2), 205-219. [Link]

WORKING PAPERS (from Ph.D. projects, drafts available)

2.  Lukumon, G., Picat, L., Chemla, E., & Strickland B. Myside Bias in Scientific Decision-Making: Exploring Speed-Accuracy Trade-Offs and Implications for Biases and Scientific Communities. (under review in Cognitive Science).

3.  Lukumon, G., Cusimano, C., & Strickland B. Optimism and attribution of dis(loyalty) in Group. 
          (in preparation).

4.  Lukumon, G., Byrd N., & Strickland B. Adversarial collaboration among fact-checkers: bipartisanship outweighs partisanship in preferences and trust towards news. (in preparation).

JOURNAL PUBLICATIONS (others)

5.  El Habouz, Y., El Mourabit, Y., Iggane, M., El Habouz, H., Lukumon, G., & Nouboud, F. (2023). Efficient semi-supervised learning model for limited otolith data using generative adversarial networks. Multimedia Tools and Applications, 1-14. [Link]

6.  Anlló, H., Bavard, S., Benmarrakchi, F., Bonagura, D., Cerrotti, F., Cicue, M., …, Lukumon G., ... & Palminteri, S. (2023). Outcome context-dependence is not WEIRD: Comparing reinforcement-and description-based economic preferences worldwide. Research Square. [Link]

7.  Lukumon, G., & Maharaj, A. (2022). Students’ Experiences on the Remote Teaching and Learning of Linear Algebra During COVID-19. African Journal of Research in Mathematics, Science and Technology Education, 26(1), 35-46. [Link]

8.  Shindin, S., Parumasur, N., & Lukumon, G. (2022). Numerical analysis of Fourier pseudospectral methods for the Klein–Gordon equation with smooth potentials: Fourier pseudospectral methods for Klein–Gordon equation. Afrika Matematika, 33(3), 85. [Link]

9.  Maharaj, A., & Lukumon, G. (2021). Commerce students’ ability to correctly apply integration rules. Technology Report of Kansai University, 63(2), 7083–7105. [Link]

10. Jolaoso, L. O., Lukumon, G. A., & Aphane, M. (2021). Convergence theorem for system of pseudomonotone equilibrium and split common fixed point problems in Hilbert spaces. Bollettino dell'Unione Matematica Italiana, 14, 403-428. [Link]

11. Lukumon, G. A. (2018). Numerical solution of the Klein-Gordon equation in an unbounded domain (Masters dissertation). [Link]

12. Lukumon, G., & Ayegbusi R. Myside bias and militarization of election. (in preparation).


PEER-REVIEWED CONFERENCE PROCEEDINGS 

13. Lukumon, G., Cusimano, C., & Strickland B (2023). Optimism and attribution of dis(loyalty) in Group. Proc. of the 2023 SJDM annual conference. [Link]

14. Lukumon, G; Boon Falleur; & Strickland B. (2022). Expressive responding, myside bias and moral conviction. Proceedings of 2022 UM6P JDD Conference, UM6P. [Link]

15. Lukumon, G; & Klein, M. (2021). Idea filtering with Bag of Lemons. Proceedings of 2021 UM6P JDD Conference, UM6P. [Link]

   16.  Lukumon, G., Shindin, S., & Parumasur N. (2019). On Lax Pairs analysis of the Sine-Gordon
equation. Proc of CAES, UKZN Postgraduate Research and Innovation Symposium.  [Link]

    17.    Lukumon, G., Shindin, S., & Parumasur N. (2018). On the numerical Solution of the Klein-
Gordon equation in an Unbounded Domain. Proc. of CAES, UKZN Postgraduate Research and Innovation Symposium. [Link]


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
