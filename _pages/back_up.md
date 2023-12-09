---
title: "Sharing"
permalink: /sharing/
author_profile: false
sidebar:
  title: "Sample Title"
  nav: sidebar-sample
toc: true
layout: splash
hidden: true
header:
  image: /assets/images/head2.png
  actions:
    - label: "<i class='fas fa-download'></i> Install now"
      url: "/docs/quick-start-guide/"
excerpt: >
  A flexible two-column Jekyll theme. Perfect for building personal sites, blogs, and portfolios.<br />
  <small><a href="https://github.com/mmistakes/minimal-mistakes/releases/tag/4.24.0">Latest release v4.24.0</a></small>
feature_row:
  - image_path: /assets/images/news.png
    alt: "customizable"
    title: "News"
    excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
    url: "/docs/quick-start-guide/"
    btn_class: "btn--inverse"
    btn_label: "Learn more"
  - image_path: /assets/images/publications.png
    alt: "fully responsive"
    title: "Publications"
    excerpt: "Built with HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/year-archive/"
    btn_class: "btn--inverse"
    btn_label: "Learn more"
  - image_path: /assets/images/about-us.png
    alt: "100% free"
    title: "About us"
    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
    url: "/about/"
    btn_class: "btn--inverse"
    btn_label: "Learn more"      
  - image_path: /assets/images/about-us.png
    alt: "100% free"
    title: "About us"
    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
    url: "/about/"
    btn_class: "btn--inverse"
    btn_label: "Learn more"      
gallery:
  - url: /assets/images/home-s1.png
    image_path: assets/images/home-s1.png
    alt: "placeholder image 1"
  - url: /assets/images/home-s2.png
    image_path: assets/images/home-s2.png
    alt: "placeholder image 2"
  - url: /assets/images/home-s3.png
    image_path: assets/images/home-s3.png
    alt: "placeholder image 3"
  - url: /assets/images/home-s3.png
    image_path: assets/images/home-s3.png
    alt: "placeholder image 4"
---

<div> 
    <map name="hotpoint">
      <area shape="rect" coords="0,0,100,100" href="/year-archive/" target="_blank" alt="baidu">
    </map>
    <map name="hotpoint_news">
      <area shape="rect" coords="150,300,300,400" href="/year-archive/" target="_blank" alt="baidu">
    </map>
    <map name="hotpoint_research">
      <area shape="rect" coords="150,180,300,280" href="/year-archive/" target="_blank" alt="baidu">
    </map>
    <map name="hotpoint_pub">
      <area shape="rect" coords="150,230,300,330" href="/year-archive/" target="_blank" alt="baidu">
    </map>
    <img src="/assets/images/research_v1.png" width="1800" height="1200" usemap="#hotpoint_research" />
    <img src="/assets/images/news_v2.png" width="1800" height="1200" usemap="#hotpoint_news" />
    <img src="/assets/images/blank_v1.png" width="1800" height="1200"  />
    <img src="/assets/images/pub_v1.png" width="1800" height="1200" usemap="#hotpoint_pub" />
    <map name="hotpoint1">
      <area shape="rect" coords="0,0,100,100" href="/year-archive/" target="_blank" alt="baidu">
    </map>
</div>






<img src="{{ site.url }}{{ site.baseurl }}/assets/images/home-s2.png" alt="" onclick="location.href='/year-archive/'">

<a href="https://www.csdn.net/"><img src="/assets/images/home-s2.png"/></a>


[![foo](/assets/images/research_v1.png)](/news/)
[![foo](/assets/images/news_v2.png)](/news/)
[![foo](/assets/images/pub_v1.png)](/news/)


{% include feature_row %}

{% include gallery caption="This is a sample gallery to go along with this case study." %}