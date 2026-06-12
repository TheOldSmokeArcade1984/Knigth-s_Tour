# ♞ KNIGHT'S TOUR • NEON SPECTER SYS.

> Entra nel **Neon Specter Sys**: il classico Rompicapo del Cavallo rinasce in un'atmosfera cyberpunk! 100 caselle, 100 mosse, una sola regola: toccale tutte esattamente una sola volta. Lasciati ipnotizzare dalla pioggia digitale di scacchi, colori neon reattivi e transizioni 3D. Accetti la sfida? Il Tour perfetto ti aspetta.

## 🌌 Il Progetto
Questo progetto è una rivisitazione in chiave retro-futuristica del celebre problema matematico del percorso del cavallo. L'applicazione è costruita con un'architettura a file singolo (HTML/CSS/JS) ottimizzata per essere eseguita direttamente nel browser o ospitata tramite **GitHub Pages**.

Nessuna libreria esterna, solo codice puro per garantire la massima fluidità delle animazioni 3D e degli effetti visivi.

## ✨ Caratteristiche Principali
* **Estetica Cyberpunk Dinamica:** L'interfaccia non ha colori statici. Usa l'Angolo Aureo (137.5 gradi) per generare tinte neon sempre diverse e in perfetto contrasto ad ogni mossa giocata.
* **Matrix Chess Rain:** Lo sfondo in Canvas HTML5 genera una pioggia digitale composta da caratteri Unicode degli scacchi (`♔♕♖♗♘♙...`). Man mano che la partita avanza, la pioggia "ricorda" e assorbe i colori delle caselle già visitate.
* **Motore 3D CSS Cinematico:** Ogni spostamento del cavallo sulla scacchiera innesca un'animazione tridimensionale fluida, con calcolo automatico dell'orientamento della telecamera e proiezione di ologrammi prismatici.
* **Audio Generativo Retrò:** Gli effetti sonori stile sala giochi anni '80 sono sintetizzati in tempo reale sfruttando la *Web Audio API* del browser.
* **Salvataggio Locale:** Il gioco salva automaticamente lo stato della partita e il record di mosse nel `localStorage` del browser.
* **Multilingua Integrato:** Supporto per 7 lingue (IT, EN, JA, ZH, FR, DE, ES) con aggiornamento dell'interfaccia in tempo reale.

## 🕹️ Come Giocare
1. Seleziona la lingua e attiva l'audio se lo desideri.
2. Clicca su **START** per inizializzare il sistema.
3. Posiziona il Cavallo sulla griglia di partenza.
4. Muoviti sfruttando la classica "L" del cavallo degli scacchi. Le mosse possibili verranno evidenziate.
5. **Obiettivo:** Riempi tutte le 100 caselle della griglia senza mai ripassare su una casella già visitata.

## 🛠️ Tecnologie Utilizzate
* **HTML5:** Struttura e Canvas rendering.
* **CSS3:** Variabili dinamiche (`:root`), Grid layout, animazioni e transform 3D (`preserve-3d`).
* **Vanilla JavaScript (ES6):** Logica di gioco, manipolazione del DOM, calcoli trigonometrici per la telecamera 3D e generazione audio.

## 🚀 Installazione e Uso
Non c'è bisogno di build tools o server node. 
Ti basta clonare il repository e aprire il file `index.html` nel tuo browser web preferito, oppure navigare direttamente alla pagina del progetto se abilitato su GitHub Pages.

# Apri index.html
oppure vai direttamente al sito:
https://theoldsmokearcade1984.github.io/Knigth-s_Tour/
