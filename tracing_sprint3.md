# Tracing-Dokumentation – Sprint 3

**📎 UML-Diagramme (Sprint 3):**

- [Klassendiagramm US-6.1, US-3.1, US-3.2, US-10.1](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Klassendiagramm_US-6.1_US-3.1_US-3.2_US-10.1.png)
- [Klassendiagramm US-2.1, US-2.2](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/raw/main/docs/userstory_klassendiagramm.png)
- [Sequenzdiagramm US-2.1, US-2.2](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/raw/main/docs/userstory_sequenz.png)
- [Sequenzdiagramm US-6.1, US-3.1, US-3.2, US-10.1](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Sequenzdiagramm_US-6.1_US-3.1_US-3.2_US-10.1.png)
- [Klassendiagramm US-5.1, US-5.2](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Klassendiagramm_US-5.1_und_US-5.2.png)
- [Sequenzdiagramm US-5.1, US-5.2](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Sequenzdiagramm_US-5.1_und_US-5.2.png)
- [Klassendiagramm US-10.1](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Klassendiagram_US-10.1.png)
- [Sequenzdiagramm US-10.1](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Sequenzdiagramm_US-10.1.png)

Diese Tabelle zeigt die Verbindung zwischen UML-Diagramm und Code-Implementierung.

---

## UML-Klassen und Implementierung im Code:

| UML-Klasse    | Code-Klasse                                         | GitLab-Link                                                                 |
|---------------|-----------------------------------------------------|-----------------------------------------------------------------------------|
| Task          | `com.example.demo.model.Task`                       | [Task.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/model/Task.java) |
| TaskFile      | `com.example.demo.model.TaskFile`                   | [TaskFile.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/model/TaskFile.java) |
| User          | `com.example.demo.model.User`                       | [User.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/model/User.java) |
| UserStory     | `com.example.demo.model.UserStory`                  | [UserStory.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/model/UserStory.java) |
| TaskRepository| `com.example.demo.repository.TaskRepository`        | [TaskRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/TaskRepository.java) |
| UserRepository| `com.example.demo.repository.UserRepository`        | [UserRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/UserRepository.java) |
| UserStoryRepository | `com.example.demo.repository.UserStoryRepository`   | [UserStoryRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/UserStoryRepository.java) |
| TaskService   | `com.example.demo.service.TaskService`              | [TaskService.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/service/TaskService.java) |
| NotificationService | `com.example.demo.service.NotificationService`      | [NotificationService.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/service/NotificationService.java) |
| TaskController| `com.example.demo.controller.TaskController`        | [TaskController.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/controller/TaskController.java) |
| ProfileController    | `com.example.demo.controller.ProfileController`     | [ProfileController.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/controller/ProfileController.java) |
| TeamController       | `com.example.demo.controller.TeamController`        | [TeamController.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/controller/TeamController.java) |
| AccountService       | `com.example.demo.service.AccountService`           | [AccountService.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/service/AccountService.java) |
| UserRepository       | `com.example.demo.repository.UserRepository`        | [UserRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/UserRepository.java) |
| User                 | `com.example.demo.model.User`                       | [User.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/model/User.java) |

---

## UML-Interfaces und Implementierung im Code:

| UML-Interface       | Code-Interface                                                        | GitLab-Link                                                                  |
|---------------------|------------------------------------------------------------------------|------------------------------------------------------------------------------|
| TaskRepository       | `com.example.demo.repository.TaskRepository`                          | [TaskRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/TaskRepository.java) |
| UserRepository       | `com.example.demo.repository.UserRepository`                          | [UserRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/UserRepository.java) |
| UserStoryRepository  | `com.example.demo.repository.UserStoryRepository`                     | [UserStoryRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/UserStoryRepository.java) |

---