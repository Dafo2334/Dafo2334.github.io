---
layout: page
title: Currency Converter
description: WorldWideWallet is a currency converter app designed for travelers and frequent users of currency exchange.
img: assets/img/CProfile.png
importance: 1
category: work
---

WorldWideWallet is a currency converter app designed for travelers and frequent users of currency exchange. It features a home page displaying currency history, charts for conversion rates over time, a news page with financial updates, and a profile page for personalized user insights. Future updates will include multi-language support, an interactive map, and a social connection feature.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ConverterPage.png" title="Conversion Tool" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/CurrencyConverter.jpeg" title="Currency Trends and History" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/NewsPage.png" title="News Page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Showcasing WorldWideWallet's tools: the conversion tool, currency trends and history, and the News Page for financial updates.
</div>

The conversion tool is designed to simplify currency exchange, while the trends page offers insights into historical data for smarter decisions.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/CProfile.png" title="Full Page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Profile Page provides a personalized user experience, showing insights and usage history.
</div>

You can also put regular text between your rows of images. Each feature has been crafted with travelers in mind to enhance their financial decisions and currency management.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/DatabaseNews.png" title="Future Features: Multi-language and Interactive Map" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Future updates will include multi-language support and an interactive map for better user connectivity.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/FutureFeatures.jpg" title="Future Features: Multi-language and Interactive Map" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
