---
permalink: /
title: "About me"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to Yuxiang Peng's homepage.

## **Bio**

I am an Assistant Professor in the Department of Computer Science at Purdue University. My research focuses on theoretical and practical explorations of high-assurance software toolchains for quantum computing, including programming languages, compilers, and systems. My research goal is to advance the frontier of and help common users harness the power of modern quantum computers and other emerging computing instruments in various domain problems, such as optimization.

I am actively looking for self-motivated students interested in my research directions. 

I obtained my Ph.D. at the [Department of Computer Science](https://www.cs.umd.edu/), University of Maryland, College Park in Spring 2024. I was also affiliated with the [Joint Center for Quantum Information and Computer Science](https://quics.umd.edu/). I was advised by Prof. [Xiaodi Wu](https://www.cs.umd.edu/~xwu/). 
In 2019, I received a Bachelor of Engineering from the [Institute for Interdisciplinary Information Science](https://iiis.tsinghua.edu.cn/en/), Tsinghua University, and a Bachelor of Science (double major) from the [Department of Mathematical Science](https://www.math.tsinghua.edu.cn/), Tsinghua University. In 2022, I received a Master of Science from the [Department of Computer Science](https://www.cs.umd.edu/), University of Maryland, College Park.

## **Selected Publications**

{% assign featured_publications = site.data.publications | where: "featured", true | sort: "featured_order" %}
<div class="publication-list">
  {% for publication in featured_publications %}
    {% if publication.show != false %}
      {% include publication-item.html publication=publication %}
    {% endif %}
  {% endfor %}
</div>

## **Advisees**

* Post-doc: Peiyi Li

* Ph.D.: Yu-Hsuan Wu, Yi Yu, Joel Jurado Diaz (co-advised with [Ruizhe Zhang](https://ruizhezhang.com/))

## **Teaching**

* [Fall 2026] [CS 58900 Quantum Computing](https://purdue.simplesyllabus.com/doc/ew85izopk/WL-Fall-2026-CS-%28WL%29-58900-IQC-Quantum-Computing?mode=view)

* [Spring 2026] [CS 59200 Quantum Computer Software Stacks](https://cs.purdue.edu/homes/yxpeng/QCSS/26/)

* [Fall 2025] [CS 59300 Introduction to Quantum Computing](https://www.math.purdue.edu/~esampert/IQC/) (co-taught with [Eric Samperton](https://www.math.purdue.edu/~esampert/))

## **News**

* [10/2025] An animation film that I participated in, [The Shyness of Trees](https://www.youtube.com/watch?v=aiQC-8E_7lE), received a Student Academy Award, bronze medal for animation.

{% seo %}
