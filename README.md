# Engine Simulator Suite: download

Banco prova motore virtuale: simulazione fisica in tempo reale, pannelli live su più schermi, automazione delle prove.

Questo repository contiene solo gli installer. L'applicazione installata controlla qui le nuove versioni e si aggiorna da sola.

## Scarica l'ultima versione

**[Vai all'ultima release](https://github.com/Mattemn97/engine-simulator-suite-releases/releases/latest)** e scegli il file per il tuo sistema:

| Sistema | File | Installazione |
|---|---|---|
| Windows 10/11 (64 bit) | `engine-simulator-suite-<versione>-win-x64.exe` | Avvia l'installer. Se Windows SmartScreen avvisa, scegli **Ulteriori informazioni > Esegui comunque** (l'installer non è ancora firmato). |
| macOS (Apple Silicon) | `engine-simulator-suite-<versione>-mac-arm64.dmg` | Apri il dmg e trascina l'app in Applicazioni. Al primo avvio: clic destro sull'app > **Apri** (l'app non è firmata). |
| macOS (Intel) | `engine-simulator-suite-<versione>-mac-x64.dmg` | Come sopra. |
| Linux (64 bit) | `engine-simulator-suite-<versione>-linux-x86_64.AppImage` | `chmod +x` sul file, poi avvialo. |

I file `latest*.yml` e `.blockmap` servono all'aggiornamento automatico: non vanno scaricati.

## Aggiornamenti

L'applicazione controlla gli aggiornamenti all'avvio e ogni 4 ore, li scarica in background e chiede di riavviare. Non serve alcun account né token.

Le versioni fino alla 0.10 cercavano gli aggiornamenti in un altro repository: se ne hai una, aggiornala alla 0.11 o successiva scaricando l'installer da qui.

## Novità

Le note di ogni versione sono nella pagina della sua [release](https://github.com/Mattemn97/engine-simulator-suite-releases/releases).
