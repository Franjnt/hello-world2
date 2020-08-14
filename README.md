<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NPM Clone</title>
    <link rel="stylesheet" href="./estilos.css" />
</head>

<h1>Rover</h1>

<body>
    <div id="space"></div>
        <div id="rover"></div>
</div>

</html>




//css

#space {
    width: 200px;
    height: 200px;
    background: green;
    position: relative;
}

#rover {
    width: 50px;
    height: 50px;
    background: red;
    position: absolute;
}



var horizontal = i(9);
var vertical = j(9);

rover = (0, 0);

function moveRight() {
    for(i=0, i =< 9, i++);
        if(rover === 37, i++);
            console.log(rover[i]);
            else {
                if(i>9, !moveRight);
            }
}

function moveLeft() {
    for(i=9, i >= 0, i--);
        if(rover === 39, i--);
            console.log(rover[i]);
            else{
                if(i<0, !moveLeft);
            }
}

function moveDown() {
    for(j=0, j =< 9, j++);
        if(rover === 40, i++);
            console.log(rover[j]);
            else {
                if(j>9, !moveDown);
}

function moveUp() {
    for(j=9, j >= 0, j--);
        if(rover === 38, j--);
            console.log(rover[j]);
            else {
                if(j<0, !moveUp);
