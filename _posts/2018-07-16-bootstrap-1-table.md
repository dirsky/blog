---
layout: post
title: 表格
author: Frank
category: Learn
tags: Learn
published: true
---

### 基本表格
<table class="table table-striped">
<!-- On rows -->
<tr class="active"><td>...</td></tr>
<tr class="success"><td>...</td></tr>
<tr class="warning"><td>...</td></tr>
<tr class="danger"><td>table-striped</td></tr>
<tr class="info"><td>...</td></tr>
</table>

<table class="table table-bordered">
<!-- On cells (`td` or `th`) -->
<tr>
  <td class="active">...</td>
  <td class="success">...</td>
  <td class="warning">...</td>
  <td class="danger">...</td>
  <td class="info">...</td>
</tr>
<tr>
  <td class="active">...</td>
  <td class="success">...</td>
  <td class="warning">table-bordered</td>
  <td class="danger">...</td>
  <td class="info">...</td>
</tr>
</table>

<table class="table table-hover">
<!-- On cells (`td` or `th`) -->
<tr>
  <td class="active">悬停</td>
  <td class="success">table-hover</td>
  <td class="warning">...</td>
  <td class="danger">...</td>
  <td class="info">...</td>
</tr>
<tr>
  <td class="active">...</td>
  <td class="success">...</td>
  <td class="warning">...</td>
  <td class="danger">...</td>
  <td class="info">...</td>
</tr>
</table>

<table class="table table-condensed">
<!-- On cells (`td` or `th`) -->
<tr>
  <td class="active">压缩</td>
  <td class="success">table-condensed</td>
  <td class="warning">...</td>
  <td class="danger">...</td>
  <td class="info">...</td>
</tr>
<tr>
  <td class="active">...</td>
  <td class="success">...</td>
  <td class="warning">...</td>
  <td class="danger">...</td>
  <td class="info">...</td>
</tr>
</table>



### 栅格表格
<div class="container-fluid">
<!-- Stack the columns on mobile by making one full-width and the other half-width -->
<div class="row">
  <div class="col-xs-12 col-md-8">.col-xs-12 .col-md-8</div>
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
</div>

<!-- Columns start at 50% wide on mobile and bump up to 33.3% wide on desktop -->
<div class="row">
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
</div>

<!-- Columns are always 50% wide, on mobile and desktop -->
<div class="row">
  <div class="col-xs-6">.col-xs-6</div>
  <div class="col-xs-6">.col-xs-6</div>
</div>
</div>