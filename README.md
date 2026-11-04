# Pensare in Python — Think Python 3ª edizione in italiano

Traduzione italiana **non ufficiale** di [*Think Python*, 3ª edizione](https://allendowney.github.io/ThinkPython/) di **Allen B. Downey**, pubblicata come sito web da consultare per studiare.

**Leggi il libro:** https://pensare-in-python.github.io/3a-edizione/

## Cosa contiene

- La prefazione e tutti i 19 capitoli, con ogni sezione, glossario ed esercizio tradotti.
- Il codice di ogni esempio, identico all'originale, con l'output che produce (testo, diagrammi, disegni della tartaruga, messaggi di errore).
- Un indice delle sezioni per ogni capitolo, la ricerca in tutto il libro e la possibilità di segnare i capitoli come letti (salvato solo nel tuo browser).
- I **notebook Jupyter tradotti** di ogni capitolo, nella cartella [`notebooks/`](notebooks/), da aprire su Google Colab con un clic o da scaricare.

Alla prima definizione e nei glossari i termini tecnici sono accompagnati dall'originale inglese tra parentesi, perché messaggi di errore e documentazione usano quei nomi.

## Fonte e licenza

- Opera originale: *Think Python: How to Think Like a Computer Scientist*, 3ª edizione, © Allen B. Downey — <https://allendowney.github.io/ThinkPython/>, repository <https://github.com/AllenDowney/ThinkPython/tree/v3>.
- **Testo**: distribuito dall'autore con licenza [Creative Commons Attribuzione - Non commerciale - Condividi allo stesso modo 4.0 Internazionale (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.it). Questa traduzione è un'opera derivata ed è distribuita con la **stessa licenza**: puoi condividerla e modificarla citando la fonte, ma non per scopi commerciali, e i lavori derivati devono usare la stessa licenza.
- **Codice** degli esempi: [licenza MIT](https://mit-license.org/), © Allen B. Downey, lasciato invariato.

Questa traduzione non è approvata né revisionata dall'autore. Eventuali errori di traduzione sono del traduttore: segnalali aprendo una *issue* in questo repository. Per gli errori del libro originale, l'autore indica l'indirizzo `feedback@thinkpython.com` (in inglese).

Le versioni stampata ed ebook dell'originale si possono acquistare da [Bookshop.org](https://bookshop.org/a/98697/9781098155438) e altri rivenditori.

## Notebook

Ogni capitolo è anche un notebook Jupyter in italiano, con il testo tradotto e il codice originale (senza output: si generano eseguendo le celle).

| Capitolo | Apri su Colab |
| --- | --- |
| Prefazione | [chap00.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap00.ipynb) |
| 1 | [chap01.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap01.ipynb) |
| 2 | [chap02.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap02.ipynb) |
| 3 | [chap03.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap03.ipynb) |
| 4 | [chap04.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap04.ipynb) |
| 5 | [chap05.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap05.ipynb) |
| 6 | [chap06.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap06.ipynb) |
| 7 | [chap07.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap07.ipynb) |
| 8 | [chap08.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap08.ipynb) |
| 9 | [chap09.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap09.ipynb) |
| 10 | [chap10.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap10.ipynb) |
| 11 | [chap11.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap11.ipynb) |
| 12 | [chap12.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap12.ipynb) |
| 13 | [chap13.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap13.ipynb) |
| 14 | [chap14.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap14.ipynb) |
| 15 | [chap15.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap15.ipynb) |
| 16 | [chap16.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap16.ipynb) |
| 17 | [chap17.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap17.ipynb) |
| 18 | [chap18.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap18.ipynb) |
| 19 | [chap19.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/chap19.ipynb) |
| Introduzione a Jupyter | [jupyter_intro.ipynb](https://colab.research.google.com/github/pensare-in-python/3a-edizione/blob/main/notebooks/jupyter_intro.ipynb) |

All'inizio di ogni notebook c'è una cella che scarica i file di supporto del libro (`thinkpython.py`, `diagram.py`, `jupyturtle.py`, …) dal repository originale: eseguila per prima.

## Struttura del repository

- `index.html` — l'app (una sola pagina, nessuna dipendenza da installare)
- `data/` — il testo tradotto e il codice di ogni capitolo (`ch00.json` … `ch19.json`) e l'indice (`toc.json`)
- `img/` — gli output grafici generati eseguendo i notebook originali
- `notebooks/` — i notebook Jupyter tradotti (`chap00.ipynb` … `chap19.ipynb`, `jupyter_intro.ipynb`)

Per provarla in locale: `python3 -m http.server` nella cartella del repository e apri <http://localhost:8000>.
