set(SRC
    TP/CondVar.cpp
    TP/Mutex.cpp
    TP/Task.cpp
    TP/ThreadPool.cpp
)
set(HEADERS
    TP/CondVar.h
    TP/Mutex.h
    TP/Task.h
    TP/ThreadPool.h
    TP/Global.h
)

add_library(TP_lib SHARED ${HEADERS} ${SRC})
