Greetings like welcome, goodbye and banbye can set in different ways
1. You can change greetings video by changing WELCOME or BANBYE or GOODBYE var<br>
```WELCOME:url```<br>
 <img src="https://i.imgur.com/gQc2lhO.jpeg" width=406 height=131><br>
 <img src= "https://i.imgur.com/WcuLd4b.jpeg" width=406 height=83><br>
if bot not working set to WELCOME:false<br>
2. You can also set a specific video for a group by setting WELCOME_JID or GOODBYE_JID or BANBYE_JID , While setting this You have to note one thing that if setting one jid then you have to set two urls in WELCOME, similarly if you set two jids then three urls so on.<br>
```WELCOME_JID:jid and WELCOME:url1,url2``` or<br>
```WELCOME_JID:jid1,jid2 && WELCOME:url1,url2,url3```<br>
 <img src="https://i.imgur.com/qofTT9M.jpeg" width=406 height=145><br>
 <img src="https://i.imgur.com/pwTTZzT.jpeg" width=406 height=111><br>
 <img src= "https://i.imgur.com/vSGK9Bq.jpeg" width=406 height=89><br>
3. Now about the message, You can set welcome message in 4 different ways like a message without mention or buttons, with mention , with mention and button , button only.

```Example : without mention and button => .welcome Hi welcome to * Group.
Example : with mention => .welcome Hi `mention` welcome to * Group.
Example : with mention and button => .welcome Hi `mention` welcome to * Group. `button/I'm fine` `button/I'm ok` `button/Not Bad` `header/How are you?`
Example : with button => .welcome Hi welcome to * Group `button/I'm fine` `button/I'm ok` `button/Not Bad` `header/How are you?`
```
to delete => ```.welcome delete ```<br>
to get current greetings => ```.welcome```