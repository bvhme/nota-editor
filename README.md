# Nota-editor

WYSIWYG-editor voor nota's (korte bestanden voor besluitvoering), in het Nederlands.
Statische single-page app — geen build, geen server nodig. Live via GitHub Pages.

## Vaste vorm die de editor afdwingt

- **Pagina 1 — maximaal ½ A4** (rode stippellijn + melding bij overschrijding):
  - **Aanleiding** — genummerde lijst, max. 3 punten, in volgordelijkheid
  - **Advies** — max. 3 punten, belangrijkste boven (▲ ▼ om te sorteren)
  - **Kern** — max. 3 punten, belangrijkste boven (▲ ▼ om te sorteren)
- **Pagina 2 — maximaal 1 A4** (melding bij overschrijding):
  - **Toelichting** — vrije opgemaakte tekst (vet, cursief, lijsten)
  - **Vervolg en proces** — vrije opgemaakte tekst

## Functies

- Begeleiding per sectie (uitklapbare hints) plus zijpaneel met de vaste vorm en schrijftips
- Live teller per puntlijst (`x/3 punten`) en paginameter per pagina (percentage + aantal woorden)
- Enter voegt een punt toe tot maximaal 3; Backspace op een leeg punt verwijdert het punt
- Automatisch tussentijds opslaan in `localStorage`
- "Afdrukken / PDF" drukt af als twee echte A4-pagina's zonder hulp-UI
