# First_web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <input type="text" id="p1" placeholder="Enter 1st number">
    <br>
    <br>
    <input type="text" id="p2" placeholder="Enter 2nd number">
    <br>
    <br>
    <button onclick="ADD()">ADD</button>
    <h2 id="result">  Result- </h2>
    <script>
        function ADD(){
            let a1=document.getElementById('p1').value;
            let a2=document.getElementById('p2').value;
            document.getElementById('result').innerHTML = `Result - ${Number(a1)+Number(a2)}`
        }
    </script>
</body>
</html>
