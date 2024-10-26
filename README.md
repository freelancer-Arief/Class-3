# Class-3
<!Doctype html>
<html>
	<head>
		<title>Class 03||WDD 2409 | Roll - 08</title>
		</head>
		
<body>
<p>Use Iframe tag to show any website in your website.<br><iframe src="Website url"></iframe></p><br>
	<iframe src="https://drive.google.com/drive/folders/1uDcd2XASfhHE2inUqcdkyU72MsU9cWM7"></iframe>
	<iframe src="https://uylab.org/"></iframe>
	<iframe src="https://www.youtube.com/"></iframe><br><br><br><br>
	
	<iframe src="https://drive.google.com/drive/folders/1uDcd2XASfhHE2inUqcdkyU72MsU9cWM7" width="200" Height="150"></iframe>
	<iframe src="https://uylab.org/"></iframe>
	<iframe src="https://www.youtube.com/"></iframe>
	
<p>How to Purchase Domain & Hosting From Namecheap | UY Lab</p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlK7Tkj8QU?si=R0gDQNBxwBO6alWa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<a href="https://maps.app.goo.gl/e4Q7ZH2HKJtttE2i6" target="-blank">গণভবন লোকেশন</a>

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1871983.1297748196!2d88.20879339375001!3d23.596547500000007!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3755c1ba10483ab3%3A0xf9e797ed24edcd81!2z4KaX4Kaj4Kat4Kas4KaoIOCmquCngeCmsuCmv-CmtiDgpqzgppXgp43gprg!5e0!3m2!1sbn!2sbd!4v1729522404073!5m2!1sbn!2sbd" width="560" height="315" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

<marquee>To scroll  text you have to use marquee tag</marquee>

<marquee onmouseover="this.stop()" onmouseout="this.start()">
    This text will stop scrolling when hovered.
</marquee>
	

<video width="600" height="300" controls><source src="video/videoplayback.mp4"></video>

<video width="600" height="300" controls><source src="Class 3 homework/Bitul Mukarram.mp4"></video>

<h5>Nation anthem of Bangladesh</h5>

<audio controls><source src="Class 3 homework/আমার সোনার বাংলা_Amar Sonar Bangla (BTV).mp3"></audio>

<audio controls><source src="video/National anthem.mp3"></audio>

<br><br>

<h3>How to create a form</h3>

<form>

<h1>Registration Form</h1>
<label>Name</label>
<input type="text" required="required" placeholder="Input your name" pattern="[A-Za-z\s]+" title="Only letters and spaces are allowed">

<br>

<label>Phone Number</label>
<input type="Number" placeholder="Input your phone number">

<label>Phone Number</label>
  <input type="tel" placeholder="Input your phone number" pattern="\d{11}" title="Phone number must be exactly 11 digits with no spaces" maxlength="11" required>

<br>

<label>Email</label>
<input type="email" placeholder="Input your E-mail address">

<br>

<label>Password</label>
<input type="Password" placeholder="Input your Password" pattern="(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{8,}" title="Password must contain at least one uppercase letter, one lowercase letter, one number, and one special character. Minimum 8 characters." required>

<br>

<label>Gender</label>
<input type="Radio" name="I">Male
<input type="Radio" name="I">Feale
<input type="Radio" name="I">Third Gender

<br>

<label>Hobby:-</label>
<input type="Checkbox">Movie
<input type="Checkbox">Gaming
<input type="Checkbox">Playing
<input type="Checkbox">Reading
<input type="Checkbox">Travelling

<br>

<label>Birthday</label>
<input type="date">

<br>
<br>

<label>Address (Maximum 100 characters allowed):</label>
<textarea placeholder="Input your address" maxlength="100" style="resize: none;width: 400px; height: 100px;"></textarea>
<style resize: none></style>

<br>
<br>

<label>Address (Maximum 100 characters allowed):</label>
<textarea id="address" placeholder="Input your address" maxlength="100" oninput="updateCount()" style="resize: none;width: 400px; height: 100px;"></textarea>
<p id="charCount">100 characters remaining</p>

<script>
function updateCount() {
  const textarea = document.getElementById('address');
  const remaining = 100 - textarea.value.length;
  document.getElementById('charCount').textContent = remaining + ' characters remaining';
}
</script>

<br><br>

<label>Upload photo/video</label>
<input type="file">

<br><br>

<button type="submit">Submit</button>
<button type="reset">Reset</button>

</form>

</body>
</html>
