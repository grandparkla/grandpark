---
title: Areas of the park
permalink: /areas/
---

<nav markdown="1">
* [Plan your visit](/visit/)
</nav>

{% if site.use_illustrations %}
<style>
.illustration {
  grid-column: -3/-1;
  grid-row: 3/6;
}
.illustration svg {
  height: 17vmax;
  width: auto;
}
main h1 {
  grid-column-end: -3;
}
main h1 + p,
main h1 + p + nav {
  grid-column-end: -3;
}
main > nav:first-child {
  grid-row-start: 1;
}
main > h1 + nav {
  grid-column-end: -3;
  align-self: start;
}

nav + figure {
  width: calc(100vw - 3em);
  height: calc(100vw - 3em);
  border-radius: 50%;
}
nav + figure img {
  display: block;
  width: calc(100vw - 3.75em);
  height: calc(100vw - 3.75em);
  object-fit: cover;
  border-radius: 50%;
  max-width: none;
}
@media (min-width: 60em) {
  nav + figure {
    width: auto;
    height: auto;
    grid-column: -3/-1;
    grid-row: 3/6;
    justify-self: end;
    align-self: start;
    margin-bottom: 0;
    margin-top: -1.5em;
  }
  nav + figure img {
    width: 25vw;
    height: 25vw;
  }
}
@media (min-width: 80em) {
  nav + figure {
    margin-right: 5vw;
    grid-row: 2/6;
  }
  nav + figure img {
    width: calc(2/8 * 100vw - 3em);
    height: calc(2/8 * 100vw - 3em);
  }
}
</style>

{% comment %}
<div class="illustration">
{% include backgrounds/palm-trees.svg %}
</div>
{% endcomment %}
{% endif %}

<style media="false">
@media (min-width: 60em) {
  body > main > figure:first-of-type {
    grid-column: 1/-1;
    margin-left: -1.5em;
    margin-right: -1.5em;
    margin-top: 0;
    margin-bottom: 0;
  }
  /*
  body > main > figure:first-of-type img {
    height: 50vw;
    object-fit: cover;
    object-position: bottom;
  }
  */
</style>

<style media="false">
@media (min-width: 60em) {
  body > main > figure:first-of-type {
    grid-column: 1/-1;
    grid-row: 1/4;
    margin-left: -1.5em;
    margin-right: -1.5em;
    margin-top: -15.5em;
    position: relative;
    z-index: -1;
  }
  body > main > figure:first-of-type::after {
    content: "";
    background-image: linear-gradient(to top, hsla(0, 0%, 0%, 0.25) 25%, hsla(0, 0%, 0%, 0.25) 25%, hsla(0, 0%, 0%, 0));
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
  body > main > figure:first-of-type img {
    width: 100%;
    height: calc(100vh + 1.5rem);
    min-height: 50vw;
    object-fit: cover;
  }
  body > main > nav:first-of-type {
    grid-row: 1/2;
    position: relative;
    z-index: 2;
    color: var(--snow);
    align-self: start;
  }
  body > main > h1:first-of-type {
    grid-row: 2/3;
    position: relative;
    z-index: 1;
    color: var(--snow) !important;
    align-self: start;
  }
  body > .sun {
    display: none;
  }
}
</style>

<style>
body > main > main > h2 {
  grid-column: 3/6;
  justify-self: start;
  text-align: left;
  margin-left: 0;
}
body > main > main > h2 + nav {
  margin-top: 0;
}
body > main > main > h2 + nav {
  grid-column: 3/6;
}
body > main > main > h2 small {
  font-style: italic;
  font-weight: normal;
}
body > main > main > h2 small[class] {
  margin-top: 0.75em;
  display: block;
  font-size: 0.6666666667em;
}
</style>

Areas of the park
========

<!--
<p style="max-width: 25em">All areas of the park are open daily. Just drop by for a picnic or a splash!</p>
-->

{% comment %}
<nav markdown="1">
* [Park areas](#list)
* [Map](#map)
</nav>
{% endcomment %}

{% comment %}
<figure>
  <img src="/assets/temporary/misc/2017_11_4_17_GrandAveArts2017_Javier_Guillen-17.jpg" alt="Photo 1"   height="500" />
</figure>
{% endcomment %}

<main markdown="1" class="lime" id="list" style="background: transparent;">

<h2>
  <small>Between</small>
  Grand Avenue
  <small>and</small>
  Hill Street
  <small class="avoid-break">(Close to The Music Center)</small>
</h2>



<nav markdown="1">
*   [Fountain Overlook](https://www.google.com/maps/@34.0566769,-118.2473678,3a,75y,268.99h,90t/data=!3m8!1e1!3m6!1sAF1QipOSqCkOrYhHvAlE7jz5qoGyWozxBXV-QTyqa-6m!2e10!3e11!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipOSqCkOrYhHvAlE7jz5qoGyWozxBXV-QTyqa-6m%3Dw203-h100-k-no-pi-0-ya268.77747-ro0-fo100!7i4096!8i2048)
*   [Splash Pad](/splash-pad/)
*   [Coffee Shop](https://www.starbucks.com/store-locator/store/69543/grand-1st-grand-park-217-n-hill-street-los-angeles-ca-900122705-us)
*   [Olive Court](https://www.google.com/maps/@34.0561469,-118.2465843,3a,75y,0.88h,90t/data=!3m8!1e1!3m6!1sAF1QipML2RPHAvc5P25ps6isJAc5SGGdWFYnQUH99Hwh!2e10!3e11!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipML2RPHAvc5P25ps6isJAc5SGGdWFYnQUH99Hwh%3Dw203-h100-k-no-pi-0-ya318.72827-ro-0-fo100!7i8704!8i4352)
*   [Performance Lawn](/performance-lawn/)
*   [Gardens](/gardens/)
</nav>

## <small>Between</small> Hill Street <small>and</small> Broadway

<nav markdown="1">
*   [Community Terrace](https://www.google.com/maps/@34.0552361,-118.245177,3a,75y,17.44h,81.6t/data=!3m8!1e1!3m6!1sAF1QipPtp9sNgxC3pehPweyL_lLNWCBea8eshiLT6wmy!2e10!3e11!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipPtp9sNgxC3pehPweyL_lLNWCBea8eshiLT6wmy%3Dw203-h100-k-no-pi-0-ya72.9286-ro-0-fo100!7i6912!8i3456)
*   [Flag Garden](https://www.google.com/maps/place/Court+of+Historic+American+Flags/@34.0550793,-118.2450466,19.38z/data=!4m12!1m6!3m5!1s0x80c2c64efa935b59:0x77b7e277c784395f!2sGrand+Park+Playground!8m2!3d34.0542522!4d-118.2443347!3m4!1s0x80c2c64e59103b2f:0x2b959dd34791344c!8m2!3d34.0550556!4d-118.2448532)
*   [Metro Station](https://www.google.com/maps/@34.0554164,-118.2453169,3a,75y,160.93h,79.88t/data=!3m8!1e1!3m6!1sAF1QipP6PYGlHXiASxoeXr9EeGZAdRxEvxrGJwxf8Atg!2e10!3e11!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipP6PYGlHXiASxoeXr9EeGZAdRxEvxrGJwxf8Atg%3Dw203-h100-k-no-pi-0-ya75.437515-ro-0-fo100!7i6912!8i3456)
</nav>

## <small>Between</small> Broadway <small>and</small> Spring Street <small class="avoid-break">(Close to City Hall)</small>

<nav markdown="1">
*   [Event Lawn](https://www.google.com/maps/@34.0544049,-118.2440014,3a,75y,115.14h,90t/data=!3m8!1e1!3m6!1sAF1QipM0DHAIwelTkFxdqyPziAa69fl2YvFrvEGPrZs!2e10!3e11!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipM0DHAIwelTkFxdqyPziAa69fl2YvFrvEGPrZs%3Dw203-h100-k-no-pi-0-ya129.52591-ro0-fo100!7i8000!8i4000)
*   [Playground](/playground/)
*   [Restrooms](https://www.google.com/maps/place/Grand+Park+Restrooms/@34.0542376,-118.2442947,19.47z/data=!4m12!1m6!3m5!1s0x80c2c64efa935b59:0x77b7e277c784395f!2sGrand+Park+Playground!8m2!3d34.0542522!4d-118.2443347!3m4!1s0x80c2c64ee1ccdb15:0xa8dd350b3a605e37!8m2!3d34.0539567!4d-118.2439506)
*   [Marketplace](https://www.google.com/maps/@34.0540165,-118.2437182,3a,75y,89.22h,90t/data=!3m8!1e1!3m6!1sAF1QipPxDlDYHxAb98V4h_NMhSLrSd8502jzoHFixVhH!2e10!3e11!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipPxDlDYHxAb98V4h_NMhSLrSd8502jzoHFixVhH%3Dw203-h100-k-no-pi-0-ya47.057156-ro-0-fo100!7i8704!8i4352)
*   [Off-leash Dog Run](/dog-run/)
</nav>

<div></div>
<div></div>
<div></div>

</main>
<main markdown="1" class="lime-light">

* * *

## <a id="map"></a> Map of the Park

<div></div>

<figure style="max-width: 35em; justify-self: center;">
<a href="/assets/images/map.png">
  <img src="/assets/images/map.png" height="300" style="width: 35em; height: auto; max-width: 100%" alt="Map of Grand Park" />
</a>
</figure>



</main>



{% comment %}



<figure>
<div data-aspect-ratio-landscape="2/1" data-aspect-ratio="1/1">
<a href="https://www.google.com/maps/place/Grand%20Park%20LA/@34.056329,-118.246771,16z/data=!4m5!3m4!1s0x0:0xebf5893d7caaf0de!8m2!3d34.0563289!4d-118.2467713?ll=34.056329,-118.246771&z=16&t=m&hl=en-US&gl=US&mapclient=embed&cid=17002646865384763614" class="has-icon">
<!--
<picture>
<source srcset="/images/grand-park-on-google-maps-1280x640.png 1280w" sizes="100vw" media="(min-aspect-ratio: 1/1)"/>
<source srcset="/images/grand-park-on-google-maps-1280x1280.png 1280w" sizes="100vw" />
<img src="/images/grand-park-on-google-maps-1280x1280.png" width="1000" alt="" />
</picture>
-->
<!-- Jim’s Google Maps API key -->
<picture>
<source srcset="https://maps.googleapis.com/maps/api/staticmap?center=34.056329,-118.246771&amp;markers=size:mid%7Ccolor:0xff0000%7Clabel:%7C34.056329,-118.246771&amp;zoom=16&amp;size=640x320&amp;scale=2&amp;key=AIzaSyBP5KxqO9v1sLhXlkrG3vDiDdOJvYLJ0H4 640w, https://maps.googleapis.com/maps/api/staticmap?center=34.056329,-118.246771&amp;markers=size:mid%7Ccolor:0xff0000%7Clabel:%7C34.056329,-118.246771&amp;zoom=16&amp;size=640x320&amp;scale=2&amp;key=AIzaSyBP5KxqO9v1sLhXlkrG3vDiDdOJvYLJ0H4 1280w" sizes="100vw" media="(min-aspect-ratio: 1/1)"/>
<source srcset="https://maps.googleapis.com/maps/api/staticmap?center=34.056329,-118.246771&amp;markers=size:mid%7Ccolor:0xff0000%7Clabel:%7C34.056329,-118.246771&amp;zoom=16&amp;size=640x640&amp;key=AIzaSyBP5KxqO9v1sLhXlkrG3vDiDdOJvYLJ0H4 640w, https://maps.googleapis.com/maps/api/staticmap?center=34.056329,-118.246771&amp;markers=size:mid%7Ccolor:0xff0000%7Clabel:%7C34.056329,-118.246771&amp;zoom=16&amp;size=640x640&amp;scale=2&amp;key=AIzaSyBP5KxqO9v1sLhXlkrG3vDiDdOJvYLJ0H4 1280w" sizes="100vw" />
<img src="https://maps.googleapis.com/maps/api/staticmap?center=34.056329,-118.246771&amp;markers=size:mid%7Ccolor:0xff0000%7Clabel:%7C34.056329,-118.246771&amp;zoom=16&amp;size=640x640&amp;key=AIzaSyBP5KxqO9v1sLhXlkrG3vDiDdOJvYLJ0H4" height="200" alt="" />
</picture>
<span class="icon">
<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="20" height="20" viewBox="0 0 20 20">
<path fill="black" d="M17.9,2.4c-0.1-0.2-0.2-0.3-0.4-0.4C17.5,2,17.4,2,17.3,2h-5.8c-0.4,0-0.7,0.3-0.7,0.7s0.3,0.7,0.7,0.7h4.1
L10.9,8c-0.3,0.3-0.3,0.7,0,1c0.1,0.1,0.3,0.2,0.5,0.2c0.2,0,0.4-0.1,0.5-0.2l4.6-4.6v4.1c0,0.4,0.3,0.7,0.7,0.7
c0.4,0,0.7-0.3,0.7-0.7V2.7C18,2.6,18,2.5,17.9,2.4z"/>
<path fill="black" d="M9.1,10.9c-0.3-0.3-0.7-0.3-1,0l-4.6,4.6v-4.1c0-0.4-0.3-0.7-0.7-0.7S2,11.1,2,11.5v5.8
c0,0.1,0,0.2,0.1,0.3c0.1,0.2,0.2,0.3,0.4,0.4C2.5,18,2.6,18,2.7,18h5.8c0.4,0,0.7-0.3,0.7-0.7c0-0.4-0.3-0.7-0.7-0.7H4.5L9.1,12
C9.3,11.7,9.3,11.2,9.1,10.9z"/>
</svg>
</span>
<span class="credit">Grand Park on Google Maps</span>
</a>
</div>
</figure>





<figure>
  <a href="/assets/images/map.png">
    <img src="/assets/images/map.png" height="300" alt="Map of Grand Park" />
  </a>
</figure>

Located in Downtown L.A.’s Bunker Hill neighborhood at the crossroads of Little Tokyo, Historic Core, Union Station, Chinatown and Olvera Street, Grand Park provides all Angelenos a central gathering place to relax, celebrate and connect.

Grand Park spans four city blocks in downtown Los Angeles between The Music Center and City Hall and features distinct amenities, including:

*   Arthur J. Will Memorial Fountain with a quarter inch splash pad and jets open for play
*   Expansive lawns that include tables and chairs ideal for picnics, relaxing and gatherings
*   24 gardens featuring plants that grow in the world’s six floristic kingdoms
*   Off-leash dog run
*   On-site Metro and Purple Lines
*   Playground with 12-foot tube slide<br /><small>(recommended for ages 5-12)</small>

<ol class="event-list" style="grid-template-columns: 1fr 1fr;">
  <li>
    <a href="/splash-pad/">
      <div>
        <h3>Areas of the Park</h3>
        <h4>Splash Pad</h4>
        <p>
          Open daily
        </p>
      </div>
      <img src="/assets/temporary/misc/Select_JMC1743.jpg" alt="Splash Pad" height="500" />
    </a>
  </li>
  <li>
    <a href="/playground/">
      <div>
        <h3>Areas of the Park</h3>
        <h4>Playground</h4>
        <p>
          Open daily
        </p>
      </div>
      <img src="/uploads/areas/playground-2.jpg" height="300" alt="" />
    </a>
  </li>
</ol>
<ol class="event-list" style="grid-template-columns: 1fr;">
  <li>
    <a href="/gardens/">
      <div>
        <h3>Areas of the Park</h3>
        <h4>Gardens</h4>
        <p>
          Open daily
        </p>
      </div>
      <img src="/uploads/areas/gardens-2.jpg" height="300" alt="" />
    </a>
  </li>
</ol>
<ol class="event-list" style="grid-template-columns: 1fr 1fr;">
  <li>
    <a href="/dog-run/">
      <div>
        <h3>Areas of the Park</h3>
        <h4>Dog Run</h4>
        <p>
          Open daily
        </p>
      </div>
      <img src="/uploads/areas/dog-run.jpg" height="300" alt="" />
    </a>
  </li>
  <li>
    <a href="/performance-lawn/">
      <div>
        <h3>Areas of the Park</h3>
        <h4>Performance Lawn</h4>
        <p>
          Open daily
        </p>
      </div>
      <img src="/uploads/programs/sunday-sessions-5.jpg" height="300" alt="" />
    </a>
  </li>
</ol>

{% endcomment %}

