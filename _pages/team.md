---
title: "TW's Research Group - Team"
layout: gridlay
excerpt: "TW's Research Group - Team"
sitemap: false
permalink: /team/
---

## Open Positions!

<p>We are looking for *highly self-motivated* PhD, MS, and undergraduate students joining us, doing research on **heterogeneous computing**, **computer-aided design**, **quantum computing**, and **machine learning systems**.
Please <a href="mailto:tsung-wei.huang@wisc.edu">email Prof Huang</a> your resume and research interest (see our [Research](/research) and [Why Join Our Team?](#why-join-our-team)). </p>

<hr>

<!-- Faculty -->
## Faculty

<div class="row align-items-center">
  <div class="col-md-2 col-sm-2 vertical-align">
  <div style="max-width: 200px; text-align: center;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/twhuang_uwm.jpg" class="img-responsive" style="width: 100%" />
  </div>
  </div>

  <div class="col-md-10 col-sm-10">
  <h4>Tsung-Wei (TW) Huang</h4>
  Associate Professor, Department of ECE and CS (affiliate)<br>
  University of Wisconsin at Madison, Madison, WI, USA, 53706<br>
  Office: Engineering Hall (EH) 3423<br>
  BS/MS (<a href="http://www.csie.ncku.edu.tw/ncku_csie/">NCKU-CS@Taiwan</a>), PhD (<a href="https://ece.illinois.edu/">UIUC-ECE@USA</a>)<br>
  <a href="mailto:tsung-wei.huang@wisc.edu"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-email.png" height=25px></a>
  <a href="{{ site.url }}{{ site.baseurl }}/resumes/twhuang_cv.pdf"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-cv.png" height=25px></a>
  <a href="https://github.com/tsung-wei-huang"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-github.jpg" height=25px></a>
  <a href="https://scholar.google.com/citations?user=ibeirYQAAAAJ&hl=en"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-scholar.jpg" height=25px></a>
  <a href="https://x.com/twh760812"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-X-black.png" height=25px></a>
  <a href="https://www.linkedin.com/in/tsung-wei-huang-44bba087/"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-linkedin.png" height=25px></a>
  <a href="https://orcid.org/0000-0001-9768-3378"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-orcid.png" height=25px></a>
  <a href="https://www.youtube.com/@dr.twhuang"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-youtube.png" height=25px></a>
  </div>
  
</div>

<div class="row align-items-center">
  <div class="col-md-12 col-sm-12 vertical-align">
  <p><span class="badge badge-dark">Bio</span> Dr. Huang is an Associate Professor in ECE at the University of Wisconsin-Madison (UW-Madison), with an affiliate appointment in CS. Previously, he was an Assistant Professor at UW-Madison (2023--2025) and University of Utah (2019--2023). He earned his PhD in ECE from UIUC (2017) and BS/MS in CS from Taiwan's NCKU (2011). His research focuses on building software systems for performance-critical applications, including CAD, machine learning, and quantum computing. His tools, such as Taskflow and OpenTimer, are widely used in industry and academia.</p>

  <p>Dr. Huang has received several awards, including the ACM SIGDA Outstanding PhD Dissertation Award, NSF CAREER Award, Humboldt Research Fellowship, ACM SIGDA Outstanding New Faculty Award, ICCAD 10-Year Most Influential Paper Award (OpenTimer), and DAC Under-40 Innovator Award. Beyond research, he is passionate about software performance and has won top 3 in multiple programming contests, such as ACM SIGDA CADathlon, TAU Timing Contest, IEEE HPEC Graph Challenge, ICCAD CAD Contest, and ACM PPoPP FCPC. Dr. Huang has served on the TPC in DAC, ICCAD, MICRO, ASPLOS, HPCA, SC, IPDPS, etc.</p>
  </div>
</div>

<hr>

<!-- PhD students -->

## PhD Students

{% assign number_printed = 0 %}
{% for member in site.data.phd_students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} </i>
  {% if member.research %}
  <p>Research: {{ member.research }}</p>
  {% endif %}
  {% if member.experience %}
  <p>Experience: {{ member.experience }}</p>
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

<!-- Master Students -->

## Master Students
{% assign number_printed = 0 %}
{% for member in site.data.ms_students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} </i>
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

<!-- Undergraduate Students -->

## Undergraduate Students
{% assign number_printed = 0 %}
{% for member in site.data.bs_students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>
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

### PhD 🎉🎉🎉

{% assign number_printed = 0 %}
{% for member in site.data.phd_alumni %}

<div class="row">
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>
  {% if member.research %}
  <p>Research: {{ member.research }}</p>
  {% endif %}
  {% if member.dissertation %}
  <p>Dissertation: {{ member.dissertation }}</p>
  {% endif %}
  <p>{{ member.experience }}</p>
</div>
</div>

{% endfor %}

### MS 🎉🎉

{% assign number_printed = 0 %}
{% for member in site.data.ms_alumni %}

<div class="row">
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>
  {% if member.research %}
  <p>Research: {{ member.research }}</p>
  {% endif %}
  {% if member.dissertation %}
  <p>Dissertation: {{ member.dissertation }}</p>
  {% endif %}
  <p>{{ member.experience }}</p>
</div>
</div>

{% endfor %}

### BS 🎉

{% assign number_printed = 0 %}
{% for member in site.data.bs_alumni %}

<div class="row">
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>
  {% if member.research %}
  <p>Research: {{ member.research }}</p>
  {% endif %}
  {% if member.dissertation %}
  <p>Dissertation: {{ member.dissertation }}</p>
  {% endif %}
  <p>{{ member.experience }}</p>
</div>
</div>

{% endfor %}


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
<li>Apply ECE/CS knowledge to solve scientific computing problems</li>
<li>Create impactful research projects and software systems</li>
<li>Become a good programmer and an independent researcher</li>
</ul>

<p>
We collaborate with many people from industry, academia, and government agencies.
You can work with people around the world to explore different research ideas.
After you leave our group, you will be ready for many job opportunities
in both software and hardware companies.
For instance, my students have been working in Nvidia, Intel, Cadence, Synopsys, IBM, Google, Huawei, etc.
</p>

<div class="row align-items-center">
  <div class="col-md-4 col-sm-4">
  <a href="https://www.nvidia.com/en-us/"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/nvidia-logo.png" style="width: 100%;"></a>
  </div>
  
  <div class="col-md-4 col-sm-4">
  <a href="https://www.intel.com/"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/intel-logo.png" style="width: 100%;"></a>
  </div>
  
  <div class="col-md-4 col-sm-4">
  <a href="https://www.cadence.com"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/cadence-logo.jpeg" style="width: 100%;"></a>
  </div>
</div>

<div class="row align-items-center">
  <div class="col-md-4 col-sm-4">
  <a href="https://www.drivevariant.com/"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/variant-logo.jpeg" style="width: 100%;"></a>
  </div>
  <div class="col-md-4 col-sm-4">
  <a href="https://www.ibm.com/en-us/"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/ibm-logo.png" style="width: 100%;"></a>
  </div>
  <div class="col-md-4 col-sm-4">
  <a href="https://www.synopsys.com/en-us/"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/synopsys-logo.jpeg" style="width: 100%;"></a>
  </div>
</div>

<div class="row align-items-center">
  <div class="col-md-4 col-sm-4">
  <a href="https://www.google.com/"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/google-logo.png" style="width: 100%;"></a>
  </div>
  <div class="col-md-4 col-sm-4">
  <a href="https://www.huawei.com/en/"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/huawei-logo.jpg" style="width: 100%;"></a>
  </div>
</div>


According to <a href="https://www.usnews.com/best-graduate-schools/top-engineering-schools/electrical-engineering-rankings">2024 US News</a>, the ECE Department of UW-Madison is ranked #9 among public universities and #15 among all universities. You will find plenty of resources to help you grow and advance your research career in our department and UW-Madison!

<center><div style="max-width: 700px">
<p><img src="{{ site.url }}{{ site.baseurl }}/images/newspic/2024-UW-Madison-ECE-Ranking.jpeg" style="max-width: 100%"></p>
</div></center>


<br>





