### Hi there 👋
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            background-color: #ecefff
        }

        .center {
            position: absolute;
            margin: auto;
            left: 0;
            top: 0;
            bottom: 0;
            right: 0;
            width: 250px;
            height: 250px;
            background-color: #42a5f5;
            box-shadow: 0px 0px 50px 3px #000;
        }

        span {
            left: 10%;
            top: 10%;
            box-shadow: 0px 0px 25px #000;
        }

        span:nth-child(1) {
            position: absolute;
            width: 220px;
            height: 220px;
            background-color: #90caf9;
            left: 6%;
            animation: ani 3s infinite;
            animation-delay: 0.3s;
        }

        span:nth-child(2) {
            position: absolute;
            width: 200px;
            height: 200px;
            background-color: #bbdefb;
            left: 10%;
            top: 10%;
            animation: ani 3s infinite;
            animation-delay: 0.4s;
        }

        span:nth-child(3) {
            position: absolute;
            width: 180px;
            height: 180px;
            background-color: #e3f2fb;
            left: 14%;
            top: 14%;
            animation: ani 3s infinite;
            animation-delay: 0.5s;
        }

        span:nth-child(4) {
            position: absolute;
            width: 160px;
            height: 160px;
            background-color: #90caf9;
            left: 18%;
            top: 18%;
            animation: ani 3s infinite;
            animation-delay: 0.6s;
        }

        span:nth-child(5) {
            position: absolute;
            width: 140px;
            height: 140px;
            background-color: #e3f2fd;
            left: 22%;
            top: 22%;
            animation: ani 3s infinite;
            animation-delay: 0.7s;
        }

        span:nth-child(6) {
            position: absolute;
            width: 120px;
            height: 120px;
            background-color: #90caf9;
            left: 26%;
            top: 26%;
            animation: ani 3s infinite;
            animation-delay: 0.8s;
        }

        span:nth-child(7) {
            position: absolute;
            width: 100px;
            height: 100px;
            background-color: #bbdefb;
            left: 33%;
            top: 33%;
            animation: ani 3s infinite;
            animation-delay: 1s;
        }

        @keyframes ani {
            0% {
                transition: 0.7s;
                transform: rotate(0deg);
            }

            20% {
                transition: 0.7s;
                transform: rotate(95deg);
            }

            50% {
                transition: 0.7s;
                transform: rotate(360deg);
            }

            100% {
                transition: 0.7s;
                transform: rotate(0deg);
            }

        }
    </style>
    <title>Document</title>
</head>

<body>
    <div class="center">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>

    </div>

</body>

</html>
