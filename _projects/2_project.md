---
layout: page
title: Lead in Water in Schools and Childcares
description: Research and technical assistance to measure and remediate lead in water in schools and childcares
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---

We conduct research and offer technical assistance related to monitoring and remediating lead in water in schools and childcares in Massachusetts.

Communities: schools and childcares across Massachusetts

Impact: 

*Technical Assistance*
University of Massachusetts - Amherst provides support to <a href="https://doi.org/10.1002/aws2.1358">Water-Smart</a>, a program of the Massachusetts Department of Environmental Protection (MassDEP) that engages eligible public and private schools and childcare facilities no-cost drinking water lead testing, along with access to results and solutions for elevated lead levels if found. The program launched in 2016 and is voluntary - there's no state law requiring schools to test for lead in drinking water. 

The program has shown strong participation rates. Nearly 1,300 schools and 500 childcare facilities have participated in the program,

We support this program through:
- Program design 
- Coordinating sampling of facilities
- Facilitating data communication with facilities


*Research*

We have studied which facilities are at highest risk and the factors that may help identify the schools and daycare centers at greatest risk for elevated levels of lead in drinking water. The most telling characteristic for schools in Massachusetts is building age, with facilities built in the 1960s and 1970s—nearly a third of the facilities tested—at the greatest risk for having dangerously high water lead level. 

Amery, L., Tobiason, J., Kumpel, E., 2023. Water lead levels in Massachusetts schools and early education and childcare facilities. AWWA Water Science 5, e1358. <a href="https://doi.org/10.1002/aws2.1358">https://doi.org/10.1002/aws2.1358</a>


    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/LeadInBuildings.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
