Excel Modul 2 – Uppslag med XLOOKUP
Andra caset i min Excel-träning. Det här handlar helt om XLOOKUP.
Utgångsläget är en orderlista för ett påhittat tillverkningsbolag, Nordvik Industri. Den har 350 rader, men bara produktkoder, kundkoder och antal – inga namn, inga priser, ingen intäkt. Uppgiften var att fylla i resten med uppslagsfunktioner.

Vad jag gjorde

Hämtade produktnamn, styckpriser och självkostnader ur ett produktregister
Hämtade kundnamn ur ett kundregister, och hanterade saknade kundkoder så att de visar "Okänd kund" istället för ett felmeddelande
Räknade ut intäkt per orderrad
Lade till mängdrabatt med en XLOOKUP med approximativ matchning (rabatten beror på antal och matchas mot en rabattrappa)
Byggde en enkel dashboard med total intäkt, täckningsbidrag och uppdelning per månad och produktkategori

Vad jag tog med mig
Hur argumenten i XLOOKUP faktiskt fungerar, skillnaden mellan exakt och approximativ matchning, och varför strukturerade tabellreferenser som tblOrder[...] gör formler mycket lättare att läsa än A2, B2, C2.
Fil
Övningscase_2_Excel.xlsx – öppna fliken Order för att se formlerna, eller fliken Dashboard för sammanställningen.
Byggd i Excel 365.ShareProject contentExcel mästareCreated by youAdd PDFs, documents, or other text to reference in this project.Contentm1_case.xlsxxlsxÖvningscase 1 Excel.xlsxxlsxindex (6).htmlhtmlÖvningscase 2 Excel.xlsxxlsxJunior Business Controller till tillverkande bolag i Jönköping.md68 linesmd# Excel-learning-modul-2
