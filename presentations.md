---
layout: default
title: Presentations
---
<link rel="stylesheet" href="/Garden-Assistant-Application/assets/css/custom.css">
<!-- NAV BAR -->
{% include nav.html %}

# Feasibility Presentation

<div class="slide-wrap">
  <iframe src="https://docs.google.com/presentation/d/1UHvCibJWSSQanufIapTHNkI1VKHAXvQrTxWj9il7cdk/edit?usp=sharing"
          frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>

<style>
.slide-wrap { position: relative; padding-top: 56.25%; }
.slide-wrap iframe { position:absolute; top:0; left:0; width:100%; height:100%; }
</style>
<style>
/* Tab styles */
.tabs { max-width: 1200px; margin: 0 auto; }
.tabs input[name="ppt-tab"] { display: none; }
.tab-controls {
  display: flex; gap: .5rem; flex-wrap: wrap;
  border-bottom: 1px solid #ddd;
}
.tab-controls label {
  padding: .6rem 1rem;
  font-weight: 600;
  background: #f2f2f2;
  cursor: pointer;
  border: 1px solid #ddd;
  border-bottom: none;
  border-radius: .5rem .5rem 0 0;
}
.tab-panel {
  display: none;
  padding: 1rem;
  border: 1px solid #ddd;
  border-radius: 0 .5rem .5rem .5rem;
}
#ppt1:checked ~ .panels #panel1,
#ppt2:checked ~ .panels #panel2,
#ppt3:checked ~ .panels #panel3,
#ppt4:checked ~ .panels #panel4 { display: block; }
#ppt1:checked ~ .tab-controls label[for="ppt1"],
#ppt2:checked ~ .tab-controls label[for="ppt2"],
#ppt3:checked ~ .tab-controls label[for="ppt3"],
#ppt4:checked ~ .tab-controls label[for="ppt4"] {
  background: white;
  border-bottom: 1px solid white;
}

/* Responsive slide embed */
.embed-wrap {
  position: relative;
  width: 100%;
  padding-bottom: 56.25%;
  height: 0;
}
.embed-wrap iframe {
  position: absolute;
  top: 0; left: 0;
  width: 100%;
  height: 100%;
  border: 0;
}
</style>

<div class="tabs">
  <!-- Tab buttons -->
  <input type="radio" name="ppt-tab" id="ppt1" checked>
  <input type="radio" name="ppt-tab" id="ppt2">
  <input type="radio" name="ppt-tab" id="ppt3">
  <input type="radio" name="ppt-tab" id="ppt4">

  <div class="tab-controls">
    <label for="ppt1">Prototype</label>
    <label for="ppt2">Design</label>
    <label for="ppt3">Feasibility V2</label>
    <label for="ppt4">Feasibility V1</label>
  </div>

  <!-- Tab content panels -->
  <div class="panels">
    <section id="panel1" class="tab-panel">
      <h3>Prototype Presentation</h3>
      <div class="embed-wrap">
        <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRCaEeMyenTFGZ90qMKUtQgRGkSFXomGk7P8PnUPAxhF5V7QrEPEb7wmfKIt3PqOe-Qc8vuaJFB2EsY/embed?start=false&loop=false&delayms=3000" allowfullscreen></iframe>
      </div>
    </section>

    <section id="panel2" class="tab-panel">
      <h3>Design Presentation</h3>
      <div class="embed-wrap">
        <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRCaEeMyenTFGZ90qMKUtQgRGkSFXomGk7P8PnUPAxhF5V7QrEPEb7wmfKIt3PqOe-Qc8vuaJFB2EsY/embed?start=false&loop=false&delayms=3000" allowfullscreen></iframe>
      </div>
    </section>

    <section id="panel3" class="tab-panel">
      <h3>Feasibility V2</h3>
      <div class="embed-wrap">
        <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRCaEeMyenTFGZ90qMKUtQgRGkSFXomGk7P8PnUPAxhF5V7QrEPEb7wmfKIt3PqOe-Qc8vuaJFB2EsY/embed?start=false&loop=false&delayms=3000" allowfullscreen></iframe>
      </div>
    </section>

    <section id="panel4" class="tab-panel">
      <h3>Feasibility V1</h3>
      <div class="embed-wrap">
        <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRCaEeMyenTFGZ90qMKUtQgRGkSFXomGk7P8PnUPAxhF5V7QrEPEb7wmfKIt3PqOe-Qc8vuaJFB2EsY/embed?start=false&loop=false&delayms=3000" allowfullscreen></iframe>
      </div>
    </section>
  </div>
</div>
