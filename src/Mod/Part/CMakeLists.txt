
add_subdirectory(App)
if(FREECAD_BUILD_GUI)
    add_subdirectory(Gui)
endif(FREECAD_BUILD_GUI)

INSTALL(
    FILES
        Init.py
        InitGui.py
        MakeBottle.py
        TestPartApp.py
        TestPartGui.py
    DESTINATION
        Mod/Part
)
