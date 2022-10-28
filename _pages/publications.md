---
title: "AML Lab - Publications"
layout: gridlay
excerpt: "AML Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

<!-- 
## Highlights
(For a full list see [below](#full-list) or go to [Google Scholar](https://scholar.google.com/citations?user=et6IhFcAAAAJ))
{% assign number_printed = 0 %}
{% for publi in site.data.publist %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}
{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>
{% assign number_printed = number_printed | plus: 1 %}
{% if even_odd == 1 %}
</div>
{% endif %}
{% endif %}
{% endfor %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
<p> &nbsp; </p>
-->

You may also see our work on [Google Scholar](https://scholar.google.com/citations?user=Nkm9r2IAAAAJ).

## Full List

### Publications in 2022

[Gromov-Wasserstein Guided Representation Learning for Cross-Domain Recommendation](https://dl.acm.org/doi/abs/10.1145/3511808.3557338)\
Xinhang Li, Zhaopeng Qiu, Xiangyu Zhao, Zihao Wang, Yong Zhang, Chunxiao Xing, Xian Wu
CIKM'22, Proceedings of the 31st ACM International Conference on Information & Knowledge Management

[Hierarchical Item Inconsistency Signal Learning for Sequence Denoising in Sequential Recommendation](https://dl.acm.org/doi/abs/10.1145/3511808.3557348)\
Chi Zhang, Yantong Du, Xiangyu Zhao, Qilong Han, Rui Chen, Li Li
CIKM'22, Proceedings of the 31st ACM International Conference on Information & Knowledge Management


[//]: # ({% for publi in site.data.publist %})

[//]: # ()
[//]: # (  {{ publi.title }} <br />)

[//]: # (  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>)

[//]: # ()
[//]: # ({% endfor %})

