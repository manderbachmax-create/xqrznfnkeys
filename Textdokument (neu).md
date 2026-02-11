**<!DOCTYPE html>**

**<html>**

**<head>**

**<title>XQRZNFN ULTRA</title>**

**<style>**

**body {**

    **background: black;**

    **color: #00ff88;**

    **font-family: monospace;**

    **text-align: center;**

    **padding-top: 80px;**

**}**

**input, button {**

    **background: black;**

    **color: #00ff88;**

    **border: 1px solid #00ff88;**

    **padding: 10px;**

    **font-size: 16px;**

**}**

**#panel { display: none; margin-top: 40px; }**

**#download { display: none; margin-top: 20px; }**

**</style>**

**</head>**

**<body>**



**<h1>XQRZNFNKEYS ULTRA</h1>**

**<p>Private Access Required</p>**



**<input type="password" id="master" placeholder="Master Password">**

**<button onclick="unlockAdmin()">Enter</button>**



**<div id="panel">**

    **<h2>Generate Key</h2>**

    **<button onclick="generateKey()">Generate</button>**

    **<p id="generated"></p>**



    **<hr>**



    **<h2>Enter Key</h2>**

    **<input type="text" id="keyInput" placeholder="Enter Access Key">**

    **<button onclick="validateKey()">Unlock</button>**

**</div>**



**<div id="download">**

    **<h2>🔥 ACCESS GRANTED</h2>**

    **<a href="tweaks.zip" download style="color:#00ff88;">Download Tweaks</a>**

**</div>**



**<script>**

**const MASTER\_PASSWORD = "XQRZNFN2026";**

**let validKeys = \[];**



**function unlockAdmin(){**

    **const pw = document.getElementById("master").value;**

    **if(pw === MASTER\_PASSWORD){**

        **document.getElementById("panel").style.display = "block";**

    **} else {**

        **alert("Wrong Password");**

    **}**

**}**



**function generateKey(){**

    **const chars = "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789";**

    **let key = "XQRZNFN-";**

    **for(let i=0;i<12;i++){**

        **key += chars.charAt(Math.floor(Math.random()\*chars.length));**

    **}**

    **validKeys.push(key);**

    **document.getElementById("generated").innerText = "New Key: " + key;**

**}**



**function validateKey(){**

    **const input = document.getElementById("keyInput").value;**

    **if(validKeys.includes(input)){**

        **document.getElementById("download").style.display = "block";**

    **} else {**

        **alert("Invalid Key");**

    **}**

**}**

**</script>**



**</body>**

**</html>**



