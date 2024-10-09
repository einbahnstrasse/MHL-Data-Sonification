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

#### Terms, Concepts, Objects, Shortcuts    
- high level programming language     
- JavaScript Console   
- HTML   
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
- declaration       
- comments  
   
* * *  
   
## Week 4: {{ site.week-04 }}  
### <span style="color: #10999e;">{{ site.week-04-topic }}</span>    

#### Terms, Concepts, Objects, Shortcuts    
- control flow  
- iteration   
- "for loop"  
- `for x in myExs`  
- while loop  
- conditional statement   
- comparison operators (`==`, `===`, `!=`, `!==`, `<`, `>`, `>=`, `<=`, `is`, `is not`)  
- logical operators (`&&`, `||`, `!`, `and`, `or`, `not`)  
- `=` vs. `==` vs. `!==` vs. `===`   
- local vs. global variables   
- variable scope: `var`, `let`, and `const`       

* * *  

## Week 5: {{ site.week-05 }}  
### <span style="color: #10999e;">{{ site.week-05-topic }}</span>    
    
#### Terms, Concepts, Objects, Shortcuts    
- recursion  
- recursive function   

* * *   
  
## Week 6: {{ site.week-06 }}  
### <span style="color: #10999e;">{{ site.week-06-topic }}</span>    

* * *

## Week 7: {{ site.week-07 }}  
### <span style="color: #10999e;">{{ site.week-07-topic }}</span>    

* * *  

## Week 8: {{ site.week-08 }}  
### <span style="color: #10999e;">{{ site.week-08-topic }}</span>    
   
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
