### **SUDO**<br>
```
setvar SUDO:919876543210 //if number is +91 98765 43210 
for more sudos SUDO:9876543210,9012345678
You can change in apps settings too
```
### **What do if i logout or changed whatsapp ?**<br>
```
No need to deploy new APP 
take new session by scanning QR
change ASENA_SESSION with new session and
set CLR_SESSION = true //then after Successful login
set CLR_SESSION = false
```
### **Change ALIVE message ?**<br>
```
Example: .alive Hey I'm running for #uptime //for text only
Example: .alive Hi https://i.pinimg.com/736x/89/96/d2/8996d212b2cb35d5fc18898a78cad391--heart-love.jpg //for image or video
```
### **How enable anti link ?**<br>
```
Example: .antilink on //for Enabling and off for Disabling.
Example: .antilink instagram.com,facebook.com,fb.com // for allow any links in group.
```
### **How enable anti fake ?**<br>
```
Example: .antifake on // for Enabling and off for Disabling.
Example: .antifake 1,994,44 // for Choosing the country codes.
```
### **How enable anti bad ?**<br>
```
Example: .antibad on // for Enabling and off for Disabling
Example: .antibad word1,word2 // for adding words.
```
### **How to change sticker pack info ?**<br>
```
setvar STICKER_PACKNAME: name,author // with name and author
setvar STICKER_PACKNAME: name // only name
setvar STICKER_PACKNAME: false // no pack info
OR
STICKER_PACKNAME = name,author //in heroku settings
```
### **What is difference between banbye and goodbye ?**
```
BANBYE is when kicking from group.
GOODBYE is when left from group.
```
### **How to use mention ?**
```
Example: .mention on //to enable
Example: .mention hello // to update mention message
use image url for => image, sticker
use video url for => gif, mp4, sticker, audio

Example

.mention url type/sticker
.mention url type/mp4 caption
.mention url type/audio 

can add multiple urls (randomly send)
```
### **How to set HANDLERS free ?**
```
Example: .setvar HANDLERS:false
```
### **How to change prefix or HANDLERS ?**
```
Example: .setvar HANDLERS:^[.!,]
```
### **What about BAN?** 
```
Don't use bot in way that against WhatsApp policies.
Don't use add command in fake number and better don't use it often.
Don't use forward or broadcast to too much jids.
```
### **Delete Broadcast**
```
You can't delete Broadcast once created
but you can update jids (use same name and create as new one)
```

### **Can I block or disable bot in specific chat?**
```
.setvar DISABLE_BOT:jid1,jid2...
or
DISABLE_BOT = jid1,jid2,jid3,... in heroku app settings var
```