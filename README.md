


# Building Web and Mobile ArcGIS Server Applications with JavaScript - Second Edition
This is the code repository for [Building Web and Mobile ArcGIS Server Applications with JavaScript - Second Edition](https://www.packtpub.com/application-development/building-web-and-mobile-arcgis-server-applications-javascript-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781787280526), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
ArcGIS Server is the leading software for developing both web and mobile GIS applications. The ArcGIS API for JavaScript is the preferred way of developing your custom applications for ArcGIS Server since it can be used for both web and mobile application development. It's easy to use and doesn't require the use of a browser plugin. This practical guide provides you with hands-on experience in developing custom web and mobile ArcGIS Server applications with step-by-step style exercises.

Along with introducing you to the HTML/CSS/JavaScript technology stack, you will learn to add intuitive geographic layers of information to your map, interactive query and display of spatial data, add user interface widgets, access geoprocessing tasks, and many more in your own web and mobile GIS applications. You will be able to develop fully-functional online GIS applications with ArcGIS Server using the ArcGIS API for JavaScript, which has been updated to 4.x. After creating your own map, you will explore how to add geographic layers from a variety of sources including tiled and dynamic map services, add graphics to the map, and stream geographic features to the browser using a FeatureLayer. You will also learn how to work with 3D maps, get a hold onto the analytics tools, visualizations, etc. Most applications include the specific functionalities implemented by ArcGIS Server as tasks. You'll learn how to use the various tasks provided by ArcGIS Server including spatial and attribute queries, identification of features, finding features by attribute, and more. Geocoding and geoprocessing tasks are covered in-depth to help you accomplish your task in GIS. Finally, you'll learn just how easy it is to integrate ArcGIS content into your custom developed applications by building a complete app.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
function computeServiceArea(evt) {
  map.graphics.clear();
  var pointSymbol = new SimpleMarkerSymbol();
  pointSymbol.setOutline = new 
  SimpleLineSymbol(SimpleLineSymbol.STYLE_SOLID, new Color([255, 0, 
  0]), 1);
  pointSymbol.setSize(14);
  pointSymbol.setColor(new Color([0, 255, 0, 0.25]));      
}
```

To complete the activities in this book, you will need access to a web browser--preferably Google Chrome or Firefox. Each chapter contains practices designed to supplement the material presented. You will complete these practices using the ArcGIS API for JavaScript Sandbox to write and test your code. The sandbox can be found at https://developers.arcgis.com/javascript/3/sandbox/sandbox.html. All the practices will access publicly available instances of ArcGIS Server, so you will not need to install ArcGIS Server yourself.

## Related Products
* [Building Web and Mobile ArcGIS Server Applications with JavaScript](https://www.packtpub.com/application-development/building-web-and-mobile-arcgis-server-applications-javascript?utm_source=github&utm_medium=repository&utm_campaign=9781849697965)

* [Mastering ArcGIS Server Development with JavaScript](https://www.packtpub.com/application-development/mastering-arcgis-server-development-javascript?utm_source=github&utm_medium=repository&utm_campaign=9781784396459)

* [Building Web Applications with ArcGIS](https://www.packtpub.com/application-development/building-web-applications-arcgis?utm_source=github&utm_medium=repository&utm_campaign=9781783552955)
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781787280526">https://packt.link/free-ebook/9781787280526 </a> </p>