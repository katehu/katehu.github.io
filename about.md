---
layout: page
permalink: /about/index.html
title: Kate Hu
tags: 
imagefeature: fourseasons.jpg
chart: true
---
<figure>
  <img src="{{ site.url }}/images/katehu-2015.jpg" alt="Kate" style="width: 50%; height: 50%"/>
  <figcaption>Kate Hu</figcaption>
</figure>

{% assign total_words = 0 %}
{% assign total_readtime = 0 %}
{% assign featuredcount = 0 %}
{% assign statuscount = 0 %}

{% for post in site.posts %}
    {% assign post_words = post.content | strip_html | number_of_words %}
    {% assign readtime = post_words | append: '.0' | divided_by:200 %}
    {% assign total_words = total_words | plus: post_words %}
    {% assign total_readtime = total_readtime | plus: readtime %}
    {% if post.featured %}
    {% assign featuredcount = featuredcount | plus: 1 %}
    {% endif %}
{% endfor %}


 **Kate Hu** is a National Research Service Award postdoctoral fellow at Harvard University, developing causal inference methods that leverage auxiliary information embedded in time series and spatial data to adjust for unmeasured and mismeasured confounding, and applying them to impact studies of climate change.
 
Before returning to academia, Dr. Kate Hu was the Head of Data Science at Aclima Inc, where she drives the company’s data science research and development to deliver hyper-local air pollution maps and insights at unprecedented block-by-block resolution, by dispatching a fleet of vehicles equppied with environmental sensors. This environmental “big data” fills a big gap in what policymakers and activists rely on to bring environmental justice to underserved communities.  Prior to joining Aclima Inc, Dr. Kate Hu was a senior quantitative researcher at the Climate Corporation, innovating precision agriculture solutions to help farmers maximize the economical return and adapt to climate change.  She first led the research program in sampling and experimental designs to collect field data scientifically for model calibration and evaluation. Then she led the interdisciplinary research efforts to develop precision nitrogen treatment algorithms that respond to local environmental and climate change,  by combining mechanistic models, statistical models, and new sensing technologies. 

Kate graduated with First Class Honours from the University of Hong Kong, received an M.S. from Harvard University, and obtained a Ph.D. in Biostatistics from the University of Washington, Seattle. Her PhD dissertation is A Z-estimation System for Semiparametric Models with Two-phase Sampling Designs under the guidance of Norman Breslow, Jon Wellner, and Gary Chan. 
 

 <!---
It currently has {{ site.posts | size }} posts in {{ site.categories | size }} categories which combinedly have {{ total_words }} words, which will take an average reader ({{ site.wpm }} WPM) approximately <span class="time">{{ total_readtime }}</span> minutes to read. 

{% if featuredcount != 0 %}There are <a href="{{ site.url }}/featured">{{ featuredcount }} featured posts</a>, you should definitely check those out.{% endif %} The most recent post is {% for post in site.posts limit:1 %}{% if post.description %}<a href="{{ site.url }}{{ post.url }}" title="{{ post.description }}">"{{ post.title }}"</a>{% else %}<a href="{{ site.url }}{{ post.url }}" title="{{ post.description }}" title="Read more about {{ post.title }}">"{{ post.title }}"</a>{% endif %}{% endfor %} which was published on {% for post in site.posts limit:1 %}{% assign modifiedtime = post.modified | date: "%Y%m%d" %}{% assign posttime = post.date | date: "%Y%m%d" %}<time datetime="{{ post.date | date_to_xmlschema }}" class="post-time">{{ post.date | date: "%d %b %Y" }}</time>{% if post.modified %}{% if modifiedtime != posttime %} and last modified on <time datetime="{{ post.modified | date: "%Y-%m-%d" }}" itemprop="dateModified">{{ post.modified | date: "%d %b %Y" }}</time>{% endif %}{% endif %}{% endfor %}. The last commit was on {{ site.time | date: "%A, %d %b %Y" }} at {{ site.time | date: "%I:%M %p" }} [UTC](http://en.wikipedia.org/wiki/Coordinated_Universal_Time "Temps Universel Coordonné").
***This is the space to create.*** 
-->

