# Dinero Frontend Test

### Opgavebeskrivelse
Du skal bygge en ny angular-applikation. Applikationen skal gøre brug af det åbne [Starwars API (Swapi)](https://swapi.dev/).

Din applikation kommer til at bestå af to sider. Den første side skal bestå af en liste over planeterne, man kan hente fra Swapi. Bare den første side – du behøver ikke lave pagination. På denne side skal man kunne trykke på en planet i listen og komme til en underside, der viser detaljer om planeten, man har trykket på.

Listesiden skal du selv “designe”, mens undersiden med detaljerne om planeten har et vedhæftet design, du skal følge. Designet er relativt simpelt, så der er plads til personlige touches. Du finder designet under `design` mappen - ligeledes findes de forskellige billeder og ikoner i `assets` mappen.

Dét, du skal fokusere på, er ikke bare at skrive en kode, som får det til at virke, men derimod at skrive en kode, som du mener er den bedste/flotteste løsning, og som du har lyst til at vise frem.

### Opgave 1
- **1:** Lav en side som tilgås via `/planets`
- **2:** Hent planeterne fra `https://swapi.co/api/planets`
- **3:** Vis resultatet fra swapi på din nye side. Det kan laves som en simpel liste, cards, eller hvad end du synes.
- **4:** Hvert item skal linke til sin underside `/planets/{planetId}`

### Opgave 2
- **1:** Lav en side som tilgås via `/planets/{planetId}`
- **2:** Hent planetens data fra `https://swapi.co/api/planets/{planetId}`
- **3:** Implementer det vedhæftede design og vis dataerne fra API’et
