```mermaid
classDiagram
    class UserInterface {
        +User user
        +register()
        +login()
        +logout()
        +check_temp_login() bool
    }

    class User

    UserInterface --> User


```