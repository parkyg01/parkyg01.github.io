---
layout: home
title: "Home"
---
<img align="right" style="width: 30%; padding-left: 3%;" src="{{ site.github.url }}/assets/img/ygpark.jpg" alt="Yonggon Park">

I am an Ph.D. Student in the [Department of Computer Science Engineering](https://cse.postech.ac.kr) at [POSTECH](https://www.postech.ac.kr), working with [Prof. Jisung Park](https://jisung-park.github.io/) who leads the the [Computer Architecture and Operating Systems (CAOS) Office](https://www.caos.postech.ac.kr/). I earned my B.S. degree in Computer Science Engineering from [POSTECH](https://www.postech.ac.kr). My research interests lie in NAND flash-based storage systems, computer architecture, and memory systems.

<br>
#### Contact

- Email: [{{site.data.basic.email}}](mailto:{{site.data.basic.email}})
- Phone: {{site.data.basic.phone}}
- Office: {{site.data.basic.office}}, {{site.data.basic.institution_address}}

#### Education

- Ph.D. in Computer Science Engineering, POSTECH, Sep 2023 -- Present (Advisor: Prof. Jisung Park)
- B.S. in Computer Science Engineering, POSTECH, Mar 2020 -- Jul 2023

#### Research Experience

- Research Intern (In-Person), SAFARI Research Group, ETH Zurich, Mar 2026 -- Present
- Research Intern (Remote), SAFARI Research Group, ETH Zurich, Jan 2024 -- Jan 2025
- Intern, Autocrypt, Seoul, Korea, Jun 2022 -- Sep 2022 (Automotive Security, Bluetooth Protocol Fuzzing)

#### Teaching Experience

{% for section in site.data.experience %} 
- {{section.position}}, {{section.institution}}, {{section.period}} {% endfor %}
