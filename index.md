---
title: UCSB CS111
---

# {{site.course}} {{site.quarter}}&mdash;{{site.course_title}}

{% include cs111_logo.html %}


{% include catalog_description.md %}

{% include collapse-button.html label="Information and Resources" id="info-list" %}
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

{% include collapse-button.html label="Discussion Section Notes and Files" id="discussions" %}
<div class="collapse" id="discussions">
 <div class="card card-body" markdown="1">
   <a href="https://github.com/ucsb-cs111/w20-lecture-files/tree/master/discussion_section_files">Files</a>
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
