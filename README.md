<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div id="app">
        <p>這裡有一個p標籤</p>
    </div>
    <script>

        let app = document.querySelector('#app').innerHTML;
        let app_text = document.querySelector('#app').innerText;
        console.log(app);
        console.log(app_text);
        
    </script>


</body>
</html>

