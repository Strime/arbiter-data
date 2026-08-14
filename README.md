# arbiter-data

Données publiques de l'extension **Arbiter** (badge d'origine des produits sur
les drives français). Le contenu servi est sur la branche `gh-pages`,
déployée exclusivement par la CI du projet :
https://strime.github.io/arbiter-data/

## Sources et licence des données

La base de marques (`data/brands.json`) est une œuvre dérivée de la liste
`assets/brandlist.json` du projet [DeTrumpez-vous](https://github.com/Sacha213/detrumpez-vous)
de Sacha213, distribuée sous licence
[GNU GPL v3.0](https://github.com/Sacha213/detrumpez-vous/blob/main/LICENSE).
Environ 92 % des entrées en proviennent ; elles ont été filtrées, remappées
(`parentOrigin` → `country`) et fusionnées avec d'autres sources (Wikidata
CC0, ajouts manuels) — modifications 2026.

Conformément à la GPL v3, `data/brands.json` est distribué sous licence
**GPL-3.0** (voir `LICENSE-DATA` sur le site publié). Le code de l'extension
Arbiter est un composant distinct sous licence MIT (agrégat, GPLv3 §5).
