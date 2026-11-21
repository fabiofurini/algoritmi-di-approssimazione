---
title: Notebook
---

# I notebook del corso

Il codice degli algoritmi dei capitoli sullo zaino e sul bin packing sta nei **notebook Colab**, uno per capitolo e per linguaggio: **Python** e **C++**. Nelle pagine del sito gli algoritmi sono scritti in pseudocodice; nei notebook gli stessi algoritmi sono implementati (con gli indici da 0) ed eseguiti su tutti gli esempi del capitolo e su tutte le istanze degli esercizi, con il controllo dei valori attesi, e una cella «Try it yourself» per provarli con dati tuoi.

**I notebook sono per ora in inglese**: commenti, testi e output sono quelli dei notebook del sito inglese; il codice e i risultati sono gli stessi delle pagine italiane.

- **Cos'è Colab.** [Google Colab](https://colab.research.google.com/) esegue i notebook nel browser, su un computer di Google: serve solo un account Google, sul tuo computer non si installa niente.
- **Come si apre.** Clicca su un badge della tabella, oppure sui pulsanti «Esegui in Colab» sotto lo pseudocodice nelle pagine dei capitoli. Per conservare le tue modifiche: *File → Salva una copia in Drive*.
- **Come si esegue.** *Runtime → Esegui tutte* (Ctrl+F9) esegue tutte le celle dall'alto in basso; una cella sola si esegue con Maiusc+Invio.
- **C++.** Ogni file viene scritto da una cella (`%%writefile`); la cella dopo `Main.cpp` compila tutto con `g++` ed esegue gli esempi: tutto avviene in Colab.
- **Un notebook per linguaggio.** I due notebook di un capitolo contengono gli stessi algoritmi e stampano gli stessi risultati.

Il link **.ipynb** apre il notebook su GitHub, da dove si scarica (*Download raw file*) per usarlo con Jupyter sul proprio computer.

<div class="tabella-notebook" markdown>

| Capitolo | Python | C++ |
|---|:---:|:---:|
| [2. Algoritmi di approssimazione per lo zaino](knapsack-approximation.md) | [![Apri in Colab (Python)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiofurini/approximation-algorithms/blob/main/notebooks/knapsack-approximation_python.ipynb) [.ipynb](https://github.com/fabiofurini/approximation-algorithms/blob/main/notebooks/knapsack-approximation_python.ipynb) | [![Apri in Colab (C++)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiofurini/approximation-algorithms/blob/main/notebooks/knapsack-approximation_cpp.ipynb) [.ipynb](https://github.com/fabiofurini/approximation-algorithms/blob/main/notebooks/knapsack-approximation_cpp.ipynb) |
| [3. Algoritmi di approssimazione per il bin packing](bin-packing-approximation.md) | [![Apri in Colab (Python)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiofurini/approximation-algorithms/blob/main/notebooks/bin-packing-approximation_python.ipynb) [.ipynb](https://github.com/fabiofurini/approximation-algorithms/blob/main/notebooks/bin-packing-approximation_python.ipynb) | [![Apri in Colab (C++)](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiofurini/approximation-algorithms/blob/main/notebooks/bin-packing-approximation_cpp.ipynb) [.ipynb](https://github.com/fabiofurini/approximation-algorithms/blob/main/notebooks/bin-packing-approximation_cpp.ipynb) |

</div>
