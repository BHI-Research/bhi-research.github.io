---
hide:
  - navigation
---

# BHI-Research Group

We are a multidisciplinary research group at [Universidad Tecnológica Nacional, Facultad Regional Bahía Blanca](https://www.frbb.utn.edu.ar/), Argentina. We work on **Computer Vision**, **Machine Learning**, and **High Performance Computing**, with a focus on AI that runs on everyday hardware such as a personal computer.

[Publications](#latest-publications){ .md-button .md-button--primary }
[Projects](#projects){ .md-button }
[People](#people){ .md-button }
[GitHub](https://github.com/BHI-Research){ .md-button }

## Latest publications

### pico-JEPA v2: When Do Many Small Models Beat One Big Model?

*Original title: pico-JEPA v2: ¿Cuándo Superan Muchos Modelos Pequeños a Uno Grande?*

A. Rostagno, J. Iparraguirre, R. Briatore, A. González, S. Aggio.<br>
**CACIC 2026**, XXXII Congreso Argentino de Ciencias de la Computación, Concepción del Uruguay, Entre Ríos, Argentina, October 2026.

Instead of training one model on all the data, we train several tiny models (about 3.4 million parameters each) on separate slices and combine their predictions. When the small models are diverse and a learned meta-model combines them, the group beats the single model by +5.1 percentage points on a 30-class video classification task. The advantage disappears if each model is too small or there are too few classes.

[:material-web: Project page](https://bhi-research.github.io/pico-jepa-v2/){ .md-button }
[:material-file-document: Paper (ES)](https://github.com/BHI-Research/pico-jepa-v2/blob/main/paper/paper_pico-JEPA-v2.pdf){ .md-button }
[:material-github: Code](https://github.com/BHI-Research/pico-jepa-v2){ .md-button }
[:material-presentation: Slides (EN)](https://github.com/BHI-Research/pico-jepa-v2/blob/main/slides/pico-JEPA-v2_CACIC-2026-presentation_EN.pdf){ .md-button }
[:material-presentation: Slides (ES)](https://github.com/BHI-Research/pico-jepa-v2/blob/main/slides/pico-JEPA-v2_CACIC-2026-presentation_ES.pdf){ .md-button }

### pico-JEPA: Understanding Video with Ultra-Light Models and Collective Wisdom

*Original title: pico-JEPA: Comprendiendo el Video con Modelos Ultra-Ligeros y la Sabiduría Colectiva*

A. Rostagno, J. Iparraguirre, G. Friedrich, S. Aggio, R. Briatore, L. Tobio, D. Coca.<br>
**CACIC 2025**, XXXI Congreso Argentino de Ciencias de la Computación, Viedma, Argentina, October 2025.

A very small video model that learns without labels, combined with a voting scheme across several copies of the model to make its classifications more accurate and robust.

[:material-file-document: Paper (ES)](https://github.com/BHI-Research/pico-JEPA/blob/main/publications/pico-JEPA-paper-ES.pdf){ .md-button }
[:material-github: Code](https://github.com/BHI-Research/pico-JEPA){ .md-button }

### nano-JEPA: Democratizing Video Understanding with Personal Computers

A. Rostagno, J. Iparraguirre, J. Ermantraut, L. Tobio, S. Foissac, S. Aggio, G. Friedrich.<br>
**WASI 2024**, XXV Workshop Agentes y Sistemas Inteligentes, CACIC 2024.

A scaled-down version of a video JEPA model that can be trained and run on a personal computer instead of a large GPU cluster.

[:material-file-document: Paper](https://drive.google.com/file/d/11vOMCMP7_4FWqvXLhkEkX-7KgNgwdsij/view){ .md-button }
[:material-github: Code](https://github.com/BHI-Research/nano-jepa){ .md-button }

## Projects

All our code is open source and available on [GitHub](https://github.com/BHI-Research).

### Video understanding with small models

<div class="grid cards" markdown>

-   :material-movie-open:{ .lg .middle } **pico-JEPA v2**

    ---

    An ensemble of tiny JEPA models that can beat one bigger model, and a map of when it does.

    [:material-web: Project page](https://bhi-research.github.io/pico-jepa-v2/) ·
    [:material-github: Code](https://github.com/BHI-Research/pico-jepa-v2)

-   :material-movie-open-outline:{ .lg .middle } **pico-JEPA**

    ---

    Small JEPA models plus voting for video understanding.

    [:material-github: Code](https://github.com/BHI-Research/pico-JEPA)

-   :material-laptop:{ .lg .middle } **nano-JEPA**

    ---

    A video Joint Embedding Predictive Architecture (JEPA) that runs on a personal computer.

    [:material-github: Code](https://github.com/BHI-Research/nano-jepa)

-   :material-database:{ .lg .middle } **nano-datasets**

    ---

    Build small custom subsets of big public video datasets, so experiments fit on modest hardware.

    [:material-github: Code](https://github.com/BHI-Research/nano-datasets)

</div>

### Video summarization

<div class="grid cards" markdown>

-   :material-flash:{ .lg .middle } **Flash Video Summarization**

    ---

    A video summarization algorithm that runs faster than real time.

    [:material-github: Code](https://github.com/javierip/flash-video-summarization)

-   :material-toolbox:{ .lg .middle } **Open Summarization Toolbox**

    ---

    Tools to evaluate video summaries, in Python and C++.

    [:material-github: Python](https://github.com/BHI-Research/ost-python) ·
    [:material-github: C++](https://github.com/BHI-Research/ost)

-   :material-folder-multiple:{ .lg .middle } **OST datasets**

    ---

    A compilation of datasets widely used in video summarization research.

    [:material-github: Code](https://github.com/BHI-Research/ost-datasets)

</div>

### Optimization and parallel computing education

<div class="grid cards" markdown>

-   :material-rocket-launch:{ .lg .middle } **PSO-JAX**

    ---

    An accelerated Particle Swarm Optimization (PSO) tool built on JAX.

    [:material-github: Code](https://github.com/BHI-Research/PSO-JAX)

-   :material-school:{ .lg .middle } **Edu-PSO**

    ---

    Particle Swarm Optimization as a teaching tool for parallel processing, with Python, C++, OpenMP, CUDA and JavaScript versions.

    [:material-play-circle: Demo code](https://github.com/BHI-Research/Edu-PSO/tree/master/DEMO) ·
    [:material-github: Code](https://github.com/BHI-Research/Edu-PSO)

-   :material-human-male-board:{ .lg .middle } **Parallel Processing Teaching Toolkit**

    ---

    Examples and material for teaching parallel processing.

    [:material-github: Code](https://github.com/javierip/parallel-processing-teaching-toolkit)

</div>

## People

### Current members

* [Javier Iparraguirre](https://javierip.github.io/)
* [Guillermo Friedrich](https://github.com/guillermo-friedrich)
* [Adrián Rostagno](https://github.com/arostag)
* [Santiago Aggio](https://github.com/sancolo)
* [Roberto Briatore](https://github.com/Roberto-Briatore)
* [Agustín González](https://github.com/gonzalezagustin512-creator)

### Past members

* [Ariel Iván Díaz](https://github.com/arielivandiaz)
* [Leandro Balmaceda](https://github.com/leanbalma)
* [Joel Ermantraut](https://github.com/JoelErmantraut)
* [Lucas Tobio](https://github.com/Lucas-Tobio)
* [Segundo Foissac](https://github.com/segufoissac)
* [Tomás Crisol](https://github.com/tomascrisol)
