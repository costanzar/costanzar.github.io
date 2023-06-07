---
layout: posts
title: "Codes and Data paper ventilation"
excerpt: "Description of the codes and data used for the paper 'Fast and slow response modes in the ventilation of a living computer laboratory'. "
header:
  teaser: "http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_c.jpg"
tags: 
  - sample post
  - images
  - test
---

## Codes and Data paper ventilation
Here are some useful information regarding the data and codes used in the paper 'Fast and slow response modes in the ventilation of a living computer laboratory' (add doi and information about publication). The data and codes are available here.

### CO<sub>2</sub> vs Occupancy


<figure>
	<a href="/assets/images/scatter_CO2_occupancy.pdf"><img src="/assets/images/scatter_CO2_occupancy.pdf" width="800"></a>
	<figcaption>Excess CO<sub>2</sub> concentration measurements from the sensors in the room versus the occupancy from data recorded in July 2022. The black straight line indicates the theoretical values of CO2 concentration from the steady state of the theoretical model. The red dots and line represent the measured data’s mean and linear fit.</figcaption>
</figure>

Example of equation:

$$ x = y^2 /sqrt{2} $$
#### Two Up

Apply the `half` class like so to display two images side by side that share the same caption.

```html
<figure class="half">
    <a href="/assets/images/image-filename-1-large.jpg"><img src="/assets/images/image-filename-1.jpg"></a>
    <a href="/assets/images/image-filename-2-large.jpg"><img src="/assets/images/image-filename-2.jpg"></a>
    <figcaption>Caption describing these two images.</figcaption>
</figure>
```

And you'll get something that looks like this:

<figure class="half">
	<a href="http://placehold.it/1200x600.JPG"><img src="http://placehold.it/600x300.jpg"></a>
	<a href="http://placehold.it/1200x600.jpeg"><img src="http://placehold.it/600x300.jpg"></a>
	<figcaption>Two images.</figcaption>
</figure>

#### Three Up

Apply the `third` class like so to display three images side by side that share the same caption.

```html
<figure class="third">
	<img src="/images/image-filename-1.jpg">
	<img src="/images/image-filename-2.jpg">
	<img src="/images/image-filename-3.jpg">
	<figcaption>Caption describing these three images.</figcaption>
</figure>
```

And you'll get something that looks like this:

<figure class="third">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<figcaption>Three images.</figcaption>
</figure>
