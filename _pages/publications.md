---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

The full list my publications is available [here](https://ui.adsabs.harvard.edu/search/q=author%3A%22Toscano%2C%20Teresa%22&sort=date%20desc%2C%20bibcode%20desc&p_=0){:target="_blank"}.

## 2022
---

{% for publi in site.data.publications %}

 <strong> {{ publi.title }} </strong> <br />
 <span style="color:grey"> <em>{{ publi.month }} {{ publi.year }},  {{ publi.journal }}, {{ publi.volume }}, {{ publi.pages }} </em> </span> <br />
  <em>{{ publi.authors }} </em><br /> <a href="{{ publi.url }}"> DOI: {{ publi.doi }}</a>
 
{% endfor %}

