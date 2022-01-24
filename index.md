---
layout: splash
excerpt: "**Panther** is an outdoor tracked robot based in ROS1 melodic. <small>Designed & made by [Raffaello Bonghi](https://rnext.it)</small>"
tagline: "An outdoor tracked robot based in ROS1 melodic.<br/> <small>Designed & made by [Raffaello Bonghi](https://rnext.it)</small>"
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/intro.jpg
  actions:
  - label: ":sparkling_heart: Sponsor"
    url: "https://github.com/sponsors/rbonghi"
intro: 
  - excerpt: ':tiger2: **Panther** is an outdoor tracked robot, with a [ZED2](https://www.stereolabs.com/zed-2/) stereocamera and an NVIDIA Jetson [AGX Xavier](https://developer.nvidia.com/embedded/jetson-agx-xavier-developer-kit), this robot can interact with all objects around it.'
feature_row:
  - image_path: /assets/images/about.jpg
    alt: "about"
    title: "ℹ️ About"
    excerpt: "Panther born in 2016 with the idea to explore huge environments outdoor"
    url: "/about/"
    btn_label: "About Panther"
    btn_class: "btn--success"
  - image_path: /assets/images/design/panther-cad.png
    alt: "design"
    title: "📐 Design"
    excerpt: "In this page an overview of all design steps, starting from the track to the frame"
    url: "/design/"
    btn_label: "How is designed"
    btn_class: "btn--warning"
  - image_path: /assets/images/navigation/Detail-Map-Panther.jpg
    alt: "navigation"
    title: "📍 Navigation"
    excerpt: "Navigation and mapping, how Panther recognize the world"
    url: "/map/"
    btn_label: "read more"
    btn_class: "btn--primary"
github:
  - excerpt: "Explore Panther GitHub. Panther is currently running on ROS melodic"
    url: "https://github.com/rpanther"
    btn_label: "GitHub"
    btn_class: "btn--success"
footer: 
  - excerpt: ':tiger2: **Panther** is proudly part of :pizza: [pizzarobotics](https://pizzarobotics.org) community'
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="github" type="center" %}

{% include video id="IjHqjM4LzU4" provider="youtube" %}

----------

{% include feature_row id="footer" type="center" %}
