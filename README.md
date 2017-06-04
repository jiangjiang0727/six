<html>
<head>
<meta charset="utf-8">
<script src="https://libs.baidu.com/jquery/1.10.2/jquery.min.js">
</script>
<script>
$(document).ready(function(){
  $("#btn1").click(function(){
    $("ol").prepend("<li> </li>");
  });
 $("#btn2").click(function(){
    $("ol").empty();
  });
});
</script>
</head>

<body>
<p>全运会比赛开始时间</p>
<button id="btn1">开始时间</button>
<button id="btn2">清除</button>
<ol>
</ol>
</body>
</html>
