# De 15 opskrifter

Hver opskrift er én opgave, du allerede laver i forvejen. Strukturen er den samme hele vejen:

**Formål** → **Det skal du have klar** → **Sådan gør du** → **FRAME-prompt** → **Explore · Refine · Commit** → **Sådan viser du værdien**

> **Eksemplerne er pladsholdere.**
> Prompterne er skrevet med eksempler fra et advokatfirma — de står inde i de firkantede parenteser, sådan her: `[MIN ROLLE – fx advokat]`. Det er ikke, fordi playbooken er til jurister. Det er, fordi en tom skabelon er svær at komme i gang med.
> Når du kører [START.md](START.md), skriver din AI dem om til dit fag. Så er advokaten væk.

> **🔒 markerer opskrifter, der bruger kunde- eller klientmateriale.** De kræver adgangsbilletten — se [Spilleregler i PLAYBOOK.md](PLAYBOOK.md#spilleregler--før-du-bruger-den-på-rigtigt-arbejde). Uden den: kør dem på afidentificeret materiale.
>
> **Startpakken uden ventetid:** opskrift 15, 1 og 10. De kører på dit eget udkast, dine egne noter og offentligt materiale — ingen tilladelser nødvendige.

---

## 1. Husk mit tidligere arbejde

**Formål:** Få AI'en til at fungere som din personlige hukommelse over egne notater, udkast og skabeloner, så du ikke skal lede eller skrive det samme to gange.

**Det skal du have klar**
- En håndfuld af dine egne notater, gode udkast, checklister og skabeloner — 5–20 dokumenter er rigeligt. De må ligge hvor som helst, du selv kan finde dem.
- Ingen kundefortrolige dokumenter i første omgang.

**Sådan gør du**
1. Kan du vedhæfte filer, så vedhæft dem. Kan du ikke, så kopiér teksten ind — ét dokument ad gangen, med en overskrift foran hvert.
2. Indsæt prompten og udfyld spørgsmålet.
3. Bruger du de samme dokumenter igen og igen, kan de måske gemmes som faste kilder i dit værktøj. Spørg din AI, om du har den mulighed.

**FRAME — starter-prompt**
```
Du er min personlige assistent. Jeg har givet dig mine egne notater, udkast og
skabeloner fra tidligere arbejde.

Opgave: Svar på spørgsmålet nedenfor UDELUKKENDE ud fra det materiale, jeg har givet dig.

Spørgsmål: [SKRIV DIT SPØRGSMÅL – fx "Hvordan formulerede jeg sidst en
konkurrenceklausul, og hvilke forbehold tog jeg?"]

Format:
1. Kort svar (max 5 linjer).
2. Relevante tekstuddrag, citeret ordret, med dokumentnavn og afsnit.
3. Hvad der IKKE kunne findes i materialet – gæt ikke, og brug ikke generel viden.
4. Forslag til 2-3 opfølgende spørgsmål, jeg kunne stille.
```

**Explore · Refine · Commit**
- **Explore:** *"Er der flere steder i materialet, der berører det samme? Vis mig de tre vigtigste — også dem du er i tvivl om."*
- **Refine:** *"Det andet uddrag er det rigtige. Find alt, hvad jeg har skrevet om netop den formulering."*
- **Commit:** Du vælger, hvad du genbruger, og tjekker det mod den aktuelle opgave.

**Sådan viser du værdien**
- Tag tid på 5 spørgsmål, du normalt ville lede efter i gamle filer.
- Notér hvor ofte svaret var korrekt og citerede det rigtige dokument (mål: 4 af 5).
- Notér hvad du fandt, som du havde glemt eksisterede — det er den skjulte gevinst.

⚠ **Pas på:** AI'en svarer kun på det, du har givet den. "Finder" den noget, du ikke genkender, så tjek kilden.

---

## 2. 🔒 Udkast til svar på en vanskelig mail

**Formål:** Få et solidt første udkast til et svar på få minutter — i din egen tone og baseret på sagens materiale.

**Det skal du have klar**
- Mailen (kopiér teksten).
- De 1–3 bilag eller afsnit, svaret skal bygge på.
- Evt. et tidligere svar fra dig, så AI'en kan ramme din tone.

**Sådan gør du**
1. Vedhæft bilagene — eller indsæt dem som tekst under prompten.
2. Udfyld pladsholderne og send.
3. Læs udkastet kritisk, ret, og kopiér det til din mail. Du er altid afsender.

**FRAME — starter-prompt**
```
Du er en erfaren [MIN ROLLE – fx advokat]. Jeg er ansvarlig for denne sag.

Opgave: Skriv et udkast til mit svar på mailen nedenfor.

Tone: Professionel, klar og imødekommende. Ingen floskler. Du-form til modtageren.
Længde: Max [200] ord.
Struktur: (1) kvittering, (2) svar på spørgsmålene i den rækkefølge de blev stillet,
(3) næste skridt og hvad jeg behøver fra modtageren, (4) venlig afslutning.
Regler: Byg kun på det materiale, jeg giver dig. Marker alt, du ikke kan belægge,
med [TJEK]. Giv ingen faglig konklusion, som ikke fremgår af materialet.

Afslut med en kort liste: "Punkter jeg bør overveje før afsendelse".

=== MAILEN ===
[INDSÆT]
=== RELEVANT MATERIALE ===
[INDSÆT ELLER HENVIS TIL VEDHÆFTEDE FILER]
=== EKSEMPEL PÅ MIN TONE (valgfrit) ===
[INDSÆT ET TIDLIGERE SVAR FRA DIG]
```

**Explore · Refine · Commit**
- **Explore:** *"Giv mig tre udkast: ét kort og konkret, ét mere imødekommende, ét der holder mulighederne åbne."*
- **Refine:** *"Nummer to er tættest på. Gør den 30 ord kortere, og fjern fagsproget i andet afsnit."*
- **Commit:** Du retter til, tjekker alle [TJEK]-markeringer og sender fra din egen mail. Ansvaret er dit.

**Sådan viser du værdien**
- Vælg 5 mails i en uge. Notér tiden fra mail åbnet til svar klar, og hold den op mod dit eget registrerede tal.
- Notér hvor mange ændringer du lavede (få / nogle / skrev om). Mål: "få" i mindst 3 af 5.
- Gem det bedste eksempel (anonymiseret) som case.

⚠ **Pas på:** Fjern personoplysninger, modtageren ikke har bedt om at få delt. Tjek alle [TJEK]-markeringer.

---

## 3. Sammenligning med tidligere opgaver

**Formål:** Finde ligheder, forskelle og brugbare argumenter mellem en ny opgave og 2–5 tidligere — hurtigere end at genlæse dem alle.

**Det skal du have klar**
- Et kort resumé af den nye opgave (5–10 linjer).
- 2–5 referencer: offentligt materiale, eller eget materiale du har afidentificeret, så hverken parter, beløb, branche eller forløb kan henføres. Aldrig en anden kundes dokumenter.

**Sådan gør du**
1. Vedhæft referencerne — eller indsæt teksten med en overskrift foran hver (`=== SAG 1 ===`).
2. Indsæt prompten med resuméet af den nye opgave.
3. Bed om uddybning af de rækker i tabellen, der overrasker dig.

**FRAME — starter-prompt**
```
Du er analytiker inden for [MIT FAGOMRÅDE – fx erhvervsret]. Jeg har givet dig
[ANTAL] referencer – vedhæftet eller indsat.

Her er den nye opgave:
[INDSÆT RESUMÉ: parter, faktum, spørgsmålet der skal afklares, hvad kunden ønsker]

Opgave:
1. Lav en tabel med én række pr. reference og kolonnerne: Reference | Situation i
   korte træk | Spørgsmål | Udfald/konklusion | Lighed med ny opgave (høj/middel/lav)
   | Væsentligste forskel.
2. List de 3-5 argumenter fra referencerne, der er stærkest for min sag, med
   henvisning til hvilken reference og hvilket afsnit de kommer fra.
3. List de argumenter, modparten kan bruge imod os.
4. Hvad adskiller den nye opgave så meget, at referencerne ikke kan bruges direkte?

Byg kun på det materiale, jeg har givet dig. Skriv [IKKE I MATERIALET], hvis du
mangler grundlag.
```

**Explore · Refine · Commit**
- **Explore:** *"Hvilke tre argumenter er stærkest — og hvilke ville du selv være i tvivl om?"*
- **Refine:** *"Uddyb argument 2 med de præcise passager, det bygger på."*
- **Commit:** Du afgør, hvilke referencer der kan bruges, og læser dem selv.

**Sådan viser du værdien**
- Sammenlign med din egen analyse: fandt AI'en det samme? Fandt den noget, du ikke så?
- Tag tid på begge dele, og brug dit eget registrerede tal som før-tid. Husk at tælle kontroltiden med.
- Lad en kollega, der i forvejen er på opgaven, lave samme analyse uden AI — og sammenlign.

---

## 4. 🔒 Opsummer en lang mailtråd og formuler svar

**Formål:** Få overblik over en lang tråd på ét minut — hvem sagde hvad, hvad er aftalt, hvad er åbent — og få et udkast til næste svar.

**Det skal du have klar**
- Mailtråden, kopieret som tekst.

**Sådan gør du**
1. Har dit mailprogram en opsummeringsknap, er det den hurtigste vej.
2. Vil du have mere kontrol, eller har du ikke de knapper: markér hele tråden, kopiér den, og brug prompten nedenfor.
3. Ret udkastet og send fra din egen mail.

**FRAME — starter-prompt**
```
Nedenfor er en mailtråd fra en sag. Jeg er [DIT NAVN], ansvarlig for sagen.

Opgave A – Overblik:
1. Kronologisk resumé, max 10 punkter: dato, afsender, pointen i én linje.
2. Hvad er aftalt (med dato og hvem der har forpligtet sig)?
3. Hvad er stadig åbent eller uafklaret?
4. Frister og datoer nævnt i tråden.
5. Tonen i tråden: er der noget, jeg bør være opmærksom på?

Opgave B – Udkast til mit næste svar:
Skriv et svar til [MODTAGER], der (1) lukker de åbne punkter jeg kan lukke,
(2) stiller præcise spørgsmål til resten, (3) bekræfter næste skridt.
Max [150] ord. Markér alt, du ikke kan belægge i tråden, med [TJEK].

=== MAILTRÅD ===
[INDSÆT – ældste mail nederst er fint]
```

**Explore · Refine · Commit**
- **Explore:** *"Hvad kan jeg have overset i tråden? Nævn tre ting, der kan vise sig vigtige."*
- **Refine:** *"Listen over frister ser ikke komplet ud — gennemgå tråden igen, kun for datoer og tilsagn."*
- **Commit:** Du bekræfter aftaler og frister mod dine egne noter, før du handler på dem.

**Sådan viser du værdien**
- Vælg tråde med 8+ mails. Notér tid til overblik med AI mod at læse tråden selv.
- Tjek om AI'en fangede alle frister og aftaler — notér udeladelser.
- Notér hvor ofte udkastet kunne sendes med små rettelser.

---

## 5. 🔒 Mødereferater

**Formål:** Referat, beslutninger og actions fra et møde uden at nogen skal sidde og skrive.

**Det skal du have klar**
- Aftal med deltagerne, at mødet transskriberes — inden mødet.
- Online møde: slå transskription til ved start, og tjek at sproget er sat rigtigt. Er det sat forkert, bliver referatet ubrugeligt.
- Fysisk møde: dine stikord efter mødet — gerne rodede.

**Sådan gør du**
1. Har dit mødeværktøj en oversigts- eller referatfunktion, så start der. Mangler den, hent transskriptionen og brug prompten nedenfor.
2. Indsæt transskription eller noter.
3. Send referatet til deltagerne til godkendelse.

**FRAME — starter-prompt**
```
Du er referent for et møde. Nedenfor er [transskription / mine stikord].

Mødets formål: [FX "Statusmøde med kunden om projekt X"]
Deltagere: [NAVNE OG ROLLER]
Dato: [DATO]

Skriv et referat med disse afsnit:
1. Formål og deltagere (2 linjer).
2. Drøftet – pr. emne, max 3 linjer pr. emne. Ingen ord-for-ord gengivelse.
3. Beslutninger – nummereret, med hvem der besluttede.
4. Actions – tabel: Hvad | Hvem | Frist.
5. Åbne spørgsmål til næste møde.

Regler: Neutral tone, ingen vurderinger af deltagerne. Er noget uklart, skriv
[UKLART] i stedet for at gætte. Max 1 side.

=== MATERIALE ===
[INDSÆT]
```

**Explore · Refine · Commit**
- **Explore:** *"Er der noget i referatet, der kan læses på to måder? Vis mig hvor."*
- **Refine:** *"Beslutning 3 er gengivet forkert — det var kun en anbefaling. Ret den."*
- **Commit:** Du sender referatet til godkendelse. Det er dig, der står inde for det.

**Sådan viser du værdien**
- Notér din egen før-tid, og hvad det tog nu inkl. kontrol og godkendelse.
- Spørg deltagerne: Var referatet lige så godt som normalt? Bedre?
- Notér om actions faktisk blev fulgt op.

⚠ **Pas på:** Optag eller transskribér aldrig et møde, uden at alle ved det.

---

## 6. 🔒 Præsentation til møde eller pitch

**Formål:** Et første udkast til en præsentation ud fra et notat — så tiden går med indholdet, ikke med at flytte tekstbokse.

**Det skal du have klar**
- Et notat eller en tekst med det, præsentationen skal indeholde (1–2 sider).
- Husets skabelon.
- Målgruppe og formål: hvem sidder i rummet, og hvad skal de beslutte?

**Sådan gør du**
1. Åbn en ny præsentation fra husets skabelon.
2. Har du en "opret fra fil"-funktion, så brug den. Filen skal typisk ligge i skyen — en fil på skrivebordet kan ofte ikke vælges. Har du ikke knappen, så brug prompten i chatten.
3. Forvent et råt udkast med nogenlunde rigtig rækkefølge — ikke et færdigt design. Layout, billeder og alle tal retter du selv.

**FRAME — starter-prompt**
```
Lav en præsentation på [8] slides til [MÅLGRUPPE – fx "bestyrelsen hos kunden"].

Formål med mødet: [FX "Beslutte om vi går videre med løsning A eller B"]
Grundlag: [HENVIS TIL NOTATET eller indsæt teksten nedenfor]

Opbygning:
1. Titel og formål
2. Situationen kort (max 3 punkter)
3-5. Hovedpunkter – ét budskab pr. slide, max 4 bullets, max 12 ord pr. bullet
6. Muligheder og konsekvenser (tabel: Mulighed | Fordele | Risici | Omkostning)
7. Vores anbefaling
8. Næste skridt og den beslutning, vi beder om i dag

Stil: Nøgtern og professionel. Ingen stock-billeder. Skriv talenoter til hver slide
(3-5 linjer), som jeg kan bruge som manuskript.

=== INDHOLD ===
[INDSÆT NOTAT]
```

**Explore · Refine · Commit**
- **Explore:** *"Giv mig tre måder at bygge budskabet op på — hvilken fortælling passer bedst til denne målgruppe?"*
- **Refine:** *"Brug nummer et, men byt slide 4 og 5 om, og gør anbefalingen tydeligere."*
- **Commit:** Du gennemgår alle tal, navne og konklusioner, før du viser den frem.

**Sådan viser du værdien**
- Notér tid til første brugbare udkast — og brug dit eget registrerede tal som før-tid.
- Notér hvor mange slides du beholdt uændret, ændrede eller slettede.
- Bed en kollega vurdere præsentationen — og sig, at den er AI-assisteret.

---

## 7. 🔒 Gennemgang af en kontrakt eller aftale

**Formål:** Systematisk gennemgang mod din egen checkliste — risikopunkter, afvigelser fra standard og forslag til ordlyd.

**Det skal du have klar**
- Kontrakten.
- Din checkliste: 5–15 punkter, du altid tjekker. Har du ikke en, så lad AI'en foreslå en først.
- Hvem din side er i aftalen.

**Sådan gør du**
1. Vedhæft kontrakten. Indsætter du teksten i stedet, så slå ændringsmarkeringer fra først — ellers reviderer AI'en også det, modparten har streget ud.
2. Indsæt checklisten i prompten.
3. Gennemgå tabellen. Den er dit arbejdsredskab, ikke dit svar til kunden.

**FRAME — starter-prompt**
```
Du er en erfaren [MIN ROLLE – fx erhvervsadvokat]. Jeg repræsenterer
[MIN SIDE – fx "kunden"] i den vedhæftede aftale. Modparten er [MODPARTENS ROLLE].

Min checkliste:
[INDSÆT – fx: 1. Ansvarsbegrænsning 2. Opsigelse og bindingsperiode
3. Betalingsvilkår 4. Lovvalg og værneting 5. Databehandling 6. IP-rettigheder]

Opgave:
1. Tabel med én række pr. checklistepunkt: Punkt | Hvor i aftalen (punkt-nr.) |
   Hvad står der (kort) | Risiko for min side (Høj/Middel/Lav) | Begrundelse |
   Forslag til ændret ordlyd.
2. Punkter i aftalen, der er usædvanlige eller skæve til modpartens fordel, og som
   IKKE er på min checkliste.
3. Interne modsigelser, udefinerede begreber og manglende bilag.
4. Top 3 punkter jeg bør forhandle først, og hvorfor.

Henvis altid med punktnummer eller overskrift – aldrig med sidetal. Kan du ikke
angive punktnummer, skriv [UVERIFICERBAR HENVISNING]. Gæt ikke: skriv
[IKKE FUNDET], hvis et punkt ikke er reguleret.
```

**Explore · Refine · Commit**
- **Explore:** *"Hvilke tre punkter ville du forhandle først, hvis du sad på modpartens side?"*
- **Refine:** *"Giv mig to alternative formuleringer af punkt 12.2 — én hård og én, modparten kan sige ja til."*
- **Commit:** Du beslutter, hvad der skal forhandles, og læser selv hvert punkt, du ændrer.

**Sådan viser du værdien**
- Gennemgå aftalen selv først, og sammenlign med AI'ens tabel: Hvad fandt den, du missede? Hvad missede den?
- Notér tid for en standardaftale på 15–30 sider mod dit eget registrerede tal.
- Over 5 aftaler: Lav en liste over typer af fejl, AI'en laver.

⚠ **Pas på:** AI'en kan overse ting i lange aftaler. Brug den som ekstra sæt øjne, ikke som erstatning for din gennemgang.

---

## 8. 🔒 Gennemgang af mange dokumenter

**Formål:** Trække de samme oplysninger ud af mange dokumenter og få dem i én tabel — i stedet for at åbne hvert dokument.

**Det skal du have klar**
- Et udsnit af dokumenterne (start med 5–10 af samme type).
- Listen over oplysninger, du skal have ud af hvert dokument.

**Sådan gør du**
1. Vedhæft dokumenterne — gerne i én samtale pr. dokumenttype. Kan du ikke vedhæfte, så indsæt dem som tekst med `=== DOKUMENT 1 ===` foran hvert.
2. Indsæt prompten med din udtræksliste. Kopiér tabellen ind i et regneark.
3. Kontrollér alle felter markeret [USIKKER], alle ⚠, og hvert felt i 3 tilfældigt valgte dokumenter.

**FRAME — starter-prompt**
```
Du er analytiker. Jeg har givet dig [ANTAL] dokumenter af typen
[FX "kundekontrakter"].

Opgave: Lav én tabel med én række pr. dokument og disse kolonner:
[TILPAS LISTEN – fx] Dokumentnavn | Parter | Dato | Løbetid/udløb |
Opsigelsesvarsel | Change-of-control (ja/nej + punkt-nr.) | Eksklusivitet |
Ansvarsbegrænsning | Lovvalg | Andet bemærkelsesværdigt

Regler:
- Skriv [IKKE FUNDET], hvis en oplysning ikke står i dokumentet. Gæt aldrig.
- Angiv punktnummer eller overskrift i parentes ved hver oplysning – aldrig sidetal.
- Marker med ⚠ alt, der afviger fra normal markedsstandard.
- Marker med [USIKKER], hvor du ikke entydigt kan læse oplysningen ud af dokumentet.
  Det er en anden markering end ⚠ – den handler om dig, ikke om dokumentet.

Afslut med: (1) de 5 dokumenter jeg bør læse grundigst og hvorfor, (2) mønstre på
tværs, (3) dokumenter der ser ud til at mangle bilag eller underskrift.
```

**Explore · Refine · Commit**
- **Explore:** *"Hvilke felter er du mest usikker på? Lav en liste over dem, jeg bør kontrollere først."*
- **Refine:** *"Kolonnen for opsigelsesvarsel ser forkert ud i tre rækker — gennemgå kun den igen."*
- **Commit:** Du stikprøvekontrollerer mod dokumenterne og står inde for tabellen.

**Sådan viser du værdien**
- Tag tid på de første 10 dokumenter manuelt mod med AI + kontrol. Ekstrapolér ikke tidsbesparelsen uden at ekstrapolere fejlraten med.
- Notér, hvor mange felter der var forkerte ved kontrollen — og hvilken slags felter.

⚠ **Pas på:** Tabellen er din læseplan, ikke dit resultat. Den går aldrig videre til kunden uden fuld gennemgang. Del desuden op i portioner af 5–10 dokumenter.

---

## 9. 🔒 Kronologi over et forløb

**Formål:** En tidslinje over forløbets begivenheder med kildehenvisning — grundlaget for sagsfremstillingen og for at opdage huller i dokumentationen.

**Det skal du have klar**
- Bilagene: mails, breve, aftaler, mødereferater.
- En bilagsliste med numre, hvis der findes en.

**Sådan gør du**
1. Vedhæft bilagene, eller indsæt dem som tekst. Ved mange bilag: tag dem i portioner og bed AI'en udbygge tidslinjen.
2. Indsæt prompten. Kopiér tabellen ud og hold den ved lige.
3. Spørg videre: *"hvilke perioder mangler vi dokumentation for?"*

**FRAME — starter-prompt**
```
Du hjælper med at lave en kronologi over et forløb. Jeg repræsenterer [MIN SIDE].
Bilagene er vedhæftet eller indsat nedenfor. Bilagsliste: [INDSÆT, HVIS DEN FINDES]

Opgave:
1. Tabel i kronologisk orden: Dato | Begivenhed (1-2 linjer, neutralt formuleret) |
   Aktør(er) | Kilde (bilagsnr. eller dokumentnavn – aldrig sidetal) | Betydning.
2. Perioder hvor der ikke er dokumentation, men hvor der sandsynligvis er sket noget.
3. Begivenheder hvor bilagene modsiger hinanden (dato, beløb, hvem sagde hvad).
4. De 5 begivenheder der er mest centrale for spørgsmålet: [INDSÆT SPØRGSMÅL].

Regler: Brug kun datoer der står i bilagene. Usikre datoer markeres "ca." med
begrundelse. Ingen vurdering af skyld eller ansvar – kun hvad der skete ifølge kilderne.
```

**Explore · Refine · Commit**
- **Explore:** *"Hvor er der huller i tidslinjen, og hvilke bilag mangler vi sandsynligvis?"*
- **Refine:** *"Begivenhederne i marts er for upræcise — uddyb dem med kildehenvisning."*
- **Commit:** Du kontrollerer datoer og kilder, før kronologien bruges.

**Sådan viser du værdien**
- Notér tid til første kronologi mod dit eget registrerede tal på et forløb med 20–40 bilag.
- Tjek stikprøvevis 10 rækker mod bilagene: korrekt dato og kilde? (Mål: alle 10.)
- Notér om AI'en fandt modsigelser eller huller, du ikke selv havde set.

---

## 10. Opsummering af et langt dokument

**Formål:** Forstå et langt dokument på 5 minutter og vurdere, om det er relevant — før du bruger en time på at læse det.

**Det skal du have klar**
- Dokumentet: en afgørelse, en rapport, en standard, et regelsæt.
- 2–5 linjer om den opgave, du vil bruge det i.

**Sådan gør du**
1. Vedhæft dokumentet — eller indsæt teksten — og indsæt prompten.
2. Læs resuméet, og læs derefter selv de afsnit, AI'en peger på som afgørende.
3. Gem resuméet i din "AI-kontekst"-mappe (opskrift 1), så du kan finde det igen.

**FRAME — starter-prompt**
```
Du er research-assistent. Vedhæftet er [DOKUMENTTYPE – fx en afgørelse fra
Højesteret / en brancherapport / en ny standard].

Min opgave i korte træk: [INDSÆT 2-5 LINJER]

Opgave – skriv et resumé med disse afsnit:
1. Hvad handler det om (max 5 linjer).
2. Det centrale spørgsmål, dokumentet tager stilling til.
3. De vigtigste synspunkter eller parter.
4. De afgørende passager, citeret ordret med angivelse af afsnit eller punktnummer
   (ikke sidetal).
5. Resultatet eller konklusionen.
6. Relevans for min opgave: Hvad støtter min sag? Hvad taler imod? Hvad adskiller?
7. Forbehold eller uenigheder i dokumentet, hvis der er nogen.

Regler: Citér ordret, når du gengiver det afgørende. Skriv [USIKKER], hvis du er i
tvivl om, hvad der blev lagt vægt på. Max 1 side.
```

**Explore · Refine · Commit**
- **Explore:** *"Hvad taler imod at bruge dokumentet i min opgave? Giv mig modargumenterne."*
- **Refine:** *"Citér ordret de passager, du bygger relevansvurderingen på."*
- **Commit:** Du læser dokumentet selv, før du henviser til det. Resuméet er ikke en kilde.

**Sådan viser du værdien**
- Læs dokumentet selv bagefter: Var resuméet dækkende? Misforstod AI'en noget?
- Tag tid: Hvor lang tid sparede du på de dokumenter, der viste sig IKKE at være relevante?
- Saml resuméerne — efter 10 har du begyndelsen på en personlig vidensbase.

⚠ **Pas på:** AI'en kan fejlgengive. Brug aldrig resuméet som kilde i noget, du sender ud.

---

## 11. 🔒 Standarddokumenter fra skabelon

**Formål:** Udfylde en skabelon med opgavens oplysninger uden gentastning — og få markeret alt, der mangler.

**Det skal du have klar**
- Skabelonen med tydelige pladsholdere (fx `[PART A]`, `[DATO]`, `[BELØB]`).
- Oplysningerne som tekst.

**Sådan gør du**
1. Kopiér skabelonens tekst ind i chatten sammen med prompten, og sæt resultatet tilbage i dit dokument. (En "skriv udkast"-knap i tekstbehandlingen skriver nyt indhold — den udfylder ikke pladsholdere og lader resten stå.)
2. Søg efter `[MANGLER]` i resultatet og udfyld selv.
3. Gem som nyt dokument. Skabelonen røres ikke.

**FRAME — starter-prompt**
```
Skabelonen er vedhæftet eller indsat nedenfor. Den har pladsholdere i firkantede
parenteser.

Opgave: Udfyld skabelonen med oplysningerne nedenfor og returnér hele dokumentet.

Regler:
- Ændr IKKE skabelonens tekst, rækkefølge eller formulering – udfyld kun pladsholdere.
- Mangler en oplysning, skriv [MANGLER: beskrivelse] i stedet for at gætte.
- Er en oplysning tvetydig, skriv [TJEK: ...] og forklar.
- Bøj navne og beløb korrekt (fx "selskabets", "kr. 125.000,00").

Afslut med en liste over alle [MANGLER]- og [TJEK]-markeringer.

=== OPLYSNINGER ===
Part A: [NAVN, ADRESSE, CVR]
Part B: [NAVN, ADRESSE, CVR]
Dato: [ ]   Beløb: [ ]   Øvrigt: [ ]
```

**Explore · Refine · Commit**
- **Explore:** *"Er der steder, hvor mine oplysninger kan passe på flere måder? Vis mig dem."*
- **Refine:** *"Punkt 4 skal formuleres som i det forrige dokument — her er teksten."*
- **Commit:** Du udfylder alle [MANGLER] og godkender dokumentet.

**Sådan viser du værdien**
- Notér tid pr. dokument mod dit eget registrerede tal, og antal fejl i stamdata fundet ved kontrol.
- Notér hvor ofte [MANGLER]-listen fangede noget, du ellers ville have overset.

---

## 12. 🔒 Hvad lavede jeg i dag

**Formål:** Få en huskeliste over dagens aktiviteter, så du ikke glemmer at registrere noget, du faktisk har lavet. AI'en foreslår aldrig et tidsforbrug — den lister aktiviteter, du selv sætter tid på.

**Det skal du have klar**
- Dagens kalender.
- Dagens sendte mails — emnelinjer er nok.
- Dine egne stikord om, hvad du ellers lavede.

**Sådan gør du**
1. Sidst på dagen: prøv først at spørge din AI, om den selv kan se dine møder og mails. Kan den ikke, så kopiér dem ind.
2. Indsæt prompten og suppler med dine stikord.
3. Gennemgå listen, sæt selv tid på hver aktivitet, og overfør det, du kan stå inde for.

**FRAME — starter-prompt**
```
Hjælp mig med at huske, hvad jeg har lavet i dag.

Lav en tabel: Sag/kunde | Aktivitet (hvad jeg gjorde, max 15 ord, i datid) |
Hvornår (klokkeslæt hvis det fremgår) | Kilde (møde/mail/stikord) |
Tid (lad denne kolonne stå TOM).

Regler:
- Du må IKKE foreslå tidsforbrug eller varighed. Tidskolonnen udfylder jeg selv.
  Gæt aldrig på, hvor lang tid noget tog.
- Skriv kun aktiviteter, du kan belægge i materialet. Udfyld intet efter sandsynlighed.
- Beskriv neutralt, hvad der skete – ikke hvad det er værd.
- Slut med: hvilke perioder af dagen er der ingen spor fra? Spørg mig, hvad jeg
  lavede der.

=== KALENDER I DAG ===
[INDSÆT]
=== SENDTE MAILS I DAG (emne + modtager) ===
[INDSÆT]
=== MINE STIKORD ===
[INDSÆT]
```

**Explore · Refine · Commit**
- **Explore:** *"Hvor ser det ud til, at jeg mangler at registrere noget? Spørg mig om de huller, du finder."*
- **Refine:** *"Slå de tre poster på samme sag sammen til én, og gør beskrivelsen mere neutral."*
- **Commit:** Du godkender hver post. Registrér aldrig tid, du ikke selv kan stå inde for.

**Sådan viser du værdien**
- Notér antallet af aktiviteter, du havde glemt, og som listen mindede dig om.
- Notér tid brugt på selve registreringen mod en normal dag.
- Mål ikke på "flere timer faktureret". Det er ikke et resultat, du kan forsvare.

⚠ **Pas på:** AI'en må minde dig om aktiviteter — aldrig sætte tid på dem. Et AI-skøn er ikke dokumentation.

---

## 13. 🔒 Oversæt til modtagerens sprog

**Formål:** Oversætte fagtekst til noget modtageren forstår — eller til et andet sprog med korrekt fagterminologi.

**Det skal du have klar**
- Teksten.
- Hvem modtageren er.

**Sådan gør du**
1. Indsæt prompten. Vælg variant A (forklaring) eller B (oversættelse).
2. Læs resultatet som modtageren: Er det korrekt OG forståeligt? Ret det faglige, hvis forenklingen er gået for langt.

**FRAME — starter-prompt**
```
VARIANT A – Forklaring uden fagsprog:
Forklar teksten nedenfor til [MODTAGER – fx "en ejer af en mindre virksomhed uden
faglig baggrund"]. Krav: Du-form, ingen fagudtryk uden forklaring, max [150] ord.
Struktur: (1) Hvad betyder det for dig? (2) Hvad skal du gøre? (3) Hvad er risikoen,
hvis du ikke gør det? Ændr ikke betydningen – skriv [TJEK], hvis en forenkling kan
misforstås.

VARIANT B – Oversættelse:
Oversæt teksten nedenfor til [SPROG] til brug over for [MODTAGER]. Bevar struktur og
nummerering. Brug etablerede fagtermer. Lav en tabel til sidst med de 5-10 fagudtryk
og de valgte termer, så jeg kan godkende terminologien.

=== TEKST ===
[INDSÆT]
```

**Explore · Refine · Commit**
- **Explore:** *"Giv mig to versioner: én meget enkel og én, der bevarer flere forbehold."*
- **Refine:** *"Den enkle er bedst, men forbeholdet om frister skal med igen."*
- **Commit:** Du tjekker, at forenklingen ikke har ændret betydningen.

**Sådan viser du værdien**
- Variant A: Spørg modtageren, om forklaringen var til at forstå. Notér færre opfølgende spørgsmål.
- Variant B: Notér tid mod en ekstern oversætter og antal termer, du måtte rette.

---

## 14. 🔒 Forberedelse før et møde

**Formål:** Møde velforberedt: få en liste over de spørgsmål, du bør stille, og de huller, du bør lukke — før mødet.

**Det skal du have klar**
- 5–10 linjer om opgaven og mødets formål.
- Evt. de dokumenter, du allerede har.

**Sådan gør du**
1. Indsæt prompten 10 minutter før mødet.
2. Vælg de 5–8 spørgsmål, du faktisk vil stille. Tag listen med.
3. Efter mødet: Brug opskrift 5 på dine noter.

**FRAME — starter-prompt**
```
Du er en erfaren [MIN ROLLE], der hjælper mig med at forberede et møde.

Opgaven: [INDSÆT 5-10 LINJER: type, parter, hvad kunden ønsker, hvor vi står]
Mødets formål: [FX "Første møde med ny kunde om en mulig opgave"]
Hvad jeg allerede ved/har: [DOKUMENTER, FAKTA]

Opgave:
1. De 10 vigtigste spørgsmål jeg bør stille – prioriteret, og med én linje om hvorfor
   hvert spørgsmål er vigtigt for udfaldet.
2. Dokumenter og oplysninger jeg bør bede om at få tilsendt.
3. Typiske faldgruber eller forhold, kunder ofte glemmer at nævne i denne slags sager.
4. 3 ting kunden sandsynligvis vil spørge mig om – og stikord til mit svar.
5. Hvilke frist- eller deadlinespørgsmål bør jeg selv undersøge? Angiv aldrig selv en
   frist – nævn kun, hvad jeg skal slå op.

Hold det til én side. Markér med [TJEK], hvis du er usikker på gældende regler.
```

**Explore · Refine · Commit**
- **Explore:** *"Hvilke spørgsmål ville du tilføje, hvis opgaven viser sig at handle om noget andet?"*
- **Refine:** *"Fokusér på dokumentation — giv mig fem spørgsmål mere i den retning."*
- **Commit:** Du vælger de spørgsmål, du faktisk stiller, og styrer selv mødet.

**Sådan viser du værdien**
- Notér efter mødet: Hvor mange af AI'ens spørgsmål stillede du? Hvor mange havde du selv tænkt på?
- Notér om listen fangede noget, der viste sig vigtigt.
- Tid: Din egen sædvanlige forberedelsestid mod denne gang.

⚠ **Pas på:** Svar om gældende regler, frister og deadlines skal altid efterprøves — det er dér, en sprogmodel lyder mest overbevisende, når den tager fejl.

---

## 15. Kvalitetssikring af dit eget udkast

**Formål:** Få et ekstra sæt øjne på noget, du selv har skrevet — interne modsigelser, forkerte krydshenvisninger, tal der ikke stemmer, og steder hvor du lover mere end grundlaget bærer. Fagligt er den let at kontrollere: du kender teksten og kan efterprøve hvert punkt på sekunder.

**Det skal du have klar**
- Dit eget udkast: notat, rapport, aftale, kundebrev.
- Dit udkast er fortroligt materiale på lige fod med alt andet på sagen — at du selv har skrevet det, ændrer ikke på det. Indtil adgangsbilletten er på plads: kør den på et internt notat eller en afidentificeret tekst.

**Sådan gør du**
1. Vedhæft udkastet, eller indsæt teksten.
2. Indsæt prompten.
3. Gennemgå listen punkt for punkt. Du behøver ikke være enig — men du skal forholde dig til hvert punkt.

**FRAME — starter-prompt**
```
Du er en kritisk og grundig kollega. Nedenfor er et udkast, jeg selv har skrevet.
Du skal ikke omskrive det. Du skal finde fejl og svagheder.

Dokumenttype: [FX "notat til kunden om opsigelsesvarsel"]
Modtager: [HVEM SKAL LÆSE DET]

Gennemgå teksten for:
1. Interne modsigelser – steder hvor to afsnit ikke kan passe samtidig.
2. Krydshenvisninger der peger forkert (punkt, bilag, afsnit).
3. Tal og datoer der ikke stemmer overens gennem dokumentet.
4. Påstande hvor jeg lover eller konkluderer mere, end teksten selv belægger.
5. Uklare formuleringer, der kan læses på to måder af en modpart.
6. Manglende forbehold, som jeg sandsynligvis burde have taget.

Format: Tabel med Sted (citér de 5-8 ord) | Hvad er problemet | Hvor sikker er du
(høj/middel/lav). Sortér med det vigtigste først.

Regler: Byg kun på teksten foran dig. Vurdér ikke, om fagligheden er rigtig – kun om
dokumentet hænger sammen med sig selv. Finder du ingen problemer i en kategori, så
skriv det i stedet for at opfinde noget.

=== MIT UDKAST ===
[INDSÆT]
```

**Explore · Refine · Commit**
- **Explore:** *"Hvilke af punkterne ville du selv være mest i tvivl om? Og er der noget, du ikke nævnte, fordi du var usikker?"*
- **Refine:** *"Punkt 3 er ikke en fejl — det er bevidst. Se bort fra det, og gennemgå resten igen."*
- **Commit:** Du afgør, hvad der er en reel fejl. Et rent svar er ikke en godkendelse af dokumentet.

**Sådan viser du værdien**
- Notér, hvor mange reelle fejl den fandt, som du selv ville have sendt af sted.
- Notér antallet af falske alarmer — forholdet mellem de to er casen.
- Tid: Hvor lang tid tog gennemgangen mod at bede en kollega læse udkastet igennem?

⚠ **Pas på:** Den vurderer, om dokumentet hænger sammen — ikke om fagligheden er rigtig. Et rent svar betyder ikke, at udkastet er korrekt.
