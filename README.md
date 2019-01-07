# javascriptact4
act4
<!DOCTYPE html>
<html>
<head>
	<title>Quennie nicole alcasin</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1"		>
</head>
<body>

<label>Enter Amount:</label>
<input type="text" id="result">
<input type="button" value="350ML" onclick="coffee1()">
<input type="button" value="450ML" onclick="coffee2()">
<input type="button" value="750ML" onclick="coffee3()">
<script type="text/javascript">

function acceptinput()
{
 var x = Number(document.getElementById('value').value);
 return x;
}
function getchange (change)
{
 alert("Enjoy your coffee"+"your change is"+ change)
}
function checkamount (amount,price)
{
 if (isNaN(amount))
{
 alert ('INVALID')
}
else if (amount >=price)
{
 var change =0;
 change=amount-price;
 getchange(change)
}

}


function coffee1()
{  
 var x = acceptinput();
 var cprice=25;
 checkamount(x,price);
 }

function coffee2()
{  
 var x = acceptinput();
 var cprice=30;
 checkamount(x,price);
 }

function coffee3()
{  
 var x = acceptinput();
 var cprice=50;
 checkamount(x,price);
 }

</script>
</body>
</html>


