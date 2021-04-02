# sp_archive
Data from several archives containing Spanish Civil War material — what there is and how to gather it.

**PARES**
The *Político Social* section of the [PARES archive](http://pares.mcu.es/ParesBusquedas20/catalogo/contiene/7321975) holds 69 *ficheros* of files, each of which has around 37_000 different files. This makes around two million files in all. The urls for the 69 folders are in **list_of_69_folder_urls.txt**. The [first *fichero*](http://pares.mcu.es/ParesBusquedas20/catalogo/contiene/7523902) holds 37_061 files. As an example, these *fichero 1* urls are gathered in **folder_1_allurls_37061.json**. Each file is available not just on a web page [at its url](http://pares.mcu.es/ParesBusquedas20/catalogo/description/12223783) but also [as an XML file at a similar address](http://pares.mcu.es/ParesBusquedas20/catalogo/description/exportEAD/12223783). A notebook in the PARES folder (COLLECT XML FILES) demonstrates how all the XML files could be gathered.


**DEPORTED**
[This site](https://banc.memoria.gencat.cat/ca/app/#/results/deportats?) has 9_158 pages at individual urls. These pages are all served from an API which can, if necessary, be queried directly. A notebook of how to do it is in the DEPORTED folder.


**COSTA HUMA**
[This site](https://dedalo4.bancmemorial.extranet.gencat.cat/web_mdcat_cost_huma/) holds 62_061 urls to individual pages. Once the 1000-per-page option is selected in the dropdown there are thus 63 pages of links. The list of these 62_061 urls is in the COST_HUMA folder as a .txt and a .pkl file.


