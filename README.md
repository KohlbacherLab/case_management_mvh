# Fallverwaltung Modellvorhaben Genomsequenzierung

Beispielprojekt in REDCap als Vorlage zur Anpassung an lokale Gegebenheiten. 

## Installation
- Voraussetzung ist eine REDCap Installation. Eine REDCap-Lizenz kann hier beantragt werden: https://projectredcap.org/partners/join/.
- Das Beispielprojekt kann von einem REDCap Administrator mit der [CDISC ODM XML-Vorlage](FallverwaltungModell_REDCap.xml) erstellt werden.
- Alternativ kann ein leeres Projekt erstellt werden und dort die Datenstruktur mit der [CSV Datei](FallverwaltungModellvorhaben_DataDictionary.csv) importiert werden (Strichpunkt als Separator).

Zur einfacheren Bedienung können optional externe Module installiert und aktiviert werden. Diese müssen von einem REDCap Administrator vom offiziellen Repository heruntergeladen und installiert werden:
- Instance Select: Auswahl einer Fallnummer für Datenupload
- Instance Table: Eingabe mehrerer Fallnummern pro Patient
- Orca Search Module: Suchmaske für verschiedene Felder. ([ZIP Datei zum Import der Einstellungen](FallverwaltungModellvorhaben_ModuleSettingsExport.zip))
- Ansicht der im Projekt aktivierten Module: 
![Module](Screenshot_MVH_Module.png)


## Übersicht über die Datenstruktur
- [PDF Datei](Fallverwaltung_Modellvorhaben_Genomsequenzierung_REDCap.pdf)
 
## Anmerkungen zur Datenstuktur:
- Automatisch eingelesene Felder sind mit dem Action Tag @READONLY versehen, bitte anpassen!

