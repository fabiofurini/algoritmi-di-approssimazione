---
title: Algoritmi di approssimazione
hide:
  - navigation
  - toc
---

<div class="hero" markdown>

# Algoritmi di approssimazione

<!-- collana-riga -->
<p class="collana-riga" markdown>Un corso della collana <b>Ricerca Operativa e Matematica</b> · [tutti i corsi](#la-collana)</p>
<!-- /collana-riga -->

Materiale didattico ideato e sviluppato da **[Fabio Furini](https://fabiofurini.github.io/)**, professore
associato al [DIAG](https://www.diag.uniroma1.it/), Sapienza Università di Roma.

**Le dispense del corso, online**: che cosa garantisce un algoritmo di approssimazione e come lo si dimostra; algoritmi, analisi del caso peggiore e istanze tight per lo zaino, il bin packing, il TSP metrico e lo scheduling su macchine parallele; schemi di approssimazione; i limiti dell'approssimazione per la colorazione dei vertici, la clique massima e il TSP generale. Con definizioni, risultati con dimostrazione, esempi svolti, esercizi con le soluzioni, notebook Colab e app interattive.

Prerequisiti: [Ottimizzazione combinatoria](https://fabiofurini.github.io/ottimizzazione-combinatoria/) per i problemi e [Algoritmi euristici](https://fabiofurini.github.io/algoritmi-euristici/) per gli algoritmi che qui si analizzano (greedy, First Fit, LPT, nearest neighbour…).

[Comincia :material-arrow-right:](approximation.md){ .md-button .md-button--primary }
[:material-pencil: Esercizi](esercizi/index.md){ .md-button }
[:material-gesture-tap: Laboratorio](laboratorio/index.md){ .md-button }
[:material-clipboard-check-outline: Quiz](autovalutazione.md){ .md-button }
[:material-download: Materiale](materiale.md){ .md-button }

</div>

<!-- collana-app -->
## Provalo subito

L'algoritmo di Christofides su dieci città: il giro trovato sopra il giro ottimo, con il rapporto che resta sotto la garanzia 3/2. Premi «Esegui» per rivedere albero ricoprente minimo, accoppiamento, circuito euleriano e scorciatoie, oppure passa al double tree.

<div class="gi" data-grafico="oc-tsp-approx" data-vetrina="ch | 7 4 ; 14 8 ; 9 9 ; 19 0 ; 17 5 ; 17 10 ; 6 11 ; 3 4 ; 10 2 ; 20 12"></div>

[:material-gesture-tap: Altre app nel laboratorio](laboratorio/index.md){ .md-button }
<!-- /collana-app -->

## Le parti del corso

I capitoli, per famiglia di problemi come nel menu: ogni scheda dice il capitolo della dispensa.

<div class="grid cards" markdown>

-   :material-approximately-equal: **1. Principi degli algoritmi di approssimazione**

    ---

    *Principi*

    Algoritmi di approssimazione · Schemi di approssimazione

    [:octicons-arrow-right-24: Leggi il capitolo](approximation.md) · [Esercizi](esercizi/approximation.md)

-   :material-approximately-equal: **2. Algoritmi di approssimazione per lo zaino**

    ---

    *Problemi di zaino*

    Notazione · Oggetto critico e capacità residua · L'algoritmo greedy · L'algoritmo Ext-Greedy

    [:octicons-arrow-right-24: Leggi il capitolo](knapsack-approximation.md) · [Esercizi](esercizi/knapsack-approximation.md)

-   :material-approximately-equal: **3. Algoritmi di approssimazione per il bin packing**

    ---

    *Problemi di packing*

    Notazione · Next Fit · La classe Any Fit · Proprietà di riempimento a metà

    [:octicons-arrow-right-24: Leggi il capitolo](bin-packing-approximation.md) · [Esercizi](esercizi/bin-packing-approximation.md)

-   :material-approximately-equal: **4. Colorazione dei vertici: limiti dell'approssimazione**

    ---

    *Problemi di colorazione*

    Notazione · Il VCP non è approssimabile · Casi particolari · Esempi

    [:octicons-arrow-right-24: Leggi il capitolo](coloring-inapproximability.md) · [Esercizi](esercizi/coloring-inapproximability.md)

-   :material-approximately-equal: **5. Clique massima: limiti dell'approssimazione**

    ---

    *Problemi di clique*

    Notazione · Il MCP non è approssimabile · Casi particolari · Esempio

    [:octicons-arrow-right-24: Leggi il capitolo](clique-inapproximability.md) · [Esercizi](esercizi/clique-inapproximability.md)

-   :material-approximately-equal: **6. TSP: il caso generale e il caso metrico**

    ---

    *Problemi di routing*

    Il TSP generale non è approssimabile · Un caso particolare: il TSP metrico · L'algoritmo del doppio albero e l'algoritmo di Christofides · Proprietà strutturali

    [:octicons-arrow-right-24: Leggi il capitolo](tsp-approximation.md) · [Esercizi](esercizi/tsp-approximation.md)

-   :material-approximately-equal: **7. Approssimazione per P||Cmax**

    ---

    *Problemi di scheduling*

    Notazione · Gli algoritmi $LIST$ e $LPT$ · Una proprietà del list scheduling · Garanzie di prestazione

    [:octicons-arrow-right-24: Leggi il capitolo](pcmax-approximation.md) · [Esercizi](esercizi/pcmax-approximation.md)

</div>

<!-- collana-da-non-perdere -->
## Da non perdere

<div class="grid cards" markdown>

-   :material-pencil-box-multiple: **Esercizi con le soluzioni**

    ---

    Esercizi per ogni capitolo, ciascuno con la soluzione svolta che si apre con un clic.

    [:octicons-arrow-right-24: Gli esercizi](esercizi/index.md)

-   :material-clipboard-check-outline: **Quiz di autovalutazione**

    ---

    Un facsimile d'esame nuovo a ogni avvio: 13 domande, 33 punti, con la soluzione e il link alle dispense. In Materiale c'è anche la banca completa delle domande.

    [:octicons-arrow-right-24: Mettiti alla prova](autovalutazione.md)

-   :material-gesture-tap: **Laboratorio interattivo**

    ---

    App che girano nel browser: muovi i parametri e guarda le idee del corso lavorare, un passo alla volta.

    [:octicons-arrow-right-24: Il laboratorio](laboratorio/index.md)

-   :material-download: **Dispense in PDF**

    ---

    Dispense, eserciziari e slide in PDF, con la stessa numerazione del sito.

    [:octicons-arrow-right-24: Il materiale](materiale.md)

-   :material-language-python: **Notebook in Colab**

    ---

    Il codice del corso che gira nel browser, senza installare niente.

    [:octicons-arrow-right-24: I notebook](notebook.md)

-   :material-format-list-numbered: **Indice completo**

    ---

    Tutti i capitoli con le loro sezioni in una pagina, e come è fatto ogni capitolo.

    [:octicons-arrow-right-24: L'indice](indice.md)

</div>
<!-- /collana-da-non-perdere -->

---

<!-- collana -->
## La collana

Tutti i corsi della collana hanno la stessa impostazione: dispense online e in PDF, esercizi con le soluzioni, laboratorio interattivo e quiz di autovalutazione.

<div class="grid cards" markdown>

-   :material-function-variant: **[Analisi Matematica 1](https://fabiofurini.github.io/analisi-matematica-1/)**

    numeri reali, funzioni, limiti, derivate e serie, con i grafici interattivi

-   :material-matrix: **[Algebra lineare](https://fabiofurini.github.io/algebra-lineare/)**

    vettori, matrici, determinanti, sistemi lineari e autovalori, con il laboratorio di calcolo

-   :material-code-braces: **[Algoritmi](https://fabiofurini.github.io/algoritmi/)**

    rappresentazione dei numeri, pseudocodice, ordinamento e ricerca, analisi e algoritmi ricorsivi

-   :material-vector-triangle: **[Programmazione lineare](https://fabiofurini.github.io/programmazione-lineare/)**

    poliedri, algoritmo del simplesso, dualità e simplesso duale, con il laboratorio interattivo

-   :material-dots-grid: **[Programmazione lineare intera](https://fabiofurini.github.io/programmazione-lineare-intera/)**

    rilassamento continuo, disuguaglianze valide, piani di taglio, branch-and-bound e branch-and-cut

-   :material-vector-curve: **[Ottimizzazione convessa](https://fabiofurini.github.io/ottimizzazione-convessa/)**

    insiemi e funzioni convesse, problemi di ottimizzazione convessa, con grafici interattivi

-   :material-graph-outline: **[Ottimizzazione su reti](https://fabiofurini.github.io/ottimizzazione-su-reti/)**

    grafi, alberi ricoprenti, cammini minimi, flussi su reti, simplesso su reti e gestione dei progetti

-   :material-hexagon-multiple-outline: **[Problemi di ottimizzazione combinatoria](https://fabiofurini.github.io/ottimizzazione-combinatoria/)**

    zaino, bin packing, colorazione, TSP, scheduling e lot sizing: i problemi, le formulazioni e gli algoritmi ad hoc

-   :material-table-large: **[Programmazione dinamica](https://fabiofurini.github.io/programmazione-dinamica/)**

    principi e algoritmi di PD per zaino, lot sizing, cambio monete e taglio delle aste

-   :material-map-marker-path: **[Algoritmi euristici](https://fabiofurini.github.io/algoritmi-euristici/)**

    euristiche costruttive, ricerca locale, metaeuristiche ed euristiche MIP per i problemi di ottimizzazione combinatoria

-   :material-approximately-equal: **Algoritmi di approssimazione** · *questo corso*

    garanzie di prestazione, schemi di approssimazione e limiti dell'approssimazione per i problemi combinatori

-   :material-vector-polygon: **[Modellazione MIP](https://fabiofurini.github.io/modellazione-mip/)**

    modelli di programmazione lineare a variabili intere, dalla formulazione alla soluzione con i solver

-   :material-chart-timeline-variant: **[Laboratorio di Ricerca Operativa](https://fabiofurini.github.io/laboratorio-ricerca-operativa/)**

    modellazione e risoluzione di problemi di ottimizzazione con Python e i solver

</div>
<!-- /collana -->

---

Materiale didattico di **[Fabio Furini](https://fabiofurini.github.io/)** —
[DIAG](https://www.diag.uniroma1.it/), Sapienza Università di Roma.

*Questo sito è disponibile anche in [inglese](https://fabiofurini.github.io/approximation-algorithms/).*
