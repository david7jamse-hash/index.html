<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DekeVana SAT Resources - Grade 10</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #4CAF50; /* Green background */
            color: white;
            text-align: center;
            padding: 50px;
        }
        h1 {
            font-size: 2em;
            margin-bottom: 40px;
        }
        button {
            background-color: #2E7D32;
            color: white;
            border: none;
            padding: 15px 25px;
            margin: 10px;
            font-size: 1em;
            cursor: pointer;
            border-radius: 8px;
        }
        button:hover {
            background-color: #1B5E20;
        }
    </style>
</head>
<body>
    <h1>DekeVana SAT Resources - Grade 10</h1>

    <button onclick="openLink('https://satsuite.collegeboard.org/media/pdf/sat-student-guide.pdf')">
        Open SAT Student Guide PDF
    </button>
    <br>
    <button onclick="openLink('https://satsuite.collegeboard.org/media/pdf/sat-practice-test-10-digital.pdf')">
        Open Digital SAT Practice Test PDF
    </button>
    <br>
    <button onclick="openLink('https://edu.google.com/')">
        Open Google Education
    </button>

    <script>
        function openLink(url) {
            window.open(url, '_blank');
        }
    </script>
</body>
</html>
