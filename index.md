---
title: UCSB CS111
---

# {{site.course}} {{site.quarter}}&mdash;{{site.course_title}}

{% include cs111_logo.html %}

{% include collapse-button.html label="About this course" id="about" %}
<div class="collapse" id="about">
 <div class="card card-body" markdown="1">
A course taught 
in the [Dept. of Computer Science](http://www.cs.ucsb.edu) at
[UC Santa Barbara](http://www.ucsb.edu)

{% include catalog_description.md %}


This site is maintained in this github repo: <{{site.github_url}}>

</div>
</div>


{% include collapse-button.html label="Information" id="info-list" %}
<div class="collapse" id="info-list">
 <div class="card card-body">
  {% include info_list.html %}
 </div>
</div>


{% include collapse-button.html label="Lecture Notes and Files" id="lectures" %}
<div class="collapse" id="lectures">
 <div class="card card-body" markdown="1">
   {%include lecnot_table.html %}
 </div>
</div>

{% include collapse-button.html label="Homework" id="hwk" %}
<div class="collapse" id="hwk">
 <div class="card card-body">
  {% include hwk_table.html %}
 </div>
</div>

{% include collapse-button.html label="Exams" id="exams" %}
<div class="collapse" id="exams">
 <div class="card card-body">
  {%include exam_table.html %}
 </div>
</div>


