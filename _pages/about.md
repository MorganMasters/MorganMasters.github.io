---
permalink: /
title: "Get the robots dirty!"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

I am a Ph.D. student in Electrical and Computer Engineering at UC Santa Cruz,
building field-robotics systems that keep an eye on things people cannot afford
to watch by hand — remote wireless sensor networks, working farms, and the
environments they sit in. I am co-advised by Dr. Steve McGuire (field robotics)
and Dr. Colleen Josephson (wireless sensing). I also work at the University of
Washington's Applied Physics Laboratory on physics-informed deep-learning visual
tracking for marine robotics.

My research question is a planning question: **given a mission budget, which
traversal collects the most informative dataset?** Three threads, all rooted in
combinatorial optimization — traveling-salesman and next-best-view planning:

+ Traversing a geotagged environment to collect user-curated imagery, turning a
  single flight into a supervised training dataset for robotic vision models.
+ Compressive-sensing schemes that subsample oversized environmental sensor
  arrays without losing state-estimation accuracy.
+ Choosing the set of views that best trains novel view synthesis methods.

That work ships as **BirdsEye**, a low-cost UAV and RTK geoannotation pipeline
that replaces manual image labeling with ground-based geotagging. It won the
[ACM SIGBED Student Research Competition at ESWEEK 2025](/posts/2025/09/sigbed-src-champion/)
and reached the [finals of the Farm Robotics Challenge & Academy 2026](/posts/2026/08/frc-2026-finalist/).

Before UC Santa Cruz: M.S. in Applied Mathematics (University of Washington,
2019, with Dr. J. Nathan Kutz) and B.S. degrees in Physics & Mathematics and in
Materials Science & Engineering (Iowa State University, 2018, advised by Dr.
Paul C. Canfield).

## Recent news

<ul>
{% for post in site.posts limit: 3 %}
  <li>
    <strong>{{ post.date | date: "%B %Y" }}</strong> —
    <a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

[All news &rarr;](/news/)
