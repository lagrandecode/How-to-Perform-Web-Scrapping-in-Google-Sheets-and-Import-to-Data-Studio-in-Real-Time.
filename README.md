# How-to-Perform-Web-Scrapping-in-Google-Sheets-and-Import-to-Data-Studio-in-Real-Time.
Google Sheets is a spreadsheet program included as part of the free, web-based Google Docs Editors suite offered by Google. Google Data Studio provides sophisticated visualization of reporting that includes dashboards, maps and graphs that can be customized. Although the brand is fairly new, data analysts have embraced the platform as it allows them to create various charts and graphs in a more visually attractive manner.
In this video, I’ll show you how to perform web scrapping in google sheets and connect to data studio in real time.
At the end of this video, viewers should be able to create dashboard like this https://datastudio.google.com/s/s0hHt...
showing the visualization of coronavirus in real time.
To make use of the animation in the video, click on the link below.
Animation GIF
CODE TO DETERMINE TABLE IN A SITE
COPY THIS AND PASTE IT IN CONSOLE
Tables: var i = 1; [].forEach.call(document.querySelectorAll('table'), function(x) { console.log(i++, x); });
