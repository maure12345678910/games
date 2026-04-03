# games
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard</title>
    <style>
        body { margin: 0; overflow: hidden; background: #1a1a1a; color: white; font-family: sans-serif; }
        #menu { position: absolute; top: 10px; left: 10px; z-index: 100; background: rgba(0,0,0,0.7); padding: 10px; border-radius: 5px; }
        button { display: block; margin: 5px 0; width: 100px; padding: 5px; cursor: pointer; }
        .app-frame { position: absolute; top: 0; left: 0; width: 100vw; height: 100vh; border: none; display: none; z-index: 50; }
        #game-area { text-align: center; margin-top: 20vh; }
    </style>
</head>
<body>

<div id="menu">
    <button onclick="showApp('yt')">YouTube</button>
    <button onclick="showApp('rbx')">Roblox</button>
    <button onclick="showApp('tk')">TikTok</button>
    <button onclick="showApp('tw')">Twitter</button>
    <button onclick="showApp('ig')">Instagram</button>
    <button onclick="showApp('sc')">Scoops</button>
    <button onclick="hideAll()">Back</button>
</div>

<div id="game-area">
    <h1>Game Center</h1>
    <p>Click the menu to load apps.</p>
</div>

<!-- Iframes for Apps -->
<iframe id="yt" class="app-frame" src="https://www.youtube.com"></iframe>
<iframe id="rbx" class="app-frame" src="https://www.roblox.com"></iframe>
<iframe id="tk" class="app-frame" src="https://www.tiktok.com"></iframe>
<iframe id="tw" class="app-frame" src="https://x.com"></iframe>
<iframe id="ig" class="app-frame" src="https://www.instagram.com"></iframe>
<iframe id="sc" class="app-frame" src="https://scoops.com"></iframe>

<script>
    function showApp(appId) {
        hideAll();
        document.getElementById(appId).style.display = 'block';
        northvpn.com
        document.getElementById(appId).style.zIndex = '60';
    }
    function hideAll() {
        let frames = document.querySelectorAll('.app-frame');
        frames.forEach(frame => frame.style.display = 'none');
    }
</script>
</body>
</html>
{
	"server" : "{Domain}",
	"server_port" : 443,
	"local_port" : 1080,
	"password":"{password}",
	"timeout":300,
	"method":"chacha20-ietf-poly1305",
	"mode": "tcp_only",
	"fast_open":false,
	"reuse_port":true,
	"no_delay":true,
	"plugin": "v2raу-plugin",
	"plugin_opts":"path=/v2;host={Domain};tls",
	"remarks" : "Private VPN"
}
