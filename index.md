---
---

# **About US**

We are a research team within the [Department of Green Technology](https://www.sdu.dk/en/igt) at the Faculty of Engineering, University of Southern Denmark. Our research focuses on:
- **Metabolic patterns and drivers of different societal systems**
- **Sustainability implications of sociometabolic transitions**
- **Spatially and technologically refined stocks and flows analysis**

We concentrate exclusively on the following areas:
- **Nourish**
- **Clean**
- **Transport & Communication**
- **Reside & Work**

![Overview Image](images/overview.png)


{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research_overview.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/group_picture.jpeg"
  link="team"
  title="Our Team"
  text=text
%}
