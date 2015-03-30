---
title       : Indicadores de Violência Institucional
subtitle    :  Medindo a violência dos estados
author      : Maria Gorete Marques de Jesus 
job         : José de Jesus Filho
framework   : io2012     # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, bootstrap, quiz]
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
assets      : {js: 'test.js'}

---



## Introdução

<html>
<iframe src="int.htm"></iframe>
</html>

----
## Metodologia
<html>
<iframe src="calc.htm"></iframe>
</html>

---
## Tabela de cálculo de indicadores de diagnóstico

<html>
<head>
<style>
.center {
    margin-left: auto;
    margin-right: auto;
    width: auto;
   }
   </style>
   <head>
  <body>
  <div class="center">
  <iframe src="Tdia.htm"></iframe>
  </div>
  <body>
</html>

----

## Tabela de cálculo de indicadores de desempenho

<html>
<head>
<style>
.center {
    margin-left: auto;
    margin-right: auto;
    width: auto;
   }
   </style>
   <head>
  <body>
  <div class="center">
  <iframe src="Td.htm"></iframe>
  </div>
  <body>
</html>

---

## Classificação dos estados segundo a violência e o desempenho institucionais

<!-- Table generated in R 3.1.2 by googleVis 0.5.8 package -->
<!-- Mon Mar 30 07:21:54 2015 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataTableID37f82fca4e1a () {
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
function drawChartTableID37f82fca4e1a() {
var data = gvisDataTableID37f82fca4e1a();
var options = {};
options["allowHtml"] = true;
options["width"] = "600px";
options["height"] = "600px";
options["page"] = "disable";

    var chart = new google.visualization.Table(
    document.getElementById('TableID37f82fca4e1a')
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
callbacks.push(drawChartTableID37f82fca4e1a);
})();
function displayChartTableID37f82fca4e1a() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartTableID37f82fca4e1a"></script>
 
<!-- divChart -->
  
<div id="TableID37f82fca4e1a" 
  style="width: 600px; height: 600px;">
</div>

---

## Mapa dos estados segundo o nível de violência

<!-- GeoMap generated in R 3.1.2 by googleVis 0.5.8 package -->
<!-- Mon Mar 30 06:38:03 2015 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoMapID374e63b616f9 () {
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
function drawChartGeoMapID374e63b616f9() {
var data = gvisDataGeoMapID374e63b616f9();
var options = {};
options["dataMode"] = "regions";
options["width"] = "600px";
options["height"] = "600px";
options["region"] = "BR";
options["title"] = "Passe o mouse para ver valor respectivo";
options["colors"] = ['0xffffb2','0xfed976','0xfeb24c','0xfd8d3c','0xf03b20','0xbd0026'];
options["resolution"] = "provinces";

    var chart = new google.visualization.GeoMap(
    document.getElementById('GeoMapID374e63b616f9')
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
callbacks.push(drawChartGeoMapID374e63b616f9);
})();
function displayChartGeoMapID374e63b616f9() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoMapID374e63b616f9"></script>
 
<!-- divChart -->
  
<div id="GeoMapID374e63b616f9" 
  style="width: 600px; height: 600px;">
</div>

---

## Mapa do estados segundo o desempenho institucional

<!-- GeoMap generated in R 3.1.2 by googleVis 0.5.8 package -->
<!-- Mon Mar 30 06:38:03 2015 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoMapID374e70e3afa0 () {
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
function drawChartGeoMapID374e70e3afa0() {
var data = gvisDataGeoMapID374e70e3afa0();
var options = {};
options["dataMode"] = "regions";
options["width"] = "600px";
options["height"] = "600px";
options["region"] = "BR";
options["title"] = "Passe o mouse para ver valor respectivo";
options["colors"] = ['0xf0f9e8','0xbae4bc','0x7bccc4','0x43a2ca','0x0868ac'];
options["resolution"] = "provinces";

    var chart = new google.visualization.GeoMap(
    document.getElementById('GeoMapID374e70e3afa0')
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
callbacks.push(drawChartGeoMapID374e70e3afa0);
})();
function displayChartGeoMapID374e70e3afa0() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoMapID374e70e3afa0"></script>
 
<!-- divChart -->
  
<div id="GeoMapID374e70e3afa0" 
  style="width: 600px; height: 600px;">
</div>


