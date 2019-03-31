<!--# Survey-Form
It is a simple html form with little touch of css.-->

 <!DOCTYPE hmtl>
<html lang="eng">

<head>
	<title>
		My Survey Form
	</title>
 <script type="text/css">
 	
body {
	background-color: #66624b;
    display: inline-block;
	padding: 50px;
	margin: 20px;
}

#description {
	text-align: center;
    font-style: 
}

#title {
	color: #96ad64; 
	text-align: center;
	margin: 20px;
}
 
#survey-form {
	background-color: #726109;
	font-family: cursive;
}


#description {
	font-family: 
}
 </script>
	
</head>

<body> 
	<div id="container">
	<h1 id="title">Survey Form</h1>
	<p id="description">Kindly input your details in the following</p>
	
	<form id="survey-form">
	<fieldset>
		<p><label id="name-label" for="name">Name:</label><br>
		<input type="name" id="name" name="name" placeholder="Enter name" required="required" />
		<br/> 
		<label id="email-label" for="emai">Email:</label><br>
		<input type="email" id="email" name="email" placeholder="Enter email" required="required" /><br />
        <label id="number-label" for="number">Number:</label><br>
		<input type="number" id="number"  placeholder="Enter number" min="11" max="13"  value="+234" required="required" /></p>
		<div>
		<span class="title">Gender:</span>
		<input type="radio" name="gender" id="male"
		value="M" />
		<label for="male">Male</label>
		<input type="radio" name="gender" id="female"
		value="F" />
		<label for="female">Female</label>
		<input type="radio" name="gender" id="others"
		value="O" />
		<label for="others">Others</label><br/>
		</div>

		<p>Please select your favorite genre:
		<input type="checkbox" name="afrobeat"
		value="afrobeat" checked="checked" />Afrobeat 
		<input type="checkbox" name="jazz"
		value="jazz" /> Jazz
		<input type="checkbox" name="pop"
		value="pop" /> Pop
		<input type="checkbox" name="rock"
		value="rock" /> Rock
		</p>

		<p><label for="continent"> Kindly select your continent:</label>
			<select name="continent" id="dropdown">
				<option class="">Africa</option>
				<option>Europe</option>
				<option>South America</option>
				<option>North America</option>
				<option>Australia</option>
				<option>Asia</option>
				<option>Others</option>
			</select></p>
			<p>Kindly add more details in case some vital info are skipped</p>
			<textarea name="comments" cols="20" rows="4">Enter your comments...</textarea>
			<br />
			<input id="submit" type="submit" name="submit"
			value="Submit" />
	</fieldset>	
	</form>
</div>
</body>
</html>
