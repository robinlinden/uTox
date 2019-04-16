project(utoxLAYOUT LANGUAGES C)

add_library(utoxLAYOUT STATIC
    friend.c
    group.c
    notify.c
    settings.c
    sidebar.c
    userbadge.c
    background.c
    tray.c
    )

target_include_directories(utoxLAYOUT
    PUBLIC
        include
    PRIVATE
        include/layout
    )
