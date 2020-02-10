# Semplificazione Amministrativa
Nell'ambito delle attività in corso del **Tavolo tecnico interoperabilità per la semplificazione amministrativa**, il presente progetto è stato reso disponibile come area di condivisione per le attività del Gruppo di Lavoro denominato **GdL Architetture ** per dare seguito alla linea d'azione **Definizione Sistema Sportelli Unici (SSU)**.

## Sistema Sportelli Unici - Interfacce di Servizio
Al presente repository sono disponibili gli IDL (Interface Description Languange) descritti in linguaggio [WSDL (Web Service Description Language)](https://it.wikipedia.org/wiki/Web_Services_Description_Language) delle interfacce di servizio dei sistemi componenti l'SSU. 

L’architettura logica del Sistema degli Sportelli Unici (SSU) è caratterizzata dalla seguenti
componenti:
 -  **Front-office**, consente l&#39;interazione con i soggetti che presentano
un&#39;istanza e assicura la raccolta delle informazioni relative al singolo
procedimento amministrativo, nonché la realizzazione di tutte le
comunicazioni necessarie per la gestione e conclusione del procedimento
amministrativo avviato con l’istanza del richiedente;

- **Back-office**,  riceve l’istanza dal **Front-office** e assicura il
coordinamento delle comunicazioni da e verso gli **Enti terzi** interessati allo
specifico procedimento amministrativo avviato con l’istanza del richiedente;

- **Enti terzi**, consente alle pubbliche amministrazioni che intervengono nello
specifico procedimento amministrativo di ricevere l’istanza inoltrata dal Back-
office e svolgere tutte le attività necessarie per l&#39;adozione del parere di
propria competenza;

- **Catalogo**, costituisce la base di conoscenza unica e condivisa,
comprende l’elenco dei sistemi informatici di cui sopra l’insieme delle regole per lo svolgimento dei procedimenti amministrativi.
