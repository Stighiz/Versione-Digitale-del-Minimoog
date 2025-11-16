Questo progetto realizza una versione digitale del celebre sintetizzatore analogico monofonico Minimoog, sfruttando la libreria Pyo di Python per l'elaborazione audio in tempo reale.

È stata sviluppata un'interfaccia grafica (GUI) dedicata con PySimpleGui, che permette all'utente di controllare ogni parametro del sintetizzatore in modo intuitivo, replicando il layout e le funzionalità dello strumento originale.

<img width="1761" height="958" alt="immagine" src="https://github.com/user-attachments/assets/ee161f09-3ee1-4ade-92e5-6d7473bcf982" />

Il cuore del sintetizzatore è composto da:
- Tre oscillatori con forme d'onda personalizzate e importabili.
- Un generatore di rumore (bianco/rosa) e un mixer per bilanciare le sorgenti sonore.
- Un filtro passa-basso risonante di 4° ordine, elemento iconico del suono Moog, dotato di un proprio inviluppo ADSR (Filter Contour).
- Un inviluppo ADSR principale (Loudness Contour) per modellare l'ampiezza del suono nel tempo.
- Una sezione di modulazione flessibile che consente di utilizzare l'oscillatore 3, il rumore o un LFO per creare suoni complessi e dinamici.
