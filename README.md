# WhatsApp-Script

Send Whatspp Text By JavaScript
Here is small JS Script for sending a message in a loop.

Steps to Do it:-

Open Whatsapp web on your browser Chrome (https://web.whatsapp.com/)
Scan the QR Code
Select the person you want to send the text
press clt + shift + j
In developer Console paste the code
Change the text "Sample Texts" in the code by your message like "Hey Bro!!"
Send Enter Note Make sure your mobile has Internet Connection
```
var count = 100 // Change the Number to change var looper = 0 
for(looper=0;looper<count;looper++) { window.InputEvent = window.Event || window.InputEvent; 
var d = new Date(); var event = new InputEvent('input', {bubbles: true}); 
var textbox= document.querySelector('#main > footer > div._3pkkz > div._1Plpp > div > div._2S1VP.copyable- text.selectable-text'); textbox.textContent = "Sample Text"; 
textbox.dispatchEvent(event); document.querySelector("#main > footer > div._3pkkz > div > button > span").click(); }
```
