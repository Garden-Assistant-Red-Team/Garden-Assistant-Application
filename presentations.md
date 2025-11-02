---
layout: default
title: Presentations
permalink: /presentations/
---

{% include nav.html %}

{% raw %}
<style>
/* Tabs Styling */
.tabs { max-width: 1200px; margin: 0 auto; padding: 20px; }
.tabs input[name="ppt-tab"] { display: none; }
.tab-controls { display: flex; gap: .5rem; flex-wrap: wrap; border-bottom: 1px solid #ddd; margin-bottom: 10px; }
.tab-controls label {
  padding: .6rem 1rem; font-weight: 600; cursor: pointer;
  background: #f2f2f2; border: 1px solid #ddd; border-bottom: none;
  border-radius: .5rem .5rem 0 0;
}
.tab-panel { display: none; border: 1px solid #ddd; border-radius: 0 .5rem .5rem .5rem; padding: 1rem; }

/* Show Active Panel */
#ppt1:checked ~ .panels #panel1,
#ppt2:checked ~ .panels #panel2,
#ppt3:checked ~ .panels #panel3,
#ppt4:checked ~ .panels #panel4 { display: block; }

/* Highlight Active Tab */
#ppt1:checked ~ .tab-controls label[for="ppt1"],
#ppt2:checked ~ .tab-controls label[for="ppt2"],
#ppt3:checked ~ .tab-controls label[for="ppt3"],
#ppt4:checked ~ .tab-controls label[for="ppt4"] {
  background: #fff; border-bottom: 1px solid #fff;
}

/* Responsive Slide Embed */
.embed-wrap { position: relative; width: 100%; padding-bottom: 56.25%; height: 0; margin-top: 10px; }
.embed-wrap iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0; }
</style>

<div class="tabs">
  <!-- Radio buttons (tabs) -->
  <input type="radio" name="ppt-tab" id="ppt1" checked>
  <input type="radio" name="ppt-tab" id="ppt2">
  <input type="radio" name="ppt-tab" id="ppt3">
  <input type="radio" name="ppt-tab" id="ppt4">

  <!-- Tab Labels -->
  <div class="tab-controls">
    <label for="ppt1">Prototype</label>
    <label for="ppt2">Design</label>
    <label for="ppt3">Feasibility V2</label>
    <label for="ppt4">Feasibility V1</label>
  </div>

  <!-- Tab Content -->
  <div class="panels">
    <section id="panel1" class="tab-panel">
      <h3>Prototype Presentation</h3>
      <div class="embed-wrap">
        <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRNO2rK8lowBGTZS3g50nB5VppiFsM4JSl8WgN_qFwV8b6Wt6kMk8p49412CKTZ_qOk1jOb5Sq4fYkG/pubembed?start=false&loop=false&delayms=3000" allowfullscreen></iframe>
      </div>
    </section>

    <section id="panel2" class="tab-panel">
      <h3>Design Presentation</h3>
      <div class="embed-wrap">
        <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRNO2rK8lowBGTZS3g50nB5VppiFsM4JSl8WgN_qFwV8b6Wt6kMk8p49412CKTZ_qOk1jOb5Sq4fYkG/pubembed?start=false&loop=false&delayms=3000" allowfullscreen></iframe>
      </div>
    </section>

    <section id="panel3" class="tab-panel">
      <h3>Feasibility V2 Presentation</h3>
      <div class="embed-wrap">
        <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRNO2rK8lowBGTZS3g50nB5VppiFsM4JSl8WgN_qFwV8b6Wt6kMk8p49412CKTZ_qOk1jOb5Sq4fYkG/pubembed?start=false&loop=false&delayms=3000" allowfullscreen></iframe>
      </div>
    </section>

    <section id="panel4" class="tab-panel">
      <h3>Feasibility V1 Presentation</h3>
      <div class="embed-wrap">
        <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRNO2rK8lowBGTZS3g50nB5VppiFsM4JSl8WgN_qFwV8b6Wt6kMk8p49412CKTZ_qOk1jOb5Sq4fYkG/pubembed?start=false&loop=false&delayms=3000" allowfullscreen></iframe>
      </div>
    </section>
  </div>
</div>
{% endraw %}

