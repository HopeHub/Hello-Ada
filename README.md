# Hello-Ada
Resume
I love :indoor rock climbing:, :skydiving:, :coding:.
I love :dogs:, :cars:, :movies:.
@@ -0,0 +1,74 @@
+# David Hamp-Gonsalves
+## Senior Developer & Problem Solver
+
+> [davidhampgonsalves.com](http://www.davidhampgonsalves.com)
+> [davidhampgonsalves@gmail.com](mailto:davidhampgonsalves@gmail.com)
+> (902) 817-3574
+
+------
+
+### Technical
+
+1. Java
+1. Javascript / NodeJS
+1. Python
+1. Android / iOS
+1. Phonegap / Cordova
+1. Backbone.js / Require.js
+1. Wicket / Spring
+1. Git / SVN
+1. Weblogic / Websphere
+1. Tomcat / Jetty
+1. Oracle DB / MSSQL
+1. PostgreSQL / MySQL
+
+------
+
+### Experience
+
+**NTTData** *Senior Consultant* __2012 to present__
+ Designed modern single arctecture Backbone.js based replacement for existing customer facing legacy system. Pioniered BDD style testing using Jasmine.js/Karma on existing application code. Developed modern solutions and features for large Enterprise Java systems. Colaborated with and guided global team members transitioning to client side archetecture.
+ **Technical Environment** SpringSource, Tomcat, Backbone.js, Underscore.js, Require.js.
+
+**Sumtotal Systems** *Senior Java Developer* __2008 to 2012__
+ Designed and implemented features and improvements for multiple enterprise sized applications. Automated the generation of scheduled reports using the existing ticketing systems SOAP web services to provide consistent and accurate team analytics. Designed and developed quality code solutions to mission critical production issues for major clients in a timely and efficient manner. Proposed, designed and implemented a real time tracking, deployment and notification system for our test environments.
+ **Technical Environment** Weblogic/Websphere, Struts/SpringSource, MSSQL/Oracle, JUnit.
+
+**We Can Pretend** *Technical Consultant* __2011 to 2011__
+ Archetected and implemented a interactive media streaming service that enabled the host to interact with viewers using synchronized prompts, overlays and widgets. Created detailed documentation regarding technical requirements, project time lines and staffing guidelines for realizing their total product offering.
+ **Technical Environment** Wowza Media Server, Adobe Flex, Javascript.
+
+**Redline Distribution** *Web Application Developer* __2008 to 2008__
+ Wrote a versatile Java EE based, database-driven, e-commerce system for the real time sale, processing and shipping of products available from external distributors such as Baker-Taylor and DeepDiscount. The system interfaced with external distributors to ensure current inventory, status and price and used AJAX rich components to improve usability, convenience and efficiency.
+ **Technical Environment** JBoss, Seam, MySQL, Hbernate, JSF, RichFaces, EJB.
+
+**CIBC** *Test Analyst* __2007 to 2008__
+ Eliminated manual testing processes with automated QTP scripts to increase productivity and limit repetitive human task based testing. Worked cohesively with other developers and team mates to plan, design and implement multi-system automated tests which simulate multiple users and roles.
+ **Technical Environment** VB, Quick Test Professional.
+
+------
+
+### Projects
+
+* **Ethical Barcode**
+ [ethicalbarcode.com](http://www.ethicalbarcode.com)
+ Cordova based app(iOS & Android) that leverages a huge amalagamation of public data. Driven by over 30 web spiders, 15 webservices and multiple external databases it provides brand ratings from non-profit organizations by scanning product barcodes.
+
+* **Halifax Crime Heatmap**
+ [crimeheatmap.ca](http://www.crimeheatmap.ca)
+ HTML5 Animated heatmap visualizing crimes in the city of Halifax. Built on a customized Heatmap.js library to enable smooth animation. It was chosen as a featured showcase for the Heatmap.js library.
+
+* **Foxish**
+ [chrome.google.com](https://chrome.google.com/webstore/detail/jpgagcapnkccceppgljfpoadahaopjdb)
+ Chrome extension that enables Firefox-style live RSS feeds with over twelve thousand active users a 4.5/5 star rating. It was Featured on [Gizmoto](http://gizmodo.com/5609633/10-add+ons-you-have-to-know-about-for-google-chrome) & [LifeHacker](http://lifehacker.com/5603602/foxish-live-rss-adds-live-bookmarks-to-google-chrome).
+
+* **Hourly Weather**
+ [hourweather.com](http://www.hourweather.com) & [play.google.com](https//play.google.com/store/apps/details?id=com.hourlyweather)
+ Android based app/widget that provides location aware hourly weather forecasting. HTML5 version shares the same core code base and focuses on graphical experence and simplicity.
+
+------
+
+### Education
+
+**Bachelor Degree of Software Development** __2003 to 2007__
+ Seneca College of Applied Arts and Technology (Seneca@York), Toronto, Ontario
171  screen.css
@@ -0,0 +1,171 @@
+
+
+/*
+ Mobile layout
+ 240–479 px
+ Zoomed out below 320 px
+*/
+
+@media screen {
+ body {
+ padding:0;
+ }
+
+ .container {
+ width:100%;
+ }
+}
+
+
+/*
+ Wide mobile layout
+ 480-767 px
+ Zoomed in above 480 px
+*/
+
+@media screen and (min-width: 30em) {
+}
+
+
+/*
+ Tablet layout
+ 600-911 px
+ Zoomed in above 600 px
+*/
+
+@media screen and (min-width: 37.5em) {
+ blockquote {
+ top: 10px;
+ right: 50px;
+ position: absolute;
+ }
+ h1 { /* Open up the top section height so we don't collapse on the blockquote */
+ margin-top: .5em;
+ }
+ ol {
+ margin: 0 0 0 1em;
+ }
+ ol li {
+ width: 50%;
+ margin: 0;
+ }
+ ol li:nth-child(1), ol li:nth-child(2) {
+ border-top: none;
+ }
+}
+
+
+/*
+ Widescreen layout
+ 912-1887 px
+ Zoomed in above 912 px
+*/
+
+@media screen and (min-width: 57em) {
+ .container {
+ /*width: 912px;*/
+ width: 100%;
+ }
+ .resume {
+ margin:0 auto;
+ padding: 40px 50px;
+ width: 912px;
+ }
+ blockquote {
+ top: 40px;
+ right: 50px;
+ position: absolute;
+ }
+ h1 {
+ margin-top: 0;
+ font-size: 44px;
+ text-transform: uppercase;
+ letter-spacing: 3px;
+ font-weight: normal;
+ }
+ h2 {
+ text-transform: uppercase;
+ font-style: italic;
+ letter-spacing: 2px;
+ font-weight: normal;
+ }
+
+ h3 {
+ float: left;
+ width: 16%;
+ }
+
+ h3~p {
+ float: left;
+ margin-left: 16%;
+ }
+
+ h3+p {
+ margin-left: inherit;
+ float: left;
+ width: 84%;
+ }
+
+ ul li {
+ width: 28%;
+ float: left;
+ }
+ ul dl {
+ dt {
+ font-size: 122%;
+ font-weight: normal;
+ margin-bottom: .75em;
+ }
+ dd {
+ padding: 0 4em 0 0;
+ }
+ }
+
+ ol {
+ float: left;
+ width: 84%;
+ margin: .6em 0 0;
+ }
+
+ ol li {
+ width: 33%;
+ margin: 0;
+ }
+ ol li:nth-child(3n) {
+ width: 34%;
+ }
+ ol li:nth-child(1), ol li:nth-child(2), ol li:nth-child(3) {
+ border-top: none;
+ }
+
+ dl {
+ margin: .5em 0 0;
+ dt {
+ }
+ dd {
+ }
+ strong {
+ float: right;
+ margin-top: -2em;
+ }
+ em {
+ font-size: 130%;
+ font-style: normal;
+ }
+
+ }
+
+
+}
+
+
+/*
+ Huge-screen layout
+ 1888-2520 px
+ Zoomed in above 1920 px
+*/
+
+@media screen and (min-width: 118em) {
+
+
+}
HopeHub

    Write
    Preview

Markdown supported
Edit in fullscreen

Attach images by dragging & dropping or selecting them.
