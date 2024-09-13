cmake_minimum_required(VERSION 3.22.1) # объявляем минимальную версию cmake
project(test) # устанавливаем имя проекта
set(SOURCES test.cpp) # переменной SOURCES присваиваем значение test.cpp
add_executable(test ${SOURCES}) # добавляем переменную SOURCES к исполняемым файлам

