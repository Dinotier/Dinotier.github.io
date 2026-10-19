# dinotier.github.io

Link-Domain für AudioProto-Anrufe (Anmeldung per SMS):

* `/.well-known/assetlinks.json` – bestätigt Android, dass `https://dinotier.github.io/c…` zur App
  `org.audioproto.probe` gehört (SHA-256 des Signaturschlüssels). Danach öffnen Links in SMS direkt die App.
* `/c/` – Seite für den Fall, dass der Link im Browser landet: zeigt Art und Rufnummer und übergibt
  den Anruf per „In AudioProto öffnen“ an die App.

Die Anrufdaten stehen im Link hinter `#` und werden nie an GitHub übertragen. Kein Code, keine Daten hier.
