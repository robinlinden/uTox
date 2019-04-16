project(utoxLAYOUT LANGUAGES C)

add_library(utoxLAYOUT STATIC
    layout/friend.c
    layout/group.c
    layout/notify.c
    layout/settings.c
    layout/sidebar.c
    layout/userbadge.c
    layout/background.c
    layout/tray.c
    )

target_include_directories(utoxLAYOUT
    PUBLIC
        .
    )
