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

<tr><th> First</th> <th>Last</th> <th>Degree(s)</th> <th>Department(s)</th> <th>Position</th> <th>Organization</th> <th>Email</th></tr>

  </thead>
  <tbody id="myTable">

<tr><td> Mindy</td> <td>Hong</td> <td>PhD, MSPH</td> <td>Statistics</td> <td>Postdoctoral Researcher</td> <td>Northwestern University Department of Dermatology - Feinberg School of Medicine</td> <td></td></tr>



</tbody>
</table>
  


</body>
</html>


