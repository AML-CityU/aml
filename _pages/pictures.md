---
title: "AML Lab - Pictures"
layout: piclay
excerpt: "AML Lab -- Pictures"
permalink: /pictures/
---

# AML Lab Photos

[//]: # ({% assign number_printed = 0 %})

[//]: # ({% for pic in site.data.pic %})

[//]: # ()
[//]: # ({% assign even_odd = number_printed | modulo: 1  %} )

[//]: # ()
[//]: # ({% if even_odd == 0 %})

[//]: # (<div class="row">)

[//]: # ({% endif %})

[//]: # (<div class="picpage">)

[//]: # (<p style= "text-align:center">)

[//]: # (<b>{{ pic.title }}</b><br>)

[//]: # (</p>)

[//]: # (<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/{{ pic.image }}" />)

[//]: # (</div>)

[//]: # (  )
[//]: # ({% assign number_printed = number_printed | plus: 1 %})

[//]: # (  )
[//]: # (</div>)

[//]: # ()
[//]: # ({% endfor %})

[//]: # ()
[//]: # ()
[//]: # (<p> &nbsp; </p>)




<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover" >

    <!-- Menu -->

    <ol class="carousel-indicators">

        <li data-target="#carousel" data-slide-to="0" class="active"></li>

        <li data-target="#carousel" data-slide-to="1"></li>

    </ol>


    <!-- Items -->
    <div class="carousel-inner" markdown="0">
        {% for pic in site.data.pic %}
            <div class="item">
                <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/{{ pic.image }}" />
            </div>
        {% endfor %}
    </div>


  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">

    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>

    <span class="sr-only">Previous</span>

  </a>

  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">

    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>

    <span class="sr-only">Next</span>

  </a>

</div>


[//]: # (No pictures yet. We will update our activity photos in the future.)



[//]: # (<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover" >)

[//]: # ()
[//]: # (    <!-- Menu -->)

[//]: # ()
[//]: # (    <ol class="carousel-indicators">)

[//]: # ()
[//]: # (        <li data-target="#carousel" data-slide-to="0" class="active"></li>)

[//]: # ()
[//]: # (        <li data-target="#carousel" data-slide-to="1"></li>)

[//]: # ()
[//]: # (    </ol>)

[//]: # ()
[//]: # (    <div class="carousel-inner" markdown="0">)

[//]: # ()
[//]: # (        <div class="item active">)

[//]: # ()
[//]: # (            <img src="{{ site.url }}{{ site.baseurl }}/images/homepic/cityu.jpg" alt="Slide 1" />)

[//]: # ()
[//]: # (        </div>)

[//]: # ()
[//]: # (        <div class="item">)

[//]: # ()
[//]: # (            <img src="{{ site.url }}{{ site.baseurl }}/images/homepic/cityu1.jpg" alt="Slide 2" />)

[//]: # ()
[//]: # (        </div>)

[//]: # ()
[//]: # (    </div>)

[//]: # ()
[//]: # (  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">)

[//]: # ()
[//]: # (    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>)

[//]: # ()
[//]: # (    <span class="sr-only">Previous</span>)

[//]: # ()
[//]: # (  </a>)

[//]: # ()
[//]: # (  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">)

[//]: # ()
[//]: # (    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>)

[//]: # ()
[//]: # (    <span class="sr-only">Next</span>)

[//]: # ()
[//]: # (  </a>)

[//]: # ()
[//]: # (</div>)