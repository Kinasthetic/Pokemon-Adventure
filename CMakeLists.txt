cmake_minimum_required(VERSION 3.29)
project(PokemonAdventure_v1)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(PokemonAdventure_v1
    BasePokemon.h
    globals.cpp
    globals.h
    KantoPokemon.cpp
    KantoPokemon.h
    main.cpp
    Market.cpp
    Market.h
    Player.cpp
    Player.h)
