# Interni IT oddelek

## Opis
Projekt predstavlja statično spletno stran za interni IT oddelek podjetja.
Namen projekta je prikaz osnovne priprave projekta, uporabe Git/GitHub workflowa
in deploya na platformi Vercel.

## Uporabljene tehnologije
- HTML
- CSS
- JavaScript
- Git
- GitHub
- Vercel
- Environment Variables
- Cloudflare DNS (opcijsko)

## Deploy
Production URL:
https://interni-it-oddelek.vercel.app/

## CI/CD
Projekt je povezan z GitHub repozitorijem in Vercelom.
Ob vsakem pushu v vejo main se samodejno izvede production deploy.
Ob pushu v ločeno vejo, v tem primeru update-content se ustvari preview deploy na katerem se lahko ločeno razvija projekt. Ko hočemo, da se spremembe na tej veji pojavijo na aktivni/produkcijski strani, izvedemo pull in merge obeh vej.

## Dodatna konfiguracija
V projektu so bile uporabljene environment variables v Vercelu.
Dodana je bila spremenljivka SITE_NAME kot primer konfiguracije po okoljih.
Pri statičnem HTML projektu brez build procesa spremenljivke niso neposredno vidne v brskalniku,
vendar predstavljajo pomemben del konfiguracije aplikacije.


## Težave
Ni bilo večjih težav z delom. Kakšna napaka pri push, zaradi napačnega ukaza.

