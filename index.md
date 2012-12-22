---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

### Journal Papers
- D.N. Miller and R.A. de Callafon, “Subspace Identification with Eigenvalue
  Constraints,” accepted to Automatica, 2013.

- D.N. Miller, J. Hulett, J. McLaughlin, and R.A. de Callafon, “Thermal
  Dynamical Identification of Light-Emitting Diodes by Step-Based
  Realization and Convex Optimization,” in press, IEEE Transactions on
  Components, Packaging, and Manufacturing Technology, 2013, (preliminary
  [doi: 10.1109/TCPMT.2012.2229464](http://dx.doi.org/).

- D.N. Miller, M.J. Brenner, and R.A. de Callafon, “A Covariance-Based
  Realization Algorithm for the Identification of Aeroelastic Dynamics from
  In-Flight Data,” AIAA Journal of Guidance, Control and Dynamics, 2012,
  Vol.35: 1169-1177, [doi:
  10.2514/1.55770](http://dx.doi.org/10.2514/1.55770).
