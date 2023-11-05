<center>
  <div id="fullscreen-text" style="cursor: pointer; text-decoration: underline; color: blue;">Play in Fullscreen</div>
</center>
<script>
document.getElementById("fullscreen-text").addEventListener("click", openGame);

function openGame() {
  var win = window.open();
  var url = "URL BRUH";
  var iframe = win.document.createElement('iframe');
  iframe.style.width = "100%";
  iframe.style.height = "100%";
  iframe.style.border = "none";
  iframe.src = url;
  win.document.body.appendChild(iframe);
}
</script>
