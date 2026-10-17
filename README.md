# LISTN2 – Releases

Hier liegen nur die Windows-Installer von LISTN2 und der Update-Feed `latest.json`.
Installierte LISTN2 fragen diesen Feed ab und bieten neue Versionen selbst an.
Der Code liegt in einem privaten Repo.

**Installieren:** unter [Releases](../../releases/latest) die Datei `LISTN2_<Version>_x64-setup.exe`
laden und ausführen. Die Installation läuft nur für den eigenen Windows-Benutzer, ohne Admin-Rechte.

**Bitte hier nichts von Hand ändern.** Releases entstehen über `scripts/release-windows.ps1`
im Code-Repo. Jede Installer-Datei ist signiert; die App nimmt nur Updates mit gültiger Signatur an.

## Lizenz

LISTN2 basiert auf [Meetily](https://github.com/Zackriya-Solutions/meeting-minutes) und steht
wie Meetily unter der MIT-Lizenz:

```
MIT License

Copyright (c) 2024 Zackriya Solutions

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

Gestaltung und Anpassung: agentic3.
