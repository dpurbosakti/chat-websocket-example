# This is a simple chat using websocket

Step 1.

Run main.go

Step 2.

Open any web browser and open the console tab using inspect or simply press f12

Step 3. 

Connect client and server by copy and paste this following syntax in console tab
```bash
let socket = new WebSocket("ws://localhost:8000/ws")
```

```bash
socket.onmessage = (event) => {console.log("received from server: ", event.data) }
```

Step 4.

Send your message 
```bash
socket.send("msg")
```

change the msg with your desire message

# Note
You may want to connect with **_2 or more_** different browser tab so u can chat with each other tab