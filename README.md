<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
</head>
<style type="text/css">
	body{
		background-color: #D7BDE2  ;
		user-select: none;
	}
	.cal{
		display: grid;
		grid-template-columns: 1fr 1fr 1fr 1fr 1fr ;
		grid-gap: 12px;
		padding: 12px;
		font-family: bold;
		max-width: none;
	}
	.eee{
		background-color: #F5EEF8;
		padding: 16px;
		display: flex;
		justify-content: center;
     	cursor: pointer;
		font-size: 16px;
		font-weight: bold;
	}
	form{
		max-width: 100%;

	}
	input{
		width:90%;
		height: 60%;
		border: 5px;
		font-size: 25px;
		outline: none;
		text-align: right;
	 
	}

  </style>
  <form action="numbers" name="hhh" class="cal">
  <input type="numbers" name="num" class="cal" readonly>
	<span class="eee" onclick="document.hhh.num.value+='1'">1</span>
	<span class="eee" onclick="document.hhh.num.value+='2'">2</span>
	<span class="eee" onclick="document.hhh.num.value+='3'">3</span>
	<span class="eee" onclick="document.hhh.num.value+='4'">4</span>
	<span class="eee" onclick="document.hhh.num.value+='+'">+</span>
	<span class="eee" onclick="document.hhh.num.value+='5'">5</span>
	<span class="eee" onclick="document.hhh.num.value+='6'">6</span>
	<span class="eee" onclick="document.hhh.num.value+='7'">7</span>
	<span class="eee" onclick="document.hhh.num.value+='8'">8</span>
	<span class="eee" onclick="document.hhh.num.value+='-'">-</span>
	<span class="eee" onclick="document.hhh.num.value+='9'">9</span>
	<span class="eee" onclick="document.hhh.num.value+='0'">0</span>
	<span class="eee" onclick="document.hhh.num.value+='('">(</span>
	<span class="eee" onclick="document.hhh.num.value+=')'">)</span>
    <span class="eee" onclick="document.hhh.num.value+='*'">*</span>
    <span class="eee" onclick="document.hhh.num.value+='%'">%</span>
	<span class="eee sqrt" onclick="document.hhh.num.value=Math.sqrt(document.hhh.num.value)">√</span>
	<span class="eee" onclick="document.hhh.num.value+='**'">^</span>
	<span class="eee" onclick="document.hhh.num.value+='.'">.</span>
	<span class="eee" onclick="document.hhh.num.value+='/'">/</span>
		<span class="eee" onclick="document.hhh.num.value=Math.sin(document.hhh.num.value)">sin</span>
	<span class="eee" onclick="document.hhh.num.value=Math.cos(document.hhh.num.value)">cos</span>
	<span class="eee" onclick="document.hhh.num.value=Math.tan(document.hhh.num.value)">tg</span>
	<span class="eee" onclick="document.hhh.num.value=1/Math.tan(document.hhh.num.value)">ctg</span>
	<span class="eee" onclick="document.hhh.num.value=eval(hhh.num.value)">=</span>
	
	<span class="eee clean" onclick="document.hhh.num.value=''">C</span>
	<script type="text/javascript">
		function clean(){
		document.hhh.num.value=document.hhh.num.value="";
	}
	
</script>

