---
title: 'WIST Alumnae'
author: ''
date: '2019-12-23'
slug: alumnae
categories: []
tags:
subtitle: ''
summary: ''
authors: []
lastmod: '2019-12-23T14:00:01-06:00'
featured: no
image: 
  caption: ''
  focal_point: ''
  preview_only: true
projects: []

---

<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
  $("#myInput").on("keyup", function() {
    var value = $(this).val().toLowerCase();
    $("#myTable tr").filter(function() {
      $(this).toggle($(this).text().toLowerCase().indexOf(value) > -1)
    });
  });
});
</script>

</head>
<body>

<input id="myInput" type="text" placeholder="Search..">
<br><br>

<table>
  <thead>
<!-- PUT THE TABLE HEADER BETWEEN THESE TWO LINES -->

<tr><th> Name</th> <th>Position</th> <th>Organization</th> </tr>

<!-- PUT THE TABLE HEADER BETWEEN THESE TWO LINES -->
  </thead>
  <tbody id="myTable">

<!-- PUT THE TABLE BODY BETWEEN THESE TWO LINES -->


<tr><td> Mindy Hong (2019)</td> <td>Postdoctoral Researcher</td> <td>Northwestern University Department of Dermatology - Feinberg School of Medicine</td> </tr>
<tr><td> Minhai Zheng (2019)</td> <td>Data Scientist</td> <td>Capital One</td> </tr>
<tr><td> Wenqian Wang (2019)</td> <td>Data Scientist</td> <td>LinkedIn</td> </tr>


<!-- PUT THE TABLE BODY BETWEEN THESE TWO LINES -->
</tbody>
</table>
  


</body>
</html>


