---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---
This course aims to introduce the use of containers with the goal of using them to effect reproducible computational environments. Such environments are useful for ensuring reproducible research outputs and for simplifying the setup of complex software dependencies across different systems. The course will introduce the use of Docker and Singularity containers but the material will be of use for whatever container technology you plan to, or end up, using.

> ## After completing this session you should:
> - Have an understanding of what Docker/Singularity containers are, why they are useful and the common terminology used
> - Have a working Docker installation on your local system to allow you to use containers
> - Understand how to use existing Docker containers for common tasks
> - Be able to build your own Docker/Singularity containers by understanding both the role of a Dockerfile/Singularity recipe in building containers, and the syntax used in Dockerfiles/Singularity recipes
> - Understand how to manage Docker/Singularity containers on your local system
> - Appreciate decisions that need to be made around containerising research workflows
> - Understand the differences between Docker and Singularity containers and why Singularity is more suitable for multi-user systems (e.g. HPC)
> - Appreciate issues around reproducibility in software, understand how containers can address some of these issues and what the limits to reproducibility using containers are
{: .objectives}

The material on this site corresponds to part 1 of the course - covering Docker and running on 28 and 29 Mar 2023. Part 2 of the course will look at Singularity on 4 and 5 of Apr 2023 and 
[the part 2 material is available on a separate site](https://epcced.github.io/2023-04-04_singularity-intro_online/).

{% include links.md %}

{% comment %}

TODO: systematically check for Windows-isms

<!--  LocalWords:  prereq links.md endcomment
 -->
{% endcomment %}
