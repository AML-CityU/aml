---
title: "AML Lab - Pictures"
layout: piclay
excerpt: "AML Lab -- Pictures"
permalink: /pictures/
---

# Pictures
No pictures yet. We will update our activity photos in the future.


<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover" >
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">
        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/homepic/cityu.jpg" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/homepic/cityu1.jpg" alt="Slide 2" />
        </div>
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

[//]: # (Jump to: [Leiden]&#40;#leiden&#41;, [ETHZ]&#40;#ethz&#41;, [Cornell]&#40;#cornell&#41;, [St Andrews]&#40;#st-andrews&#41;)


[//]: # (## Leiden)

[//]: # (#### Timelapse of our STM assembling [&#40;see LION news item&#41;]&#40;https://www.physics.leidenuniv.nl/index.php?id=11573&news=867&type=lion&ln=EN&#41;:)

[//]: # (<iframe width="560" height="315" src="https://www.youtube.com/embed/3iKvUMv1h5A" frameborder="0" allowfullscreen></iframe>)

[//]: # ()
[//]: # (#### Gallery)

[//]: # (&#40;Right-click *'view image'* to see a larger image.&#41;)

[//]: # ({% assign number_printed = 0 %})

[//]: # ({% for pic in site.data.pictures_Leiden %})

[//]: # ()
[//]: # ({% assign even_odd = number_printed | modulo: 4 %})

[//]: # ()
[//]: # ({% if even_odd == 0 %})

[//]: # (<div class="row">)

[//]: # ({% endif %})

[//]: # ()
[//]: # (<div class="col-sm-3 clearfix">)

[//]: # (<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />)

[//]: # (</div>)

[//]: # ()
[//]: # ({% assign number_printed = number_printed | plus: 1 %})

[//]: # ()
[//]: # ({% if even_odd > 2 %})

[//]: # (</div>)

[//]: # ({% endif %})

[//]: # ()
[//]: # ()
[//]: # ({% endfor %})

[//]: # ()
[//]: # ({% assign even_odd = number_printed | modulo: 4 %})

[//]: # ({% if even_odd == 1 %})

[//]: # (</div>)

[//]: # ({% endif %})

[//]: # ()
[//]: # ({% if even_odd == 2 %})

[//]: # (</div>)

[//]: # ({% endif %})

[//]: # ()
[//]: # ({% if even_odd == 3 %})

[//]: # (</div>)

[//]: # ({% endif %})

[//]: # ()
[//]: # (<p> &nbsp; </p>)

[//]: # ()
[//]: # (First advertisement.)

[//]: # (<figure>)

[//]: # (<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageLeiden_red.jpg" width="60%" >)

[//]: # (</figure>)

[//]: # ()
[//]: # ()
[//]: # (## ETHZ)

[//]: # (From the [group of Andreas Wallraff]&#40;http://www.qudev.ethz.ch/&#41;.)

[//]: # (<figure>)

[//]: # (<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageETH_red.jpg" width="60%">)

[//]: # (</figure>)

[//]: # ()
[//]: # (## Cornell)

[//]: # (From the [group of Seamus JC Davis]&#40;http://davisgroup.lassp.cornell.edu&#41;.)

[//]: # (<figure>)

[//]: # (<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageCornell_red.jpg" width="60%">)

[//]: # (</figure>)

[//]: # ()
[//]: # (## St Andrews)

[//]: # (From the [group of Felix Baumberger]&#40;http://dqmp.unige.ch/baumberger/&#41; &#40;now at University of Geneva&#41;.)

[//]: # (<figure>)

[//]: # (<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageSTA_red.jpg" width="60%">)

[//]: # (</figure>)

