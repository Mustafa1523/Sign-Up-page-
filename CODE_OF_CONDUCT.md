<!-- 
|add by Mustafa
|01152478229
|Facebook:Mu ST aFa 

-->
<!DOCTYPE html>
<html>
<head>
	<title>Button_Title</title>
</head>
<style type="text/css">
.top
{
	font-family:sans-serif;
	justify-content:center;
	align-items:center;
	background-image:linear-gradient(125deg,#7481c9,#54cce2,#6c80ee);
	background-size:500%;
	animation-name:intro;
	animation-delay:.5s;
	animation-duration:20s;
	animation-timing-function:ease-in;
	animation-iteration-count:infinite;
}

@keyframes intro {
	0% {
		background-position:100% 0% ;

	}

	50% {background-position: 50% 0% }

	100% {background-position: 0% 100%}
}





.hello
{
  width:30em;
  height:300px;
  background:#fff;
  margin:10% auto;
  border-radius: 100px 10px 100px  0px;
  
}

.top .hello h3
{
	text-align: center;
    padding: 5%;
    margin-bottom: 0px;
    font-size: 20px;
    font-family: sans-serif;
    text-transform: uppercase;
    color: #5266d7;
}
.top .hello form > input
{
	padding: 7px;
    margin: 3% 12.5%;
    width: 25em;
    border: 0px;
    border-bottom: 1px solid #5c70e0;
}

.top .hello form > .btn_info {
    width: 123px;
    height: 45px;
    margin-top: 0px;
    border: 0px;
    background: linear-gradient(125deg,#5d71e1,#8394f4);
    color: aliceblue;
    font-size: 19px;
    font-family: sans-serif;
    text-transform: uppercase;
    box-shadow: 0px 1px 5px #9e9c9c;
}



</style>
<body class="top">
	<div class='hello'>
		<h3>Sgin Up</h3>
  <form>
    
    <input type="text" placeholder="Username">
    <input type="email" name="email" placeholder="@Email">	
    <input type="text" name="password" placeholder="Password">
    <input class="btn_info" type="submit"	value="Sgin">
  </form>
</div>
</body>
</html>
