---
title: "AML Lab - Team"
layout: gridlay
excerpt: "AML Lab -- Team"
sitemap: false
permalink: /team/
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

# Group Members

 **We are  looking for passionate Postdocs, PhD students, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/openings) **!**


Jump to [Faculty](#faculty), [PhD students](#phd-students), [MS Students](#ms-students), [Visiting Scholars and Online RAs](#visiting-scholars-and-online-ras).

## Faculty
{% assign number_printed = 0 %}
{% for member in site.data.advisors %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}
  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

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

***

## PhD Students

### Enrollment Date: 2020

{% assign number_printed = 0 %}
{% for member in site.data.phd20 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">


  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

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

### Enrollment Date: 2021

{% assign number_printed = 0 %}
{% for member in site.data.phd21 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">


  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

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

### Enrollment Date: 2022

{% assign number_printed = 0 %}
{% for member in site.data.phd22 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">


  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

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

### Enrollment Date: 2023

{% assign number_printed = 0 %}
{% for member in site.data.phd23 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">


  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

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

***

## MS Students

### Enrollment Date: 2021

{% assign number_printed = 0 %}
{% for member in site.data.ms21 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">


  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

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

### Enrollment Date: 2022

{% assign number_printed = 0 %}
{% for member in site.data.ms22 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">


  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

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

***




## Visiting Scholars and Online RAs
{% assign number_printed = 0 %}
{% for member in site.data.visitors %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">


  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

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
