# Matúš Bača - náhľad webu

Toto je plochá statická verzia webu pripravená na rýchly náhľad cez GitHub Pages.

## Ako to nahrať na GitHub

1. Otvor repository `matusbaca-preview`.
2. Klikni `Add file` -> `Upload files`.
3. Nahraj celý obsah priečinka `matusbaca-github-flat-upload` priamo do koreňa repository.
4. Commitni upload.
5. V repository otvor `Settings`.
6. Vľavo klikni `Pages`.
7. V časti `Build and deployment` nastav:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
8. Klikni `Save`.
9. Po chvíli GitHub vytvorí link:
   `https://storagestoragesk-lang.github.io/matusbaca-preview/`

## Dôležité

Toto nie je skutočné zabezpečenie heslom. Ak je repository verejné, stránku môže vidieť každý, kto má link. Súbor `robots.txt` iba hovorí vyhľadávačom, aby stránku neindexovali, ale nezabraňuje prístupu.

Po schválení návrhu odporúčané:

- zmazať repository,
- alebo ho prepnúť na private,
- a finálnu verziu nahrať na oficiálny hosting domény.
