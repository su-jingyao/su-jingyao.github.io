---
title: "Towards interval-based autonomous integrity monitoring: Error bounding and uncertainty propagation"
publication_types: ['dissertation']
authors:
  - admin
doi: '10.15488/19619'
publication: Wissenschaftliche Arbeiten der Fachrichtung Geodäsie und Geoinformatik der Leibniz-Universität Hannover; Nr. 410; Deutsche Geodätische Kommission der Bayerischen Akademie der Wissenschaften Reihe C; Nr. 965
#publication_short: In *ION GNSS+ 2022*
abstract: "Satellite navigation can provide essential positioning, navigation and timing (PNT) information to a broad range of users. With the development of the Global Navigation Satellite System (GNSS), various applications have emerged and grown with substantial economic impact over the past decades. For safety-critical GNSS applications, estimation errors must be reliably quantified and safely bounded. This requirement is crucial for ensuring navigation integrity, which was originally formulated for aviation navigation. It concerns the trust that can be placed in a navigation solution under rare-event conditions and, hence, differs from the commonly expressed user demand in accuracy, focusing on the trustiness and reliability of the navigation system. Conventional solutions have been concentrating on stochastic approaches, relying on distributional assumptions for the observation errors before they are propagated through state estimation. However, the exact error distribution is either unknown or hardly validated, and the remaining systematics persist in the GNSS measurements after applying correction methods. In this regard, purely stochastic modeling of all error sources will not be adequate, necessitating the exploration of alternative approaches. Interval is a promising alternative representation of uncertainty. It provides deterministic bounds that indicate the possible variation of errors and, hence, is feasible to represent the uncertainty due to remaining systematic effects. Grounded on the interval-described uncertainty modeling, an innovative integrity monitoring framework is developed in this dissertation, providing an alternative approach to classical stochastic methods such as (Advanced) Receiver Autonomous Integrity Monitoring (RAIM and ARAIM). Critical integrity-focused questions include: (i) how representative the navigation solutions are and (ii) how their uncertainty can be safely modeled to yield integrity assurance. To address these questions, practical methods of determining interval bounds for various GNSS error sources are developed and validated through experiments. Building on the interval bounds, the state estimation problem is investigated, with an emphasis on error bounding. Two novel point estimators are proposed by exploring the set-described uncertainty models, showing advantageous error bounding performance. The set-based fault detector, intended to be integrated into the new integrity monitoring architecture, is discussed and assessed in comparison with classical methods. By utilizing the multiple hypotheses framework that is also adopted by ARAIM, the developed approach can handle multiple simultaneous faults, protecting the navigation system from loss of integrity. Its effectiveness is demonstrated by various evaluation strategies and compared to state-of-art methods, including analytical and Monte Carlo assessments, as well as performance analysis with real-world experiments. Additionally, this dissertation proposes to improve the baseline ARAIM algorithms by implementing the interval extension of the least-squares estimator."
draft: false
featured: true
tags:
  - GNSS
  - error bounding
  - interval mathematics
  - uncertainty modeling
  - integrity monitoring
# projects:
#  - icsens
# image:
#  filename: featured.png
#  focal_point: Smart
#  preview_only: false
#summary: "In this contribution, we aim to demonstrate the feasibility of
#  applying the alternative integrity approach to autonomous navigation in terms
#  of several key aspects, i.e., the handling of GNSS multipath effect in the
#  urban environment, fault detection and exclusion, and further consideration of
#  applying weighting models. "
date: '2025-03-26T14:00:00.000Z'
url_pdf: 'https://repo.uni-hannover.de/bitstreams/bacdeabb-ef67-4906-9a26-f1c9e6aa2e6d/download'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
links:
  - name: Research@Leibniz University
    url: https://www.fis.uni-hannover.de/portal/de/publications/towards-intervalbased-autonomous-integrity-monitoring(20244e9b-5421-4c55-a3eb-c07ff1f345ff).html
    icon: hero/book-open
  - name: DGK
    url: https://publikationen.badw.de/en/050454888/050454888.pdf
    icon: hero/book-open
---
