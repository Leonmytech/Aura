[README.md](https://github.com/user-attachments/files/33721955/README.md)
[README.md](https://github.com/user-attachments/files/33721953/README.md)
<div align="center">

# Aura

**Music player nativo per macOS, elegante e leggero.**

![Platform](https://img.shields.io/badge/platform-macOS%2014%2B-black?logo=apple)
![Swift](https://img.shields.io/badge/SwiftUI-native-orange?logo=swift)
![Arch](https://img.shields.io/badge/arch-Apple%20Silicon%20%7C%20Intel-blue)
![Version](https://img.shields.io/badge/version-2.0.0-green)

</div>

Aura è un music player nativo per macOS scritto in SwiftUI: sfoglia la tua libreria locale per album e artisti, ascolta MP3, FLAC, AIFF, WAV e M4A, con visualizer, sfondo animato Metal che reagisce alla musica, mini player e icona nella barra dei menu. Leggero, elegante, universale (Apple Silicon + Intel).

<!-- Aggiungi qui uno screenshot:
![Aura screenshot](docs/screenshot.png)
-->

## Funzionalità

- **Libreria locale**: importa le tue cartelle e naviga per **album**, **artisti** e brani
- **Formati audio**: MP3, FLAC, AIFF, WAV, M4A/AAC
- **Visualizer** con stile e intensità personalizzabili
- **Sfondo animato Metal** che può reagire alla musica
- **Mini player** con posizione e dimensione ricordate
- **Icona nella barra dei menu** (opzionale)
- **Scelta dell'uscita audio** (dispositivo di output dedicato)
- **Temi**, animazione di avvio opzionale e onboarding al primo avvio
- **Apri con Aura**: associabile ai file audio da Finder
- Interfaccia in italiano

## Requisiti

- macOS **14 Sonoma** o successivo
- Mac Apple Silicon o Intel (binario universale)

## Installazione

1. Scarica l'ultima versione dalla pagina [**Releases**](../../releases):
   - `Aura.dmg` – immagine disco (consigliata)
   - `Aura.zip` – archivio dell'app
2. Apri il `.dmg` e trascina **Aura** nella cartella **Applicazioni**.
3. Al primo avvio segui l'onboarding e importa la tua libreria musicale.

### Primo avvio: avviso di Gatekeeper

L'app è firmata in modalità *ad-hoc* e **non è notarizzata** da Apple, quindi macOS potrebbe mostrare *"Aura non può essere aperta perché proviene da uno sviluppatore non identificato"*. Per aprirla:

- **Tasto destro** su `Aura.app` → **Apri** → **Apri**, oppure
- da Terminale:

```bash
xattr -dr com.apple.quarantine /Applications/Aura.app
```

## Verifica dell'integrità

Controlla gli hash SHA-256 dei file scaricati:

```
3ca801f3804872bf05b1ef1a453742c22d4652d950410f3957f034646e24d414  Aura.dmg
1da924145048e3d1e1e7dad08436bcdc56a2cb2c5796a83aebd043174fafc9ab  Aura.zip
```

```bash
shasum -a 256 Aura.dmg
```

## Informazioni sull'app

| | |
|---|---|
| Nome | Aura |
| Bundle ID | `com.aura.music` |
| Versione | 2.0.0 (build 3) |
| Categoria | Musica |
| Tecnologie | SwiftUI, Metal |

## Segnalare un problema

Hai trovato un bug o hai un'idea? Apri una [issue](../../issues) indicando:

- versione di macOS e modello di Mac
- versione di Aura (menu **Aura → Informazioni su Aura**)
- passaggi per riprodurre il problema

## Licenza

Copyright © 2026 Aura Music. Tutti i diritti riservati.

> Se vuoi rendere il progetto open source, aggiungi un file `LICENSE` (ad esempio MIT) e aggiorna questa sezione.
