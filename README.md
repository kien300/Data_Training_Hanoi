# Data literacy training Hanoi
**Building data products - January 29-31 - Hanoi**<br>
*Thomas Roca, PhD, Economist & Data Strategist - Microsoft*

Stay in touch via [Twitter](https://twitter.com/Thomas_Roca), [Github](https://github.com/ThomasRoca/) or [LinkedIn](https://www.linkedin.com/in/thomas-roca-43347484/)

#### Dataviz workshop: [Lecture slides available]

**Tools we are going to use:**
For this workshop, you will need to install a code editor (e.g. [Bracket](https://sourceforge.net/projects/bracketsportable/) or [Notepad++](https://notepad-plus-plus.org/fr/), these editors can be installed without admin rights);

We are also going to use: 
- 	**JSFiddle**, a javascript online editor [sign up here - free](https://jsfiddle.net/user/signup/)
- 	**Carto** an online map editor [sign up here - free](https://carto.com/signup/)

**! To save time during the workshop, register to jsfiddle and carto**

---

**I. Basic introduction to data representation [15min]**
- 	What, and why dataviz ? 
	- Better understanding
	- Communication
	- Interactivity and Story telling
-	Using packages with Stata, Python and R
-	SIG using cloudbased soft [Microsoft Office 365' PowerBI](https://powerbi.microsoft.com/fr-fr/desktop/) and [Carto](https://carto.com/)

---

**Practical: Create a heatmap with Carto [30min]**
  - map Kenya Health sites using CSV file from HDX plateform;
  - Map Cameroon population in 2015 using the data in the Github folder (CMR sub)
--- 

**II. Basic instroduction to the web languages: HTML, CSS, JavaScript [20min]**
-	Basic introduction to [HTML](https://www.w3schools.com/html/default.asp), [CSS](https://www.w3schools.com/css/default.asp)
- 	Introduction to [SVG](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics)

**JavaScript library & dataviz**
- 	dataviz the example of [Highcharts](https://www.highcharts.com/)
- 	SIG using [Highmaps](https://www.highcharts.com/) and [leaflet](http://leafletjs.com/)

**III. Data and programmming for the web: [30min]**

**A tiny bit of code [20min]**
- 	Quick intro to [JavaScript](https://www.w3schools.com/js/default.asp)
	+ [Example of JavaSript Language](https://jsfiddle.net/ThomasRoca/50snpv6r/)

**When data comes in [10min]**
- Data are not only stored in xls!
	+ Text format to store data:
		CSVs, TSVs, etc.
	+ Structured text data:
		+ Intro to XML
		+ Intro to [JSON](https://en.wikipedia.org/wiki/JSON)
		+ Intro to YAML
	
---

### Part II. 14.00
---

**IV. Getting real time data: from scrapper to API, the data revolution: [20min]**
- Introduction: what is an [API](https://en.wikipedia.org/wiki/Application_programming_interface) ?
-  Use cases:An application leveraging [World Bank API](https://datahelpdesk.worldbank.org/knowledgebase/articles/889392-api-documentation)
-  Example: DHS API app': http://data.afd.fr/DataTools/DHS/DHS+browser.html 

 
---


**Practical: Option A. Create a DataStory with Highcharts and Carto**
   + use [Data Story Template](http://data.afd.fr/datastory/Data%20Story%20Template.html) in the github repository
   It can be about :
   - health
   - Education
   - sociaux economic conditions etc.
   You can use data sources such as the World Bank indicators, UN OCHA HDX platform, etc.

--- 
**Pratical: OPtion B. Use world bank API & the DHS application** 
- World bank [API](https://datahelpdesk.worldbank.org/knowledgebase/articles/898581-api-basic-call-structure)
	- GDP growth (annual %) of Kenya (WDI)
	- last 20 observation
   	- using highcharts
- DHS [API](https://api.dhsprogram.com/#/api-querybuilder.cfm)
	- Create a heatmap using [leaflet](http://leafletjs.com/examples/choropleth/)
	- display age specific literacy rate 15-19
	- subnational level in Kenya
	- for the last DHS available
---   	
	
## Further reading:
- Friendly, M., 1999, "Re-Visions of Minard", [link](http://www.datavis.ca/gallery/minard/minard.pdf])
- Friendly, M., 2008, "A Brief History of Data Visualization" [link](http://byrneslab.net/classes/biol607/readings/Friendly_2008_dataviz_history.pdf)
- Lupi, H., Posavec, S.,2016, "Dear Data", http://www.dear-data.com/
- Yau, N. 2011, visualize this: the flowingdata guide to design, visualization, and statistics [link](http://book.flowingdata.com)
- The Smithonianmag:"The Revolutionary Infographics of W.E.B. Du Bois And Booker T. Washington" [link](http://www.smithsonianmag.com/smart-news/the-revolutionary-infographics-of-web-du-bois-and-booker-t-washington-180959756)
- ToucanTouco, Infographie vs Dataviz: Faites la différence. [Link](https://toucantoco.com/blog/infographie-vs-dataviz/)
- Tufte, E. R. The Visual Display of Quantitative Information. Graphics Press, Cheshire, CT, 1983.
- Hagley, J. What is the difference bewteen infographic and dataviz ? [Link](http://www.jackhagley.com/What-s-the-difference-between-an-Infographic-and-a-Data-Visualisation)

### Tutorials
- **Code sample we saw on JSfiddle**:
	- [SVG](http://jsfiddle.net/ThomasRoca/q754amnd/)
	- [highcharts](http://jsfiddle.net/ThomasRoca/fps87ooa)
	- [leaflet](http://leafletjs.com/examples/quick-start/example-popups.html)
	- [Javascript](http://jsfiddle.net/ThomasRoca/50snpv6r/)
	- [parse JSON data](http://jsfiddle.net/ThomasRoca/5f4jh80c)
	- [World Bank Application](http://jsfiddle.net/ThomasRoca/1vpypyc9)
	- [API WDI](http://jsfiddle.net/ThomasRoca/0eata2p0)
	- [DHS API](http://jsfiddle.net/ThomasRoca/069Lqfkz)
- **Highcharts:**
	- https://www.highcharts.com/demo
	- https://www.highcharts.com/blog/
- **Carto:**
	- Video tutorial for Carto: in [french](https://www.youtube.com/watch?v=nRKSR635-Kk), in [spanish](https://www.youtube.com/watch?v=o2dUzQiwUYE&t=2s)
	- Carto Workshop tutorial:https://github.com/CartoDB/carto-workshop
- **HTML, CSS and JS:** 
	- https://www.w3schools.com

- [Data Glossary - Data-Pop Alliance](https://github.com/ThomasRoca/Lecture-Columbia-Science-Po-2017/blob/master/Glossary.md)
- [Mapping Data Sources for development](https://afdlab4dev.github.io/Wiki-DataExploration-in-AFD/)

