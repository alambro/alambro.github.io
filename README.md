# alambro.github.io
  
<!DOCTYPE html>
<html lang="en">
<meta charset="UTF-8">




<style>
	h1 {text-align: center;}
	h2 {text-align: center;}
	h3 {text-align: center;}
</style>

<div>
	<h1>3 box thoughts </h1>
</div>


<body style="background-color:#F0F8FF;">


 
<div>
<h2>
 	<button onclick= "Next()"; type="button">Next</button>
 	<button onclick= "Previous()";type="button"> Previous</button>
 	<button onclick= "Random()"; type="button">Random</button>
	<button onclick= "Archive()"; type="button">Archive</button>
</h2>
</div>


<div>
<h3>

	<p id="demo"> </p>
    <img id="image" src = "alambro/alambro.github.io/comicphotos/bigbook_1.jpg" alt= "comic" >
    

<script type="text/javascript"> 
	   var x = 1
	   var comic = "alambro/alambro.github.io/comicphotos/bigbook_" + i + ".jpg"
	function Next()
		{
		var i = x++
		var comic = "alambro/alambro.github.io/comicphotos/bigbook_" + i + ".jpg"
	    	document.getElementById("demo").innerHTML= comic 
            document.getElementById("image").src = comic
		} 
	function Previous()
		{
		var i = x--
		var comic = "alambro/alambro.github.io/comicphotos/bigbook_" + i + ".jpg"
	    	document.getElementById("demo").innerHTML= comic 
	    	document.getElementById("image").src = comic
		}

</script>


	
</h3>
</div>

</body>
</html>
