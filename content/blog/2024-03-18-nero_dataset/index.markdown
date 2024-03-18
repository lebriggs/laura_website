---
title: "Information For The Data Pre-Analysis Plan Workshop"
subtitle: "Instructions And Dataset"
excerpt: "Information required for a 30-minute hands-on workshop exploring the world of effective data pre-analysis planning using Canva. 


Through a real dataset example, we'll tackle challenges like a myopic view of your data and work together to enhance your data analysis decision-making skills. Ever wished for a visual aid to communicate your analysis plan? You're in luck! No previous knowledge of Canva is needed – just bring your curiosity and enthusiasm!"
date: 2024-03-18
author: "Laura Briggs"
draft: false
images:
series:
tags:
categories:
  - GSD data
  - workshop
  - data cleaning
layout: single
---

{{< here >}}

### A Data Pre-Analysis Plan Using Canva: Workshop Description

This 30-minute hands-on workshop will introduce you to the world of effective data pre-analysis planning using Canva. Delivered through a completed example with a real dataset, you’ll gain insights into overcoming challenges such as a myopic view of your data and improving your data analysis decision-making skills. Wish you had a visual aid to communicate your analysis plan? Then join me for a practical session that transforms how you approach data analysis! No previous knowledge of Canva is required.

## Intended Audience

This workshop is designed for anyone who has a keen interest in data analysis. No previous knowledge of the tool, Canva, is required. However, it will be helpful if you have an understanding of a few fundamental terms used in R Studio such as categorical variable and dataframe. Questions are encouraged during the workshop!

- Faculty Members
- Graduate Students
- Undergraduate Students
- UVic Staff
- General Public

## Learning Outcomes

By the end of this workshop, participants will be able to:

Understand the advantages of creating a data pre-analysis plan in Canva.
Identify the six sections of a robust data pre-analysis plan.
Know how to add and read comments on an existing data pre-analysis plan in Canva.
Recognize when and how to integrate a data pre-analysis plan into their own projects.
Leave with an editable version of the example discussed in the workshop that can be modified to suit their own work.

## Agenda

The agenda for today’s workshop is outlined below.

1.  Introduction & Demonstration of the Data Pre-Analysis Plan in Canva (7 min)
2.  Explanation of the Activity (3 min)
3.  The Activity (10 min)
4.  Group Discussion (5 min)
5.  Additional Resources (2 min)

## Description Of The Dataset Used To Create The Example

The Nero vom Buchonia dataset contains show ratings, performance titles, and health information about the offspring of a male workingline German Shepherd Dog named G Nero vom Buchonia IGP3 KKL.
It represents a typical dataset observed in the context of German Shepherd Dog (GSD) breeding. Note that it uses specialized terminology that might be unfamiliar to you.
There are missing values in the dataset.
The information is derived from a mixture of public and private data sources.

### It’s important to note that:

The table below is only a small subset of a much larger dataset.
No data dictionary is available, a common feature of canine datasets.
For educational purposes, web scraping is permitted in order to access the data for analysis.

### Acknowledgement:

Thank you to Jennifer Lee, Nero’s owner, for helping to create this dataset for the workshop.

## The Dataset: Nero vom Buchonia’s Offspring

<div id="rnxyaljcvk" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#rnxyaljcvk table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#rnxyaljcvk thead, #rnxyaljcvk tbody, #rnxyaljcvk tfoot, #rnxyaljcvk tr, #rnxyaljcvk td, #rnxyaljcvk th {
  border-style: none;
}
&#10;#rnxyaljcvk p {
  margin: 0;
  padding: 0;
}
&#10;#rnxyaljcvk .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 3px;
  border-top-color: #D5D5D5;
  border-right-style: solid;
  border-right-width: 3px;
  border-right-color: #D5D5D5;
  border-bottom-style: solid;
  border-bottom-width: 3px;
  border-bottom-color: #D5D5D5;
  border-left-style: solid;
  border-left-width: 3px;
  border-left-color: #D5D5D5;
}
&#10;#rnxyaljcvk .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#rnxyaljcvk .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#rnxyaljcvk .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#rnxyaljcvk .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#rnxyaljcvk .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D5D5D5;
}
&#10;#rnxyaljcvk .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D5D5D5;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#rnxyaljcvk .gt_col_heading {
  color: #FFFFFF;
  background-color: #004D80;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#rnxyaljcvk .gt_column_spanner_outer {
  color: #FFFFFF;
  background-color: #004D80;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#rnxyaljcvk .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#rnxyaljcvk .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#rnxyaljcvk .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D5D5D5;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#rnxyaljcvk .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#rnxyaljcvk .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D5D5D5;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D5D5D5;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#rnxyaljcvk .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D5D5D5;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D5D5D5;
  vertical-align: middle;
}
&#10;#rnxyaljcvk .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#rnxyaljcvk .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#rnxyaljcvk .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #89D3FE;
  border-left-style: solid;
  border-left-width: 1px;
  border-left-color: #89D3FE;
  border-right-style: solid;
  border-right-width: 1px;
  border-right-color: #89D3FE;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#rnxyaljcvk .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #5F5F5F;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#rnxyaljcvk .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#rnxyaljcvk .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#rnxyaljcvk .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#rnxyaljcvk .gt_summary_row {
  color: #333333;
  background-color: #89D3FE;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#rnxyaljcvk .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D5D5D5;
}
&#10;#rnxyaljcvk .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#rnxyaljcvk .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D5D5D5;
}
&#10;#rnxyaljcvk .gt_grand_summary_row {
  color: #FFFFFF;
  background-color: #00A1FF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#rnxyaljcvk .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D5D5D5;
}
&#10;#rnxyaljcvk .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D5D5D5;
}
&#10;#rnxyaljcvk .gt_striped {
  background-color: #F4F4F4;
}
&#10;#rnxyaljcvk .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D5D5D5;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D5D5D5;
}
&#10;#rnxyaljcvk .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#rnxyaljcvk .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#rnxyaljcvk .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#rnxyaljcvk .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#rnxyaljcvk .gt_left {
  text-align: left;
}
&#10;#rnxyaljcvk .gt_center {
  text-align: center;
}
&#10;#rnxyaljcvk .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#rnxyaljcvk .gt_font_normal {
  font-weight: normal;
}
&#10;#rnxyaljcvk .gt_font_bold {
  font-weight: bold;
}
&#10;#rnxyaljcvk .gt_font_italic {
  font-style: italic;
}
&#10;#rnxyaljcvk .gt_super {
  font-size: 65%;
}
&#10;#rnxyaljcvk .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#rnxyaljcvk .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#rnxyaljcvk .gt_indent_1 {
  text-indent: 5px;
}
&#10;#rnxyaljcvk .gt_indent_2 {
  text-indent: 10px;
}
&#10;#rnxyaljcvk .gt_indent_3 {
  text-indent: 15px;
}
&#10;#rnxyaljcvk .gt_indent_4 {
  text-indent: 20px;
}
&#10;#rnxyaljcvk .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="7" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><strong>Nero vom Buchonia Offspring Data</strong></td>
    </tr>
    &#10;    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="&lt;strong&gt;Name&lt;/strong&gt;"><strong>Name</strong></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="&lt;strong&gt;KKL&lt;/strong&gt;"><strong>KKL</strong></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="&lt;strong&gt;Birth Date&lt;/strong&gt;"><strong>Birth Date</strong></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="&lt;strong&gt;Sex&lt;/strong&gt;"><strong>Sex</strong></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="&lt;strong&gt;Colour&lt;/strong&gt;"><strong>Colour</strong></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="&lt;strong&gt;Hips And Elbows Rating&lt;/strong&gt;"><strong>Hips And Elbows Rating</strong></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="&lt;strong&gt;ZW&lt;/strong&gt;"><strong>ZW</strong></th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Name" class="gt_row gt_left">G Nero vom Buchonia IGP3</td>
<td headers="KKL" class="gt_row gt_left">Yes</td>
<td headers="BirthDate" class="gt_row gt_left">March 9, 2013</td>
<td headers="Sex" class="gt_row gt_left">Male</td>
<td headers="Colour" class="gt_row gt_left">grey</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left">a-normal; Normal</td>
<td headers="ZW" class="gt_row gt_right">88</td></tr>
    <tr><td headers="Name" class="gt_row gt_left gt_striped">Faine Auf der Marquis IGP1</td>
<td headers="KKL" class="gt_row gt_left gt_striped"></td>
<td headers="BirthDate" class="gt_row gt_left gt_striped">May 10, 2019</td>
<td headers="Sex" class="gt_row gt_left gt_striped">Male</td>
<td headers="Colour" class="gt_row gt_left gt_striped">black-tan</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left gt_striped">a-normal; Normal</td>
<td headers="ZW" class="gt_row gt_right gt_striped">80</td></tr>
    <tr><td headers="Name" class="gt_row gt_left">Falco Auf der Marquis IGP1</td>
<td headers="KKL" class="gt_row gt_left"></td>
<td headers="BirthDate" class="gt_row gt_left">May 10, 2019</td>
<td headers="Sex" class="gt_row gt_left">Male</td>
<td headers="Colour" class="gt_row gt_left">grey</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left">a-normal; Normal</td>
<td headers="ZW" class="gt_row gt_right">80</td></tr>
    <tr><td headers="Name" class="gt_row gt_left gt_striped">Forest Ranger Auf der Marquis IGP1</td>
<td headers="KKL" class="gt_row gt_left gt_striped"></td>
<td headers="BirthDate" class="gt_row gt_left gt_striped">May 10, 2019</td>
<td headers="Sex" class="gt_row gt_left gt_striped">Male</td>
<td headers="Colour" class="gt_row gt_left gt_striped">grey</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left gt_striped">a-normal; Normal</td>
<td headers="ZW" class="gt_row gt_right gt_striped">80</td></tr>
    <tr><td headers="Name" class="gt_row gt_left">Fallon Auf der Marquis IGP1</td>
<td headers="KKL" class="gt_row gt_left"></td>
<td headers="BirthDate" class="gt_row gt_left">May 10, 2019</td>
<td headers="Sex" class="gt_row gt_left">Female</td>
<td headers="Colour" class="gt_row gt_left">bicolor</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left">a-normal; Normal</td>
<td headers="ZW" class="gt_row gt_right">80</td></tr>
    <tr><td headers="Name" class="gt_row gt_left gt_striped">Yogi vom Owenberg</td>
<td headers="KKL" class="gt_row gt_left gt_striped"></td>
<td headers="BirthDate" class="gt_row gt_left gt_striped">May 10, 2019</td>
<td headers="Sex" class="gt_row gt_left gt_striped">Male</td>
<td headers="Colour" class="gt_row gt_left gt_striped">black-tan</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left gt_striped">a-normal; Fast Normal</td>
<td headers="ZW" class="gt_row gt_right gt_striped">80</td></tr>
    <tr><td headers="Name" class="gt_row gt_left">SG Brynn vom Adlerland IGP2</td>
<td headers="KKL" class="gt_row gt_left"></td>
<td headers="BirthDate" class="gt_row gt_left">August 28, 2018</td>
<td headers="Sex" class="gt_row gt_left">Female</td>
<td headers="Colour" class="gt_row gt_left">sable</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left">Excellent; Normal</td>
<td headers="ZW" class="gt_row gt_right"></td></tr>
    <tr><td headers="Name" class="gt_row gt_left gt_striped">Banshee vom Aderland ACT2</td>
<td headers="KKL" class="gt_row gt_left gt_striped"></td>
<td headers="BirthDate" class="gt_row gt_left gt_striped">August 28, 2018</td>
<td headers="Sex" class="gt_row gt_left gt_striped">Female</td>
<td headers="Colour" class="gt_row gt_left gt_striped">bicolor</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left gt_striped">Good; Normal</td>
<td headers="ZW" class="gt_row gt_right gt_striped"></td></tr>
    <tr><td headers="Name" class="gt_row gt_left">Baha vom Aderland CGC</td>
<td headers="KKL" class="gt_row gt_left"></td>
<td headers="BirthDate" class="gt_row gt_left">August 28, 2018</td>
<td headers="Sex" class="gt_row gt_left">Female</td>
<td headers="Colour" class="gt_row gt_left">black-tan</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left">Good; Normal</td>
<td headers="ZW" class="gt_row gt_right"></td></tr>
    <tr><td headers="Name" class="gt_row gt_left gt_striped">Baalos vom Aderland</td>
<td headers="KKL" class="gt_row gt_left gt_striped"></td>
<td headers="BirthDate" class="gt_row gt_left gt_striped">August 28, 2018</td>
<td headers="Sex" class="gt_row gt_left gt_striped">Male</td>
<td headers="Colour" class="gt_row gt_left gt_striped">black-tan</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left gt_striped">Good; Normal</td>
<td headers="ZW" class="gt_row gt_right gt_striped"></td></tr>
    <tr><td headers="Name" class="gt_row gt_left">Tesla vom Wildhaus IGP1</td>
<td headers="KKL" class="gt_row gt_left"></td>
<td headers="BirthDate" class="gt_row gt_left">January 13, 2018</td>
<td headers="Sex" class="gt_row gt_left">Female</td>
<td headers="Colour" class="gt_row gt_left">black-tan</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left">a-normal; Normal</td>
<td headers="ZW" class="gt_row gt_right">80</td></tr>
    <tr><td headers="Name" class="gt_row gt_left gt_striped">Trauma vom Wildhaus IGP1</td>
<td headers="KKL" class="gt_row gt_left gt_striped"></td>
<td headers="BirthDate" class="gt_row gt_left gt_striped">January 13, 2018</td>
<td headers="Sex" class="gt_row gt_left gt_striped">Female</td>
<td headers="Colour" class="gt_row gt_left gt_striped">sable</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left gt_striped">Excellent; Normal</td>
<td headers="ZW" class="gt_row gt_right gt_striped"></td></tr>
    <tr><td headers="Name" class="gt_row gt_left">Torque vom Wildhaus</td>
<td headers="KKL" class="gt_row gt_left"></td>
<td headers="BirthDate" class="gt_row gt_left">January 13, 2018</td>
<td headers="Sex" class="gt_row gt_left">Male</td>
<td headers="Colour" class="gt_row gt_left">bicolor</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left">NA; Normal</td>
<td headers="ZW" class="gt_row gt_right"></td></tr>
    <tr><td headers="Name" class="gt_row gt_left gt_striped">Chimera von Bairdhaus</td>
<td headers="KKL" class="gt_row gt_left gt_striped"></td>
<td headers="BirthDate" class="gt_row gt_left gt_striped">January 13, 2018</td>
<td headers="Sex" class="gt_row gt_left gt_striped">Female</td>
<td headers="Colour" class="gt_row gt_left gt_striped">grey</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left gt_striped">Mittlere; Normal</td>
<td headers="ZW" class="gt_row gt_right gt_striped">120</td></tr>
    <tr><td headers="Name" class="gt_row gt_left">SG Halo z Tammik BH</td>
<td headers="KKL" class="gt_row gt_left"></td>
<td headers="BirthDate" class="gt_row gt_left">September 15, 2020</td>
<td headers="Sex" class="gt_row gt_left">Male</td>
<td headers="Colour" class="gt_row gt_left">black-tan</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left">a-normal; Normal</td>
<td headers="ZW" class="gt_row gt_right">80</td></tr>
    <tr><td headers="Name" class="gt_row gt_left gt_striped">Blackthorn's Game Changer</td>
<td headers="KKL" class="gt_row gt_left gt_striped"></td>
<td headers="BirthDate" class="gt_row gt_left gt_striped">November 20, 2020</td>
<td headers="Sex" class="gt_row gt_left gt_striped">Male</td>
<td headers="Colour" class="gt_row gt_left gt_striped">sable</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left gt_striped">Good; Normal</td>
<td headers="ZW" class="gt_row gt_right gt_striped"></td></tr>
    <tr><td headers="Name" class="gt_row gt_left">G Kikki von Bairdhaus IGP3</td>
<td headers="KKL" class="gt_row gt_left">Yes</td>
<td headers="BirthDate" class="gt_row gt_left">December 20, 2020</td>
<td headers="Sex" class="gt_row gt_left">Female</td>
<td headers="Colour" class="gt_row gt_left">grau</td>
<td headers="HipsAndElbowsRating" class="gt_row gt_left">a-fast normal; Fast Normal</td>
<td headers="ZW" class="gt_row gt_right">99</td></tr>
  </tbody>
  &#10;  
</table>
</div>