
<!-- saved from url=(0259)https://615110777-atari-embeds.googleusercontent.com/embeds/16cb204cf3a9d4d223a0a3fd8b0eec5d/inner-frame-minified.html?jsh=m%3B%2F_%2Fscs%2Fabc-static%2F_%2Fjs%2Fk%3Dgapi.lb.en.AOzoyjtjrhQ.O%2Fd%3D1%2Frs%3DAHpOoo9-fA1P7IZFa1fdRj158NoDqrnbYA%2Fm%3D__features__ -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><!--<base target="_blank">--><base href="." target="_blank"></head><body><button class="c-button">PLAY FULLSCREEN</button>
<style>
.c-button {
  min-width: 100%;
  font-family: fantasy;
  appearance: none;
  border: 0;
border-color: #fff;
  border-radius: 5px;
  background: #274e13;
  color: #fff;
  padding: 0px 46px;
  font-size: 20px;
  cursor: pointer;
}

.c-button:hover {
  background: #6aa84f;
}

.c-button:focus {
  outline: none;
  box-shadow: 0 0 0 4px #cbd6ee;
}
  
 .c-button {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100%;
}

</style>

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
