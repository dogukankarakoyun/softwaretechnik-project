# Tracing-Dokumentation – Sprint 2

**📎 UML-Diagramme (Sprint 2):**

- [Klassendiagramm 1 – US-1.1 und US-1.2](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Klassendiagram_US-1.1_und_US-1.2.jpeg)
- [Klassendiagramm 2 – US-1.3](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Klassendiagramm_US-1.3.jpeg)
- [Klassendiagramm 3 – US-3.1 & US-3.3 & US-3.4](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Klassendiagramm_US-3.1___US-3.3___US-3.4.png)



Diese Tabelle zeigt die Verbindung zwischen UML-Diagramm und Code-Implementierung.

---

## UML-Klassen und Implementierung im Code:

| UML-Klasse              | Code-Klasse                                                    | GitLab-Link                |
|-------------------------|----------------------------------------------------------------|----------------------------|
| MainController          | com.example.demo.controller.MainController                     | [MainController.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/controller/MainController.java) |
| ViewController          | com.example.demo.controller.ViewController                     | [ViewController.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/controller/ViewController.java) |
| AccountService          | com.example.demo.service.AccountService                        | [AccountService.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/service/AccountService.java) |
| AuthorizationService    | com.example.demo.service.AuthorizationService                  | [AuthorizationService.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/service/AuthorizationService.java) |
| EmailVerificationService| com.example.demo.service.EmailVerificationService              | [EmailVerificationService.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/service/EmailVerificationService.java) |
| NotificationService     | com.example.demo.service.NotificationService                   | [NotificationService.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/service/NotificationService.java) |
| ValidationService       | com.example.demo.service.ValidationService                     | [ValidationService.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/service/ValidationService.java) |
| TaskService             | com.example.demo.service.TaskService                           | [TaskService.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/service/TaskService.java) |
| TaskQueryService        | com.example.demo.service.TaskQueryService                      | [TaskQueryService.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/service/TaskQueryService.java) |
| SubtaskService          | com.example.demo.service.SubtaskService                        | [SubtaskService.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/service/SubtaskService.java) |
| PasswordHasher          | com.example.demo.service.PasswordHasher                        | [PasswordHasher.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/service/PasswordHasher.java) |
| DatabaseManager         | com.example.demo.repository.DatabaseManager                    | [DatabaseManager.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/repository/DatabaseManager.java) |
| UserRepository          | com.example.demo.repository.UserRepository                     | [UserRepository.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/repository/UserRepository.java) |
| User                    | com.example.demo.model.User                                    | [User.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/model/User.java) |
| Project                 | com.example.demo.model.Project                                 | [Project.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/model/Project.java) |
| Task                    | com.example.demo.model.Task                                    | [Task.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/model/Task.java) |
| Subtask                 | com.example.demo.model.Subtask                                 | [Subtask.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/model/Subtask.java) |
| TaskFile                | com.example.demo.model.TaskFile                                | [TaskFile.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/model/TaskFile.java) |
| UserRole                | com.example.demo.model.UserRole                                | [UserRole.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/model/UserRole.java) |
| TaskStatus              | com.example.demo.model.TaskStatus                              | [TaskStatus.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/model/TaskStatus.java) |
| Priority                | com.example.demo.model.Priority                                | [Priority.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/model/Priority.java) |

---

## UML-Interfaces und Implementierung im Code:

| UML-Interface           | Code-Interface                                                 | GitLab-Link                |
|-------------------------|----------------------------------------------------------------|----------------------------|
| IAccountManagement      | com.example.demo.dao.IAccountManagement                | [IAccountManagement.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/dao/IAccountManagement.java) |
| IUserAuthentication     | com.example.demo.dao.IUserAuthentication               | [IUserAuthentication.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/dao/IUserAuthentication.java) |
| IEmailVerification      | com.example.demo.dao.IEmailVerification                | [IEmailVerification.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/dao/IEmailVerification.java) |
| IPasswordHasher         | com.example.demo.dao.IPasswordHasher                   | [IPasswordHasher.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/dao/IPasswordHasher.java) |
| TaskRepository          | com.example.demo.repository.TaskRepository                    | [TaskRepository.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/repository/TaskRepository.java) |
| SubtaskRepository       | com.example.demo.repository.SubtaskRepository                 | [SubtaskRepository.java](https://git.informatik.uni-rostock.de/-/ide/project/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/edit/main/-/Team1_demo_project/src/main/java/com/example/demo/repository/SubtaskRepository.java) |

---

