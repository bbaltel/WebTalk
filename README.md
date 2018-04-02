# WebTalk
A simple server and client for communicating with friends

## Dependencies:

To run the <code>server.js</code>, you need the module <code>websocket</code>  
Get it by running
```bash
$ sudo npm install websocket
```

## Setup:
```bash
$ sudo git clone "https://github.com/bbaltel/WebTalk"
```

before you run, you need to edit a few things  

You need to

- Get a domain
- Get port forwarding set up towards your computer off the domain (on 8080)
- Edit frontend.js (on line 25) to replace with your domain
- Give the clients a copy of the <code>index.html</code> and <code>frontend.js</code>

run server.js on one computer for the server, and index.html for the clients

## Running:

```bash
$ sudo node server.js
```

## TODO:
- [ ] Add commands like kicking users, muting users, etc.
- [ ] Add emoji support :+1:
- [ ] Support markdown text
- [ ] Better frontend
