<center>
<button onclick="openGame()" > Play in Fullscreen </button>
<script>
function openGame() {
	var win = window.open ()
	var url = "URL BRUH"
	var iframe = win.document.createElement('iframe')
	iframe.style.width = "100%"
	iframe.style.height = "100%"
	iframe.style.border = "none"
	iframe.src = url
	win.document.body.appendChild(iframe)
}
</script>
</center>
