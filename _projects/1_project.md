---
layout: page
title: Text2Graph
description: Semantic role labeling pipeline for knowledge graph construction
img: assets/img/text2graph.jpg
importance: 1
category: work
related_publications: false
---

## Text2Graph: Semantic Role Labeling for Knowledge Graph Construction

**Duration:** January 2019 – May 2023  
**Institution:** Indiana University

### Project Overview

Text2Graph is a comprehensive semantic role labeling pipeline designed to extract pseudo-Abstract Meaning Representations (AMRs) from unstructured text, enabling knowledge graph construction at scale. This project represents a significant advancement in automated knowledge extraction and graph-based text understanding.

### Key Contributions

- **Semantic Role Labeling Pipeline**: Developed a robust system for identifying semantic roles and relationships within natural language text
- **Pseudo-AMR Extraction**: Created methods to generate AMR-like representations that capture the semantic structure of sentences
- **Scalable Architecture**: Designed the system to handle large-scale text processing for knowledge graph construction
- **Knowledge Graph Integration**: Enabled seamless conversion from textual data to structured graph representations

### Technical Approach

The Text2Graph pipeline combines state-of-the-art natural language processing techniques with graph-based representations:

1. **Text Preprocessing**: Advanced tokenization and linguistic analysis
2. **Semantic Role Identification**: Machine learning models for role classification
3. **Relationship Extraction**: Automated detection of semantic relationships
4. **Graph Construction**: Conversion of semantic structures to knowledge graphs
5. **Scalability Optimization**: Efficient processing for large text corpora

### Impact and Applications

This work has significant implications for:
- **Information Extraction**: Automated knowledge discovery from text
- **Question Answering Systems**: Enhanced understanding of textual content
- **Knowledge Base Construction**: Scalable methods for building structured knowledge
- **Semantic Search**: Improved text understanding for search applications

### Technologies Used

- **Natural Language Processing**: Advanced NLP libraries and frameworks
- **Graph Processing**: Specialized tools for knowledge graph manipulation
- **Machine Learning**: Custom models for semantic role classification
- **Scalable Computing**: Distributed processing for large-scale text analysis

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
