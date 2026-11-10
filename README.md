# Anatomia del Compromesso Storico (1972-1978)
**Crisi cilena, Eurocomunismo e strategia politica del PCI di Enrico Berlinguer: Edizione Digitale e Rete Semantica**

Progetto universitario di Digital Humanities e Patrimonio Culturale sul Web (*Alma Mater Studiorum - Università di Bologna*).

🔗 **Sito Web (GitHub Pages):** [Applica qui il tuo link github.io]

---

## Obiettivo del Progetto
Il progetto ricostruisce l'ecosistema documentario, fotografico e audiovisivo legato alla genesi del **Compromesso Storico** (1972-1978), offrendo:
1. **Catalogo Multimediale Eterogeneo (10 Item):** 1 Trilogia testuale integrale, 3 Risorse iconografiche (fotografie storiche e 7 tavole digitalizzate dall'Archivio della Fondazione Gramsci) e 6 Fonti audiovisive (RAI / RaiPlay, AAMOD, Radio Magallanes), accessibili tramite filtri tipologici, ricerca libera e Timeline cronologica.
2. **Edizione Critica Digitale XML/TEI P5:** codifica integrale dei tre articoli pubblicati da Enrico Berlinguer su «Rinascita» dopo il golpe cileno dell'11 settembre 1973 (*I. Imperialismo e coesistenza alla luce dei fatti cileni*, 28 sett. 1973; *II. Via democratica e violenza reazionaria*, 5 ott. 1973; *III. Alleanze sociali e schieramenti politici*, 12 ott. 1973) con **313 annotazioni semantiche** su un corpus di **9.654 parole**.
3. **Rete Semantica (Linked Open Data) e Analisi Quantitativa:** riconciliazione di 22 entità storiche con gli Authority File internazionali (Wikidata, VIAF, SBN, ISNI, LCCN/LCSH, GND, Getty TGN) e visualizzazione dei dati di *distant reading* (statistiche TEI P5 e frequenze lessicali Voyant Tools).

---

## Standard Descrittivi e Tecnologie Implementate
* **Interfaccia e Architettura Web:** HTML5 semantico, CSS3 (variabili, Flexbox/Grid, selettori di attributo per tag TEI), JavaScript ES6 Vanilla (architettura *Single-Page Application* a 4 viste).
* **Metadati Descrittivi Trasversali:** Dublin Core (`DCMES 1.1` e `DCTERMS` ISO 15836).
* **Fonti Testuali:** `XML / TEI P5` (moduli *core*, *tei*, *header*, *textstructure*, *namesdates*).
* **Fonti Iconografiche e Scansioni:** `VRA Core 4.0` e `METS/MODS`.
* **Fonti Video e Radiotelevisive:** `PBCore 2.1` / `EDM (Europeana Data Model)`.

---

## Struttura del Repository
* `index.html` — Applicazione web completa (4 viste: *Home & Progetto*, *Catalogo & Timeline*, *Pagina Item con Trilogia TEI*, *Pagina Dati LOD & Developer Tool*).
* `berlinguer-dc.xml` — File XML dei metadati descrittivi in formato Dublin Core / DCTERMS.
* `berlinguer-tei.xml` — File XML/TEI P5 contenente il `<teiHeader>` e il full-text integrale dei 3 saggi (`<group>` TEI: `SCR_0522`, `SCR_0523`, `SCR_0524`).
* `README.md` — Documentazione tecnica e metodologica del repository.

---

## Licenza
Progetto rilasciato con licenza [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).
