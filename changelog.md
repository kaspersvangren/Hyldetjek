# Ændringer i Hyldetjek

Nyeste øverst. Versionsnummeret står øverst i værktøjet ved siden af navnet.

Numrene betyder: første tal ændrer sig, hvis værktøjet grundlæggende laves om. Andet tal er nye ting, man kan. Tredje tal er rettelser og sproglige ændringer.

---

## 1.9.0

- **Klassifikation kan afgrænses til et interval.** Ved siden af "er præcis", "begynder med" og "indeholder" er der nu "mellem", hvor du skriver fra og til – fx 64 til 64.12, eller 99.1 til 99.94. Tallet forrest i klassemærket er det, der tæller, så "99.4 Ditlevsen, Tove" regnes som 99.4. Undergrupper kommer med i toppen af intervallet: slutter du ved 64.12, er 64.125 med. Klassemærker uden tal – "sk" for skønlitteratur – kan ikke ligge i et interval og kommer ikke med.

## 1.8.4

- Panelet foldede "Afgræns materialerne" sammen og sprang op i toppen af siden, hver gang det blev tegnet om. Det skete ved sortering, ved valg af en gemt opsætning, ved Gem og Nulstil og ved skift af felt under Sted. Nu bliver åbne afsnit, åbne hjælpetekster, indtastede søgeord og din plads på siden, hvor de var.

## 1.8.3

- Vejledningerne er skrevet om til eksempler frem for anvisninger. Afsnittet hedder nu "Eksempler på brug" og fortæller, hvad du får ud af en opsætning – ikke hvad du bør gøre bagefter.

## 1.8.2

- Feltet "og hører også til her" hedder nu **"og har også et eksemplar her"**. Det gamle navn lød, som om der blev tjekket, hvor bogen hører hjemme; der tjekkes kun, om der overhovedet står et eksemplar det sted.
- Begge steder-felter har fået hjælp, og vejledningen forklarer forskellen på de to sammenlignende funktioner.

## 1.8.1

- Sorteringsknapperne står nu **over** listen i stedet for under. Man skulle ellers scrolle forbi hele listen for at nå dem.

## 1.8.0

- **Hver liste af valgmuligheder kan sorteres.** To små knapper til højre: alfabetisk eller efter antal, og en pil, der vender rækkefølgen om. Delopstilling og Mat. type står alfabetisk fra start, resten efter antal. Valget huskes pr. liste.

## 1.7.0

- **Hjælp overalt.** Hver funktion har fået en beskrivelse, der siger, hvad den finder, og et foldbart afsnit med konkrete eksempler.
- Hvert felt i panelet har et spørgsmålstegn, der folder en forklaring ud.

## 1.6.1

- Mærkatet på en gruppe hedder nu **"N titelvarianter"** i stedet for "N udgaver". Tallet er antallet af forskellige titelstrenge i gruppen. Det er ikke et sikkert antal udgaver: tre udgaver med præcis samme titel kan ikke skelnes fra hinanden i eksporten.

## 1.6.0

- **Forfatteren står først**, i fed, med titlen under – både i resultatlisten og på hyldelisten. Det er som regel forfatteren, man leder efter ved hylden.
- Hyldelisten har fået en kolonne, der viser, hvor mange af titlen der er talt med, og hvor resten står: "1 af 3 · 2 i Hovedbiblioteket". Så kan man tage stilling ved hylden uden at gå tilbage til skærmen.

## 1.5.1

- "Ved …" og "Ill. …" bliver igen stående i titlen. De kan betyde forskellige udvalg og altså forskellige bøger – H.C. Andersens *Eventyr* ved Villy Sørensen er ikke samme bog som *Eventyr: et udvalg* med Ib Spang Olsens illustrationer. Prisen er, at en oversættelse nu tæller som sin egen titel. Det er med vilje: en overset udgave koster ingenting, en falsk triplet koster en bog.

## 1.5.0

- **Titler slås rigtigere sammen.** Før blev alt efter det første kolon skåret væk, så "PS: jeg elsker dig" og "PS: Jeg elsker dig for evigt" blev talt som samme bog. Nu beholdes undertitler, medmindre de beskriver samme bog i en anden form: genre ("roman", "krimi", "noveller"), format ("mp3", storskriftserier) eller udgave. Bindnumre trækkes stadig ud, uanset hvordan de er skrevet.

## 1.4.2

- Står det samme materialenummer to gange i filen – typisk fordi materialet skiftede status, mens udtrækket blev lavet – beholdes den række, der **ikke** siger Hjemme. Ellers kunne listen sende dig ud til en hylde, hvor bogen ikke står.
- Beskeden om det er blevet klarere og har fået en knap, der henter numrene som CSV, hvis du vil se dem i Cicero.

## 1.4.1

- Overskriften hedder "Tæl inden for samme…" i ét stykke i stedet for at være delt op.

## 1.4.0

- **Nulstil-knap** ved siden af Find, som sætter alle indstillinger tilbage til standard.
- **Favoritter.** Når du gemmer en opsætning, kan du sætte flueben i "Vis som genvej på forsiden". Så ligger den som en knap under funktionen på forsiden og kører med det samme, når du trykker. Stjernen følger med, når du deler dine opsætninger.
- Gem foregår i en lille linje i panelet i stedet for en dialogboks.

## 1.3.0

- Niveauerne hedder igen Ciceros egne: Filial, Afdeling, Opstilling, Delopstilling – og Sektion, når placeringen har fem led.
- **Vælg alle / Fravælg alle** under hvert niveau i Grundopsætningen.
- **"Tilføj filer"** og **"Start forfra"** i stedet for "Vælg en anden fil", så det er tydeligt, at man kan lægge flere filer oveni. De indlæste filer står listet på forsiden.
- Knappen, der folder en liste ud, bliver stående, hvor den var.

## 1.2.0

- **Flere CSV-filer kan læses ind på én gang.** De lægges sammen, filer med andre kolonner springes over med en besked, og rækker med et materialenummer, der allerede er læst, tælles kun én gang. Nyttigt, når Cicero ikke kan levere hele samlingen i ét udtræk.

## 1.1.0

- **Grundopsætning** på forsiden: fravælg de steder, der aldrig skal med – et arkiv, tomme filialer. Valget huskes og gælder alle opgaver.
- **"Søg i"** står nu synligt i alle funktioner med ét felt pr. placeringsniveau.
- Statusser er foldet sammen med Hjemme valgt fra start; resten kan foldes ud.

## 1.0.0

Første udgave.

- Tre funktioner: **Flere eksemplarer** (antallet vælger du selv, så tripletter, dubletter og udstillingsstakke er samme værktøj), **Hjemme her, og også dér** og **Hjemme her, men ikke dér**.
- Alle valgmuligheder – filialer, opstillinger, materialegrupper, statusser – læses ud af din egen fil, så værktøjet passer til det bibliotek, der bruger det.
- Resultatet vises med afkrydsning pr. eksemplar, så du kan fravælge, inden du eksporterer.
- To udgange: **hyldeliste** til print, sorteret efter placering, og **CSV til Cicero** med ét materialenummer pr. linje.
- Gemte opsætninger, som kan deles med kolleger som en fil.

---

## Om værktøjet

Hyldetjek kører helt i din browser. Din eksport bliver læst på din egen computer og sendes ingen steder hen. Gemte opsætninger og grundopsætning ligger i browserens eget lager – de følger den maskine og den browser, du bruger, ikke dig. Skal de med over på en anden computer, bruger du Del og Hent.
