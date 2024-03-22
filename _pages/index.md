---
layout: standard
id: all
title: All Sale Deals
nav: true
nav-order: 1
header-content: >
  <h1 class="h--banner">
    {{site.title}}
  </h1>
---

<div class="page-padding text-textBlack content-spacing bg-white">
  <div class="mx-auto max-w-screen-lg py-20 text-center">
    <h2 class="h5">Hello! I'm DE version.</h2>
    <p class="text-lg">{{site.description}}</p>
    <p class="text-lg font-bold">Browse our inspiring collections or scroll down for more offers to find a bargain escape you can't refuse!</p>
    <!-- {% include countdown.html message="Sale ends in:" class="text-lg" %} -->
  </div>
</div>

<div class="page-padding content-spacing">
  <div class="mx-auto max-w-screen-3xl pb-24">
    {% include component/se-offers.html tag="zz_blackfridayUK" %}
  </div>
</div>
