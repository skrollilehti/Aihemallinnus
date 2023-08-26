# Aihemallinnusta LDA:lla

Toteutettu Jupyter notebook mallintaa LDA:lla (latent Dirichlet allocation) lähdetekstin piileviin aiheisiin.
Aihemallinnuksessa aiheiden määrä määritetään käyttämällä tmtoolkit-kirjaston Mimno ym. (2011) metriikkaa.

## Tarvittava Python-versio

Jupyter notebook tarvitsee toimiakseen Python-version 3.8-3.10. Jos tarvittava Python-versio löytyy järjestelmästä,
niin esimerkiksi Visual Studio Codessa valitaan ao. Python-versio ja tarvittaessa annettaan VSCoden asentaa kaikki tarpeellinen notebookin tarkastelemista varten.

Jos järjestelmään on asennettuna Miniconda tai Anaconda Python-versiolla 3.8-3.10,
voidaan notebookia tarkastella myös esimerkiksi kirjoittamalla komentotulkkiin "jupyter lab", minkä jälkeen tiedostovalikosta valitaan avattava notebook.

## Olennaisimmat tarvittavat kirjastot

Notebookin sisään on kirjoitettu tiedot olennaisimpien kirjastojen asennuksesta. Ohessa mainittakoon kuitenkin seuraavat kirjastot asennusohjeineen:

- pip install -U "tmtoolkit[recommended,lda]"

Huomaa, että edellinen ei asenna lda-kirjastoa, vaan se on asennettava erikseen:

- pip install -U lda

Yleensä ottaenhan Pythonin kirjastot asennetaan tyypillisesti pip-komennolla. Komennon yhteydessä -U päivittää tarvittaessa järjestelmään kyseisen kirjaston sen tuoreimpaan versioon.
