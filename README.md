-<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>圣杯布局</title>
<style type="text/css">
      *{
      	margin: 0;
        padding: 0;
      }
      #head{
      	margin:0px 100px 0px 100px;
      

      }
      .left {
      	position: relative;
      	float: left;
      	background-color:blue; 
      	margin-left: -100%;
      	width: 100px;
      	height: 70px;
      	left: -100px;
      }
      #center{ 
      float:left; 
      	width: 100%;
      	height: 100px;
      	background-color: red;
      }
      #right{
      	position: relative;
      	margin-left: -100px;
      	float:left;
      	width: 100px;
      	height: 70px;
      	background-color: yellow;
      	right: -100px;
      }
      
</style>
</head>

<body id="head">
	<div>
	<div id="center">我是中间</div>
	<div class="left">我是左边</div>	
  <div id="right">我是右边</div>
  </div>
    
</body>

</html>
=
