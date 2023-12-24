# Deak-web

Szüksége van a kódbázisnak a szerveren 900 MB-nyi helyre, és a szervernek 1 GB RAM-ra.
Később az új content is helyet fog foglalni.

## Telepítés

Kell telepítve legyen a szerveren:

- NodeJS v20 (`corepack enable` a Yarn v4-hez)

Adatbázis nem kell, mert sqlite alapokon fut a Stripe. Viszont emiatt be kéne kötni egy back-up folyamatot, ha esetleg elveszne a szerver adatállománya. A back-upolandó fájl akár fel is kerülhetne a GitHubra, mert nincs benne semmi érzékeny adat.

## Futtatás

A README.md-ben leírtak szerint kell futtatni a szerveren.
