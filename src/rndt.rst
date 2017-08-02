1. Repertorio Nazionale dei Dati Territoriali
=============================================

Base dati di interesse nazionale ai sensi dell'articolo 60 comma 3 del CAD.  E' possibile scaricare i metadati conformi al profilo DCAT-AP_IT per questa basi di dati in :download:`RDF/Turtle <Metadati/metadatiDCATAPIT_RNDT.ttl>`, :download:`RDF/XML <Metadati/metadatiDCATAPIT_RNDT.rdf>` e :download:`JSON-LD <Metadati/metadatiDCATAPIT_RNDT.jsonld>` (nella descrizione, la base di dati è intesa come dataset di tutti i dataset del catalogo).

Denominazione ufficiale (titolo)
--------------------------------
Base dati del Repertorio Nazionale dei Dati Territoriali

Acronimo
--------
RNDT

Descrizione
-----------
La principale finalità del Repertorio  è quella di **agevolare la pubblicità dei dati geospaziali di interesse generale, disponibili presso le pubbliche amministrazioni a livello nazionale, regionale e locale**.
Esso si configura come un catalogo di metadati che supporta due macro-processi fondamentali:

 1. la raccolta dei metadati, predisposti delle amministrazioni pubbliche abilitate, relativi ai dati territoriali di interesse generale di cui all’articolo 59, comma 3, del CAD, e ai servizi a essi relativi;
 2. la ricerca e la consultazione dei suddetti metadati, accessibili a tutti (amministrazioni, cittadini, professionisti, associazioni ed imprese).

Il RNDT è altresì coerente con i Regolamenti INSPIRE relativi ai metadati e ai servizi di rete. Il rispetto delle regole tecniche del RNDT, in aderenza agli standard ISO di riferimento, assicura la contestuale conformità, senza ulteriori adempimenti, al Regolamento (CE) n. 1205/2008.
I metadati sono prodotti dalle singole Amministrazioni responsabili dei dati e servizi, che possono effettuare le operazioni di inserimento, aggiornamento e cancellazione dei metadati stessi.

L’alimentazione del Repertorio può avvenire tramite diverse modalità:

 + editor disponibile nel portale del RNDT;
 + upload di file XML conformi ai relativi schemi XSD;
 + harvesting di cataloghi conformi alle specifiche sui servizi CSW definite dall’Open Geospatial Consortium (OGC) e alla guida tecnica per l’implementazione dei servizi di ricerca definita nell’ambito di INSPIRE.

AgID, attraverso un pannello di controllo, provvede alla convalida dei metadati ricevuti per la loro pubblicazione finale nel Repertorio Nazionale. I controlli di AgID riguardano una verifica di completezza e di coerenza dei file inviati dalle amministrazioni, che restano le uniche responsabili del contenuto pubblicato. Una volta pubblicati nel Repertorio Nazionale i metadati sono disponibili per la consultazione.
Il portale può essere consultato tramite interfaccia web in modalità accessibile con semplici maschere alfanumeriche oppure in modalità estesa, con l’utilizzo anche di un navigatore geografico.

Il Repertorio, inoltre, può essere anche consultato come servizio di ricerca (discovery service) attraverso client esterni con le operazioni standard (GetCapabilities, GetRecords, GetRecordsById) previste nello Standard CSW (Catalogue Service for the Web) definito da OGC.
L’esito della ricerca sarà la visualizzazione dei metadati oggetto delle ricerca medesima nonché, ove disponibile, la possibilità di attivare un collegamento diretto ai dati e/o servizi cui tali metadati si riferiscono, presso l’Amministrazione titolare degli stessi.

L'Agenzia per l'Italia Digitale è direttamente investita nella gestione organizzativa e tecnologica del RNDT, in coerenza con le disposizioni che disciplinano il Sistema pubblico di connettività e cooperazione.
AgID, quindi, ha realizzato il portale RNDT - interamente con tecnologia open source - attraverso il quale sono fornite le due funzionalità tipiche di un servizio di catalogo:

 + la consultazione dei metadati, accessibile a tutti;
 + la gestione dei metadati, riservata alle Pubbliche Amministrazioni accreditate.

L’applicazione è strutturata in moduli logico-contettuali realizzati su una architettura multi-livello che prevede due stack tecnologici diversi ma interconnessi tra loro mediante il client che ne utilizza di volta in volta le varie funzionalità. Il componente client è costituito da due moduli interoperabili: uno geografico che si occupa di gestire l’accesso alla componente GIS del Repertorio ed uno alfanumerico che accede ai metadati alfanumerici veri e propri.
I suddetti moduli sono utilizzati sia per le funzionalità e i servizi disponibili da interfaccia web che per il servizio CSW.

.. note::
  È in corso la reingegnerizzazione del portale e dell’applicazione RNDT inserita nella gara per l’affidamento della progettazione, realizzazione, fornitura, manutenzione e gestione delle infrastrutture.

Amministrazione titolare
------------------------
Agenzia per l'Italia Digitale (AgID)

Punto di contatto
-----------------
Agenzia per l'Italia Digitale -  Area Architetture, Standard e Infrastrutture - Servizio Banche Dati e Open Data – info@rndt.gov.it

Frequenza di aggiornamento
--------------------------
In continuo aggiornamento. Secondo le specifiche DCAT-AP_IT: http://publications.europa.eu/resource/authority/frequency/UPDATE_CONT

Norme di riferimento
--------------------
 1. **Decreto legislativo 7 marzo 2005, n. 82 e s.m.i.**, recante “Codice dell’amministrazione digitale” (artt. 59 e 60);
 2. **Decreto 10 novembre 2011 del Ministro per la pubblica amministrazione e l’innovazione** di concerto con il Ministro dell’ambiente e della tutela del territorio e del mare, recante “Regole tecniche per la definizione del contenuto del Repertorio nazionale dei dati territoriali, nonché delle modalità di prima costituzione e di aggiornamento dello stesso”;
 3. **Decreto legislativo 27 gennaio 2010, n. 32**, recante “Attuazione della direttiva 2007/2/CE, che istituisce un’infrastruttura per l’informazione territoriale nella Comunità Europea (INSPIRE)” (artt. 4, 5, 7, 8 e 9);
 4. **Decreto legislativo 24 gennaio 2006, n. 36, come modificato dal D. Lgs. 102/2015** recante “Attuazione della direttiva 2013/37/UE che modifi ca la direttiva 2003/98/CE, relativa al riutilizzo dell’informazione del settore pubblico”;
 5. **Decreto legge 18 ottobre 2012, n. 179 convertito con la legge 17 dicembre 2012, n. 221** recante “Ulteriori misure urgenti per la crescita del Paese” (art. 20);
 6. **Regolamento (CE) n. 1205/2008 della Commissione del 3 dicembre 2008** recante attuazione della direttiva 2007/2/CE del Parlamento europeo e del Consiglio per quanto riguarda i metadati;
 7. **Regolamento (CE) n. 976/2009 della Commissione del 19 ottobre 2009 e s.m.i.** recante attuazione della direttiva 2007/2/CE del Parlamento europeo e del Consiglio per quanto riguarda i servizi di rete;
 8. **Regolamento (UE) n. 1089/2010 della Commissione del 23 novembre 2010 e s.m.i.** recante attuazione della direttiva 2007/2/CE del Parlamento europeo e del Consiglio per quanto riguarda l'interoperabilità dei set di dati territoriali e dei servizi di dati territoriali.

Conformità a standard
---------------------
 + ISO 19115:2003
 + ISO 19119:2005
 + ISO TS 19139:2007
 + INSPIRE Metadata Implementing Rules: Technical Guidelines based on EN ISO 19115 and EN ISO 19119
 + INSPIRE Technical Guidance for the implementation of INSPIRE Discovery Services
 + OGC Catalogue Services Specification 2.0.2 - ISO Metadata Application Profile

Home page o pagina web di riferimento
-------------------------------------
http://www.rndt.gov.it

Data di ultimo aggiornamento
----------------------------
07/06/2017

Benefici
--------
 1. Certificazione dell’esistenza dei dati territoriali, e relativi servizi, che vengono documentati nel Repertorio;
 2. Pubblicità dei dati territoriali di interesse generale disponibili presso le Pubbliche Amministrazioni;
 3. Maggiore accessibilità e disponibilità generalizzata del patrimonio informativo relativo ai dati e servizi territoriali prodotti e/o gestiti dalle Pubbliche Amministrazioni;
 4. Facilitazione nella ricerca dei dati territoriali esistenti e supporto nelle decisioni riguardanti l’utilizzo di tali dati. Come indicato al punto (15) del preambolo della Direttiva 2007/2/CE (INSPIRE), il tempo e le risorse necessarie per la ricerca dei dati rappresentano un ostacolo decisivo allo sfruttamento ottimale dei dati disponibili;
 5. Facilitazione nella realizzazione di servizi che richiedono l’integrazione di dati di competenza di più amministrazioni e agevolazione della cooperazione nel programmare l’acquisizione di nuovi dati, razionalizzandone i costi;
 6. Valorizzazione e incentivazione del riuso dei dati pubblici in quanto il RNDT rende ufficialmente noto, a livello nazionale, quali dati territoriali sono disponibili, presso quale amministrazione, quali caratteristiche tecniche presentano e quali modalità di accesso sono possibili, compresi eventuali vincoli, restrizioni e costi;
 7. Attivazione di processi di pianificazione e di coordinamento tra le amministrazioni in relazione alla possibilità di verificare attraverso il RNDT l’eventuale esistenza di esigenze comuni e la conseguente opportunità di attivare specifici accordi di collaborazione tra amministrazioni interessate alla stessa tipologia di dati, con conseguente riduzione dei costi complessivi e ottimizzazione delle risorse.

Modalità di fruizione
---------------------
Il RNDT è fruibile attraverso il portale web disponibile all’indirizzo http://www.rndt.gov.it (nei prossimi mesi sarà anche attivato il dominio geodati.gov.it).
La ricerca e la consultazione delle informazioni (metadati) riguardanti i dati territoriali e i relativi servizi, aperte a tutti, possono essere effettuate o tramite le apposite funzionalità rese disponibili da interfaccia web o tramite client esterni per il servizio CSW.
La gestione dei metadati può essere effettuata solo dalle pubbliche amministrazioni accreditate attraverso un’area riservata del portale.

Canali per il supporto ad amministrazioni e altri utenti
--------------------------------------------------------
Il supporto alle amministrazioni e agli utenti è garantito attraverso vari strumenti:

 + indirizzo mail dedicato (info@rndt.gov.it);
 + form per segnalazioni e richieste disponibile sul portale;
 + contatto skype dedicato rndt.help (solo per supporto alle PA);
 + social media dedicati.

Open Data
---------
E' possibile scaricare singoli file dei metadati in XML. Inoltre con il servizio CSW http://www.rndt.gov.it/RNDT/CSW si possono ottenere tutti i record di metadati con una richiesta GetRecords secondo lo standard definito da OGC. Tutti i contenuti dell'RNDT sono licenziati secondo i termini della licenza `Creative Commons Attribution 3.0 IT <http://creativecommons.org/licenses/by/3.0>`__.

Tema di riferimento per i dati
------------------------------
Per la natura stessa del Repertorio, ovvero di catalogo di metadati di dati geospaziali, non esiste un tema specifico per i dati chiaramente identificabile ma potenzialmente tutti e 13 i `temi per i dati <https://linee-guida-cataloghi-dati-profilo-dcat-ap-it.readthedocs.io/it/latest/temi.html#>`__ possono essere riferibili ai metadati inclusi nel catalogo.
