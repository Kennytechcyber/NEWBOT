Greetings like welcome, goodbye and banbye can set in different ways
1. You can change greetings media(profile pic to image/video) by changing WELCOME or BANBYE or GOODBYE var<br>

Example<br>`WELCOME:url` and `WELCOME_JID:jid`<br>
url can be a video or image, jid is group's jid where the url's media has to.<br><br>
for multiple groups<br>
`WELCOME:url1,url2 and WELCOME_JID:jid1,jid2`

3. Now about the message, You can set welcome message in 4 different ways like a message without mention or buttons, with mention , with mention and button , button only.

```
Example : without mention and button    => .welcome Hi welcome to * Group.
Example : with mention                  => .welcome Hi `mention` welcome to * Group.
Example : with mention and button       => .welcome Hi `mention` welcome to * Group. `button/I'm fine` `button/I'm ok` `button/Not Bad` `header/How are you?`
Example : with button                   => .welcome Hi welcome to * Group `button/I'm fine` `button/I'm ok` `button/Not Bad` `header/How are you?`
```
to delete                => `.welcome delete `<br>
to get current greetings => `.welcome`