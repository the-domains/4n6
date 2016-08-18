---
datePublished: '2016-08-18T19:11:43.593Z'
sourcePath: >-
  _posts/2016-08-17-banner-work-what-happens-when-santas-elves-run-out-of-ener.md
inFeed: true
authors: []
hasPage: true
keywords: []
author: []
via: {}
dateModified: '2016-08-18T19:11:43.256Z'
title: banners in html5
publisher: {}
description: >-
  Banner work. What happens when Santa's elves run out of energy? The peppermint
  mocha latte is better than a Monster energy drink. Only from ampm. Too much
  good stuff. http://www.4n6.net/banners/html5/ampm/elves/
inLanguage: null
inNav: false
starred: false
url: banner-work-what-happens-when-santas-elves-run-out-of-ener/index.html
_type: Article

---
# banners in html5
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/3654777e-df9a-41a6-b915-2b8d6dadb14d.png)

Banner work. What happens when Santa's elves run out of energy? The peppermint mocha latte is better than a Monster energy drink. Only from ampm. Too much good stuff. http://www.4n6.net/banners/html5/ampm/elves/
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/cfa3c5f5-28de-46ba-95e8-bc5d607ae412.png)

What happens when Santa doesn't have enough to eat? Well he gets grumpy like the best of us. He just needs a spicy chicken sandwich from ampm. http://4n6.net/banners/html5/ampm/santa/
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/4c6fe7a6-17ca-439f-9dba-0230ab9e36bd.png)

Banner work. Done for ampm. This pumpkin spice latte will do the trick if you have turned into a zombie. http://www.4n6.net/banners/html5/ampm/pumpkin/
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/74908594-1c46-43e3-8787-33a2f540b85e.png)

The spicy bbq sandwich. Spicy enough to wake the dead. ampm. http://www.4n6.net/banners/html5/ampm/bbq/
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/fa2c7657-3377-41dc-b55f-55431f48af7c.png)

Sometimes you need a kiwi strawberry freeze as the perfect antidote against zombism. ampm - too much good stuff. http://www.4n6.net/banners/html5/ampm/strawberry/
![OWN IT.](https://the-grid-user-content.s3-us-west-2.amazonaws.com/95531b8e-94bd-4db2-8881-8f037e33a780.png)

Link: http://4n6.net/banners/html5/intuit/ownit/
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/2a21503a-efd0-4b83-8de2-396d258dc5c4.jpg)

Client: Honda  
Agency: RPA  
Project: Accord, Memorial Day   
Link: http://4n6.net/banners/html5/honda/lake/
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/a8a00e1a-bc81-4c40-bc06-2dc7bf60cc51.jpg)

Client: Honda  
Agency: RPA  
Project: Civic, Hiding   
Link: http://4n6.net/banners/html5/honda/civic\_hiding/
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/ac4d9bd2-cf82-4ebb-a4ec-2ff59dea0926.jpg)

    <!DOCTYPE html> <html> <head> <meta charset="UTF-8"> <title>Accord Hybrid CMBS</title> <script src="https://code.createjs.com/easeljs-0.7.1.min.js"></script> <script src="https://code.createjs.com/tweenjs-0.5.1.min.js"></script> <script src="https://code.createjs.com/movieclip-0.7.1.min.js"></script> <script src="https://code.createjs.com/preloadjs-0.4.1.min.js"></script> <script type="text/javascript" charset="utf-8" >var clickTag = "https://www.google.com";</script> <script src="DISPLAY_HRM_GENERAL_MY17_ACCORDHYBRID_LAUNCH_MMC_STANDARDTECH_NONDCO_SHOP_HTML_DESKTOP_300x600_SENSING.js"></script> <script> var canvas, stage, exportRoot; function init() { 	canvas = document.getElementById("canvas"); 	images = images||{}; 	var loader = new createjs.LoadQueue(false); 	loader.addEventListener("fileload", handleFileLoad); 	loader.addEventListener("complete", handleComplete); 	loader.loadManifest(lib.properties.manifest); } function handleFileLoad(evt) { 	if (evt.item.type == "image") { images[evt.item.id] = evt.result; } } function handleComplete(evt) { 	exportRoot = new lib.DISPLAY_HRM_GENERAL_MY17_ACCORDHYBRID_LAUNCH_MMC_STANDARDTECH_NONDCO_SHOP_HTML_DESKTOP_300x600_SENSING_v1(); 	stage = new createjs.Stage(canvas); 	stage.addChild(exportRoot); 	stage.update(); 	stage.enableMouseOver(); 	createjs.Ticker.setFPS(lib.properties.fps); 	createjs.Ticker.addEventListener("tick", stage); } </script> </head> <body onload="init();" style="background-color:#D4D4D4; margin:0px"> 	<canvas id="canvas" width="300" height="600" style="background-color:#D4D4D4"></canvas> </body> </html>