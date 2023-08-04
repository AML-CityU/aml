---
title: "AML Lab - Pictures"
layout: piclay
excerpt: "AML Lab -- Pictures"
permalink: /pictures/
---

# AML Lab Photos



<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover" >


    <!-- Menu -->


    <ol class="carousel-indicators">


        <li data-target="#carousel" data-slide-to="0" class="active"></li>


        <li data-target="#carousel" data-slide-to="1"></li>


    </ol>


    <div class="carousel-inner" markdown="0">

        {% for pic in site.data.pic %}
        <div class="item">

            <div class="picpage">
                <p style= "text-align:center"><b>{{ pic.title }}</b><br></p>
                <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/{{ pic.image }}" alt="Slides" />
            </div>

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