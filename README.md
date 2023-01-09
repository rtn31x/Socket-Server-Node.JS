# Socket-Server-Node.JS
## Hi, I'm Search Some İnformation About Socket Server İn Node.JS and I couldnt find it some source code. I'm say Why not and I'm upload code


I will upload this project on github and i will add it below.
https://glitch.com/edit/#!/socketserverforoblox

go page and remix it, run project

![image](https://user-images.githubusercontent.com/117655074/211352612-a65bf917-52a0-47cd-ad8f-4908b53cfb85.png)

Your server adress in this blank and copy it,
paste this adress in this blank and run code


```
const WebSocket = require('ws');
const serverAdress = "wss://thisblank.com/"

const ws = new WebSocket(serverAdress, {
    headers: {
        "user-agent":"Mozilla"
    }
});

ws.on('open', function(){
    ws.send("");
});

ws.on('message',function(msg) {
    console.log("Received msg from server: " + msg)
})
```


and Your message will be reflected in the server logs.
