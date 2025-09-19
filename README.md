# Inlämning 2 css

Inlämings uppgift fortsättning hmtl/css

To-do list

Estimerat:

- [ ] Fixa repo och sätta in det gamla html repot 0.5 sp
- [ ] Skapa mappstruktur och sätta upp Sass istället för bara css 0.5 sp
- [ ] Börja med mobilversionen (allt under varandra) 1 sp
- [ ] Fixa meny och logga i header (flex) 1 sp
- [ ] Lägga till sidopanel i mobilversion 1 sp
- [ ] Testa med större skärm - artiklarna i två kolumner 2 sp
- [ ] Testa ännu större skärm - 3 artiklar på rad + sidopanel bredvid 2 sp
- [ ] Göra footern så att den blir 1 kolumn i mobil och 2–3 delar i dator 1.5 sp
- [ ] Validera min Sass och html 1 sp
- [ ] Sammanfatta uppgifter i README.md och skriva hur jag använt mig utav AI 0.5 sp
- [ ] Lägga till färger och lite extra detaljer om jag hinner 1 sp
- [ ] Forma inlämningen så jag når VG, dvs skriva i Sass och bifoga en tillgänglighetsrapport 2 sp

Verkligt:

- [ ] Fixa repo och sätta in det gamla html repot 0.5 sp
- [ ] Skapa mappstruktur och sätta upp Sass istället för bara css 1.5 sp
- [ ] Börja med mobilversionen (allt under varandra) 1 sp
- [ ] Fixa meny och logga i header (flex) 2 sp
- [ ] Lägga till sidopanel i mobilversion 1 sp
- [ ] Testa med större skärm - artiklarna i två kolumner 2 sp
- [ ] Testa ännu större skärm - 3 artiklar på rad + sidopanel bredvid 2 sp
- [ ] Validera min Sass och html 0.5 sp
- [ ] Sammanfatta uppgifter i README.md och skriva hur jag använt mig utav AI 0.5 sp
- [ ] Lägga till färger och lite extra detaljer om jag hinner 0.5 sp
- [ ] Forma inlämningen så jag når VG, dvs skriva i Sass och bifoga en tillgänglighetsrapport 2 sp

Sammanfattning:
Denna uppgift var väldigt svår, hade många problem som dök upp under tiden som jag skrev. Vissa saker gick att fixa med hjölp utav youtube och AI men andra gick inte alls att fixa, möjligvis för att jag inte har så mycket erfarenhet och allting är nytt för mig men har lärt mig att jag lär mig mer och mer och börja förstå hur funktioner funkar och så vidare. I denna uppgift har AI varit ett väldigt bra hjälpmedel för att få mig förstå varför saker blir som de blir. De som inte gick att fixa för mig var att lägga till så att menyraden la sig under "loggan" och att sökmotorn skulle läggas på vänster sida. Tog tid att fixa live server och validera mitt repo. Efter att jag nu är klar och ska lämna in den känner jag att jag måste lägga in en extra växel för att lära mig och förstå alla programmerings språk som vi kommer att ha framöver.

Responsiv nyhetssida byggd med HTML + SCSS. Grid används för artikellistan, flex i headern. Fokus på enkel, tillgänglig layout som skalar från mobil till desktop. CHECK

- Hero-bild (huvudartikel): egen layout utan fast höjd – visar hela bilden, begränsad max-bredd på desktop.

- Brytpunkter: 600px, 700px och 1024px.

Har?:

- SCSS: Ja (kompileras till `css/style.css`).
- Grid: Ja (artikellistan).
- Flex: Ja (headerns navigering).
- Responsivitet: Ja – testen gjord i DevTools (mobil, tablet, desktop).
- Tillgänglighet: fokus-stilar, alt-texter, reduced-motion.

- Testad med WAVE.
- Fynd & åtgärd:
  - Kontrast OK (svart på vit bakgrund).
  - Alt-texter kompletterade på alla bilder.
  - Synligt fokus på länkar/knappar/inputs.
  - `prefers-reduced-motion` hanteras.
