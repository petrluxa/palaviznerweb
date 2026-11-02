# Pála Vízner Tennis — návrhy nového webu

Tři kompletní návrhy nového webu pro tenisový klub a akademii **Pála Vízner Tennis**
(Suttnerové 841/2, Praha 6 — Šárka). Náhrada za současný web
[palaviznertennis.cz](https://www.palaviznertennis.cz/).

Zadání: **moderní · energický · luxusní**

**Ukázka online:** https://petrluxa.github.io/palaviznerweb/
(GitHub Pages z větve `main`; stránky mají `noindex`, aby je vyhledávače neplétly se současným webem klubu)

## Varianty

Otevři [`index.html`](index.html) — galerie všech tří variant s porovnáním.

| | Varianta | Charakter |
|---|---|---|
| 01 | [`01-match-point.html`](01-match-point.html) | Tmavý, sportovní, nejvíc energie. Grafit + tenisová limetka, obří bloková typografie, widget volných kurtů přímo v hero. |
| 02 | [`02-sarka-klub.html`](02-sarka-klub.html) | Klubový luxus. Krémová + lesní zelená + mosaz, serifové titulky (Cormorant Garamond), důraz na tradici. |
| 03 | [`03-studio.html`](03-studio.html) | Světlý a čistý. Bílá + navy + oranžová (Space Grotesk), ilustrovaný kurt, nejlépe čitelné a nejlevnější na údržbu. |

## Obsah

Všechny tři varianty obsahují stejný obsah převzatý ze současného webu:

- klub a trenérský tým (František Pála, Petr Pála, Pavel Vízner + 7 dalších trenérů)
- tenisová akademie — 4 programy podle věku a výkonnosti
- letní příměstské kempy 2026 (13.–17. 7., 3.–7. 8., 24.–28. 8., 6 500 Kč)
- areál — 6 dvorců, fitness sál 100 m², indoor golf
- kompletní ceník s přepínačem letní / zimní sezóna
- kontakty a doprava

## Technicky

- Statické HTML, jeden soubor na variantu, žádný build.
- Fonty z Google Fonts, jinak vše self-contained.
- Vizuály jsou zatím kreslené v CSS (plochy s čarami kurtu) — žádné bitmapy.
- Ověřeno headless renderem na desktopu (1280 px) i mobilu (390 px).

## Co doplnit před nasazením

- [ ] **Fotografie** areálu, trenérů a dětí z kempů — nejvíc zvedne varianty 01 a 03.
- [ ] **Otevírací doba** — v návrzích odvozena z ceníku (Po–Pá 8–21, So–Ne 8–20), klub ji nikde neuvádí. Potvrdit.
- [ ] **Widget obsazenosti kurtů** ve variantě 01 je ukázkový — napojit na reálný rezervační systém.
- [ ] **Popisky trenérů** jsou obecné — doplnit konkrétní tituly a úspěchy od klubu.
- [ ] **Ceny a termíny** potvrdit, než se web spustí.
