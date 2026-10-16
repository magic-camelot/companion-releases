# Magic Camelot Companion

**Dein Begleiter für den Alltag – mit und ohne KI.** · *Your companion for everyday life – with and without AI.*

Von / by [Magic Camelot Studios](https://www.magic-camelot.com/) · [Website](https://www.magic-camelot.com/companion/) · [English website](https://www.magic-camelot.com/companion/en/)

---

## Deutsch

### Herunterladen

➜ **[Neueste Version herunterladen](https://github.com/magic-camelot/companion-releases/releases/latest)**

Unter „Assets“ die Datei `Magic-Camelot-Companion-Setup-….exe` herunterladen und mit einem Doppelklick öffnen. Das Installationsprogramm richtet alles ein, auch die Stimmen. Du musst nichts weiter installieren. Neue Versionen bietet der Companion danach selbst an.

Die beiden Einträge „Source code (zip)“ und „Source code (tar.gz)“ fügt GitHub automatisch jedem Release hinzu. Sie enthalten nur diese Beschreibung und die Lizenztexte, nicht das Programm. Zum Installieren brauchst du nur die `.exe`.

### Windows warnt beim ersten Start?

Solange der Companion noch nicht mit einem gekauften Zertifikat signiert ist, zeigt Windows „Der Computer wurde durch Windows geschützt“. Klicke auf **„Weitere Informationen“** und dann auf **„Trotzdem ausführen“**. Lade den Companion nur hier oder über die offizielle Website herunter, dann ist es das Original. Wer es genau wissen will, vergleicht die Prüfsumme mit `SHA256SUMS.txt` aus dem Release:

```powershell
Get-FileHash .\Magic-Camelot-Companion-Setup-1.0.0.exe -Algorithm SHA256
```

### Das brauchst du

- Windows 10 oder 11 (64 Bit), etwa 500 MB freien Speicherplatz
- Internet für Cloud-KI, Websuche, Radio, Nachrichten und Wetter
- Für die KI zwei Wege, auch kombinierbar:
  - **Lokale KI auf deinem PC:** kostenlos, ohne Konto, auch ohne Internet. Das passende Modell lädt der Companion auf Knopfdruck (etwa 3 bis 7 GB). Flüssig mit einer Grafikkarte ab etwa 6 GB, sonst ab 16 GB Arbeitsspeicher etwas gemächlicher.
  - **Cloud-KI:** ein eigenes [OpenRouter](https://openrouter.ai)-Konto mit etwas Guthaben, meist nur wenige Cent im Monat.
- Ohne beides kannst du im Übungsmodus alles ausprobieren; Kalender, Aufgaben, Schatzkammer, Werkstatt, Radio und Nachrichten funktionieren ganz ohne KI.

### Datenschutz

Kein Konto bei uns, kein Tracking, keine Nutzungsdaten. Gespräche bleiben verschlüsselt auf deinem PC. Was genau passiert: [Datenschutzerklärung](https://www.magic-camelot.com/datenschutz/#companion) · [Impressum](https://www.magic-camelot.com/impressum/)

### Lizenz

Der Companion ist **kostenlos** (Freeware). Du darfst das Installationsprogramm **unverändert und kostenlos** weitergeben, zum Beispiel an Familie und Freunde. Verändern, Verkaufen und das Herauslösen von Teilen (Grafiken, Figuren, Texte, Code) sind nicht erlaubt. © 2026 Magic Camelot Studios, alle Rechte vorbehalten. Die vollständigen Bedingungen stehen in [LIZENZ.txt](LIZENZ.txt).

Der Companion enthält Bestandteile anderer Urheber mit eigenen Lizenzen, etwa die Sprach-Engine Piper, die lokale KI llama.cpp und espeak-ng (GNU GPL v3, [Quellcode](https://github.com/espeak-ng/espeak-ng)). Alle Lizenzen: [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).

Der Quellcode des Companion selbst ist nicht öffentlich.

---

## English

### Download

➜ **[Download the latest version](https://github.com/magic-camelot/companion-releases/releases/latest)**

Under “Assets”, download `Magic-Camelot-Companion-Setup-….exe` and open it with a double-click. The installer sets everything up, including the voices. There is nothing else to install. After that, the Companion offers new versions by itself.

The two entries “Source code (zip)” and “Source code (tar.gz)” are added to every release by GitHub automatically. They only contain this description and the licence texts, not the program. To install, you only need the `.exe`.

### Windows shows a warning on first start?

As long as the Companion is not yet signed with a purchased certificate, Windows shows “Windows protected your PC”. Click **“More info”** and then **“Run anyway”**. Only download the Companion here or from the official website, so you know it is the original. To be sure, compare the checksum with `SHA256SUMS.txt` from the release (see the PowerShell line above).

### What you need

- Windows 10 or 11 (64-bit), about 500 MB of free disk space
- Internet for the cloud AI, web search, radio, news and weather
- For the AI there are two ways, which can be combined:
  - **Local AI on your PC:** free, no account, even without internet. The Companion downloads the right model with one click (about 3 to 7 GB). Smooth with a graphics card from about 6 GB, otherwise a little slower from 16 GB of memory.
  - **Cloud AI:** your own [OpenRouter](https://openrouter.ai) account with some credit, usually just a few cents a month.
- Without either you can try everything in practice mode; calendar, tasks, treasury, workshop, radio and news work without any AI.

### Privacy

No account with us, no tracking, no usage data. Conversations stay encrypted on your PC. The details: [privacy policy](https://www.magic-camelot.com/en/privacy/#companion) · [legal notice](https://www.magic-camelot.com/en/legal-notice/)

### Licence

The Companion is **free** (freeware). You may pass the installer on **unmodified and free of charge**, for example to family and friends. Modifying, selling and taking out parts (graphics, characters, texts, code) is not allowed. © 2026 Magic Camelot Studios, all rights reserved. Full terms in [LIZENZ.txt](LIZENZ.txt).

The Companion contains components by other authors under their own licences, such as the speech engine Piper, the local AI llama.cpp and espeak-ng (GNU GPL v3, [source code](https://github.com/espeak-ng/espeak-ng)). All licences: [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).

The Companion's own source code is not public.
