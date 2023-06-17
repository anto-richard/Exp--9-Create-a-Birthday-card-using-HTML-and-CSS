# Exp--9-Create-a-Birthday-card-using-HTML-and-CSS...

## AIM:

To create a Birthday card using HTML and CSS.

## ALGORITHM:

### Step 1:

Set up the basic structure of your HTML document and include the CSS stylesheet.

### Step 2:

Design the layout of your birthday card using HTML elements such as < div >, < h1 >, < p >, < img >, and < span >. 

### Step 3:

Add a container < div > to hold the entire birthday card content.
  
### Step 4:

Use paragraph tag to disply the personalised greeting. Add an image element to display a birthday-themed image.

## PROGRAM:

### BIRTHDAY.HTML:

```html

<!DOCTYPE html>
<html>
<head>
	<title>Birthday Card</title>
	<style>
		body {
			background-image: url('https://img.freepik.com/premium-vector/happy-birthday-greeting-card-background_9111-79.jpg');
			background-repeat: no-repeat;
			background-size: cover;
			font-family: Arial, sans-serif;
			text-align: center;
		}
		.card {
			background-color: #fff;
			box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
			max-width: 500px;
			margin: 0 auto;
			padding: 20px;
			border-radius: 10px;
			margin-top: 50px;
		}
		h1 {
			font-size: 48px;
			color: #333;
			margin-bottom: 20px;
		}
		img {
			width: 100%;
			max-width: 300px;
			margin-bottom: 20px;
			border-radius: 10px;
		}
		p {
			font-size: 24px;
			color: #666;
			line-height: 1.5;
			margin-bottom: 30px;
		}
		.btn {
			background-color: #4CAF50;
			color: #fff;
			padding: 10px 20px;
			border-radius: 5px;
			text-decoration: none;
			font-size: 20px;
			transition: all 0.3s ease-in-out;
		}
		.btn:hover {
			background-color: #3e8e41;
		}
	</style>
</head>
<body>
	<div class="card">
		<h1>Happy Birthday!</h1>
		<img src="https://www.hepper.com/wp-content/uploads/2021/11/dog-with-party-hat-and-birthday-cake_Ruth-Black_shutterstock.webp" alt="Birthday Cake">
		<p>Happie birthday Chester !!! 
            <br>
            “Your bark is my morning alarm and my ‘welcome home’ greeting. The wagging of your tail is my comfort and my stress buster. The way you cuddle beside me is all the love I ever need. Happy birthday, buddy!”</p>
		<a href="https://media.tenor.com/Uy7OBMYdocEAAAAM/excited-dog.gif" class="btn">Send a Gift</a>
	</div>
	
</body>
</html>

````

## OUTPUT:

![A](https://github.com/anto-richard/Exp--9-Create-a-Birthday-card-using-HTML-and-CSS/assets/93427534/7a57ca32-bc44-4cb7-b938-6cec55062242)


![B](https://github.com/anto-richard/Exp--9-Create-a-Birthday-card-using-HTML-and-CSS/assets/93427534/b6c37077-cf0a-4474-95db-f88b0b1302ff)


## RESULT:

So,  a birthday card is created using CSS and HTML.


