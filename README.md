# Easy Traineeship Distro
Progetto coordinato GPS/IS anno accademico 2019\2020.  
Il progetto prevede l’implementazione di un gestore di tirocini esterno all’interno del sistema esistente “English Validation”.  
Il sistema risultante avrà, quindi, come obiettivi: 
* Fornire uno strumento per supportare e promuovere l’attività di tirocinio, assicurando che tutti gli stakeholders coinvolti interagiscono in modo semplice ed efficiente;
* Creare un sistema accessibile agli studenti del Dipartimento di Informatica, alla segreteria studenti ed al Presidente del Consiglio Didattico;
* Permettere allo studente di reperire informazioni sulle aziende, e far successivamente richiesta di disponibilità, in modo veloce ed immediato; 
* Ottimizzare l’attuale iter burocratico di firma, da parte degli stakeholders, dei documenti necessari al tirocinio (“Progetto Formativo”) dando la possibilità di caricare i suddetti documenti direttamente sulla piattaforma;
* La verifica da parte della Commissione Riconoscimenti degli estremi identificativi delle assicurazioni per la responsabilità civile, il numero di CFU che dovrebbero essere riconosciuti, e la completezza delle firme necessarie per l’approvazione.
# Distro 1.0
Prima release della piattaforma "Easy-Traineeship". Per maggiorni informazioni sull' istallazione consultare il "manuale di installazione"
*Prima di installare:
  1. Scaricare e installare JDK 8
  2. Scaricare il server "apache Tomcat" v9.0
  3. Installare il server "apache Tomcat" v9.0 nella root
  4. Clone/Download della repository
  5. Inserire il file "Easy-Traineeship.war" in C:\apache-tomcat-9.0\webapps
*Preparazione ed installazione della base di dati
  1. Scaricare e installare MySQL Server/Workbench
  2. Durante l’istallazione inserire le credenziali:
     a. Nome Utente: root
     b. Password: password
     c. hostPort: 3306
     d. hostName: localhost
  3. Importare/Lanciare "C2_IstanziaDB_ET_v1.0.sql" in MySQL Server/Workbench
*Installazione
  1. Avviare il Server "apache Tomcat"
  2. Aprire il Web Browser e recarsi al link del progetto
  3. Dopo aver concluso le operazioni desiderate sulla piattaforma stoppare il "apachetomcat"
# Project managers
Vincenzo Belmonte, Vincenzo De Rosa.
# Team
* Alessandro Serritiello
* Elio Testa
* Simona Grilletto
* Giuseppe Barisano
* Luigi Barbato
* Pellegrino Aurilia
* Salvatore Amendola
* Felice Montella
# Customer/Sponsor:
Dipartimento di Informatica dell'Università degli studi di Salerno.  
Presidente del Consiglio Didattico di Informatica Prof.ssa Filomena Ferrucci.
