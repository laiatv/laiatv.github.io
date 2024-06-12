---
layout: page
title: Body in Transit
description: Exploring body perception transformation experiences through interactive sensory feedback loops
img: assets/img/3.jpg
importance: 2
category: work
---
**Years:** 2022-2023     **Location**: Universidad Carlos III de Madrid, Madrid, Spain

**In collaboration with**: [i_mBODY Lab](https://imbodylab.com/), [UCL Interaction Centre](https://www.ucl.ac.uk/uclic/ucl-interaction-centre) 

The way we perceive our body (our own body size, shape, capabilities, among others) deeply influences our behaviour, our emotions and our social interactions. Our body perception is highly plastic and can be altered through sensor-based and bodily sensory feedback interactions.

"Body in Transit" is a project funded by an ERC Consolidator Grant. It combines cognitive neuroscience, interaction design, interactive arts, and machine learning to explore and design sensory-driven changes in body perception.

In this project, I led the interaction design research efforts. My focus was on designing and evaluating various audio and haptic feedback wearables to induce desirable perceptual transformations in different groups (e.g. physically active and inactive individuals, professional dancers). Additionally, I articulated design knowledge (methods and experiential qualities) to aid in the design and evaluation of interactive experiences that transform body perception. Finally, I led collective speculation work within our multidisciplinary team to reflect on the potential personal and societal impacts of our designs in a fictitious, near future.


**PUBLICATIONS**:

**Laia Turmo Vidal**, José Vega-Cebrián, María Gastelum, Elena Márquez Segura, Judith Ley-Flores, Joaquín Díaz Durán, and Ana Tajadura-Jiménez. 2024. [Body Sensations as Design Material: An Approach to Design Sensory Technology for Altering Body Perception] (https://doi.org/10.1145/3643834.3660701). In Proc. ACM DIS, 2024.

Amar D'Adamo, Marte Roel Lesur, **Laia Turmo Vidal**, Mohammad Mahdi Dehshibi, Daniel De La Prida, Joaquín R. Diaz-Durán, Luis Antonio Azpicueta-Ruiz, Aleksander Väljamäe, and Ana Tajadura-Jiménez. 2024. [SoniWeight Shoes: Investigating Effects and Personalization of a Wearable Sound Device for Altering Body Perception and Behavior](https://doi.org/10.1145/3613904.3642651). In Proc. ACM CHI, 2024.

Judith Ley-Flores, **Laia Turmo Vidal**, Elena Márquez Segura, Aneesha Singh, Frederic Bevilacqua, Francisco Cuadrado, Joaquín Roberto Díaz Durán, Omar Valdiviezo-Hernández, Milagrosa Sánchez-Martin, and Ana Tajadura-Jiménez. 2024. [Co-Designing Sensory Feedback for Wearables to Support Physical Activity through Body Sensations] (https://doi.org/10.1145/3643499). In Proc. ACM IMWUT, 2024.

**Laia Turmo Vidal**, Ana Tajadura-Jiménez, José Manuel Vega-Cebrián, Judith Ley-Flores, Joaquin R. Díaz-Durán, and Elena Márquez Segura. 2024. [Body Transformation: An Experiential Quality of Sensory Feedback Wearables for Altering Body Perception] (https://doi.org/10.1145/3623509.3633373). In Proc. ACM TEI, 2024.

**Laia Turmo Vidal**, José Manuel Vega-Cebrián, Amar D'Adamo, Marte Roel Lesur, Mohammad Mahdi Dehshibi, Joaquín Díaz Durán, and Ana Tajadura-Jiménez. 2023. [On Futuring Body Perception Transformation Technologies: Roles, Goals and Values] (https://doi.org/10.1145/3616961.3616991) In Proc. Mindtrek, 2023. 




utilizing participatory design, soma design and speculative design approaches.
developsensory feedback loops. During my 


Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

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
