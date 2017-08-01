# Schede informative Basi di dati di interesse nazionale

Questo progetto rappresenta l'elenco delle basi di dati di interesse nazionale e di quelle equiparabili a quelle di interesse nazionale così come identificate dal [piano triennale per l'informatica nella PA (2017-2019)](https://pianotriennale-ict.italia.it/). Ciascuna base di dati è descritta da una scheda che riporta una serie di metadati definiti secondo le specifiche del profilo di metadatazione nazionale [DCAT-AP_IT](https://linee-guida-cataloghi-dati-profilo-dcat-ap-it.readthedocs.io/it/latest/dcat-ap_it.html) .

### Requisiti

- [Sphinx](http://www.sphinx-doc.org/en/stable/)

### Build
Dopo aver apportato le dovute modifiche in [`src/`](./src) esegui

```
sphinx-build -b html src docs
```

oppure

```
make html
```

### Schede descrittive navigabili online

L'elenco e le relative schede descrittive sono [navigabili online](http://pianotri-schede-bdin.readthedocs.io/en/latest/index.html)
