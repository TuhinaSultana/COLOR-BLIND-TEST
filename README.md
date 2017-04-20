# COLOR-BLIND-TEST
This system will help to test colorblindness of all ages of people
<?php 
include "header.php"; 
include "navbar.php";
?>

<html>

	<head>
	<meta http-equiv="content type" content="text/html;charset= UTF-8"/>
		<link rel= "stylesheet" type= "text/css" href= "css/bootstrap.min.css"/>
		<link rel= "stylesheet" type= "text/css" href= "css/bootstrap-theme.min.css"/>
		<link rel= "stylesheet" type= "text/css" href= "home page style.css"/>
	</head>
<body class="b"> <br><br><br><br><br><br><br>
	<div class = "container">
		<div class= "row">
			<div class = "fruit">
				<div id="my-slider" class="carousel slide" 
					data-ride="carousel">
					
					<! ---indicator dot nov--- >
					
					<ol class="carousel-indicators">
						<li data-target="#my-slider" 
						data-slide-to="0" class="active"> </li>
						
						<li data-target="#my-slider" 
						data-slide-to="1" > </li>
					</ol>
					
					<! ---wrapper for slide--- >
						
						<div class="carousel-inner" role="listbox">
							<div class="item active">
								<img src="fruits.jpg" alt="summer"/>
								<div class="carousel-caption">
									<h1>fruit</h1>
								</div>	
							</div>
							
							<div class="item">
								<img src="lake.jpg" alt="summer"/>
								<div class="carousel-caption">
									<h1>lake</h1>
								</div>	
							</div>
						</div>
					
					<! ---next & previous botton--- >
						
						<a class="left carousel-control" href="#my-slider" 
						role="button" data-slide="prev">
						
							<span class="glyphicon glyphicon-chevron-left"
							aria-hidden="true">
							</span>
							<span class="sr-only"> previous </span>
						</a>
						<a class="right carousel-control" href="#my-slider" 
						role="button" data-slide="next">
						
							<span class="glyphicon glyphicon-chevron-right"
							aria-hidden="true">
							</span>
							<span class="sr-only"> next </span>
						</a>
				</div>	
			</div>
		</div>
	</div>
	
			<div class= "CB">
 <p> 
First of all we would like to clear the concept of color blindness. Well, color blind people are not like any other blind people. They are blind about only some specific colors. That means they can not visualize all the colors individually.
Color blindness, also known as color vision deficiency, is the decreased ability to see color or differences in color.
Color blindness can make some educational activities difficult. Buying fruit, picking clothing, and reading traffic lights can also be more challenging. Problems, however, are generally minor and most people adapt. People with total color blindness, may also have decreased visual acuity.
 </p>
 <p> 
Do the autumn colors on both sides of this photo (right top) look the same to you? If so, you could have red-green color blindness.
 </p>
 <br>
 <p> <b> (In Bengali)</b> <br>
বর্ণান্ধতা সচরাচর অন্ধত্বের মত নয়। একজন বর্ণান্ধ ব্যক্তি কেবল কিছু নির্দিষ্ট বর্ণ বা রং সম্পর্কে অজ্ঞাত থাকেন। কারণ তিনি ঐ নির্দিষ্ট রং এর সাথে অন্য রং এর কোন পার্থক্য খুঁজে পান না। 
একজন বর্ণান্ধ ব্যক্তি দৈনন্দিন কাজে বেশ কিছু সমস্যার সম্মূখীন হন। যেমন- বাজার করা, কোন সুনির্দিষ্ট রং এর কাপড় বাছাই করা, ট্রাফিক সিগনাল সঠিকভাবে বুঝতে না পারা ইত্যাদি।
যদি আপনি লেকের পাশাপাশি ছবি দুটির ভেতর কোন পার্থক্য দেখতে না পান, তবে প্রাথমিকভাবে আপনি লাল-সবুজ বর্ণান্ধতার স্বীকার।
 </p>
			</div>

<br>

</body>
<?php include('footer.php')?>

<script src="js/jquery.min.js" > </script>
<script src="js/bootstrap.min.js" > </script>

</html>
