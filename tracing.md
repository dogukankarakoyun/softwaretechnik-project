**** UML-Diagramm Link
Das UML-Diagramm ist unter folgendem Link verfügbar:  
![Hier klicken, um das UML-Diagramm anzuzeigen](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/docs/uml-diagram.png/uml-diagram.png.jpg?ref_type=heads)


**** Tracing-Dokumentation

Diese Tabelle zeigt die Verbindung zwischen UML-Diagramm und Code-Implementierung:

**** UML-Klassen und ihre Implementierung im Code:
| UML-Klasse              | Code-Klasse                                         | GitLab-Link |
|-------------------------|----------------------------------------------------|-------------|
| User                   | com.example.demo.model.User                        | [User.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/User.java?ref_type=heads) |
| AccountService         | com.example.demo.service.AccountService            | [AccountService.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/02c46e1fc77e9cd8fb7b02a03ef2dea1292c11da/Team1_demo_project/src/AccountService.java) |
| DatabaseManager        | com.example.demo.repository.DatabaseManager        | [DatabaseManager.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/DatabaseManager.java?ref_type=heads)|
| EmailVerificationService | com.example.demo.service.EmailVerificationService | [EmailVerificationService.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/EmailVerificationService.java?ref_type=heads) |
| PasswordHasher         | com.example.demo.service.PasswordHasher           | [PasswordHasher.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/PasswordHasher.java?ref_type=heads) |

**** UML-Interfaces und ihre Implementierung im Code:
| UML-Interface          | Code-Interface                                     | GitLab-Link |
|------------------------|---------------------------------------------------|-------------|
| IAccountManagement     | com.example.demo.interfaces.IAccountManagement     | [IAccountManagement.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/IAccountManagement.java?ref_type=heads) |
| IUserAuthentication    | com.example.demo.interfaces.IUserAuthentication    | [IUserAuthentication.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/IUserAuthentication.java?ref_type=heads) |
| IEmailVerification     | com.example.demo.interfaces.IEmailVerification     | [IEmailVerification.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/IEmailVerification.java?ref_type=heads) |
| IPasswordHasher        | com.example.demo.interfaces.IPasswordHasher        | [IPasswordHasher.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/IPasswordHasher.java?ref_type=heads) |

Diese Annotation-basierte Tracing-Strategie stellt sicher, dass jede Code-Klasse und jedes Interface direkt mit einer UML-Komponente verknüpft ist.
