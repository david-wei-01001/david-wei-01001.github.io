---
layout: post
title: Book Excerpts
date: 2024-04-11 11:31:00
description: This includes my excerpts, many of which are in Chinese
featured: true
tags: Chinese images
categories: sample-posts
thumbnail: assets/img/9.jpg
images:
  compare: true
  slider: true
toc:
  sidebar: left
  beginning: true
---

This will record my book excerpts

## Introduction

This blog records all the sentences I encountered compelling, powerful, knowledgable, thought-provoking, or led to meditation while I reading books. These are treasuries for you and for me. Let's take a cop of coffee, sit down, clear our minds, and enjoy reading.

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR2.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR1.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR3.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/AR4.jpg" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>

## Image Comparison Slider

This is a simple image comparison slider. It uses the [img-comparison-slider](https://img-comparison-slider.sneas.io/) library. Check the [examples page](https://img-comparison-slider.sneas.io/examples.html) for more information of what you can achieve with it.

<img-comparison-slider>
  {% include figure.liquid path="assets/img/prof_pic.jpg" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/prof_pic_color.png" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>
