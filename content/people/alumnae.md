---
title: 'WIST Alumnae'
author: ''
date: '2019-12-23'
slug: executive-board
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

<tr><th> First</th> <th>Name</th> <th>WIST Role</th> <th>Department</th> <th>Position</th></tr>


  </thead>
  <tbody id="myTable">

<tr><td> Martha</td> <td>Eichlersmith</td> <td>Member</td> <td>Statistics</td> <td>Graduate Student, PhD</td></tr>
<tr><td> Yajun</td> <td>Liu</td> <td>Executive Board</td> <td>Statistics</td> <td>Graduate Student, PhD</td></tr>
<tr><td> Noelle</td> <td>Samia</td> <td>Faculty Chair</td> <td>Statistics</td> <td>Faculty</td></tr>
<tr><td> Abby</td> <td>Smith</td> <td>Executive Board</td> <td>Statistics</td> <td>Graduate Student, PhD</td></tr>
<tr><td> Mena</td> <td>Whalen</td> <td>Executive Board</td> <td>Statistics</td> <td>Graduate Student, PhD</td></tr>
<tr><td> Rrita</td> <td>Zejnullahi</td> <td>Executive Board</td> <td>Statistics</td> <td>Graduate Student, PhD</td></tr>




</tbody>
</table>
  


</body>
</html>


