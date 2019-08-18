# JavaScript
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Tic Tac Toe</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <div class='game'></div>

    <script src="js/tic-tac-toe.js"></script>
    <script>
        tic_tac_toe.init( document.querySelector('.game') );
        tic_tac_toe.start();
    </script>

</body>
</html> 
