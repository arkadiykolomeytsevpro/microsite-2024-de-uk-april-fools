---
layout: standard
id: ending
title: New Deals
permalink: /new-deals/
nav: true
nav-order: 2
header-text: New Deals
intro: We've just launched loads more deals into our End-of-January Sale to give you even more options for your next escape. With unbelievable discounts, now's the time to book your next holiday at a bargain price.
---

<div class="page-padding text-textBlack content-spacing bg-white">
  <div class="mx-auto max-w-screen-lg py-20 text-center">
    <h2 class="h4">More new deals added to the SALE!</h2>
    <p class="text-lg">{{page.intro}}</p>
    {% include countdown.html message="The End-of-January Sale ends in:" class="text-lg" %}
  </div>
</div>

<div class="page-padding content-spacing">
  <div class="mx-auto max-w-screen-3xl pb-24">
    {% include component/se-offers.html tag="zz_UK_Blackfriday_NEW" %}
    <div class="text-center pt-12">
      <a href="{{site.baseurl}}" class="btn btn--lg">{{locale.general.back-to-deals}}</a>
    </div>
  </div>
</div>
