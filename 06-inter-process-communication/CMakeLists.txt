cmake_minimum_required(VERSION 3.5.1)

set(CMAKE_CXX_STANDARD 11)

project(06-inter-process-communication)

include_directories(include)

add_executable(shm_example
  src/shm_example.c
)

add_executable(msg_example
  src/msg_example.c
)

add_executable(msg_send
  src/msg_send.c
)

add_executable(msg_recv
  src/msg_recv.c
)

add_executable(sem_example
  src/sem_example.c
)