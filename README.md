<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Heart</title>
<style>
.heart {
  width: 100px;
  height: 100px;
  position: relative;
  display: inline-block;
  background: red;
  transform: rotate(-45deg);
  margin: 50px;
}

.heart::before,
.heart::after {
  content: "";
  width: 100px;
  height: 100px;
  background: red;
  position: absolute;
  border-radius: 50%;
}

.heart::before {
  top: -50px;
  left: 0;
}

.heart::after {
  left: 50px;
  top: 0;
}
</style>
</head>
<body>

<div class="heart"></div>

</body>
</html>
