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


        <div class="item active">


            <div class="picpage">

                <p style= "text-align:center"><b>{{ site.data.pic[0].title }}</b><br></p>

                <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/{{ site.data.pic[0].image }}" alt="Slide 1" />

            </div>


        </div>
        {% assign start = 0 %}
        {% for pic in site.data.pic %}

        {% if start == 0 %}
        {% assign start = 1 %}
        <div class="item active">
            <div class="picpage">
                <p style= "text-align:center"><b>{{ site.data.pic[0].title }}</b><br></p>
                <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/{{ site.data.pic[0].image }}" alt="Slide 1" />
            </div>
        </div>

        {% else %}
        <div class="item">
            <div class="picpage">
                <p style= "text-align:center"><b>{{ pic.title }}</b><br></p>
                <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/{{ pic.image }}" alt="Slides" />
            </div>
        </div>

        {% endif %}
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