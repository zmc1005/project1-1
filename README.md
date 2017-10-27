# project1-1
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<title>Boy or girl</title>
</head>
<body>
	<script type="text/javascript">
		var fname, ltr
		fname = prompt('Enter your name', 0);
		ltr = fname.substr(fname.length -1, 1);
		
		if (ltr =='a' || ltr =='y') {
			alert('Your name is female.')
			alert(ltr);
		}
		else {
			alert('Your name is male.')
		}
		
		document.write('<h1>' + fname + '</h1>');
	</script>
</body>
</html>
