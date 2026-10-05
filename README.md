# Portfolio-website - Habib

Een moderne, overzichtelijke en **responsive** portfolio-website gebouwd met **HTML en CSS** (eventueel JavaScript).

## Specificatie (opdracht week 3)

### 1. Doel van de website
Een persoonlijke portfolio-website voor Habib (26 jaar, Nieuwegein, ICT Software Developer student
aan MBO Utrecht). De website toont wie Habib is, en fungeert als groeiend portfolio voor toekomstige
projecten én als contactpunt voor vragen en samenwerkingen.

### 2. Wat bezoekers kunnen zien en doen
- **Home**: korte introductie over Habib met directe links naar de andere pagina's.
- **About Me**: informatie over studie, woonplaats en hobby's (reizen, wandelen, hiken in de bergen,
  fotograferen en filmen).
- **Portfolio**: overzicht van (toekomstige) projecten.
- **Contact**: contactgegevens (email, telefoon, adres) en een contactformulier.
- Navigeren via een vast navigatiemenu (mobiel menu op telefoon).

### 3. Welke onderdelen gebouwd moeten worden
- Header met navigatiemenu (alles pagina's).
- Home-sectie met introductie en feitenblok.
- About Me-sectie met profiel, studie, woonplaats en hobby's.
- Portfolio-sectie met projectkaarten.
- Contact-sectie met contactgegevens + formulier.
- Footer met copyright-informatie.
- Responsive layout voor mobiel, tablet en desktop.
- Duidelijke commentaarregels in HTML, CSS en (eventueel) JavaScript.

### 4. Welke bestanden aangepast moeten worden
- `index.html` — Homepagina (introductie).
- `about.html` — About Me pagina.
- `portfolio.html` — Portfolio pagina.
- `contact.html` — Contact pagina (gegevens + formulier).
- `CSS/style.css` — styling, kleuren, responsive (media queries).
- `README.md` — registreer elke wijziging (werkgreep in `AGENTS.md`).

### 5. Welke nieuwe bestanden nodig zijn (indien van toepassing)
- `JS/script.js` — alleen als JavaScript gewenst is (bijv. formulierbevestiging of mobiel menu).
- Geen nieuwe HTML-pagina's nodig; de 4 bestaande pagina's volstaan.

### 6. Wanneer is de opdracht afgerond
De opdracht is afgerond wanneer:
- Alle 4 pagina's aanwezig zijn en correct linken via het navigatiemenu.
- De website responsive is op mobiel, tablet en desktop.
- Elke pagina duidelijke commentaarregels bevat.
- De website moderne en professionele uitstraling heeft.
- Alle wijzigingen in dit `README.md` zijn vastgelegd.
- De website getest is (geen kapotte links/opmaak) en goedgekeurd door Habib.

## Stappenplan (in afwachting van akkoord)

| Stap | Wat wordt gedaan | Bestand | Waarom nodig |
|------|------------------|---------|--------------|
| 1 | Specificatie + stappenplan tonen en laten goedkeuren | `README.md` | Werken volgens de developer-richtlijnen: eerst plan, akkoord, dan bouwen |
| 2 | Navigatiestructuur en actieve pagina-controleren/bijwerken | alle `.html` | Elke pagina krijgt het juiste menu met de actieve link |
| 3 | Homepagina controleren en zo nodig bijwerken | `index.html` | Korte introductie en links naar de rest |
| 4 | About Me pagina controleren | `about.html` | Studie, woonplaats en hobby's correct tonen |
| 5 | Portfolio pagina controleren | `portfolio.html` | Toekomstige projecten tonen |
| 6 | Contact pagina + formulier controleren | `contact.html` | Contactgegevens en werkend formulier |
| 7 | Styling, kleuren en responsive verfijnen | `CSS/style.css` | Moderne professionele uitstraling op alle schermen |
| 8 | (Optioneel) JavaScript toevoegen als gebruiker dit kiest | `JS/script.js` | Extra interactie zoals formulierbevestiging |
| 9 | Website testen op mobiel, tablet en desktop | alle pagina's | Controleren dat alles werkt en er goed uitziet |
| 10 | Wijzigingen vastleggen in README en aanbieden aan Habib | `README.md` | Opdracht afronden volgens werkgreep |

## Opdracht (prompt)

De website is gebouwd aan de hand van de volgende opdracht:

> Maak een persoonlijke portfolio-website voor mij.
>
> Mijn naam is Habib, ik ben 26 jaar oud, woon in Nieuwegein en volg de opleiding ICT Software Developer aan MBO Utrecht.
>
> Gebruik alleen HTML en CSS. JavaScript. Maak de website modern, overzichtelijk en responsive voor mobiel, tablet en desktop.
>
> Voeg de volgende onderdelen toe:
> - Homepagina met een korte introductie over mezelf.
> - About Me pagina met informatie over mijn studie, woonplaats en interesses.
> - Portfolio pagina waar ik toekomstige projecten kan tonen.
> - Contactpagina met contactgegevens en een contactformulier.
>
> Mijn hobby's zijn reizen, wandelen, hiken in de bergen, fotograferen en filmen.
>
> Gebruik:
> - Een header met navigatiemenu.
> - Mooie kleuren die passen bij een ICT-student.
> - Duidelijke commentaarregels in de code.
> - Een footer met copyrightinformatie.
>
> Leg na de code kort uit waarom deze structuur is gekozen en hoe de website responsive is gemaakt.

## Aanpassingen (wat er is gedaan)

### Logo mooier gemaakt (volgens wens)
- Het logo is omgevormd van platte tekst naar een **monogram-blokje** (letter H in een
  gradient-vaak) met de naam **Habib** in verloopkleuren (wit naar cyaan).
- Header-logo op alle vier de pagina's is vervangen: `logo-mark` + `logo-text`.
- Footer-logo heeft nu een kleinere versie van hetzelfde monogram.
- Hover-effect: het blokje draait iets scheef en wordt iets groter (CSS `transform`).

De eerste versie van de website (uit week 1) was een **single-page** website met JavaScript
(een typewritereffect, scroll-animaties en een interactief formulier).

In deze nieuwe versie is het volgende aangepast:

1. **Van één pagina naar meerdere pagina's** - de site bestaat nu uit 4 losse HTML-pagina's:
   `index.html`, `about.html`, `portfolio.html` en `contact.html`.
2. **JavaScript verwijderd** - de map `JS/script.js` is verwijderd omdat de opdracht eist
   dat er alleen HTML en CSS wordt gebruikt. De interactie (zoals het mobiele menu) werkt
   nu via een pure CSS "checkbox-truc".
3. **Nieuw design en kleurenpalet** - een donker thema met indigo en cyaan, passend bij
   een ICT-student. Alle kleuren staan in CSS-variabelen bovenaan `CSS/style.css`.
4. **Modeleer content voor Habib** - leeftijd (26), woonplaats (Nieuwegein), opleiding
   (ICT Software Developer, MBO Utrecht) en hobby's (reizen, wandelen, hiken, fotograferen en filmen).
5. **Portfolio pagina toegevoegd** - projectkaarten voor toekomstige projecten,
   inclusief een "Binnenkort"-label en een uitleg dat de lijst nog wordt uitgebreid.
6. **Contact pagina toegevoegd** - contactgegevens én een contactformulier, met een
   toelichting dat het formulier nog geen echte backend heeft.
7. **Uitleg structuur en responsive** - in het antwoord van week 2 is beschreven waarom
   voor deze structuur is gekozen en hoe de website responsive is gemaakt.

## Structuur & verantwoording

**Waarom deze structuur?**

- Meerdere losse pagina's in plaats van één lange pagina: overzichtelijk per onderdeel,
  makkelijk uit te breiden en logisch opgesplitst in 4 gebieden (Home, Over Mij, Portfolio, Contact).
- Eén gedeeld `CSS/style.css` voor alle pagina's: kleuren en layout worden op één centrale
  plek beheerd via CSS-variabelen, zodat de hele site in één keer aangepast kan worden.
- Header en footer komen op elke pagina terug voor een consistent geheel.

**Hoe is de website responsive gemaakt?**

- CSS-variabelen en `clamp()` voor tekstgrootte die meeschaalt met het scherm.
- Flexbox en CSS Grid - bijvoorbeeld `repeat(auto-fit, minmax(280px, 1fr))` voor het
  portfolio-overzicht - zodat kaarten automatisch van meerdere kolommen naar één kolom gaan.
- Media queries op 768px en 480px: op mobiel klapt het menu in als hamburgermenu
  (via een pure CSS "checkbox-truc", dus zonder JavaScript) en worden de tekst en kaarten
  compacter.

## Pagina's

| Bestand | Inhoud |
|---------|--------|
| `index.html` | Homepagina met korte introductie en feitenblok |
| `about.html` | Over Mij: studie, woonplaats en interesses (reizen, wandelen, hiken, fotograferen, filmen) |
| `portfolio.html` | Portfolio met (toekomstige) projecten |
| `contact.html` | Contactgegevens en een contactformulier |
| `CSS/style.css` | Alle styling in één gedeeld stylesheet |

## Functies

- Vaste header met navigatiemenu
- Mobiel hamburgermenu via puur CSS (checkbox-truc, dus geen JavaScript)
- Kleurenpalet passend bij een ICT-student (donkerblauw, indigo, cyaan)
- Responsive met flexbox, grid en breakpoints op 768px en 480px
- Footer met copyright-informatie
- Duidelijke commentaarregels in HTML en CSS

## Gebruik

Open `index.html` in een browser. De navigatie verplaatst je naar de overige pagina's.

Voor een lokale HTTP-server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve
```

Daarna open je `http://localhost:8000`.

## Aanpassen

- **Teksten/gegevens**: bewerk de losse `.html`-pagina's.
- **Kleuren en styling**: wijzig de CSS-variabelen bovenaan `CSS/style.css`.