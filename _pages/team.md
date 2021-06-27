---
title: "TW's Research Group - Team"
layout: gridlay
excerpt: "TW's Research Group - Team"
sitemap: false
permalink: /team/
---

<p>We are looking for *highly self-motivated* PhD, MS, and undergraduate students joining us, doing research on **parallel and heterogeneous computing**, **electronic design automation**, and **machine learning computing algorithms**.
Please <a href="mailto:tsung-wei.huang@utah.edu">email Prof Huang</a> your resume and research interest.</p>


<!-- Faculty -->
## Faculty

<div class="row align-items-center">
  <div class="col-md-2 col-sm-2 vertical-align">
  <div style="max-width: 130px; text-align: center;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/twhuang.jpg" class="img-responsive" style="width: 100%" />
  </div>
  </div>

  <div class="col-md-8 col-sm-8">
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



<!-- Master and Undergraduate Students -->

## Master and Undergraduate Students
{% assign number_printed = 0 %}
{% for member in site.data.msbs_students %}

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



<!-- Alumni

## Alumni  -->

