---
layout: home
---
<section class="py-2 container-fluid" id="header">
<div class="display-2 pb-2 pt-1 text-center" style="font-family: Bantayog"><strong class="color-primary-4">Pista ng Mapa is Back!</strong></div>
<div class="container display-4 text-center pb-2" id="demo"></div>
</section>

<section class="py-4 container-fluid" id="about">
    {% include about.html %}
</section>

<section class="py-4 container-fluid bg-color-accent-2" id="cfp">
    {% include home_cfp.html %}
</section>

<section class="py-4 container-fluid bg-color-accent-2" id="registration">
    {% include home_reg.html %}
</section>


<!-- <section class="py-4 container-fluid bg-color-accent-2" id="volunteers">
    {% include home_cfv.html %}
</section>
 -->

<section class="py-4 container-fluid" id="sponsors">
    {% include home_cfs.html %}
</section>

{% include countdown.html %}