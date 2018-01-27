<div class="container padding" id="contact">
		<form role="form" action="contact.php" method="post">
			<div class="form-group">
				<label for="email">Email:</label> <input type="email" class="form-control" id="email" name="email" placeholder="buchewebzine@gmail.com>
			</div>
			<div class="form-group">
				<label for="name">Name:</label>
				<input type="text" class="form-control" id="name" name="name" placeholder="Your name here">
			
			</div>
			<div class="form-group">
				<label for="message">Message:</label>
				<textarea class="form-control" name="message" id="message" placeholder="Your message here"></textarea>
			</div>
			<div class="form-group">
			</div>
			<button type="submit" class="btn btn-default">Submit</button>
		</form>

<!--?php
$from = "buchewebzine@gmail.com";
$to = "buchewebzine@gmail.com";
$name = Trim(stripslashes($_POST['name']));
$email = Trim(stripslashes($_POST['email']));
$message = Trim(stripslashes($_POST['message']));
$promo = Trim(stripslashes($_POST['promo']));
$body ="";
$body .="Name: ";
$body .=$name;
$body .="n";
$body .="Email: ";
$body .=$email;
$body .="n";
$body .="Message: ";
$body .=$message;
$body .="n";
$body .="Promo accepted? ";
$body .=$promo;
$body .="n";
$go = mail($to, $subject, $body, "From:<$from-->
</div>
