cmake_minimum_required(VERSION 3.26)
project(the_weapon_shop)

set(CMAKE_CXX_STANDARD 20)

add_executable(the_weapon_shop main.cpp
        lib/Character.h
        lib/character.cpp
        lib/Weapon.cpp
        lib/Weapon.h
        lib/Merchant.cpp
        lib/Merchant.h
        lib/WeaponType.h
        lib/Race.h
        lib/Class.h
        src/Game.h
)
