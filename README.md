# 🥖 Verbuga Modern — Franse Werkwoorden & Tijden Trainer

Een moderne, razendsnelle en 100% standalone webapplicatie om **Franse werkwoordsvervoegingen** en **grammaticaregels** te oefenen. Gebouwd als één enkel zelfstandig HTML-bestand zonder externe afhankelijkheden — werkt direct offline in elke browser en kan met één klik gehost worden via **GitHub Pages**.

---

## ✨ Belangrijkste Functionaliteiten

### 🎮 1. Interactieve Game Startpagina
- **Retro Arcade & Modern Overzicht:** Kies tussen het sfeervolle retro startscherm (met bewegende Franse grammatica-achtergrond op HTML5 Canvas) of het uitgebreide kaarten-overzicht.
- **Spelersprofiel & Progressie:** Verdien **XP**, stijg in **Level** en houd je langste **reeks (streak)** bij in je browser (`localStorage`).

### ✍️ 2. Werkwoorden Trainer (Tijden + Voornaamwoorden)
- **28 Essentiële Werkwoorden:** Regelmatige (`-er`, `-ir`, `-re`), stamwisselende (`préférer`, `jeter`, `s'appeler`, `lever`, `employer`) en onregelmatige werkwoorden (`être`, `avoir`, `aller`, `faire`, `venir`, `pouvoir`, `vouloir`, `savoir`, `devoir`, `falloir`, `ouvrir`, `écrire`, `dire`, `recevoir`, `dormir`, `servir`, `mentir`, `sentir`, `sortir`, `partir`).
- **10 Tijden & Wijzen:**
  - *Indicatif Présent*
  - *Passé Composé*
  - *Imparfait*
  - *Plus-que-parfait*
  - *Passé Récent*
  - *Futur Simple*
  - *Futur Proche*
  - *Conditionnel Présent*
  - *Subjonctif Présent*
  - *Impératif Présent*
- **Slimme Foutdiagnose & Diff-analyse:** Zie letter voor letter waar je spelling of accent afwijkt, inclusief uitleg waarom een bepaalde stam, hulpwerkwoord (*avoir* vs. *être*) of uitgang gebruikt wordt.
- **Active Recall Herhaling:** Typ na een fout het juiste antwoord direct één keer over om het motorisch in je geheugen vast te leggen; gemiste vormen keren automatisch terug in de wachtrij (*Spaced Repetition*).
- **Franse Uitspraak (TTS) & Accentenbalk:** Ingebouwde Franse spraaksynthese (`Web Speech API`) en sneltoetsen voor Franse accenttekens (`é`, `è`, `ê`, `ë`, `ç`, `î`, `ï`, `ô`, `û`, `œ`).

### 🧠 3. Regels Grinden (Volledig Scherm)
- Interactieve meerkeuze-arena op volledig scherm om de **vormingsregels**, **stammen**, **hulpwerkwoorden (*avoir* vs. *être*)** en **uitzonderingen** te testen.
- Filter per categorie (*Tijden & Formules*, *Stammen & Onregelmatig*, *Avoir vs Être*, *Valstrikken & Uitzonderingen*) en oefen na afloop specifiek je gemiste vragen.

### 🖨️ 4. Groot Regelblad (Volledige Breedte & Printklaar)
- Overzichtelijk **2-koloms referentieblad** met alle 10 tijden, formules, signaalwoorden, uitgangen en klassieke valstrikken.
- Geoptimaliseerd `@media print` stijlregelblad om het overzicht direct op **A4 of als PDF** af te drukken als spiekbrief.

### 📖 5. Ingebouwde Grammaticagids & Werkwoorden-Opzoeker
- **4-Tab Spiekbriefje:** Tijden & Formules, Onregelmatige Stammen, Volledige Vervoegingstabel per werkwoord (alle 10 tijden naast elkaar) en Ezelsbruggetjes (*HET KOFSTUK*, *Dr. & Mrs. Vandertramp*, enz.).

### ⚙️ 6. Uitgebreide Instellingen
- Schakel tussen **Grind Mode** (maximale snelheid zonder onderbrekingen) en **Motivatie Mode** (XP, levels, geluiden en confetti).
- Kies je **accenten-striktheid**, spraaksnelheid, geluidseffecten en **Donker / Licht Thema**.

---

## 🚀 Direct Gebruiken

### Optie 1 — Lokaal openen (Geen installatie nodig)
1. Download of clone deze repository:
   ```bash
   git clone https://github.com/<jouw-gebruikersnaam>/verbuga-modern.git
   ```
2. Dubbelklik op **`index.html`** om de trainer direct in je browser te openen.

### Optie 2 — Gratis hosten via GitHub Pages
1. Ga in je GitHub-repository naar **Settings** → **Pages**.
2. Kies onder **Build and deployment** bij *Branch* voor `main` (en map `/ (root)`).
3. Klik op **Save** — binnen een minuut staat je trainer online!

---

## ⌨️ Sneltoetsen

| Toets | Actie |
| :--- | :--- |
| `Enter` | Antwoord controleren / Volgende vraag |
| `1` – `4` of `A` – `D` | Antwoordoptie kiezen tijdens *Regels Grinden* |
| `Esc` | Openstaande pop-ups (Grammaticagids / Instellingen) sluiten |

---

## 🛠️ Technische Details

- **Zero Dependencies:** Puur HTML5, CSS3 en Vanilla JavaScript (ES6+) in één enkel bestand (`index.html`).
- **Offline-first:** Gebruikt `localStorage` voor het opslaan van voorkeuren, thema en XP-voortgang.
- **Audio & Speech:** Maakt gebruik van de native `Web Audio API` (synthetische feedbacktonen) en `window.speechSynthesis` (`fr-FR`).

---

## 📄 Licentie

Vrij te gebruiken, aan te passen en te delen voor educatieve doeleinden (MIT License).
