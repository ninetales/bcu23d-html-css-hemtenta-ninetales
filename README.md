[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/Tw1TFTlo)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12690262&assignment_repo_type=AssignmentRepo)
# ⚡️ Hemtenta

## 📝 Instruktioner
- Hemtentan lämnas in senast vid den tidpunkten som finns angiven på itslearning och/eller i inlämningsuppgiften. Inskickade svar via Teams, itslearning eller motsvarande accepteras inte.

- Skriv svaren direkt i denna markdown-fil, och committa.

- Om du använder VS Code så kan du förhandsgranska Markdown-filen med hjälp av denna ikon: ![Referensbild](assets/preview-markdown.jpg)

Frågorna är strukturerade enligt följande format i dokumentet, och du skriver ditt svar genom att inleda med en s.k. "krokodilkäft", se nedan:

---
### Frågans titel
1. attribut
> mitt svar skriver jag här
---

- Betrakta även tentatillfället som en möjlighet att _lära sig något_, och inte enbart som en kunskapskontroll. Glöm alla principer från tidigare skolgång om examination; det går inte att applicera på kod (tycker jag).
- På samtliga frågor, svara _med egna ord_. Jag vill inte ha inklistrade svar från Wikipedia eller motsvarande.
- Om någon beskrivning/fråga är oklar - skriv hur du har tolkat den! Det löser sig 🚑️
- Tentan kan totalt ge 59 ⭐ (poäng) och för G krävs 60 % (35 st) och för VG 80 % (47 st).
- Du kan öppna denna fil i t.ex. Visual Studio Code, och bör då få upp en förhandsgranskning om du upplever det textbaserade filformatet besvärligt att läsa :)
- 💥 Läs igenom _alla_ frågorna innan du sätter igång med att svara, så vet du vilka som kommer att ta längre tid, och vilka som tar kortare tid.

## 🧑‍💻 Frågor

### 1. Semantik (5 ⭐)
- Vad innebär "semantik" som begrepp (i HTML)?
- Varför ska det användas på webbplatser utifrån ett utvecklarperspektiv?
- Ge ett exempel vardera på hur semantik påverkar (1) tillgänglighet, (2) SEO och (3) kodgranskning/samarbete.

### 2. Semantik (3 ⭐)
Välj ut en valfri sajt som _inte_ är en tidningssida eller någonting som du själv har gjort. Ta en skärmdump på den primära delen av sidan (= det som syns på din skärm när du surfar in på sidan). Beskriv hur du hade strukturerat upp den i block och vilka semantiska taggar du hade använt. Du kan t.ex. använda rutor med siffror för att koppla ihop dina förklaringar.

Se referensbild nedan.

![Referensbild](assets/semantik1.png)

### 3. Terminologi 1 (10 ⭐)
Beskriv med egna ord vad följande saker är:

1. attribut
2. pseudo selector
3. parent i DOM
4. sibling (i DOM)
5. child (i DOM)
6. child och sibling selectors i CSS
7. URL
8. domän
9. DNS
10. a11y

### 4. Tillgänglighet (5 ⭐)
Gör en övergripande tillgänglighetsanalys på https://www.lingscars.com. Nämn 5 saker som behöver förbättras.

### 5. Optimering (6 ⭐)
Beskriv syftet med följande (dvs. varför det görs/vad det används till):

- Komprimera (minifiera) Sass-kod (compress)
- Använda resurser från externa (CDN-)källor, t.ex. Google Fonts, istället för att ladda ner typsnitt.
- Lighthouse

### 6. Bilder (4 ⭐)
Förklara följande:

1. Varför används attributet `loading="lazy"` i HTML på vissa bilder? 
2. Vad gör motsvarande attribut `loading="eager"` i HTML? 
3. Utöver tillgänglighetsaspekten, varför bör du sätta ett `alt`-attribut på bilder?
4. Att sätta `width` och `height` som attribut i HTML-koden på bilder, vad bidrar det till?

### 7. Ramverk (4 ⭐)
Lista:

1. Två stycken kända CSS-ramverk/-bibliotek/-"helpers"
2. Ett känt HTML-template som man kan starta sina projekt utifrån
3. Nämn en bra sajt där du kan hålla koll på CSS-trender

### 8. Sass (5 ⭐)
Förklara följande koncept i Sass (bonusfråga):

1. mixin
2. lists
3. function
4. partials
5. variables

### 9. Tillgänglighet (10 ⭐)
Besvara följande frågor:

1. När ska du använda ARIA labels?
2. Vad är den minsta rekommenderade storleken på ett interaktivt element, t.ex. en knapp, på en liten skärm (t.ex. mobil) i pixlar?
3. Vad är den minsta rekommenderade font-storleken i pixlar?
4. Varför ska du använda t.ex. `rem` eller `em` som enhet på fonter istället för pixlar?
5. Vilken tillgänglighetsnivå (A) ska du eftersträva minst för publika sidor, t.ex. myndighetssidor?
6. Vilken myndighet i Sverige ansvarar för tillgänglighet?
7. Du skapar en knapp med hjälp av ett div-element. Beskriv problematiken i detta.
8. Vem är ansvarig för att tabindex sätts på interaktiva element och att det sker i rätt ordning?
9. Skriv en alt-text till följande bild, på svenska, engelska eller finska. ![La naranja mecánica](assets/la-naranja-mecanica_cuban-movie-poster.jpeg)
10. Du har lagt in hysteriska animationer på din sida. Vilken media query använder du för att avaktivera dessa för användare som inte vill ha animationer?

### 10. Sökmotoroptimering (7 ⭐)
Kantarella Löfwenskog har som målsättning att bli Sveriges största influerare och bloggare inom all form av skogskost och att ge sina läsare tips på hur man blir, är och hur det är att vara självförsörjande, mediterande skogsmulle.

Du jobbar på webbyrån Undermålig AB som Front End-utvecklare, och chefen har sagt åt dig att fixa fram 5 tips som får Kantarellas sajt att hamna högre upp i sökträffarna.

Kantarellas sajt har precis lanserats, och det finns i dagsläget 5 st blogginlägg och en "Om Kantarella"-sida.

Vilka fem saker gör du?
