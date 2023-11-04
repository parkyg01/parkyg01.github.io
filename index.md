---
layout: home
title: "Home"
---
<img align="right" style="width: 30%; padding-left: 3%;" src="{{ site.github.url }}/assets/img/ygpark.jpg" alt="Yonggon Park">

I am an Ph.D. Student (Integrated Program) in the [Department of Computer Science and Engineering](https://cse.postech.ac.kr) at [POSTECH](https://www.postech.ac.kr), working with [Prof. Jisung Park](https://jisung-park.github.io/) who leads the the [Computer Architecture and Operating Systems (CAOS) Laboratory](https://www.caos.postech.ac.kr/). I earned my B.S.E. degree in Computer Science and Engineering from [POSTECH](https://www.postech.ac.kr). My research interests lie in hardware & system security, storage systems, memory systems, system software, operating system, and computer architecture.

<br>
#### Contact

- Email: [{{site.data.basic.email}}](mailto:{{site.data.basic.email}})
- Bibliography: [DBLP](https://dblp.uni-trier.de/pid/123/2642-1.html), [Google Scholar](https://scholar.google.com/citations?user=1qw7AosAAAAJ&hl=en)
- Phone: {{site.data.basic.phone}}
- Office: {{site.data.basic.office}}, {{site.data.basic.institution_address}}

#### Education

- Ph.D. (Integrated Course) in Computer Science, POSTECH, 2023.
- B.S.E. in Computer Science, POSTECH, 2020.

#### Teaching Experience

{% for section in site.data.experience %} 
- {{section.position}}, {{section.course}}, {{section.institution}}, {{section.period}} {% endfor %}