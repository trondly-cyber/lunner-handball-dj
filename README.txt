LUNNER HK – HÅNDBALL DJ

Innhold:
- index.html: appen med 6 knapper, stopp, pausemusikk og låtvalg.
- audio/: 10 ferdig bearbeidede MP3-klipp, alle under 15 sekunder.
- tracks.json: oversikt over låter og varighet.

BRUK
1. Pakk ut hele ZIP-filen, inkludert audio-mappen.
2. Åpne index.html i Chrome for lokal test på Chromebook/PC.
3. For iPhone/Android og delt nettadresse: publiser HELE mappen på et HTTPS-webhotell, for eksempel GitHub Pages (index.html i rot).
4. Under 'Lydbank og knappeoppsett' velger du låt for knapp 1–6.
5. Pausemusikk: velg en lokal lydfil, eller lim inn en DIREKTE nettadresse til lydstrøm. Vanlige Spotify- og radiowebsider fungerer ikke som lydstrøm.

Teknisk:
- MP3-klippene er normalisert til omtrent -15 LUFS og maks -1.5 dBTP med ffmpeg loudnorm.
- Utfading på 0,85 sekunder mot slutten av hvert klipp.
- STOPP fader på omtrent 0,22 sekunder.
- iOS/Android krever brukertrykk før lyd kan starte.
- Radiostrøm må være kompatibel med nettleser og tillate avspilling.
- Knappevalg lagres lokalt på hver enhet.
- MP3-filer publisert på offentlig GitHub er offentlig tilgjengelige. Kontroller at tillatelsen også dekker slik distribusjon.

RADIO: NRK mP3 er standard pausemusikk, direkte MP3-strøm fra https://lyd.nrk.no/nrk_radio_mp3_mp3_h. Krever internett og kan endres i innstillingene. Test på hallanlegget.
