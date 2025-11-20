# Design Patterns - CSharp
## Creational Patterns (oprettelse af objekter)
### 1. Singleton
Bruges når:
* Der må kun eksistere én instans af en klasse
####
### 2. Factory Method
Bruges når
* Beslutningen, om hvilken konkret klasse der skal oprettes, udsættes .
* Der er flere mulige implementeringer af et interface.
### 3. Abstract Factory
Bruges når:
* Der skal laves familier af relaterede objekter.
* Objekterne skal passe sammen eller have samme “tema”.
### 4. Builder
Bruges når:
* Der bygges et komplekst objekt trin for trin.
* Objektet har mange konfigurationsmuligheder.
### 5. Prototype
Bruges når:
* Der ofte laves kopier af et komplekst objekt.
* At klone er billigere end at konstruere fra bunden.
####
## Structural Patterns (sammensætning af objekter)
### 6. Adapter
Bruges når:
* Inkompatible interfaces skal forbindes.
* Der bruges gammel kode, tredjepartsbiblioteker eller eksterne API’er.
### 7. Facade
Bruges når:
* Et komplekst subsystem bag et simpelt API skal skjules.
### 8. Decorator
Bruges når:
* Funktionalitet dynamisk skal udvides uden at ændre klassen.
* En eksplosiv mængde subclasses skal undgås.
### 9. Composite
Bruges når:
* Objekter er i en træstruktur, og både “dele” og “helhed” skal behandles ens.
### 10. Proxy
Bruges når:
* Adgang til et objekt skal kontrolleres.
####
## Behavioral Patterns (adfærd og samarbejde)
### 11. Strategy
Bruges når:
* Adfærdsalgoritme skifter dynamisk.
### 12. Observer
Bruges når:
* Et objekt skal informere andre objekter om ændringer.
### 13. Command
Bruges når:
* En handling skal repræsenteres som et objekt.
* Der er behov for undo/redo, køer eller logging af handlinger.
### 14. Mediator
Bruges når:
* Mange objekter kommunikerer og spaghetti-afhængigheder skal undgås.
* Al kommunikation skal gå gennem en central instans.
### 15. State
Bruges når:
* Objektets opførsel ændrer sig afhængig af dets interne tilstand.
* I stedet for if-statements → brug siderelaterede klasser.
### 16. Template Method
Bruges når:
* Der skal defineres skelet af en algoritme, men lade subclasses bestemme dele af den.
