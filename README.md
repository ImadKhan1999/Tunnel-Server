# Tunnel-Server

`server.txt` tells the Imad Tunnel app where its server is. The app reads it on every start.

- Put the server address on the first line, starting with `https://` (for example `https://tunnel.pmsprep.online`).
- Lines starting with `#` are ignored.
- To move to a new domain: set up the server on the new domain first, then edit `server.txt`. Apps switch on their next launch (GitHub can take about 5 minutes to show the change).

Keep this repo public so the app can read the file, but only you should be able to edit it.
