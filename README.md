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
Ob vsakem pushu v vejo main se samodejno izvede production deploy na Vercelu in se spletna stran posodobi.
Ob pushu v ločeno vejo se ustvari preview deploy in lahko tam ločeno spreminjaš in nadgrajuješ projekt, brez da vplivaš na javno vidno verzijo. Nato lahko izvedeš pull in merge obeh vej, da se produkcijska verzija strani posodobi.

## Dodatna konfiguracija
V projektu so bile uporabljene environment variables v Vercelu.
Dodana je bila spremenljivka SITE_NAME kot primer konfiguracije po okoljih.
Pri statičnem HTML projektu brez build procesa spremenljivke niso neposredno vidne v brskalniku,
vendar predstavljajo pomemben del konfiguracije aplikacije.


## Težave
Ni bilo večjih težav pri razvoju projekta. Le kakšna napaka v ukazih commit-ov in podobno.

