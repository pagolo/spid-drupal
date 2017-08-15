# SPID-PASW

## Cos'è SPID
SPID, Sistema Pubblico di Identità Digitale, è il nuovo metodo di login che permette a cittadini
e imprese di accedere con un’unica identità digitale a tutti i servizi online di pubbliche
amministrazioni e imprese aderenti.
Grazie a SPID vengono meno le decine di password, chiavi e codici necessari oggi per utilizzare
i servizi online di Pa e imprese.

Maggiori informazioni 
www.spid.gov.it
http://www.agid.gov.it/agenda-digitale/infrastrutture-architetture/spid

Questo modulo (SPID-PASW) è un fork di SPID-Drupal
(Il progetto SPID-Drupal ha l'obiettivo di creare un modulo per implementare in maniera agevole
SPID nei portali e servizi basati su Drupal.)

Autore del modulo: Paolo Bozzo e Nadia Caprotti nell'ambito della comunità "Porte aperte sul Web"

Crediti:
Steve Moitozo (creatore modulo SAML originale)
AGID e Comune di Firenze (modulo SPID-Drupal), in particolare Umberto Rosini e Andrea Manzi
Referenti tecnici degli IDP Spid, in particolare Gianluca Tovo

IMPORTANTE 1: il modulo è nato per essere utilizzato con pacchetto Drupal-PASW, ma dalla versione
0.1 è possibile usarlo con qualsiasi configurazione di Drupal. Nella configurarlo si presti
attenzione alla sezione "OPZIONI AVANZATE", questa sezione, inutile per gli utenti Drupal, permette
agli altri utenti di configurare il nome utente sul codice fiscale e di impostare o disattivare
l'uso di campi atti a conservare su Drupal gli attributi SPID. I campi vanno creati a mano e suc-
cessivamente impostati attraverso la configurazione (se non si vogliono utilizzare basta impostarli
su "nessun campo").

IMPORTANTE 2: il modulo preferisce la presenza della libreria simplespidphp-pasw installata tramite lo
script spidinstall scaricabile qui:
xxxxxxxxxxxxxxxx