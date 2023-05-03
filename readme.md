=======
# Introduction
Our group will complete a C language project that only includes the <stdio.h> header file in the code. This project is part of the course CSCI3251-2023 and aims to demonstrate our skills and knowledge in C programming.

# Code

{% highlight c %}
{% include_relative code.c %}
{% endhighlight %}

![c-cpp-ci.yml](https://github.com/csci3251-2023/project-team-n/actions/workflows/c-cpp-ci.yml/badge.svg)

# Contributor

{% for stu in site.stu %}
  <img src={{stu.image}}/>
  <h2>{{ stu.user }}({{ stu.name }})</h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}

---
Last updated: {{ site.time }}
