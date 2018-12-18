
<!DOCTYPE html>
<html>
<head>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
  border-right:1px solid #bbb;
}

li:last-child {
  border-right: none;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 26px;
  text-decoration: none;
}

li a:hover:not(.active) {
  background-color: #111;
}

.active {
  background-color: #4CAF50;
}
</style>
</head>
<body>

<ul>
  <li><a href="#Home">Home</a></li>
  <li><a href="#Apple">Apple</a></li>
  <li><a href="#Samsung">Samsung</a></li>
  <li><a href="#LG">LG</a></li>
  <li><a href="#Huawei">Huawei</a></li>
  <li><a href="#Sony">Sony</a></li>
  <li><a href="#Google">Google</a></li>
  <li style="float:right"><a href="#about">About</a></li>
</ul>

 <img src="phone.jpg" alt="picture phone" width="300" height="300">

  
</body>
</html>
