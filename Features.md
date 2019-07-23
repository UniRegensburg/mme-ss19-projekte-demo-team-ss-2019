# URide

## Features

| Feature | Beschreibung | Priorität | Geschätzter Aufwand | Betroffen Schichten |
|---------|--------------|-----------|--------------------|---------------------|
| **Profil anlegen und speichern** | Nutzer können beim initialen Start der Anwendung ein Nutzerprofil erstellen, in dem Name, persönliche Adresse, Alter, Gewicht und Art des Fahrrads gespeichert werden. Die Daten werden benötigt um die Erfassung der einzelnen Fahrten zu ermöglichen bzw. zu erleichtern. Die Profildaten werden dabei über eine entsprechende Maske erfasst und vor dem Speichern validiert. Mit Hilfe der [Algolia Places](https://community.algolia.com/places/)-Bibliothek wird die Adresseingabe vereinfacht. Das erstellte Profil wird dauerhaft gespeichert und steht anderen Anwendungskomponenten zur Verfügung. | hoch (kritisch) | 1 Tag | UI, Datenbank, Javascript |