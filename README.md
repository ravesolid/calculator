# calculator
const num1 = parseFloat(prompt('Enter nr1:'));
const num2 = parseFloat(prompt('Enter nr2:'));

const operator = prompt('Enter operator(+,-,/,*');
let result = 0;
if(isNaN(num1) || isNaN(num2)){
    alert('Wrong Input! Refresh the page and provide detail')
}else{
    if(operator== '+'){
        result = num1 + num2;
    }else if(operator == '-'){
        result = num1 - num2;
    }else if(operator == '/'){
        result = num1 / num2;
    }else if(operator == '*'){
        result = num1 * num2;
    }
    alert(num1+operator+num2+'=' + result);
}


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
   
</head>
<body>
    <script src="script.js"></script>
</body>
</html>
