* **SUDO**<br>
setvar SUDO:919876543210 if number is +91 98765 43210,<br>also for more sudos SUDO:9876543210,9012345678,...<br>
Also can change in apps settings<br><br>
* **What do if i logout or changed whatsapp ?**<br>
No need to deploy new APP <br>
take new session by scanning QR<br>
change ASENA_SESSION with new session and<br>
set CLR_SESSION = true then after Successful login<br>
set CLR_SESSION = false <br><br>
* **Change ALIVE message ?**<br>
setvar ALIVE_MSG: Don't take life too seriously.<br>
if you want image or video in alive message then<br>
set ALIVE_URL = https://i.pinimg.com/736x/89/96/d2/8996d212b2cb35d5fc18898a78cad391--heart-love.jpg<br><br>
* **How enable anti link ?**<br>
install anti link plugin<br>
add group jid in ANTIJID
example ANTIJID = 987654321-1689238292@g.us<br>
also can allow urls in group by adding<br>
URLS in ALLOWED_URLS<br>
example ALLOWED_URLS = fb.com,facebook.com,chat.whatsapp.com,instagram.com