# Medou Netjer, version web

Apprendre l’égyptien du Moyen Empire : https://abdoujaouhar.github.io/medou-netjer/

Ce dépôt ne contient que l’application compilée. Les textes des licences des polices sont dans `licences/`.

## Sources et licences

- Signes : police **Noto Sans Egyptian Hieroglyphs** (SIL Open Font License 1.1, texte dans `tools/data/OFL.txt`), copiée dans `tools/data/`. Les tracés de `src/data/glyphs.json` en sont dérivés et restent sous la même licence.
- Codes Gardiner, valeurs et descriptions : base **Unikemet** de l'Unicode Character Database, version 18 (`tools/data/Unikemet.txt`, conditions d'utilisation Unicode).
- Hiératique : jeux de données de la **Hieratische Paläographie DB** (Université de Tsukuba, Université de Tokyo), licence CC BY 4.0, https://moeller.jinsha.tsukuba.ac.jp/en/datasets/ ; images IIIF de l'Asian Research Library, Université de Tokyo ; d'après G. Möller, *Hieratische Paläographie* I, Leipzig 1909 (domaine public). La source de chaque forme est indiquée sur la fiche du signe.
- Cours : phrases du **Thesaurus Linguae Aegyptiae**, Original Earlier Egyptian sentences, corpus v18, premium, v1.0 (22.12.2023), éd. T. S. Richter et D. A. Werning (Académie des sciences de Berlin-Brandenburg) et H.-W. Fischer-Elfert et P. Dils (Académie saxonne des sciences de Leipzig), licence **CC BY-SA 4.0** ; gloses anglaises et graphies des lemmes du TLA dans Wikidata (CC0). Les fichiers dérivés `src/data/lexique.json` et `src/data/phrases.json` (dont les traductions françaises) sont donc diffusés sous **CC BY-SA 4.0**.
- Polices d'interface : Cormorant Garamond, Gentium Book Plus, IBM Plex Mono (OFL, via `@expo-google-fonts`).
