<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>button chenge</title>
    <style>
        .div1 {
            text-align: center;
    </style>
</head>
<body>
    2Q) Create a html button and align it on the center of the screen and on clicking that button,change the background
    color of the whole page.
    <div class="div1">
        <body id="bod">
            <button onclick="func1()">click</button>
    </div>
    <script>
        function func1() {
            document.getElementById('bod').style.backgroundColor = "red"
        }
        
    </script>
</body>
