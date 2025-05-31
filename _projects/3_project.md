---
layout: page
title: Review of Attention Models
description: In-depth analysis of transformer architectures for PhD candidacy
img: assets/img/attention_models.jpg
importance: 3
category: work
related_publications: false
---

## Review of Attention Models: Transformer Architecture Analysis

**Duration:** May 2021 – August 2021  
**Institution:** Indiana University  
**Purpose:** PhD Candidacy Requirement

### Project Overview

This comprehensive research project involved conducting an in-depth analysis of transformer architectures, particularly BERT and GPT models, and their implications for modern Natural Language Processing. The review was completed as part of the PhD candidacy requirements and provided foundational knowledge for subsequent research in LLM reasoning and alignment.

### Key Focus Areas

- **Transformer Architecture Deep Dive**: Detailed analysis of the attention mechanism and its variants
- **BERT Analysis**: Comprehensive study of bidirectional encoder representations
- **GPT Model Family**: Examination of generative pre-trained transformers and their evolution
- **Modern NLP Implications**: Assessment of how these architectures transformed the field
- **Future Research Directions**: Identification of open challenges and opportunities

### Research Methodology

The review employed systematic analysis across multiple dimensions:

1. **Architectural Analysis**: Detailed examination of model components and design choices
2. **Performance Evaluation**: Comparative analysis across various NLP tasks and benchmarks
3. **Computational Efficiency**: Study of training and inference requirements
4. **Interpretability Assessment**: Analysis of attention patterns and model behavior
5. **Scalability Considerations**: Examination of how models perform at different scales

### Key Findings and Insights

- **Attention Mechanism Evolution**: Traced the development from basic attention to multi-head self-attention
- **Bidirectional vs. Autoregressive**: Comparative analysis of BERT's bidirectional approach versus GPT's autoregressive design
- **Transfer Learning Impact**: Assessment of how pre-trained transformers revolutionized NLP
- **Scaling Laws**: Early insights into the relationship between model size, data, and performance
- **Emergent Capabilities**: Identification of unexpected behaviors in large-scale models

### Technical Deep Dives

#### Attention Mechanisms
- **Self-Attention**: Mathematical foundations and computational complexity
- **Multi-Head Attention**: Parallel processing and representation learning
- **Positional Encoding**: Methods for incorporating sequence order information

#### Model Architectures
- **BERT Variants**: RoBERTa, ALBERT, DeBERTa, and architectural improvements
- **GPT Evolution**: From GPT-1 to GPT-3 and scaling considerations
- **Hybrid Approaches**: Models combining bidirectional and autoregressive elements

### Impact on Subsequent Research

This foundational review directly informed my later research directions:
- **LLM Reasoning**: Understanding of how attention patterns relate to reasoning capabilities
- **AI Alignment**: Insights into model behavior and controllability challenges
- **Interpretability**: Foundation for developing steering techniques and understanding model internals

### Academic Contributions

- **Comprehensive Literature Survey**: Systematic review of 100+ papers on transformer architectures
- **Comparative Analysis Framework**: Methodology for evaluating different architectural choices
- **Future Research Roadmap**: Identification of promising research directions that influenced subsequent work
- **PhD Candidacy Advancement**: Successfully completed candidacy requirements with distinction

### Technologies and Tools Used

- **Research Frameworks**: PyTorch, TensorFlow for model analysis
- **Evaluation Suites**: GLUE, SuperGLUE, and custom benchmarks
- **Visualization Tools**: Attention visualization and model interpretation libraries
- **Academic Resources**: Comprehensive literature review across top-tier venues

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

