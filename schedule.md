---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: archive
layout: single   
title: Schedule   
lang: en   
ref: sched   
permalink: /schedule/   
# sidebar:
#   nav: "schedule-toc"   
toc: true  
toc_label: "Schedule" # default: Content
toc_icon: "bell"  # corr esponding Font Awesome icon name without the "fa" prefix
toc_sticky: true   # enables sticky toc 
read_time: true  
date: 2024-10-02   
last_modified_at: 2024-10-02   

---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/lipis/flag-icons@6.11.0/css/flag-icons.min.css"/>

<div class="lang-sidebar">
  {% assign pages=site.pages | where:"ref", page.ref | sort: 'lang' %}
  {% for page in pages %}
    <li class="zoom"><a href="{{ page.url }}" class="{{ page.lang }}"><span class="fi fi-{{ page.lang }}"></span></a></li>
  {% endfor %}
</div>

<div class="top-h1-icon">
  <i class="fas fa-bell fa-2x"></i>
</div>

<!-- # Schedule -->
_This page will be updated frequently with examples, video tutorials, links to new resources, and occasional updates to weekly patches. Our schedule follows the [Current MHL Academic Calendar]({{ site.MHL-calendar }}){:target="_blank"}. The following topics and their precise order may change. Check here for updates!_  

* * *

## Week 1: {{ site.week-01 }}  
### <span style="color: #10999e;">{{ site.week-01-topic }}</span>    

#### Start-of-Semester Business  

* Review [Syllabus + course policies.](/MHL-Data-Sonification/index.html){:target="_blank"}  
* Review [Software Installation.](/MHL-Data-Sonification/resources/){:target="_blank"}   

#### Topics in Sonification    
* [Class Discussion Mind Map](assets/images/sonification-day-1.drawio.svg){:target="_blank"}         
* [What is Data? Python Word Cloud](assets/images/wordcloud_data_definition.png){:target="_blank"}         
  
<img src="/MHL-Data-Sonification/assets/images/wordcloud_data_definition.png" width="70%" alt="Python Word Cloud">   
   
#### Assignments    
_(Unless otherwise noted, assignments are always due before the next class!)_ 
* Join our Digitale Kreation Discord Server and our new `#data-sonification` channel      
* **Install** Visual Studio Code (“VS Code”)  
* **Install** Python 3 (any version 3 — not 2 — will do just fine!)  
  
* **Finish these things** we made in class:   
  - `first.python.v01.py`   
    
#### Terms, Concepts, Objects, Shortcuts    
- auditory display   
- sonification      
   
* * *  

## Week 2: {{ site.week-02 }}  
### <span style="color: #10999e;">{{ site.week-02-topic }}</span>    
   
#### Downloads       
* [Population of Berlin 1955-2024 v01.xlsx](assets/boilers/Population.of.Berlin.1955-2024.v01.xlsx){:target="_blank"}         
   
#### Assignments    
* Do something fun with `coll.import.v01.maxpat`! Come prepared next week!   
* Be sure you have access to [Google Sheets](https://workspace.google.com/products/sheets/){:target="_blank"} via your own [Gmail address](https://www.google.com/intl/en_de/gmail/about/){:target="_blank"}   
   
* **Finish these things** we made in class:   
  - `Population of Berlin 1955-2024 v02.xlsx`     
  - `berlin.population.v01.txt`    
  - `import.to.coll.v01.maxpat`    
   
#### Terms, Concepts, Objects, Shortcuts    
- data dimensionality   
- spreadsheet  
- two dimensional data (2D data)  
- rows and columns   
- cell reference  
- formula   
- function   
- data range   
- smooth line chart   
- series   
- bounds   
- gridlines   
- ticks   
- concatenation       
- `MIN()`        
- `MAX()`        
- `CONCATENATE()`    
- `coll`   
- index  
  
* * *

## Week 3: {{ site.week-03 }}  
### <span style="color: #10999e;">{{ site.week-03-topic }}</span>    

#### Tutorials   
* [JavaScript Basics](https://einbahnstrasse.github.io/Goldford-MTEC1003/labs/05/js-basics.html#1.0){:target="_blank"}  
* [Introduction to Python Slides](https://einbahnstrasse.github.io/MTEC1003-slides/slides/python.intro.tutorial.v02/#/){:target="_blank"}  
   
* * *  
   
## Week 4: {{ site.week-04 }}  
### <span style="color: #10999e;">{{ site.week-04-topic }}</span>    

#### Boiler Downloads   
* [Introduction to JS + Py Boilers](https://github.com/einbahnstrasse/MHL-Datensonifikation-Week-04-boiler){:target="_blank"}  
  
*Share Your* `import.to.coll.v01.maxpat` *from Week 2!*    

#### Tutorials   
* [Completion of Week 4 Exercises](https://youtu.be/9bJ2ce2otkQ?si=qDimtVLk9KII1LfH){:target="_blank"}  

{% include video id="9bJ2ce2otkQ?si=qDimtVLk9KII1LfH" provider="youtube" %}    

#### Assignments    
* Send me a link to your **Github repository**.   
* **Finish these things** we made in class (following the ***video tutorial*** above):   
  - `week-3-exercises.js`     
  - `week-3-exercises.py`    

#### Terms, Concepts, Objects, Shortcuts    
- high level programming language    
- JavaScript Console   
- HTML  
- markup vs. markdown  
- `<script></script>`   
- values and types (numbers, strings, boolean, Infinity, `NaN`, null/undefined)  
- `typeof x` and `typeof(x)`   
- binary operators (`+`, `-`, `*`, `/`, `%`)  
- string concatenation   
- expression, statement, and program     
- function   
- call to a function   
- arguments   
- variables and `=`   
- declaration vs. initialization         
- comments  

* * *  

## Week 5: {{ site.week-05 }}  
### <span style="color: #10999e;">{{ site.week-05-topic }}</span>    

#### Tutorials   
* [For Loops (examples in Python)](https://einbahnstrasse.github.io/MTEC1003-slides/slides/python.for.loop.tutorial.v01/#/){:target="_blank"}  
* [Booleans + Conditionals (examples in Python and JavaScript)](https://einbahnstrasse.github.io/MTEC1003-slides/slides/python.conditionals.tutorial.v01/#/){:target="_blank"}  
    
#### Assignments    
* Assign [Week 6 Asynchronous Reflections](https://einbahnstrasse.github.io/MHL-Data-Sonification/week-06-asynchronous/){:target="_blank"}, to be **completed by Friday, November 8**. Since we will not be having class next week, work on this assignment ***at your own pace*** (asynchronously), and send me your reactions by next Friday's deadline.   
* **Finish these things** we made in class (following the ***video tutorial*** above):   
  - `iteration.in.max.maxpat`  
  - ~~`week-5-exercises.js`~~     
  - ~~`week-5-exercises.py`~~    

_We began_ `week-5-exercises.js` _but will continue and finish it in Week 7._   

#### Terms, Concepts, Objects, Shortcuts    
- control flow  
- iteration   
- "for loop"  
   
* * *   
  
## Week 6: {{ site.week-06 }}  
### <span style="color: #10999e;">{{ site.week-06-topic }}</span>    
   
Since we will not be having class this week, work on this assignment at your own pace (asynchronously), and send me your reactions by Friday's deadline.

* Finish [Week 6 Asynchronous Reflections](https://einbahnstrasse.github.io/MHL-Data-Sonification/week-06-asynchronous/){:target="_blank"}, **by Friday, November 8**.    
* Be sure to prepare for Week 7 by **reading the Week 7 slides** and **watching the videos**!   

* * *

## Week 7: {{ site.week-07 }}  
### <span style="color: #10999e;">{{ site.week-07-topic }}</span>    
      
#### Assignments   
* **Finish these things** we made in class:   
  - `week-5-exercises.js`     
  - ~~`week-5-exercises.py`~~    
* To facilitate this, [watch the video demonstrating the remaining exercises](https://youtu.be/06mCfjN9duY?si=1oHyMZI0Ldotiy8U){:target="_blank"} (1-18 in all):      
  
{% include video id="06mCfjN9duY?si=1oHyMZI0Ldotiy8U" provider="youtube" %}    
  
#### Terms, Concepts, Objects, Shortcuts    
- `for x in myExs`  
- while loop  
- conditional statement   
- comparison operators (`==`, `===`, `!=`, `!==`, `<`, `>`, `>=`, `<=`, `is`, `is not`)  
- logical operators (`&&`, `||`, `!`, `and`, `or`, `not`)  
- `=` vs. `==` vs. `!==` vs. `===`   
   
* * *  

## Week 8: {{ site.week-08 }}  
### <span style="color: #10999e;">{{ site.week-08-topic }}</span>    
   
_Class will be held in the **Spatial Audio Lab** of the Digital Learning Campus, in the old Karstadt building, located at Königstraße 54 in the_ [**Übergangshaus**](http://xn--bergangshaus-clb.de/){:target="_blank"}. _Click on the map below for directions. Take the escalator to the 2nd floor and find the Spatial Audio Lab._   
  
<div style="width: 100%"><iframe width="100%" height="600" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=%C3%9Cbergangshaus,%20K%C3%B6nigstra%C3%9Fe%2054,%2023552%20L%C3%BCbeck+(Digital%20Learning%20Campus)&amp;t=h&amp;z=15&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"><a href="https://www.gps.ie/">gps trackers</a></iframe></div>    

<!-- source: https://www.maps.ie/create-google-map/ -->

#### Boiler Downloads   
* [JupyterLab Coffee Data Boiler](https://github.com/einbahnstrasse/MHL-Datensonifikation-Week-08-boiler){:target="_blank"}  
* [Watch the quick installation video:](https://youtu.be/2AZ7uMqnzhY?si=lofQoCxqYG3TULx6){:target="_blank"}        
    
{% include video id="2AZ7uMqnzhY?si=lofQoCxqYG3TULx6" provider="youtube" %}    
  
#### Tutorials   
* [JavaScript Functions Revisited](https://einbahnstrasse.github.io/Goldford-MTEC1003/labs/09/js.functions.html#1.0){:target="_blank"}  
* [Python Function Defintions + Calls](https://einbahnstrasse.github.io/MTEC1003-slides/slides/functions.tutorial.v01/#/){:target="_blank"}  
* [More Kinds of Loops](https://einbahnstrasse.github.io/MTEC1003-slides/slides/more.loops.tutorial.v01/#/){:target="_blank"}, especially the sections on [self similarity + recursion (slides 18—51)](https://einbahnstrasse.github.io/MTEC1003-slides/slides/more.loops.tutorial.v01/#/18){:target="_blank"}     

#### Videos   

_Just watch these: you don't have to code them!_  

* [Thorsten Altenkirch's _Tower of Hanoi_ Solution in Python](https://youtu.be/8lhxIOAfDss?si=sisO74481tojwDiS){:target="_blank"}   
   
{% include video id="8lhxIOAfDss?si=sisO74481tojwDiS" provider="youtube" %}    
   
* [Daniel Shiffman's Fractal Tree Drawing in `p5.js`](https://youtu.be/0jjeOYMjmDU?si=TiGCIljKQkZXtG5c){:target="_blank"}   

{% include video id="0jjeOYMjmDU?si=TiGCIljKQkZXtG5c" provider="youtube" %}    
   
#### Terms, Concepts, Objects, Shortcuts    
- recursion  
- recursive function   
- self-similarity  
- local vs. global variables   
- variable scope: `var`, `let`, and `const`  
   
* * *

## Week 9: {{ site.week-09 }}  
### <span style="color: #10999e;">{{ site.week-09-topic }}</span>    

* * *

## Week 10: {{ site.week-10 }}  
### <span style="color: #10999e;">{{ site.week-10-topic }}</span>    
   
* * *

## Week 11: {{ site.week-11 }}  
### <span style="color: #10999e;">{{ site.week-11-topic }}</span>    

* * *

## Week 13: {{ site.week-13 }}  
### <span style="color: #10999e;">{{ site.week-13-topic }}</span>    

* * *

## Week 14: {{ site.week-14 }}  
### <span style="color: #10999e;">{{ site.week-14-topic }}</span>    
  
* * *

## Week 15: {{ site.week-15 }}  
### <span style="color: #10999e;">{{ site.week-15-topic }}</span>    
  
* * *

## Week 16: {{ site.week-16 }}   
### <span style="color: #10999e;">{{ site.week-16-topic }}</span>    
  
* * *

## Week 17: {{ site.week-17 }}   
### <span style="color: #10999e;">{{ site.week-17-topic }}</span>    
  
* * *

## Week 18: {{ site.week-18 }}   
### <span style="color: #10999e;">{{ site.week-18-topic }}</span>    
  
* * *
