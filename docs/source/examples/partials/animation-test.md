---
layout: false
---
<div class="white-panel">
  <graph data="graphData" width="100%" height="600px">
    <x field="Month" order-by="Date"></x>
    <y field="Unit Sales"></y>
    <graph-legend></graph-legend>
    <line field="Owner" value="Aperture"></line>
  </graph>
</div>

<button id="update_data" ng-click="update_data()" class="btn">
	Change Data
</button>
