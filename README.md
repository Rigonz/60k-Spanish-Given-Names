# +80k Spanish Given Names
+80k Spanish Given Names Scraped from 20 Sources

## Presentation
The csv files include over 80,000 Spanish given names (antroponyms, first names) extracted from some 20 sources.

Duplicated names have been removed, while variants are not considered duplicates (f.eg. Manuel, Manu and Manolo are included as different entries). The characters ñ and ç, as well as the catalan · have been preserved; accents have been removed. Only capitals are used.

The names included in the list are not necessarily of "Spanish origin" (Mohamed and Manuel or Yusuf and José are included): I am not making guesses on the degree of spaniardship, and if a name has been included in any of the repositories that I have used that is good enough for me.

The sources are mostly from Spain, but several large Argentinian repositories are also used.

It is not intended to be an exhaustive list of first names, but definitely it is a large enough database.

A related project with frequency and geographical distribution: https://osf.io/dk8rp/.

## Fields
The records have three fields: the first name, the gender (M: male, F: female, A: both, U: unknown) and the source, which is a list with the numeric codes presented in the Sources sections. 

It is possible to use the number of sources in which a name is present as a rough measure of frequency, but it is likely more useful as a measure of "spelling correctness". Anyhow, some of the sources (in particular INE) provide frequency data. In any case, it is worth noting that not all the sources have the same reliability or scope (and for the assignment of the gender I have only used "official" sources, because the other ones have proved to be too unreliable for a simple classification).

## Languages
These repositories include names in Spanish, Catalan, Galician and Vasque, as indicated in the Sources section.

## Files: Simple and Compound Names
Names as presented in the core source repositiories (after basic misspelling cleaning and dropping duplicates) are included in the csv file "03 Names R3.csv". This includes both simple (f.eg. "Ricardo") and compound names ("Ricardo María").

Compound names have been partially decomposed, f.eg. "Arturo David" is decomposed into "Arturo" and "David". When any of these simple names are included in the database an asterisk mark is attached to the source. I have tried to include all the simple names but the difference is barely 400 additional names, or 0.7%, and the components are often bizarre.

For the zipped file "03 Names R1 ARG3.csv" see section Auxiliary Sources.

## Core Sources
The core sources are the following:
1.  https://www.ine.es/daco/daco42/nombyapel/nombres_por_edad_media.xls (Spanish names)
2.  http://www.idescat.cat/nadons/?lang=es for the years 1997, 2005 and 2019, and http://www.idescat.cat/noms/?lang=es for 2020 (Catalan and Spanish names)
3.  http://justicia.gencat.cat/.content/tramits/noms/LlistatNoms.xml (Catalan and Spanish names)
4.  http://www.chubut.gov.ar/apps/nombres/ (Spanish names)
5.  https://www.scribd.com/doc/252875842/Listado-de-Nombres-Permitidos (Spanish names)
6.  https://www.buenosaires.gob.ar/areas/registrocivil/nombres/busqueda/imprimir.php?sexo=ambos (Spanish names)
7.  https://es.wikipedia.org/wiki/Categor%C3%ADa:Nombres_femeninos and https://es.wikipedia.org/wiki/Categor%C3%ADa:Nombres_masculinos (Spanish names)
8.  https://ca.wiktionary.org/wiki/Viccionari:Llista_de_noms_propis_en_catal%C3%A0 (Catalan names)
9.  https://gl.wikipedia.org/wiki/Lista_de_nomes_femininos_en_galego and https://gl.wikipedia.org/wiki/Lista_de_nomes_masculinos_en_galego (Galician names)
10.  https://es.wikipedia.org/wiki/Antroponimia_vasca (Vasque names)
11.  https://en.wiktionary.org/wiki/Appendix:Spanish_given_names (Spanish names)
12.  https://en.wiktionary.org/wiki/Category:Spanish_male_given_names and https://en.wiktionary.org/wiki/Category:Spanish_female_given_names (Spanish names)
13.  https://www.abc.es/sociedad/abci-nombres-mas-raros-espana-entre-extincion-y-particular-201906191111_noticia.html (Spanish names)
14.  https://www.eldiario.es/nidos/nombres_1_2922962.html (Spanish names)
15.  https://www.euroresidentes.com/significado-nombre/nombres-catalanes.htm (Catalan and Spanish names)
16.  https://data.world/axtscz/spanish-first-name (Spanish names)
17.  http://www.20000-names.com/male_spanish_names.htm and http://www.20000-names.com/female_spanish_names.htm (Spanish names)
18.  http://reicaz.org/miscelan/santoral/santoral.htm (Spanish names)
19.  https://www.euskaltzaindia.eus/index.php?option=com_ecoeoda&task=izenaPortada&Itemid=792&lang=es (Vasque names)

## Auxiliary Sources
20. https://datos.gob.ar/dataset/otros-nombres-personas-fisicas/archivo/otros_2.1 includes over 9 million first names from Argentina. I have tried to use it but the data is often corrupted and most names are multiply composed (f.eg. "Silvana Tomasa Filomena" or "Claudio Ruben Gervasio"). A drastic cleaning still includes almost 3 million different names, which are presented as file "03 Names R1 ARG3.csv" in zip format. Splitting them into single names and adding them to the main repository is a possibility, but careful and extensive error checking and control of variants would be necessary.

## Encoding
Data is UTF-8.
