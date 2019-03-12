# The EEECS Lego Lab

## Who We Are
The EEECS Lego Lab is a multidisciplinary space for students to develop technology enhancements aimed at improving the world around us. The model Lego city provides the facility for students to experiment with prototype solutions and realise proof of concept ideas. Projects are centred around the themes of:
* Technology enhanced living,
* Healthy days at home (supporting care and well-being of our ageing population),
* Transport,
* Smart city,
* The environment.

## Current Projects

{% assign projects = site.posts | where:"type", "project" %}

{% for post in projects %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt }}</p>
{% endfor %}

## Blog

{% assign blogs = site.posts | where:"type", "blog" %}
{% for post in blogs %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt }}</p>
{% endfor %}