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


Jump to [Faculty](#faculty), [PostDoc Members](#postdoc-members), [PhD Students](#phd-students), [MS Students](#ms-students-cityu-1-year-msds-program), [Visiting Scholars and Onsite/Online RAs](#visiting-scholars-and-onsiteonline-ras), [Alumni](#alumni).

## Faculty
{% assign number_printed = 0 %}
{% for member in site.data.advisors %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="50%"  />
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

## PostDoc Members

{% assign number_printed = 0 %}
{% for member in site.data.postdoc23 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-md-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="50%"  />
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

{% assign number_printed = 0 %}
{% for member in site.data.phd22 %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-md-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="50%" />
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

{% if even_odd == 3 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}


***

## MS Students (CityU 1-year MSDS Program)

### Enrollment Date: 2024

{% assign number_printed = 0 %}
{% for member in site.data.ms24 %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-md-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="50%" />
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

{% if even_odd == 3 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

***

## Visiting Scholars and Onsite/Online RAs
{% assign number_printed = 0 %}
{% for member in site.data.visitors %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-md-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="50%" />
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

{% if even_odd == 3 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

***

## Alumni

### PostDoc Members
{% assign number_printed = 0 %}
{% for member in site.data.alumni_postdoc %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-md-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="50%" />
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

{% if even_odd == 3 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

***

### PhD Students
{% assign number_printed = 0 %}
{% for member in site.data.alumni_phd %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-md-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="50%" />
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

{% if even_odd == 3 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

***

### MS Students (CityU 1-year MSDS Program)
{% assign number_printed = 1 %}
{% for member in site.data.alumni_ms %}
  {% if member.info %}
    {{ number_printed }}. {{ member.name }}, {{ member.year }}, {{ member.info }}
  {% else %}
    {{ number_printed }}. {{ member.name }}, {{ member.year }}
  {% endif %}
  {% assign number_printed = number_printed | plus: 1 %}
{% endfor %}

***

### Visiting Scholars and Onsite/Online RAs
<div class="alumni-text-list">
  {% assign number_printed = 1 %}
  {% for member in site.data.alumni_scholar_ra %}
    <p class="alumni-text-item">
      {% if member.info %}
        {{ number_printed }}. {{ member.name }}, {{ member.year }}, {{ member.info }}
      {% else %}
        {{ number_printed }}. {{ member.name }}, {{ member.year }}
      {% endif %}
    </p>
    {% assign number_printed = number_printed | plus: 1 %}
  {% endfor %}
</div>


