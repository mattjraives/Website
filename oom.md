---
layout: default
title: Order of Magnitude
---
The principle of order of magnitude astrophysics is scale:

My love of such problems is formented by the courses I've taken: [David Weinberg's](http://www.astronomy.ohio-state.edu/~dhw/Oom/questions.html) course in graduate school, and [E. Sterl-Phinney's](http://www.its.caltech.edu/~oom/) course as an undergrad.

{% for problem in site.problems %}
  <h2>
    <a href="{{ problem.url }}">{{ problem.title }}</a>
  </h2>
  {{ problem.excerpt }}
  <b>tags:</b> {{ problem.tags }}
{% endfor %}
