<!DOCTYPE html><html><head>

<title>Calculator</title><meta charset="utf-8">

<script type="text/javascript">

function cube() {

var num = document.getElementById("n1");

num.value = Math.pow(num.value, 3);

}

</script>

</head>

<body>

Number:

<input type="text" id="n1"><p>

<button onclick="cube()"> x^3 </button>

</body>

</html>
