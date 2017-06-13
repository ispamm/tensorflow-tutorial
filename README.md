# Notebook TensorFlow & Keras (Italiano)

In questo repository cerco di raccogliere una serie completa di tutorial (in formato notebook), dedicati a chiunque voglia avvicinarsi all'utilizzo di [TensorFlow](https://www.tensorflow.org/), lo strumento di deep learning rilasciato da Google poco più di un anno fa, in Python. Il tutorial nasce dal desiderio di avvicinare qualsiasi sviluppatore al mondo di TensorFlow, indipendentemente da una conoscenza approfondita della lingua inglese.

Anche se alcuni dei concetti più importanti sono introdotti quando necessari, il tutorial presuppone una conoscenza base di algebra lineare e deep learning. Alcuni link a materiale introduttivo sono forniti sotto.

All'interno dei tutorial cercherò di coprire una vasta quantità di materiale, partendo da un'introduzione ai meccanismi base del calcolo su grafi computazionali fino ai modelli più complessi (es., seq2seq), sempre con esempi pratici. Il tutorial è interamente work-in-progress, ma spero di aggiungere almeno un notebook a settimana.

Per qualsiasi commento o richiesta, potete contattarmi in qualsiasi momento a [simone (dot) scardapane (at) uniroma1 (dot) it].

## Visualizzare i tutorial
I link forniti sotto visualizzano i notebook tramite il servizio [NbViewer](https://nbviewer.jupyter.org/) di Jupyter. In alternativa, è possibile visualizzarli con l'editor di GitHub, ma le equazioni non saranno caricate correttamente. Per eseguire i notebook localmente, è sufficiente clonare (o scaricare) questo repository.

## Elenco dei tutorial

### T0) Concetti base ([Notebook](https://nbviewer.jupyter.org/github/ispamm/tensorflow-tutorial/blob/master/0-Concetti-base.ipynb))
  + Iniziamo introducendo alcuni dei concetti di base di TensorFlow. A partire da essi, alleniamo un semplice modello di regressione    lineare.
  **Stato**: completato (in bozza).

### T1) Reti neurali feedforward in TF ([Notebook](https://nbviewer.jupyter.org/github/ispamm/tensorflow-tutorial/blob/master/1-Reti-neurali-feedforward.ipynb))
  + Vediamo come implementare una rete neurale con uno o più strati nascosti in TF e nel modulo contrib.learn.
  **Stato**: completato (in bozza).
  
### T2) Reti neurali convolutive ([Notebook](https://nbviewer.jupyter.org/github/ispamm/tensorflow-tutorial/blob/master/2-Reti-neurali-convolutive.ipynb))
  + Introduciamo le reti neurali convolutive, essenziali nell'elaborazione di immagini. Vediamo come implementarne una in TF con gli elementi del modulo layers. **Stato**: completato (in bozza).

## Materiale di base
Per la fruizione di questi tutorial, si consiglia una conoscenza di base di machine learning e, possibilmente, del deep learning. Un modo comune di approcciarsi a queste tematiche è il corso [Machine Learning](https://www.coursera.org/learn/machine-learning), tenuto da Andrew Ng su Coursera, seguito da un [corso online sul deep learning](https://www.udacity.com/course/deep-learning--ud730).

Per chi avesse già rudimenti di machine learning, è possibile leggere gratuitamente (in versione HTML) il [libro sul deep learning](http://www.deeplearningbook.org/) recentemente pubblicato da Ian Goodfellow, Yoshua Bengio, ed Aaron Courville.
