set(PLUGIN "location")

set(HEADERS
    location.h
)

set(SOURCES
    location.cpp
)

set(LIBRARIES
    ${LIBRARIES}
    lxqt-globalkeys
    Qt5Xdg
)

BUILD_LXQT_PLUGIN(${PLUGIN})
