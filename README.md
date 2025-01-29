# Obrada, prikaz i analiza podataka popisa stanovništva i parlamentarnih izbora
## Ivan Parat, Ivan Ivančić, Kristijan Padovan Savić

Za potrebe projekta smo preuzeli i obradili navedene podatke:
- Popis stanovništva 2021. - https://dzs.gov.hr/u-fokusu/popis-2021/88
- Rezultati parlamentarnih izbora 2024. - https://www.izbori.hr/site/UserDocsImages/479
- Geografski podatci administrativnih jedinica Republike Hrvatske - https://geoportal.dgu.hr/services/atom/INSPIRE_Administrative_Units_(AU).zip

Postupak rada:
1. Preuzmite podatke s poveznice i izdvojite ih u mapu - https://1drv.ms/u/s!AreLEd6mQknmchkFaRGh7Pykqso?e=4DKkNn
2. Notebookovi election_data.ipynb, geodata.ipynb i population_census_data.ipynb korišteni su za transformaciju izvornih datoteka u format koji omogućuje lakše i učinkovitije rukovanje podacima. Nije ih potrebno pokretati ako ste preuzeli i izdvojili mapu s podacima prema prethodnom koraku, jer su sve potrebne datoteke već tamo. No, ako želite vidjeti kako su podaci obrađeni, možete ih pregledati i pokrenuti.
3. Pokrenite election_visualization.ipynb i census_visualization.ipynb za generiranje karata.
4. Pokrenite correlation.ipynb, clustering.ipynb, similarity_index.ipynb i prediction_model.ipynb za daljnju analizu.