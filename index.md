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

## Software
The interesting stuff:
- [stepalize](http://www.github.com/dnmiller/stepalize): A robust method for building linear, time-invariant models from step responses. It can also support eigenvalue constraints via semidefinite programs. The meaty details and an interesting application can be found in the publication "Thermal Dynamical Identification of Light-Emitting Diodes by Step-Based Realization and Convex Optimization."

- [RBIS](http://www.github.com/dnmiller/rbis): Some realization-based methods for building linear, time-invariant models form arbitrary input-output data using some results from classical realization theory. 

## Publications

### Book Chapters

- D.N. Miller and R.A. de Callafon, “Identification of Linear Discrete-Time
  Filters via Realization,” Linear Algebra – Theorems and Applications, H.
  Yasser, Ed. InTech: 2012, [doi:
  10.5772/3107](http://dx.doi.org/10.5772/3107).

### Journal Papers

- D.N. Miller and R.A. de Callafon, “Subspace Identification with Eigenvalue
  Constraints,” accepted to Automatica, 2013.

- D.N. Miller, J. Hulett, J. McLaughlin, and R.A. de Callafon, “Thermal
  Dynamical Identification of Light-Emitting Diodes by Step-Based
  Realization and Convex Optimization,” in press, IEEE Transactions on
  Components, Packaging, and Manufacturing Technology, 2013, (preliminary)
  [doi: 10.1109/TCPMT.2012.2229464](http://dx.doi.org/).

- D.N. Miller, M.J. Brenner, and R.A. de Callafon, “A Covariance-Based
  Realization Algorithm for the Identification of Aeroelastic Dynamics from
  In-Flight Data,” AIAA Journal of Guidance, Control and Dynamics, 2012,
  Vol.35: 1169-1177, [doi: 10.2514/1.55770](http://dx.doi.org/10.2514/1.55770).

### Selected Conference Proceedings 

- D.N. Miller, M.J. Brenner, and R.A. de Callafon, “Eigenvalue Constraints
  for Realization-Based Identification,” AIAA Atmospheric Flight Mechanics
  Conference, Minneapolis, MN: August 2012, [doi:
  10.2514/6.2012-4951](http://dx.doi.org/10.2514/6.2012-4951).

- D.N. Miller and R.A. de Callafon, “Identification of Linear Time-Invariant
  Systems Via Constrained Step-Based Realization ,” 16th IFAC Symposium on
  System Identification, Brussels, Belgium: July 2012, [doi:
  10.3182/20120711-3-BE-2027.00144](http://dx.doi.org/10.3182/20120711-3-BE-2027.00144).

- D.N. Miller and R.A. de Callafon, “Efficient Identification of Input
  Dynamics for Correlation Function-Based Subspace Identification,” Proc. of
  the 18th World Congress of the International Federation of Automatic
  Control, Milan, Italy: August 2011, [doi:
  10.3182/20110828-6-IT-1002.02597](http://dx.doi.org/10.3182/20110828-6-IT-1002.02597).

- D.N. Miller, R.A. de Callafon, and M.J. Brenner, “A Covariance-Based
  Realization Algorithm for the Identification of Aeroelastic Dynamics from
  In-Flight Data,” Proc. of the AIAA Atmospheric Flight Mechanics
  Conference, Portland, OR: August 2011.

- T.L. Paez, S.L. Lacy, V. Babuska, and D.N. Miller, “Improved Stochastic
  Process Models for Linear Structure Behavior,” Proc. of the 2011 American
  Controls Conference, pp. 42-47, San Francisco, CA: June 2011.

- D.N. Miller and R.A. de Callafon, "Subspace Identification Using Dynamic
  Invariance in Shifted Time-Domain Data,” Proc. of the 49th IEEE Conference
  on Decision and Control, Atlanta, GA: December 2010, [doi:
  10.1109/CDC.2010.5717151](http://dx.doi.org/10.1109/CDC.2010.5717151).

- R.A. de Callafon, D.N. Miller, J. Zeng, and M.J. Brenner, "Covariance
  Function Realization Algorithms for Aeroelastic Dynamic Modeling," Proc.
  of the AIAA Atmospheric Flight Mechanics Conference, Toronto, Canada:
  August 3, 2010, (doi: 10.2514/6.2010-7800).

- R.A. de Callafon, D.N. Miller, J. Zeng, and M.J. Brenner, "Step-Based
  Experiment Design and System Identification for Aeroelastic Dynamic
  Modeling," Proc. of the AIAA Atmospheric Flight Mechanics Conference,
  Chicago, IL: August 12, 2009.

- D.N. Miller and R.A. de Callafon, "Subspace Identification from Classical
  Realization Methods," Proc. of the 15th IFAC Symposium on System
  Identification, Saint-Malo, France: July 2009, (doi:
  10.3182/20090706-3-FR-2004.00016).

- N. Delson, T. Hanak, K. Loewke, and D.N. Miller, "Modeling and
  implementation of McKibben actuators for a hopping robot," Proc. of the
  International Conference on Advanced Robotics, Seattle, WA: July 2005.
  (Best Paper Finalist)
