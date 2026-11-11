# Kommunal udligning 2027 – dokumentationsgrundlag v0.1

**Status:** Løbende projektjournal, ikke slutrapport. 11. november 2026.

## Formål og afgrænsning

Simulatoren er en offentlig demonstrationsmodel for kommunal udligning i 2027. Brugeren vælger én kommune og ændrer dens økonomiske, aldersmæssige eller socioøkonomiske input. Baseline for alle 98 kommuner fastholdes, og nødvendige nationale afledninger genberegnes. Visningen sammenholder baseline, scenarie og forskel for den valgte kommune. Modellen dækker ikke alle tilskuds- og udligningsordninger og må ikke anvendes som officielt beslutningsgrundlag.

## Datakilder og sporbarhed

Arbejdsgrundlaget omfatter ministerielle 2027-publikationer om kommunal udligning og generelle tilskud, regeloversigten 2027, statsgaranteret udskrivningsgrundlag 2027 samt projektets Excel-reference v50. Originale publikationstitler i projektmaterialet: “3-tabeller-vedr-kommunal-udligning-og-generelle-tilskud-2027”, “4-regeloversigt-2027-kommuner” og “5-statsgaranteret-udskrivningsgrundlag-2027-for-kommuner”. Kilde-til-felt-mapping, direkte offentlig URL, licens og udtræksdato skal gennemgås og godkendes før publicering. Offentlig tilgængelighed er ikke i sig selv dokumentation for genbrugsrettigheder.

## Beregningsprincip

Der anvendes en fælles, uforanderlig 2027-baseline med 98 kommuner. Kun den valgte kommunes rå input ændres i scenariet. Aldersfordelte input påvirker relevante udgiftsbehov. Socioøkonomiske kriterier påvirker fordelingen af en national pulje, hvorfor afledte beløb for øvrige kommuner kan ændres uden ændring af deres egne rå input. Beregninger udføres lokalt i browseren. Den integrerede JavaScript-motor er afstemt mod Excel v50 i afgrænsede scenarier, men er ikke en fuld officiel 2027-beregningsmotor.

## Valideringsstatus

Projektets integrationsrapport dokumenterer seks friske Dragør-scenarier og 60 feltafstemninger for den integrerede motor samt 1.377 nationale isolerede kontroller. Tidligere Odense- og Langeland-scenarier er afstemt særskilt. Brugerens manuelle funktionstest af UX/UI v2.2 er positiv. Der foreligger ikke en bestået automatiseret browser-/DOM-regression eller komplet uafhængig 98-kommuners afstemning. En særskilt afvigelse for Dragørs overudligning på 12.000 kr. er åben. Dette må ikke forveksles med de seks beståede hovedudligningsscenarier.

## Versionshistorik

Excel v50 er den bevarede referencemodel. PoC 1–4 udviklede gradvist input, aldersfordeling, socioøkonomi og tre faner. UX/UI v2.1 fastlagde den godkendte brugeroplevelse. UX/UI v2.2 integrerede national socioøkonomisk omfordeling. Offentlig test v2.2 tilføjede testadvarsel; denne dokumentationsudgave tilføjer kun dokumentationslink og -side. Beregningsscriptet er ikke ændret i denne dokumentationsudgave.

## AI og projektmetode

Projektet arbejder med seks faglige perspektiver: Vidensagent, Innovationsagent, Kritisk agent, Eksekveringsagent, UX/UI-agent og Drifts-Børge. De er arbejdsroller i et AI-assisteret udviklingsforløb, ikke dokumentation for seks selvstændige systemer. Den endelige projektrapport skal vise beslutningsgrundlag, ændringer, fejlsøgning, testbeviser og menneskelig godkendelse; den skal også beskrive fejl og åbne spørgsmål.

## Åbne opgaver før endelig udgivelse

Afslut kilde- og rettighedskontrol; dokumentér præcis kilde-til-felt-sporbarhed; afklar Dragørs overudligning; gennemfør bredere uafhængig beregningsafstemning og automatiseret browserregression; dokumentér GitHub Pages-URL, versions-id, filhash og rollback-test.

