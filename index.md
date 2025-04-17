---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 50.00%;
  padding: 10px;
}
  
.column img {
  margin-top: 12px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="row">
  <div class="column">
    <a href="/spaces/">
      <img src="/images/C-Space.png" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/floors/">
      <img src="/images/C-Floor.png" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/home/">
      <img src="/images/C-Home.png" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/buildings/">
      <img src="/images/C-Building.png" style="width:100%">
    </a>
  </div>
</div>
<div class="row">
  <div class="column">
    <a href="/schools/">
      <img src="/images/C-School.png" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/neighborhoods/">
      <img src="/images/C-Neighbourhood.png" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/city/">
      <img src="/images/C-City.png" style="width:100%">
    </a>
  </div>
  <div class="column">
    <a href="/world/">
      <img src="/images/C-World.png" style="width:100%">
    </a>
  </div>
</div>

</body>
</html>
