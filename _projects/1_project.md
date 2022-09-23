---
layout: page
title: BITMAP
description: aB-IniTio calculations and MAchine learning for suPerconducting collective phenomena in novel materials
img: assets/img/BITMAP_logo.jpg
importance: 1
category: research
---

Artificial intelligence and quantum materials are now revolutionizing
the way we relate to the world. The first, in its machine learning and
deep learning facets, is now present in every aspect of our lives, from
smartphones to automation in our homes. Quantum materials, obeying the
bizarre rules of quantum mechanics, promise instead to play a
fundamental role in the field of new technologies and sustainable
energies.

However, it is not easy to imagine a meeting point between these two
revolutionary spheres. Nevertheless, more and more often in recent
years, artificial intelligence and the quantum description of the world
around us have intersected, thus giving rise to new methods for studying
the microscopic behavior of matter.

Phenomena and properties such as magnetism and superconductivity owe
their origin to the way elementary particles, electrons, interact with
each other. The description of these interactions, and the
phenomenologies that emerge from them, have occupied the minds of the
best physicists for more than a century. Many theoretical models have
thus been developed, but none of them has so far been able to give a
definite answer to the "many electron problem".

**Deep Learning the Functional Renormalization Group**

One of the most versatile of these methods is the so-called functional
renormalization group, which was born on the basis of that fundamental
theoretical construction that is the renormalization group, for which
Kenneth G. Wilson won the Nobel Prize for physics in 1982. A little more
in detail, the way in which electrons "communicate" with each other is
formalized through a very large number of so-called coupled differential
equations, up to tens of millions. The latter form the essential
mathematical language of the physical interpretation of all natural
phenomena, from the movement of celestial stars, to weather forecasts,
right up to the quantum behavior of elementary particles.

Our research work has shown, for the first time, how these differential
equations can be efficiently described, and above all simplified,
through suitable neural networks that form the basis of the so-called
deep learning. Hence the title of the publication <a href='https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.129.136402'>Deep learning the
functional renormalization group</a>. Furthermore,
since the functional renormalization group provides a temporal dynamics
in the so-called *renormalization time*, which in our case is the
temperature of the interacting electron system, the problem has also
been analyzed in the context of Koopman's spectral theory, which in the
last decade it has emerged as the dominant perspective in the study of
non-linear dynamical systems.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/architecture.pdf" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/latent_space_final.pdf" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    **Left:** The deep learning architecture. **Right** Correlation matrix of the latent vectors.
</div>

The work is the result of the Marie Curie BITMAP research project,
funded by the European community under the Horizon 2020 initiative, of
which the University of Bologna is a beneficiary through the Department
of Physics. The work was carried out mainly in New York, at the
prestigious Center for Computational Quantum Physics of the Flatiron
Institute of the Simons Foundations, during the so-called outgoing phase
of the project. The main purpose of the
BITMAP project is precisely to explore possible applications of
artificial intelligence and machine learning in the context of
describing the interaction between electrons in quantum materials.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
