```mermaid
classDiagram
    class RunProgram {
        +FileManager file_manager
        +User user
        +UserInterface ui
        +Event event_logic
        +EventInterface event_interface
        +run_program()
    }

    class FileManager
    class User
    class UserInterface
    class Event
    class EventInterface

    RunProgram --> FileManager
    RunProgram --> User
    RunProgram --> UserInterface
    RunProgram --> Event
    RunProgram --> EventInterface
```