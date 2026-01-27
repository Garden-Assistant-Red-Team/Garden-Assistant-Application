---
layout: default
title: Presentations
permalink: /presentations/
---
<link rel="stylesheet" href="/Garden-Assistant-Application/assets/css/custom.css">
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
.embed-wrap iframe { position: absolute; inset: 0; width: 100%; height: 100%; border: 0; }
</style>

<div class="tabs">
  <!-- Removed Prototype Radio (Hidden) -->
 <input type="radio" name="ppt-tab" id="ppt1">

  <!-- Keep these -->
  <input type="radio" name="ppt-tab" id="ppt2" checked>
  <input type="radio" name="ppt-tab" id="ppt3">
  <input type="radio" name="ppt-tab" id="ppt4">

  <!-- Tab Labels (Prototype Removed) -->
  <div class="tab-controls">
   <label for="ppt1">Prototype</label>
    <label for="ppt2">Design</label>
    <label for="ppt3">Feasibility V2</label>
    <label for="ppt4">Feasibility V1</label>
  </div>

  <!-- Panels Wrapper -->
  <div class="panels">

    <!-- Hidden Prototype Content -->
    
    <section id="panel1" class="tab-panel">
      <h3>Prototype Presentation</h3>
      <div class="embed-wrap">
        <iframe src="<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ0BQQ-lr4Rcec5-OW54y_lblArjCIqQOauOFHK4ZnDrRgputVF8GVuX0tWxh1iGO2Bl3A2ao8MH-ld/pubembed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>" allowfullscreen></iframe>
      </div>
    </section>
    
    <!-- Design -->
    <section id="panel2" class="tab-panel">
      <h3>Design Presentation</h3>
      <div class="embed-wrap">
        <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSPzDmFGicHJFZ0o0D3Ls44cILyQJS5Ghi1_Ryj1pK08YtQxmbpaJJssIyYYt6OhO7ZafTvZ2jBf_p0/pubembed?start=false&loop=false&delayms=3000" allowfullscreen></iframe>
      </div>
    </section>

    <!-- Feasibility V2 -->
    <section id="panel3" class="tab-panel">
      <h3>Feasibility V2</h3>
      <div class="embed-wrap">
        <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRNO2rK8lowBGTZS3g50nB5VppiFsM4JSl8WgN_qFwV8b6Wt6kMk8p49412CKTZ_qOk1jOb5Sq4fYkG/pubembed?start=false&loop=false&delayms=3000" allowfullscreen></iframe>
      </div>
    </section>

    <!-- Feasibility V1 -->
    <section id="panel4" class="tab-panel">
      <h3>Feasibility V1</h3>
      <div class="embed-wrap">
        <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRNO2rK8lowBGTZS3g50nB5VppiFsM4JSl8WgN_qFwV8b6Wt6kMk8p49412CKTZ_qOk1jOb5Sq4fYkG/pubembed?start=false&loop=false&delayms=3000" allowfullscreen></iframe>
      </div>
    </section>

  </div>
</div>
{% endraw %}

