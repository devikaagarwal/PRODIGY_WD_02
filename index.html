<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stopwatch</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        #stopwatch {
            font-size: 48px;
            margin-bottom: 20px;
        }
        button {
            font-size: 20px;
            margin: 5px;
        }
    </style>
</head>
<body>
    <div id="stopwatch">00:00:00</div>
    <button id="start">Start</button>
    <button id="pause">Pause</button>
    <button id="reset">Reset</button>
    <button id="lap">Lap</button>
    <div id="laps"></div>

    <script>
        let startTime, updatedTime, difference, tInterval;
        let running = false;
        let lapCount = 0;

        function startTimer() {
            if (!running) {
                startTime = new Date().getTime() - difference;
                tInterval = setInterval(updateTime, 1);
                running = true;
            }
        }

        function updateTime() {
            updatedTime = new Date().getTime();
            difference = updatedTime - startTime;

            let hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            let minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
            let seconds = Math.floor((difference % (1000 * 60)) / 1000);

            document.getElementById("stopwatch").innerHTML = 
                (hours < 10 ? "0" : "") + hours + ":" + 
                (minutes < 10 ? "0" : "") + minutes + ":" + 
                (seconds < 10 ? "0" : "") + seconds;
        }

        function pauseTimer() {
            clearInterval(tInterval);
            running = false;
        }

        function resetTimer() {
            clearInterval(tInterval);
            running = false;
            difference = 0;
            document.getElementById("stopwatch").innerHTML = "00:00:00";
            document.getElementById("laps").innerHTML = "";
            lapCount = 0;
        }

        function lapTimer() {
            if (running) {
                lapCount++;
                let lapTime = document.getElementById("stopwatch").innerHTML;
                document.getElementById("laps").innerHTML += "Lap " + lapCount + ": " + lapTime + "<br>";
            }
        }

        document.getElementById("start").onclick = startTimer;
        document.getElementById("pause").onclick = pauseTimer;
        document.getElementById("reset").onclick = resetTimer;
        document.getElementById("lap").onclick = lapTimer;
    </script>
</body>
</html>
