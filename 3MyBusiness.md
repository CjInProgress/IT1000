# Hello, and welcome to my Business page.

## Business

### Here are a few **quick** facts about me:
1. I started photography in 2019.
2. I get *contracted* by the University of Missouri to do video and photo work.

### **Fun Fact**
My work has recieved recognition from the Director of the Portland Foundation of Art.

### **Pictures**
This is a picture I've taken:

![alt text](https://github.com/CjInProgress/IT1000/blob/main/085A0793.jpg)

Here's a picture I've taken:

![alt text](https://images.squarespace-cdn.com/content/v1/5ea8f9fcd5913d4f94bbd59e/1601962253547-7Y0ZF6KXG7VXRBJ1T74Q/ke17ZwdGBToddI8pDm48kMXRibDYMhUiookWqwUxEZ97gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0luUmcNM2NMBIHLdYyXL-Jww_XBra4mrrAHD6FMA3bNKOBm5vyMDUBjVQdcIrt03OQ/085A2031.jpg?format=500w)

### **Code**
This is my FizzBuzz code...
``` html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 0; i < 100; i++) {
		if (i % 3 == 0 && i % 5 == 0 && i != 0) {
			displayHTML += "<p>" + "FizzBuzz" + "</p>";
		}
		else if (i % 3 == 0 && i != 0) {
			displayHTML += "<p>" + "Fizz" + "</p>";
		}
		else if (i % 5 == 0 && i != 0) {
			displayHTML += "<p>" + "Buzz" + "</p>";
		}
		else {
			displayHTML += "<p>" + i + "</p>";
		}

	}
	display.innerHTML = displayHTML
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```

### **Other Pages**
You can visit the other pages by clicking one of the links:
1. [Homepage]()
2. [Work Experience]()
3. **My Business**
4. [How I Spend My Timw]()
5. [Miscellaneous]()
6. [My Photography Page](cjharrisphotgraphy.com)
