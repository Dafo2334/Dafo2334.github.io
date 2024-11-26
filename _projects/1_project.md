---
layout: page
title: WorldWideWallet
description: A currency converter app for travelers with background image and giscus comments
img: assets/img/currency_converter.jpg
importance: 1
category: work
giscus_comments: true
---

WorldWideWallet is a feature-rich currency converter app designed for travelers and frequent currency users. It simplifies currency exchange and provides valuable insights through a user-friendly interface.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/app_home.jpg" title="Home Page: Currency History" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/app_chart.jpg" title="Conversion Chart" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/app_news.jpg" title="Financial News Page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    From left to right: The Home Page displaying currency history, a Conversion Chart showing rates over time, and the News Page with relevant financial updates.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/app_profile.jpg" title="User Profile Page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The User Profile Page offers a personalized experience, showing user-specific data and insights.
</div>

You can also put regular text between your rows of images.
WorldWideWallet was developed using cutting-edge technologies and focuses on providing a seamless user experience. Additional features include currency conversion charts, financial news, and user profiles.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/app_map.jpg" title="Interactive Map (Coming Soon)" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/app_future.jpg" title="Future Enhancements" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Future enhancements include an Interactive Map and features like multi-language support and connecting with friends and family.
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
