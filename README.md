# Sjakkur

En enkel sjakkklokke i nettleseren. Én fil (`index.html`), ingen avhengigheter.

## Funksjoner

- Hver spiller har en hel skjermhalvdel som trykkflate
- Øverste felt er rotert, så begge leser tiden fra sin side av bordet
- Ferdige tidskontroller (1+0, 3+2, 5+3, 10+5, 15+10 osv.) og egendefinert tid med tillegg per trekk
- Tideler vises når det er under 20 sekunder igjen
- Pause, nullstilling og trekkteller
- Lyd og vibrasjon når tiden går ut
- Holder skjermen våken under parti (der nettleseren støtter det)
- Husker sist valgte tid

## Bruk

1. Velg tid i menyen.
2. Spilleren som **ikke** starter trykker på sin side – da starter motstanderens klokke.
3. Etter hvert trekk trykker du på din egen side.

## Publisere med GitHub Pages

1. Legg `index.html` og `README.md` i et repo.
2. Gå til **Settings → Pages**.
3. Under *Source* velger du **Deploy from a branch**, branch `main` og mappe `/ (root)`.
4. Etter et minutt er appen tilgjengelig på `https://<brukernavn>.github.io/<repo>/`.

Tips: Åpne lenken på mobilen og velg «Legg til på startskjermen» for å bruke den som en app i fullskjerm.
