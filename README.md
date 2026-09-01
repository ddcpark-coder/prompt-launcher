# Prompt Launcher

Statična Vercel-ready aplikacija za sestavljanje promptov brez OpenAI API-ja.

## Funkcije
- popolnoma prilagodljivi glavni gumbi/predloge
- dodajanje, preimenovanje, podvajanje in brisanje gumbov
- poljubna polja/spremenljivke: text, number, textarea, select, da/ne
- poljubni podizbori
- prompt predloge s spremenljivkami `{{kljuc}}`
- geslom zaščiten Edit mode
- izvoz/uvoz konfiguracije v JSON
- konfiguracija je shranjena lokalno v brskalniku
- responsive postavitev za desktop in telefon

## Prva prijava v Edit mode
Privzeto geslo je:

`launcher`

Po prvi prijavi ga spremeni v zavihku **Geslo**.

## Varnostna opomba
Aplikacija je povsem statična. Geslo je shranjeno kot SHA-256 hash v localStorage in je namenjeno zaščiti pred nenamernim urejanjem na napravi. To ni strežniška avtentikacija. Za resnično večuporabniško/admin zaščito je potreben backend oziroma storitev za prijavo.

## Vercel
Repo lahko neposredno uvoziš v Vercel. Build command ni potreben, output je korenska mapa.
