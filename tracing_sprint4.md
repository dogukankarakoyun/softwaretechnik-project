# Tracing-Dokumentation – Sprint 4

**📎 UML-Diagramme (Sprint 4):**

- [Klassendiagramm US-9.1, US-9.2, US-9.3, US-4.5](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Klassendiagramm_US-9.1_US-9.2_US-9.3_US-4.5.png)
- [Sequenzdiagramm US-9.1, US-9.2, US-9.3, US-4.5](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Sequenzdiagramm_US-9.1_US-9.2_US-9.3_US-4.5.png)
- [Klassendiagramm US-4.6](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Klassendiagramm%20_US-4.6.png)
- [Sequenzdiagramm US-4.6](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Sequenzdiagramm_US-4.6.png)
- [Klassendiagramm US-2.1, US-2.2, US-2.3, US-4.4](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Klassendiagramm_US-2.1_US-2.2_US-2.3_US-4.4.png)
- [Sequenzdiagramm US-2.1, US-2.2, US-2.3, US-4.4](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/docs/Sequenzdiagramm_US-2.1_US-2.2_US-2.3_US-4.4.png)
---

## UML-Klassen und Implementierung im Code:

| UML-Klasse     | Code-Klasse                                      | GitLab-Link                                                                 |
|----------------|--------------------------------------------------|------------------------------------------------------------------------------|
| Task           | `com.example.demo.model.Task`                    | [Task.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/model/Task.java) |
| User           | `com.example.demo.model.User`                    | [User.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/model/User.java) |
| UserStory      | `com.example.demo.model.UserStory`               | [UserStory.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/model/UserStory.java) |
| TaskController | `com.example.demo.controller.TaskController`     | [TaskController.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/controller/TaskController.java) |
| TaskService    | `com.example.demo.service.TaskService`           | [TaskService.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/service/TaskService.java) |
| TaskRepository | `com.example.demo.repository.TaskRepository`     | [TaskRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/TaskRepository.java) |
| CalendarEntry       | `com.example.demo.model.CalendarEntry`           | [CalendarEntry.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/model/CalendarEntry.java) |
| CalendarController  |`com.example.demo.controller.CalendarController`| [CalendarController.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/controller/CalendarController.java) |
| CalendarService     | `com.example.demo.service.CalendarService`       | [CalendarService.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/service/CalendarService.java) |
| CalendarServiceImpl | `com.example.demo.service.CalendarServiceImpl`  | [CalendarServiceImpl.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/service/CalendarServiceImpl.java) |
| Priorität        | `com.example.demo.enums.Priority`                 | [Priority.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/model/Priority.java) |
| BacklogController| `com.example.demo.controller.BacklogController`    | [BacklogController.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/controller/BacklogController.java) |

---

## UML-Interfaces und Implementierung im Code`

| UML-Interface        | Code-Interface                                     | GitLab-Link                                                                  |
|----------------------|---------------------------------------------------|-------------------------------------------------------------------------------|
| TaskRepository        | `com.example.demo.repository.TaskRepository`      | [TaskRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/TaskRepository.java) |
| UserRepository        | `com.example.demo.repository.UserRepository`      | [UserRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/UserRepository.java) |
| UserStoryRepository   | `com.example.demo.repository.UserStoryRepository` | [UserStoryRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/UserStoryRepository.java) |
| CalendarRepository | `com.example.demo.repository.CalendarRepository`    | [Ca`endarRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/CalendarRepository.java) |
| UserStoryRepository  | com.example.demo.repository.UserStoryRepository     | [UserStoryRepository.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/main/Team1_demo_project/src/main/java/com/example/demo/repository/UserRepository.java) |