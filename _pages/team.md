---
title: "TW's Research Group - Team"
layout: gridlay
excerpt: "TW's Research Group - Team"
sitemap: false
permalink: /team/
---

## Open Positions!

<p>We are looking for *highly self-motivated* PhD, MS, and undergraduate students joining us, doing research on **parallel and heterogeneous computing**, **electronic design automation**, and **machine learning computing algorithms**.
Please <a href="mailto:tsung-wei.huang@utah.edu">email Prof Huang</a> your resume and research interest (see our [Research](/research) and [Why Join Our Team?](#why-join-our-team)). </p>

<hr>

<!-- Faculty -->
## Faculty

<div class="row align-items-center">
  <div class="col-md-2 col-sm-2 vertical-align">
  <div style="max-width: 130px; text-align: center;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/twhuang.jpg" class="img-responsive" style="width: 100%" />
  </div>
  </div>

  <div class="col-md-10 col-sm-10">
  <h4>Tsung-Wei Huang</h4>
  Assistant Professor, Department of ECE<br>
  University of Utah, Salt Lake City, UT, USA, 84112<br>
  Office: 2124 Merrill Engineering Building (MEB)<br>
  BS/MS (<a href="http://www.csie.ncku.edu.tw/ncku_csie/">NCKU-CS</a>), PhD (<a href="https://ece.illinois.edu/">UIUC-ECE</a>)<br>
  <a href="https://github.com/tsung-wei-huang"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-github.jpg" height=25px></a>
  <a href="https://scholar.google.com/citations?user=ibeirYQAAAAJ&hl=en"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-scholar.jpg" height=25px></a>
  <a href="{{ site.url }}{{ site.baseurl }}/resumes/twhuang_cv.pdf"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-cv.png" height=25px></a>
  <a href="mailto:tsung-wei.huang@utah.edu"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-email.png" height=25px></a>
  <a href="https://twitter.com/twh760812"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-twitter.png" height=25px></a>
  </div>
  
</div>

<div class="row align-items-center">
  <div class="col-md-12 col-sm-12 vertical-align">
  <p><b>Bio</b>: Dr. Huang is an assistant professor in the ECE Department at the University of Utah. He received his PhD from the ECE Department at the University of Illinois at Urbana-Champaign. His research makes parallel and heterogeneous computing easier to handle, with a broad interest in scientific computing, machine learning, and design automation. He has created several open-source software (e.g., <a href="https://github.com/taskflow">Taskflow</a>, <a href="https://github.com/taskflow">OpenTimer</a>) that is being used by many people. His research is recognized by several prestigious awards, such as ACM SIGDA Outstanding PhD Dissertation Award and NSF CAREER Award.</p>
  </div>
</div>

<hr>

<!-- PhD students -->

## PhD Students

{% assign number_printed = 0 %}
{% for member in site.data.phd_students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row https://utah.zoom.us/s/2468214418">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  {% if member.research %}
  <p>Research: {{ member.research }}</p>
  <p>{{ member.experience }}</p>
  {% endif %}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


<hr>

<!-- Undergraduate Students -->

## Undergraduate Students
{% assign number_printed = 0 %}
{% for member in site.data.bs_students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row https://utah.zoom.us/s/2468214418">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  {% if member.research %}
  <p>Research: {{ member.research }}</p>
  {% endif %}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<hr>


<!-- Alumni -->

## Alumni
{% assign number_printed = 0 %}
{% for member in site.data.alumni %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row https://utah.zoom.us/s/2468214418">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  {% if member.research %}
  <p>Research: {{ member.research }}</p>
  <p>{{ member.experience }}</p>
  {% endif %}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<hr>

<!-- End of Alumni -->



## Why Join Our Team?


<p>The code of conduct in our group is to *<u>respect</u>* and 
*<u>support</u>* each other.
Hierarchy does exist but only for project management.
We solve real-world problems that matter to the society.
You will find plenty of research opportunities for a BS/MS/PhD thesis.
Specifically, in our group you will learn to:
</p>

<ul>
<li>Apply EE/CS knowledge to solve scientific computing problems</li>
<li>Create impactful research projects and software systems</li>
<li>Become a good programmer and an independent researcher</li>
</ul>

<p>
We collaborate with many people from industry, academia, and government agencies.
For instance, my students have been working in Nvidia, Intel, Cadence, IBM, etc.
You can work with people around the world to explore different research ideas.
After you leave our group, you will be ready for many job opportunities
in both software and hardware companies.</p>


<br>





