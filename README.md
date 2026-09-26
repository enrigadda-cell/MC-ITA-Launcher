# 🇮🇹 MC ITA Launcher

**MC ITA Launcher** è il launcher ufficiale del server **MC ITA**, progettato per rendere l'installazione e l'aggiornamento del modpack il più semplice possibile.

L'obiettivo è permettere ai giocatori di preparare il proprio Minecraft senza dover installare manualmente decine di mod.

---

## 🚀 Funzionalità

* 🎮 Supporto dedicato a **TLauncher**
* 📁 Rilevamento automatico della cartella `.minecraft`
* 📦 Download automatico del pacchetto mod
* ⚙️ Installazione automatica delle mod nella cartella `mods`
* 🔄 Sistema progettato per ricevere futuri aggiornamenti del modpack
* 🌐 Download del pacchetto da una sorgente online
* 🛡️ Controlli e gestione degli errori durante download e installazione
* 📝 Log tecnici per facilitare la diagnosi dei problemi
* 🖥️ Applicazione Windows `.exe`

---

## 🎮 Compatibilità

| Componente          | Versione              |
| ------------------- | --------------------- |
| Minecraft           | **1.21.1**            |
| Mod Loader          | **NeoForge 21.1.248** |
| Launcher supportato | **TLauncher**         |
| Sistema operativo   | **Windows**           |

Il launcher è sviluppato specificamente per l'ambiente utilizzato dal server MC ITA.

---

## 📦 Come funziona

Il funzionamento è progettato per essere semplice:

```text
MC ITA Launcher.exe
        │
        ▼
Rilevamento di TLauncher
        │
        ▼
Rilevamento della cartella .minecraft
        │
        ▼
Connessione al server di distribuzione
        │
        ▼
Download MC-ITA-PACK.zip
        │
        ▼
Installazione delle mod
        │
        ▼
Minecraft pronto
```

Il giocatore non deve scaricare e installare manualmente ogni singola mod.

---

## 🔄 Aggiornamenti

Il launcher è progettato per utilizzare un pacchetto mod online.

Quando il modpack viene aggiornato, il pacchetto online può essere sostituito con una nuova versione.

L'obiettivo è evitare di dover distribuire un nuovo launcher `.exe` ogni volta che viene modificata una mod.

```text
Nuovo aggiornamento MC ITA
          │
          ▼
Aggiornamento del pacchetto online
          │
          ▼
MC ITA Launcher
          │
          ▼
Download della nuova versione
          │
          ▼
Modpack aggiornato
```

---

## 🛠️ Sviluppo

Il launcher viene sviluppato in **Python** e successivamente distribuito come applicazione Windows `.exe`.

Il progetto è sviluppato mantenendo particolare attenzione alla:

* semplicità d'utilizzo
* compatibilità
* gestione degli errori
* stabilità
* facilità di aggiornamento
* manutenzione del progetto

---

## 📂 Struttura del progetto

La struttura del repository verrà organizzata progressivamente durante lo sviluppo.

Una possibile struttura è:

```text
MC-ITA-Launcher/
│
├── launcher.py
├── README.md
├── .gitignore
│
└── ...
```

La struttura definitiva potrà cambiare durante lo sviluppo.

---

## 👨‍💻 Autore

**Chairman-Enrico**

MC ITA Launcher è un progetto sviluppato per il server Minecraft **MC ITA**.

---

# 🇬🇧 MC ITA Launcher

**MC ITA Launcher** is the official launcher for the **MC ITA Minecraft server**, designed to make modpack installation and updating as simple as possible.

The goal is to allow players to prepare their Minecraft installation without manually installing dozens of mods.

---

## 🚀 Features

* 🎮 Dedicated support for **TLauncher**
* 📁 Automatic detection of the `.minecraft` directory
* 📦 Automatic modpack download
* ⚙️ Automatic installation of mods into the `mods` folder
* 🔄 Designed to support future modpack updates
* 🌐 Online modpack distribution
* 🛡️ Error handling during download and installation
* 📝 Technical logs for troubleshooting
* 🖥️ Windows `.exe` application

---

## 🎮 Compatibility

| Component          | Version               |
| ------------------ | --------------------- |
| Minecraft          | **1.21.1**            |
| Mod Loader         | **NeoForge 21.1.248** |
| Supported launcher | **TLauncher**         |
| Operating system   | **Windows**           |

The launcher is specifically developed for the environment used by the MC ITA server.

---

## 📦 How it works

The planned workflow is simple:

```text
MC ITA Launcher.exe
        │
        ▼
Detect TLauncher
        │
        ▼
Detect .minecraft directory
        │
        ▼
Connect to online distribution source
        │
        ▼
Download MC-ITA-PACK.zip
        │
        ▼
Install mods
        │
        ▼
Minecraft ready
```

Players do not need to manually download and install every individual mod.

---

## 🔄 Updates

The launcher is designed to use an online modpack.

When the modpack is updated, the online package can be replaced with a newer version.

The goal is to avoid distributing a new launcher `.exe` every time a mod is updated.

```text
New MC ITA update
        │
        ▼
Update online package
        │
        ▼
MC ITA Launcher
        │
        ▼
Download new version
        │
        ▼
Updated modpack
```

---

## 🛠️ Development

The launcher is developed in **Python** and distributed as a Windows `.exe` application.

Development focuses on:

* simplicity
* compatibility
* error handling
* stability
* easy updates
* maintainability

---

## 📂 Project structure

The repository structure will be organized progressively during development.

A possible structure is:

```text
MC-ITA-Launcher/
│
├── launcher.py
├── README.md
├── .gitignore
│
└── ...
```

The final structure may change during development.

---

## 👨‍💻 Author

**Chairman-Enrico**

MC ITA Launcher is a project developed for the **MC ITA Minecraft server**.

---

## 📜 Project status

🚧 **Currently in development**

The launcher is being developed step by step, with testing performed throughout the development process.
