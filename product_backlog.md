Product Backlog

Vor dem Sprint:

US-1.1 Benutzerkonto erstellen → Basis-Registrierung für Nutzer mit Name, Email und Passwort.

US-3.1 Aufgabe erstellen → Nutzer können Aufgaben mit Titel und Beschreibung anlegen.


Nach dem Sprint:

US-1.1 Erweiterungen:
  - Passwort wird nun sicher gehasht (IPasswordHasher).  
  - E-Mail-Verifizierung wurde hinzugefügt (IEmailVerification).  
  - Benutzerrollenverwaltung wurde erweitert (IAuthorizationService).  

US-3.1 Erweiterungen:
  - CRUD-Operationen für Aufgaben (ICRUDTask, TaskService) implementiert.  
  - Aufgaben können einem Benutzer zugewiesen werden (assignedUser: User).  
  - Aufgaben können Dateien enthalten (File-Klasse).  
  - Aufgaben sind mit Projekten verknüpft (project: Project).  
