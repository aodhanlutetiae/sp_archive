# sp_archive
Data from several archives containing Spanish Civil War & Franco-era material — what there is and how to gather it.

**PARES**
The *Político Social* section of the [PARES archive](http://pares.mcu.es/ParesBusquedas20/catalogo/contiene/7321975) holds 69 *ficheros* of files, each of which has around 37_000 different files. This makes around two million files. The urls for these 69 folders are in **list_of_69_folder_urls.txt**. The [first *fichero*](http://pares.mcu.es/ParesBusquedas20/catalogo/contiene/7523902) holds 37_061 files. As an example, these *fichero 1* urls are gathered in **folder_1_allurls_37061.json**.

— Each file is available not just on a web page [at its url](http://pares.mcu.es/ParesBusquedas20/catalogo/description/12223783) but also [as an XML file at a similar address](http://pares.mcu.es/ParesBusquedas20/catalogo/description/exportEAD/12223783). One notebook in the PARES folder (COLLECT_xml_files.ipynb) demonstrates how all two million XML files could be gathered. Another (PARSE_xml_files.ipynb) shows how a clean dataset can be built from a large number of these files kept locally.

— There is also [a notebook available](https://nbviewer.jupyter.org/github/aodhanlutetiae/sp_archive/blob/main/PARES/SUMMARY_explanation.ipynb) that bypasses the code to explain what data is collected and what could be used for a smaller dataset.


**DEPORTED**
[This site](https://banc.memoria.gencat.cat/ca/app/#/results/deportats?) has 9_158 pages at individual urls. These pages are all served from an API which can, if necessary, be queried directly. A notebook of how to do it is in the DEPORTED folder.


**COSTA HUMA**
[This site](https://dedalo4.bancmemorial.extranet.gencat.cat/web_mdcat_cost_huma/) holds 62_061 urls to individual pages. Once the 1000-per-page option is selected in the dropdown there are 63 pages of links. The list of these 62_061 urls is in the COST_HUMA folder as a .txt and a .pkl file. At a given url however the data is served via javascript and jquery and so can't be gathered simply via the page's html. A solution for the jsquery is needed here.
