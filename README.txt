GSD Gauge Control v2.6.2 — iPhone fix

The ChatGPT/iOS file preview can display HTML and CSS but may not execute JavaScript. The gauges and engine controls need JavaScript.

On Windows PC:
1. Extract this ZIP to a folder.
2. Open a terminal in the folder containing index.html.
3. Run: py -m http.server 8000 --bind 0.0.0.0
4. On the PC open http://localhost:8000 in a browser.
5. For iPhone: connect both devices to the same Wi-Fi. Run ipconfig on the PC and find its Wi-Fi IPv4 address. In iPhone Safari open http://YOUR-PC-IP:8000 (e.g. http://192.168.1.25:8000). Allow Windows Firewall access for Python on private networks if prompted.

The app is an offline engine simulator. It is not yet connected to the ESP32. Do not expose this test server to the public internet.
