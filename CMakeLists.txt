cmake_minimum_required(VERSION 3.23)
project(Cinel)

set(CMAKE_CXX_STANDARD 14)

add_executable(Cinel main.cpp editora2.cpp)
add_executable(Cinel_editora2  editora2.cpp)
add_executable(Cinel_jogoGalo  jogoGalo.cpp)
add_executable(Cinel_AvalGalo avaliacoes/AvalGalo.cpp)
add_executable(Cinel_avaliaca2 avaliacoes/avaliacao2.cpp)
add_executable(Cinel_editora  editora.cpp)
add_executable(Cinel_funcoes  funcoes.cpp)
add_executable(Cinel_exercici021 exercici021.cpp)
add_executable(Cinel_exercicio16 exercicio16.cpp)
add_executable(Cinel_exercicio26 exercicio26.cpp)
add_executable(Cinel_exercicio25 exercicio25.cpp)