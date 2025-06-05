---
layout: page
title: Machine Learning Predictions of Wastewater Infrastructure Mapping
description: with background image
img: assets/img/SepticProcess.jpg
importance: 1
category: current
related_publications: true
---

<b>Communities:</b> California, Virginia, North Carolina

<b>Partners:</b> University of California Los Angeles, California State Water Resources Control Board, Virginia Department of Public Health

<b>Impact:</b> predicting wastewater infrastructure type nationwide

## The Challenge: A 30-Year Data Gap

We developed a machine learning model that leverages geospatial data and Random Forest algorithms to predict wastewater infrastructure in places where it is unknown. Our approach uses a two-stage method: Stage 1 identifies whether a parcel needs wastewater infrastructure at all, while Stage 2 determines whether parcels are served by onsite systems (like septic tanks) or centralized sewer connections. Through extensive testing, our model has been achieving high accuracy, suggesting that model confidence can serve as a reliable proxy for accuracy even where ground-truth data is limited.

## California Wastewater Needs Assessment

California launched the first-ever comprehensive statewater wastewater needs assessment in 2023. This four-year project, funded by the California State and Regional Water Resources Control Boards, represents an effort to evaluate the state's aging wastewater infrastructure and recognize Californians' equal and human right to sanitation. The project brings together partners from UCLA's Luskin Center for Innovation, UC Agricultural and Natural Resources Institute, Sacramento State's Office of Water Programs, and University of Massachusetts Amherst. For this project, we are leveraging our machine learning approach to generate a predictive model of wastewater infrastructure across California.

## Broader Impact

This work represents a paradigm shift in how we can understand and manage wastewater infrastructure across the United States. By combining machine learning techniques with comprehensive needs assessments, we are developing scalable solutions that can identify infrastructure gaps, prioritize investments, and ensure equitable access to sanitation services nationwide.

<b>Funding:</b>

California State Water Resources Control Board
UMass Amherst Center for Agriculture, Food and the Environment (CAFE) (USDA NIFA)
UMass Amherst Office of Research

\*_ Publications:
Preprint:
da Luz, N._, J. Taneja, E. Kumpel. Look Out Below: Predicting Wastewater Infrastructure Service Type at the Land Parcel Scale. Research Square [Preprint](https://dx.doi.org/10.21203/rs.3.rs-6656886/v1) (in review since 05/2025).

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/SepticProcess.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SepticMapping.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
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
