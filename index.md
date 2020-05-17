---
layout: archive
title: Hi! I'm Leo.
classes: wide
excerpt: <br>
header:
  overlay_image: /assets/images/banner.jpg
  overlay_filter: 0.15
author_profile: true
---

## About

I work as a research scientist in the verified and robust deep learning team at DeepMind. Prior to this, I completed my DPhil / PhD under the supervision of Andrew Zisserman and Pawan Kumar at University of Oxford.

My main research interests lie at the intersection between mathematical optimization and deep learning. I aim to
design algorithms that are grounded in theory and have a practical impact.

My background is mainly in applied mathematics and computer science (B.Sc. & M.Sc. Ecole Centrale Paris, M.Eng. UC
Berkeley), and I have some familiarity with fundamental physics (B.Sc. Université Paris-Sud).

## News

* I joined the Verified and Robust Deep Learning team at DeepMind as a research scientist (March 2020).
* My thesis was accepted without correction by my examiners Andrea Vedaldi and Julien Mairal (25 February 2020). Many thanks to Yougov and the EPSRC for having funded my PhD!
* I did an internship at DeepMind in the team of James Martens (June 2019 - November 2019).
* I am honored to be acknowledged in Gilbert Strang's new book: [Linear Algebra and Learning From Data](https://math.mit.edu/~gs/learningfromdata/).
* I gave a [talk](https://www.youtube.com/watch?v=Pp18exSLoKQ&t=1s) at the Machine Learning Meetup of London (August 2018).
* I presented my work at the International Symposium on Mathematical Programming (July 2018).
* Outstanding Reviewer Award at [CVPR 2018](http://cvpr2018.thecvf.com/program/reviewer_acknowledgements).


## Publications

{% for paper in site.papers %}
  <details>
      <summary>{{ paper.title }}.<br/>
    {{ paper.author }}. <i>{{ paper.journal }}</i> ({{ paper.year }}).</summary>

<p style="text-align:center;">
    <a href="{{ paper.arxivlink }}"> Arxiv link </a>
    &nbsp;
    <a href="{{ paper.githublink }}"> Github link </a>
</p>

{{ paper.content }}

</details>
<br />

{% endfor %}
