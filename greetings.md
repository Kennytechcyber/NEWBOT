Greetings like welcome, goodbye and banbye can set in different ways
1. To set image or video or profile pic<br>
```
Example: .welcome Hi `pp` for profile pic of joined or added.
Example: .welcome Hi https://i.pinimg.com/736x/8f/02/ea/8f02ea3c223cd3170176d3f180d464f2.jpg
for image or video in welcome or banbye or goodbye
```
2. Now about the message, You can set welcome message in 4 different ways like a message without mention or buttons, with mention , with mention and button , button only.

```
Example : without mention and button 
=> .welcome Hi welcome to #name.

Example : with mention 
=> .welcome Hi `mention` welcome to #name.

Example : with mention and button 
=> .welcome Hi `mention` #desc `button/Thanks` `header/welcome to #name`

Example : with button
=> .welcome Hi welcome to #name `button/Hello` `button/Hi` `header/#desc
members : #size`

#size // last joined member count or total size of group when joined
#desc // group description
#onwer // group owner
#name // group name

Of Course you can combine all this together, like button #blah mention ... 
```
to delete                => `.welcome delete `<br>
to get current greetings => `.welcome`