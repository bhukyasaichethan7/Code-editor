# Code-editor
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="bootstrap.css">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="script.js"></script>
    <title>Made By Gagan Arora</title>
</head>
<body>
    <div class="conatiner header">
        <div class="row justify-content-center">
            <h2 class="header-content">Frontend Code Editor</h2>
        </div>
    </div>
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <div class="left">
                    <label><i class="fa-brands fa-html5"></i> HTML</label>
                    <textarea id="html-code" onkeyup="ans()"></textarea>

                    <label><i class="fa-brands fab fa-css3-alt"></i> CSS</label>
                    <textarea id="css-code" onkeyup="ans()"></textarea>

                    <label><i class="fa-brands fa-js"></i> JavaScript</label>
                    <textarea id="js-code" onkeyup="ans()"></textarea>
                </div>
            </div>
            <div class="col-md-6">
                <div class="right">
                    <label><i class="fa-solid fa-play"></i> Output</label>
                    <iframe id="output"></iframe>
                </div>
            </div>
        </div>
    </div>
    <footer>
        <div class="row justify-content-center">
            <h3>Made with <span>&hearts;</span> by <a href="https://gagan.click">Gagan Arora</a></h3>
        </div>
    </footer>
</body>
</html>
