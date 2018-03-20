# 13【done】13-v2-gitter message iframe-final

# try-gitter-chatBox
same as:

(1) all in js(success in Codepen) :    https://codepen.io/kiecoo/pen/PQZdOO

(2) separate into html &js (success in Codepen): https://codepen.io/kiecoo/pen/YaqdJv

----
# difference between 3 ways

have tried 3 ways to let chatBox to success & both of them failed

【success--repo 3 】:thish one

【fail--repo 1 】
don't do this one <1. repo of [makeGitterChatbox](https://github.com/kiecoo/makeGitterChatbox/blob/master/index.html)>   :[output](https://kiecoo.github.io/makeGitterChatbox/) is all blank


In html:

using
```
makeGitterChatbox(exampleProfile)
```

【fail--repo 2 】
<2. repo of try-gitter-chatBox>            :[output](https://kiecoo.github.io/try-gitter-chatBox/) is all pink(just show background of body)
repo:https://github.com/kiecoo/try-gitter-chatBox


In html: 

using
```
var x = makeGitterChatbox(exampleProfile)
document.body.appendChild(x)

```
instead of 
```
makeGitterChatbox(exampleProfile)
```
