# Moment_102
Repos för moment 1.2 i kursen DT191G

Innehåller en applikation gjord med Blazor webassembly.
använder en gemensam layoutfil som appliceras på tre razor sidor:
en startsida, en sida för konvertering av div. enheter och en sida som läser in data från JSON och skriver ut på skärmen.

Navigationen har gjorts till en komponent som läses in med hjälp av LayoutComponentBase. 

På konverteringssidan används C# för att konvertera meter till fot och km/h till mph. Detta görs genom att användaren väljer enhet i en select-meny och skriver in ett antal i input-fältet nedanför samt klickar på knappen. 

Jag har adderat en egen JSON-fil i "test-data"-mappen med tarantino-filmer med titel och årtal. Dessa används på "json-sidan" för att skrivas ut med hjälp av htttp-client.

http-klienten hämtar objekten ur jsonfilen och därefter används C# för att skriva ut den till skärmen. 

