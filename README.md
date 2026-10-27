# halkvakt-sidor

Halkvaktens stomdokument och projektkarta som webbsidor: https://895845.github.io/halkvakt-sidor/

Sidorna byggs en gång per dygn, 05.30 UTC, ur main i [Axelstar/Halkvakt](https://github.com/Axelstar/Halkvakt) med
`scripts/sidorna.ts --bygg` och publiceras med GitHub Pages. Källan är Halkvakt-repot, så ändra aldrig sidorna här.
Run workflow under Actions bygger om direkt.

`byggd.txt` är commiten i Halkvakt som sidorna senast byggdes ur. Den håller också schemat vid liv, eftersom GitHub
stänger av scheman i ett publikt repo efter 60 dagar utan aktivitet. Genomsökningen, som kontrollerar att sidorna är
lika main, körs i Halkvakt-repot. Beslutet är DECISIONS #733 där.
