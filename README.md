Certo! Ecco la traduzione in italiano:

---

# Born2beroot

![42 Roma Luiss](https://img.shields.io/badge/42-Roma_Luiss-green)  
![110](https://img.shields.io/badge/110-green)  
![Creato](https://img.shields.io/badge/Created-February_2025-blue)  
![Stato](https://img.shields.io/badge/Status-completed-violet)

## 📖 Materiale di Studio Personale 📖  
[Parte prima](Prima_Parte.pdf)  
[Parte seconda](Parte_Seconda.pdf)  
[Preparazione alla Defence](Preparazione_Defence.pdf)  
[Tabella Comandi](Tabella_Comandi.pdf)

## 🚀 Panoramica
Born2beroot è un progetto di amministrazione di sistema focalizzato sull’apprendimento dei fondamenti della virtualizzazione, della gestione di sistemi Linux e delle pratiche essenziali di sicurezza. Il progetto prevede la creazione di una macchina virtuale con Debian Linux, configurata secondo specifiche regole di sicurezza.

## 📋 Componenti Chiave

### Configurazione della Macchina Virtuale
- Creata con Oracle VirtualBox  
- Basata su Debian GNU/Linux  
- Utilizza LVM (Logical Volume Management) per una gestione flessibile dello spazio disco  
- Include partizionamento conforme ai requisiti del progetto  

### Caratteristiche di Sicurezza
- Configurazione di UFW (Uncomplicated Firewall)  
- Politica di password forte tramite `libpam-pwquality`  
- Servizio SSH attivo sulla porta 4242  
- Accesso root disabilitato  
- AppArmor attivo per una maggiore sicurezza  
- Gestione utenti sicura e configurazione di sudo  

### Monitoraggio del Sistema
Script personalizzato che mostra:
- Architettura del sistema  
- Core fisici/virtuali della CPU  
- Utilizzo della memoria  
- Utilizzo del disco  
- Carico della CPU  
- Ultimo avvio del sistema  
- Stato di LVM  
- Connessioni attive  
- Informazioni sugli utenti  
- Stato della rete  
- Cronologia dei comandi sudo  

### Funzionalità Bonus
- Sito WordPress funzionante  
- Gestione dei servizi (Lighttpd, MariaDB, PHP)  
- Configurazione di servizi aggiuntivi  

## 🛠️ Dettagli Tecnici

### Politica delle Password
- Minimo 10 caratteri  
- Contiene lettere maiuscole e minuscole  
- Almeno un numero  
- Non più di 3 caratteri identici consecutivi  
- Lo username non deve essere incluso  
- Almeno 7 caratteri diversi dalla password precedente  
- Scadenza ogni 30 giorni  
- Minimo 2 giorni tra un cambio password e l’altro  
- Avviso 7 giorni prima della scadenza  

### Configurazione di Sudo
- Massimo 3 tentativi falliti  
- Messaggio di errore personalizzato  
- Logging dei comandi abilitato  
- TTY richiesto  
- Percorsi sicuri definiti  

### Servizi di Sistema
- SSH configurato per l’accesso remoto sicuro  
- UFW configurato con le porte necessarie  
- Script di monitoraggio eseguito ogni 10 minuti tramite crontab  

## 🎯 Competenze Acquisite
- Comprensione dell’amministrazione di sistemi Linux  
- Implementazione di misure di sicurezza  
- Gestione di utenti e gruppi  
- Configurazione e gestione di servizi  
- Concetti di virtualizzazione  
- Partizionamento del disco e LVM  
- Configurazione base di un server web  
- Monitoraggio e manutenzione del sistema  

## 📝 Note
Questo progetto è stato completato come parte del percorso formativo della scuola 42, con l’obiettivo di sviluppare competenze pratiche nell’amministrazione di sistema e nella sicurezza. L’implementazione segue rigorosamente i requisiti del progetto, offrendo un’esperienza concreta simile a quella del mondo reale.

## Statistiche GitHub 📊  
![Statistiche GitHub](https://github-readme-stats.vercel.app/api?username=vhacman&show_icons=true&theme=radical)  
![Linguaggi Principali](https://github-readme-stats.vercel.app/api/top-langs/?username=vhacman&layout=compact&theme=radical)

---

Se vuoi, posso anche aiutarti a trasformare questo in un file README per GitHub o sistemarlo graficamente per una presentazione. Fammi sapere!
