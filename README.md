<html>
<head>
    <title>SPACEPORT2000</title>
</head>
<body>  <body bgcolor="purple"><canvas id="gameCanvas" width="700" height="500"></canvas>
    <script>
        const FPS = 30; // frames per second
        const FRICTION = 0.7; // friction coefficient of space (0 = no friction, 1 = lots of friction)
        const SHIP_SIZE = 30; // ship height in pixels
        const SHIP_THRUST = 5; // acceleration of the ship in pixels per second per second
        const TURN_SPEED = 360; // turn speed in degrees per second

        /** @type {HTMLCanvasElement} */
        var canv = document.getElementById("gameCanvas");
        var ctx = canv.getContext("2d");

        // set up the spaceship object
        var ship = {
            x: canv.width / 2,
            y: canv.height / 2,
            r: SHIP_SIZE / 2,
            a: 90 / 180 * Math.PI, // convert to radians
            rot: 0,
            thrusting: false,
            thrust: {
                x: 0,
                y: 0
            }
        }


<meta charset="UTF-8">
    <title>TODO title</title>
    <style></style>



<script>
    "use strict";
    // TODO JavaScript
</script>
    <center><h1><font size="4"</font><font color="yellow"</font><font face="fixedsys"</font>My First Heading</h1></center>
    <p>My first paragraph.</p>
</body>
</html>
