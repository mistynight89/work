# work

<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
<ul>
	<li class="marked">html</li>
	<li>css</li>
	<li id="active">JavaScript
		<ul>
			<li>JavaScript Core</li>
			<li class="marked">DOM</li>
			<li class="marked">BOM</li>
		</ul>
	</li>
</ul>
<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
<script>
	
	$('#active').css('color', 'blue').find('.marked').css('background-color', 'red');
</script>

</body>
</html>
