# Colab Tools

Prevent runtime disconnect:
```
function clickConnect() {
    document.querySelector("colab-connect-button").click()
    console.log("Reconnected notebook."); 
}
setInterval(clickConnect,60000)
```
