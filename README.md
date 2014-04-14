HTML5 Canvas site traffic widget (JavaScript)
====================


Features
-----------
* Build a graph based on data array;
* Build a graph based on Yandex.Metrica counter;
* Partial or complete customization;
* Graph built using Html5 canvas;


**Documentation**: http://michael.verhov.com/en/post/site_traffic_widget


Example
-----------
<img src="https://github.com/Verhov/site_traffic_widget/blob/master/html_site_traffic_widget.png?raw=true" />


Usage
-----------
```
<script src="/informer-0.9.0.js" type="text/javascript"></script>
<canvas id="traffic-widget-ex1" height="70" width="270"></canvas>

<script type="text/javascript">
  var informer1 = $informer("traffic-widget-ex1");
  informer1.showStat("CirclesGraph", {
    pageviews: [9, 7, 8, 11, 10, 7, 5, 4, 6, 10, 13, 11],
    uniques: [3, 2, 4, 6, 5, 3, 2, 1, 3, 5, 8, 7],
    current_date: new Date()
  });
  
  // If you use of Yandex Metrics counter - set counter ID number:
  // informer1.showYandexStat("CirclesGraph", "13352758");
</script>
```



License
===========
GNU General Public License (GNU GPL)

Copyright (c) 2014 michael verhov