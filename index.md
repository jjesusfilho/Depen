---
title       : Indicadores de Violência Institucional
subtitle    :  Medindo a violência dos estados
author      : Maria Gorete Marques de Jesus
job         : José de Jesus Filho
framework   : io2012     # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, bootstrap, quiz]
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
assets      : {js: 'test.js'}

---

## Introdução


<iframe src="int.html"></iframe>


----

## Metodologia

<iframe src="calc.html"></iframe>


---
## Tabela de cálculo de indicadores de diagnóstico


 
<iframe src="Tdia.htm"></iframe>


---- class=center

## Tabela de cálculo de indicadores de desempenho


<iframe src="Td.htm"></iframe>
  

---

### Classificação dos estados segundo a violência e o desempenho institucionais

<div style='
float:left;
padding-left:100px';
>

<!-- Table generated in R 3.1.2 by googleVis 0.5.8 package -->
<!-- Wed Apr  1 06:38:26 2015 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataTableID1bba77dc86ff () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Acre",
0.4,
4 
],
[
 "Alagoas",
0.47,
4 
],
[
 "Amapá",
0.49,
2 
],
[
 "Amazonas",
0.5,
0 
],
[
 "Bahia",
0.51,
5 
],
[
 "Ceara",
0.52,
3 
],
[
 "Distrito Federal",
0.53,
3 
],
[
 "Espírito Santo",
0.58,
5 
],
[
 "Goiás",
0.59,
4 
],
[
 "Maranhão",
0.6,
4 
],
[
 "Mato Grosso",
0.6,
5 
],
[
 "Mato Grosso do Sul",
0.62,
1 
],
[
 "Minas Gerais",
0.63,
2 
],
[
 "Pará",
0.65,
4 
],
[
 "Paraíba",
0.65,
3 
],
[
 "Paraná",
0.65,
5 
],
[
 "Pernambuco",
0.66,
2 
],
[
 "Piauí",
0.66,
5 
],
[
 "Rio de Janeiro",
0.67,
5 
],
[
 "Rio Grande do Norte",
0.69,
4 
],
[
 "Rio Grande do Sul",
0.7,
2 
],
[
 "Rondônia",
0.7,
1 
],
[
 "Roraima",
0.72,
4 
],
[
 "Santa Catarina",
0.77,
3 
],
[
 "Sergipe",
0.78,
0 
],
[
 "São Paulo",
0.8,
4 
],
[
 "Tocantins",
0.8,
2 
] 
];
data.addColumn('string','estados');
data.addColumn('number','violencia');
data.addColumn('number','desempenho');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartTableID1bba77dc86ff() {
var data = gvisDataTableID1bba77dc86ff();
var options = {};
options["allowHtml"] = true;
options["width"] = "800px";
options["height"] = "450px";
options["page"] = "disable";
options["align"] = "left";

    var chart = new google.visualization.Table(
    document.getElementById('TableID1bba77dc86ff')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "table";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartTableID1bba77dc86ff);
})();
function displayChartTableID1bba77dc86ff() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartTableID1bba77dc86ff"></script>
 
<!-- divChart -->
  
<div id="TableID1bba77dc86ff" 
  style="width: 800px; height: 450px;">
</div>

</div>

--- 

## Mapa dos estados segundo o nível de violência

<div style='
margin-left:auto;
margin-right:auto;
width:70%;'>


<!-- GeoMap generated in R 3.1.2 by googleVis 0.5.8 package -->
<!-- Wed Apr  1 06:38:26 2015 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoMapID1bba261f08d2 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Acre",
0.4 
],
[
 "Alagoas",
0.47 
],
[
 "Amapá",
0.49 
],
[
 "Amazonas",
0.5 
],
[
 "Bahia",
0.51 
],
[
 "Ceara",
0.52 
],
[
 "Distrito Federal",
0.53 
],
[
 "Espírito Santo",
0.58 
],
[
 "Goiás",
0.59 
],
[
 "Maranhão",
0.6 
],
[
 "Mato Grosso",
0.6 
],
[
 "Mato Grosso do Sul",
0.62 
],
[
 "Minas Gerais",
0.63 
],
[
 "Pará",
0.65 
],
[
 "Paraíba",
0.65 
],
[
 "Paraná",
0.65 
],
[
 "Pernambuco",
0.66 
],
[
 "Piauí",
0.66 
],
[
 "Rio de Janeiro",
0.67 
],
[
 "Rio Grande do Norte",
0.69 
],
[
 "Rio Grande do Sul",
0.7 
],
[
 "Rondônia",
0.7 
],
[
 "Roraima",
0.72 
],
[
 "Santa Catarina",
0.77 
],
[
 "Sergipe",
0.78 
],
[
 "São Paulo",
0.8 
],
[
 "Tocantins",
0.8 
] 
];
data.addColumn('string','estados');
data.addColumn('number','violencia');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoMapID1bba261f08d2() {
var data = gvisDataGeoMapID1bba261f08d2();
var options = {};
options["dataMode"] = "regions";
options["width"] = "450px";
options["height"] = "450px";
options["region"] = "BR";
options["title"] = "Passe o mouse para ver valor respectivo";
options["colors"] = ['0xffffb2','0xfed976','0xfeb24c','0xfd8d3c','0xf03b20','0xbd0026'];
options["resolution"] = "provinces";

    var chart = new google.visualization.GeoMap(
    document.getElementById('GeoMapID1bba261f08d2')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "geomap";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartGeoMapID1bba261f08d2);
})();
function displayChartGeoMapID1bba261f08d2() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoMapID1bba261f08d2"></script>
 
<!-- divChart -->
  
<div id="GeoMapID1bba261f08d2" 
  style="width: 450px; height: 450px;">
</div>

</div>

---

### Mapa do estados segundo o desempenho institucional

<div style='
margin-left:auto;
margin-right:auto;
height:100%;
width:70%;'>

<!-- GeoMap generated in R 3.1.2 by googleVis 0.5.8 package -->
<!-- Wed Apr  1 06:38:26 2015 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoMapID1bba6fc6903c () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Acre",
4 
],
[
 "Alagoas",
4 
],
[
 "Amapá",
2 
],
[
 "Amazonas",
0 
],
[
 "Bahia",
5 
],
[
 "Ceara",
3 
],
[
 "Distrito Federal",
3 
],
[
 "Espírito Santo",
5 
],
[
 "Goiás",
4 
],
[
 "Maranhão",
4 
],
[
 "Mato Grosso",
5 
],
[
 "Mato Grosso do Sul",
1 
],
[
 "Minas Gerais",
2 
],
[
 "Pará",
4 
],
[
 "Paraíba",
3 
],
[
 "Paraná",
5 
],
[
 "Pernambuco",
2 
],
[
 "Piauí",
5 
],
[
 "Rio de Janeiro",
5 
],
[
 "Rio Grande do Norte",
4 
],
[
 "Rio Grande do Sul",
2 
],
[
 "Rondônia",
1 
],
[
 "Roraima",
4 
],
[
 "Santa Catarina",
3 
],
[
 "Sergipe",
0 
],
[
 "São Paulo",
4 
],
[
 "Tocantins",
2 
] 
];
data.addColumn('string','estados');
data.addColumn('number','desempenho');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoMapID1bba6fc6903c() {
var data = gvisDataGeoMapID1bba6fc6903c();
var options = {};
options["dataMode"] = "regions";
options["width"] = "500px";
options["height"] = "500px";
options["region"] = "BR";
options["title"] = "Passe o mouse para ver valor respectivo";
options["colors"] = ['0xf0f9e8','0xbae4bc','0x7bccc4','0x43a2ca','0x0868ac'];
options["resolution"] = "provinces";

    var chart = new google.visualization.GeoMap(
    document.getElementById('GeoMapID1bba6fc6903c')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "geomap";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartGeoMapID1bba6fc6903c);
})();
function displayChartGeoMapID1bba6fc6903c() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoMapID1bba6fc6903c"></script>
 
<!-- divChart -->
  
<div id="GeoMapID1bba6fc6903c" 
  style="width: 500px; height: 500px;">
</div>

</div>
