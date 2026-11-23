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

Il corso presenta gli algoritmi di approssimazione: che cosa garantiscono e come lo si dimostra;
algoritmi, analisi del caso peggiore e istanze tight per lo zaino, il bin packing, il TSP metrico e lo
scheduling su macchine parallele; gli schemi di approssimazione; i limiti dell'approssimazione per la
colorazione dei vertici, la clique massima e il TSP generale.

Prerequisiti: [Problemi di ottimizzazione combinatoria](https://fabiofurini.github.io/ottimizzazione-combinatoria/) per i problemi e [Algoritmi euristici](https://fabiofurini.github.io/algoritmi-euristici/) per gli algoritmi che qui si analizzano (greedy, First Fit, LPT, nearest neighbour…).

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

Le stesse voci del menu: ogni scheda dice a quale parte e a quali capitoli della dispensa corrisponde.

<div class="grid cards" markdown>

-   :material-lightbulb-on-outline: **Principi**

    ---

    *Parte 1 · Capitolo 1*

    Principi

    [:octicons-arrow-right-24: I capitoli](principi.md)

-   :material-package-variant-closed: **Problemi di packing**

    ---

    *Parte 2 · Capitoli 2–3*

    Zaino 0/1 (KP) · Bin packing (BPP)

    [:octicons-arrow-right-24: I capitoli](problemi-di-packing.md)

-   :material-close-octagon-outline: **Limiti dell'approssimazione**

    ---

    *Parte 3 · Capitoli 4–5*

    Colorazione dei vertici (VCP) · Clique massima (MCP)

    [:octicons-arrow-right-24: I capitoli](limiti-dell-approssimazione.md)

-   :material-map-marker-path: **Routing e scheduling**

    ---

    *Parte 4 · Capitoli 6–7*

    Commesso viaggiatore (TSP) · Macchine parallele identiche (P||Cmax)

    [:octicons-arrow-right-24: I capitoli](routing-e-scheduling.md)

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

-   :material-chart-line: **[Modellazione PL](https://fabiofurini.github.io/modellazione-pl/)**

    modelli di programmazione lineare per problemi gestionali, risolti con Python e Gurobi

-   :material-chart-bell-curve-cumulative: **[Modellazione PNL](https://fabiofurini.github.io/modellazione-pnl/)**

    modelli di programmazione non lineare, dal portafoglio al machine learning, con Python e Gurobi

-   :material-vector-polygon: **[Modellazione MIP](https://fabiofurini.github.io/modellazione-mip/)**

    modelli di programmazione lineare a variabili intere, dalla formulazione alla soluzione con i solver

</div>
<!-- /collana -->

---

Materiale didattico di **[Fabio Furini](https://fabiofurini.github.io/)** —
[DIAG](https://www.diag.uniroma1.it/), Sapienza Università di Roma.

*Questo sito è disponibile anche in [inglese](https://fabiofurini.github.io/approximation-algorithms/).*
