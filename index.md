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

.row {
  display: flex;
  flex-wrap: wrap;
  margin: -10px;
}

.column {
  flex: 1 1 50%; /* grow, shrink, base width */
  padding: 10px;
}

.column img {
  width: 100%;
  margin-top: 12px;
}

/* Optional: force exact layout for wider screens */
@media screen and (min-width: 768px) {
  .column {
    flex: 1 1 25%;
  }
}
</style>
</head>
<body>

<div class="row">
  <div class="column">
    <a href="/spaces/">
      <img src="/images/C-Space.png">
    </a>
  </div>
  <div class="column">
    <a href="/home/">
      <img src="/images/C-Home.png">
    </a>
  </div>
  <div class="column">
    <a href="/floor/">
      <img src="/images/C-Floor.png">
    </a>
  </div>
  <div class="column">
    <a href="/buildings/">
      <img src="/images/C-Building.png">
    </a>
  </div>
  <div class="column">
    <a href="/schools/">
      <img src="/images/C-School.png">
    </a>
  </div>
  <div class="column">
    <a href="/neighborhoods/">
      <img src="/images/C-Neighbourhood.png">
    </a>
  </div>
  <div class="column">
    <a href="/city/">
      <img src="/images/C-City.png">
    </a>
  </div>
  <div class="column">
    <a href="/world/">
      <img src="/images/C-World.png">
    </a>
  </div>
</div>

</body>
</html>
