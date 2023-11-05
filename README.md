<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><base href="." target="_blank"></head>
<body>
    <button class="button" onclick="openGame('classroom.google.com.html')">Cookie Clicker</button>

    <!--button template-->
    <!--<button class="button" onclick="openGame('GAME URL')">GAME NAME</button>-->

    <script>
        function openGame(url) {
            var win = window.open();
            win.document.body.style.margin = '0';
            win.document.body.style.height = '100vh';
            var iframe = win.document.createElement('iframe');
            iframe.style.border = 'none';
            iframe.style.width = '100%';
            iframe.style.height = '100%';
            iframe.style.margin = '0';
            iframe.src = url;
            win.document.body.appendChild(iframe);
        }
    </script>
</body>
</html>
