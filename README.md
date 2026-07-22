# Aktiv Heime

Statisk nettside for personleg trening og livsstilsrettleiing i Bjørnafjorden og Bergen. Sida er laga med HTML, CSS og litt vanleg JavaScript og kan publiserast direkte med GitHub Pages.

## Filer

- `index.html` – framsida og alt hovudinnhald
- `personvern.html` – personvernerklæring
- `styles.css` – design og responsiv layout
- `script.js` – mobilmeny, årstal og skjemakontroll
- `assets/` – bilete i JPG- og WebP-format
- `robots.txt`, `sitemap.xml` og `favicon.svg` – søk og nettlesarprofil

## Førehandsvis lokalt

Du kan opne `index.html` direkte i nettlesaren. For ei meir realistisk førehandsvising kan du starte ein enkel lokal nettserver, til dømes `python -m http.server 8000`, og gå til `http://localhost:8000`.

## Kontaktskjemaet

Skjemaet er kopla til Formspree-endepunktet `https://formspree.io/f/mvzebbpd`. Test innsending og stadfest mottakaradressa før publisering. Ved byte av Formspree-skjema må `action`-adressa i `index.html` oppdaterast.

## Publiser med GitHub Pages

1. Legg filene i hovudgreina i eit GitHub-repositorium.
2. Gå til **Settings → Pages**.
3. Vel **Deploy from a branch**, hovudgreina og rotmappa `/`.
4. Lagre og vent på adressa frå GitHub.

For eige domene: legg `aktivheime.no` inn under **Custom domain** i Pages-innstillingane. Følg DNS-verdiane GitHub viser hos domeneleverandøren. Aktiver HTTPS når GitHub tilbyr det. Dette må gjerast av den som eig domenet og DNS-tilgangen.

## Endre innhald

Rediger synleg tekst i HTML-filene. Erstatt bileta i `assets/` med same filnamn, eller oppdater biletreferansane. Behald tilnærma same sideforhold og lag nye WebP-versjonar for rask lasting.

## Kontroll før publisering

Test alle menylenkjer, telefon- og e-postlenkjer, personvernsida og kontaktskjemaet på mobil og datamaskin. Kontroller særleg at ansiktet i hovudbiletet er heilt synleg, og at Formspree sender til rett adresse.
