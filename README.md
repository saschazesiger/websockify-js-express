# 🎉 Websockify
## For Node.js

Modified and minified Version from websockify-js to use the Express library in Node.js


1. Install the Dependencies: `npm i` (ws, express, mime)

2. Edit Rows 84-87 (Source: NoVNC Client, Target: VNC Server)

`
    source_host = "";
    source_port = parseInt("5500");
    target_host = "10.1.3.1";
    target_port = parseInt("5905");
`

3. Start the Server `node websockify.js`
