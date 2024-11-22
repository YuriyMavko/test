classDiagram
    class RunProgram {
        +FileManager file_manager
        +User user
        +UserInterface ui
        +Event event_logic
        +EventInterface event_interface
        +run_program()
    }

    RunProgram --> FileManager
    RunProgram --> User
    RunProgram --> UserInterface
    RunProgram --> Event
    RunProgram --> EventInterface
