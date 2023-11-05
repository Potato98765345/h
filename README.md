<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><base href="." target="_blank"></head><body><button class="c-button">PLAY FULLSCREEN</button>
<style>

<script>
        var urlObj = new window.URL(window.location.href);
        var url = "https://potato98765345.github.io/h/";

        if (url) {
            var win;

            document.querySelector('button').onclick = function() {
                if (win) {
                    win.focus();
                } else {
                    win = window.open();
                    win.document.body.style.margin = '0';
                    win.document.body.style.height = '100vh';
                    var iframe = win.document.createElement('iframe');
                    iframe.style.border = 'none';
                    iframe.style.width = '100%';
                    iframe.style.height = '100%';
                    iframe.style.margin = '0';
                    iframe.src = url;
                    win.document.body.appendChild(iframe);
                    

                    var interval = setInterval(function() {
                        if (win.closed) {
                            clearInterval(interval);
                            win = undefined;

                        }
                    }, 500);
                }
            };
        }
    </script></body></html>
