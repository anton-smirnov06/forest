cmake_minimum_required(VERSION 3.13)
project(Forest)
find_package(SFML COMPONENTS window graphics REQUIRED)
add_executable(Forest
	main.cpp
	Animal.cpp
	Carnivore.cpp
	Cat.cpp
	Cow.cpp
	Creature.cpp
	Fish.cpp
	Flower.cpp
	Forest.cpp
	Herbivore.cpp
	Lion.cpp
	Mushroom.cpp
	Penguin.cpp
	Plant.cpp
	Sparrow.cpp
	Sundew.cpp
)
target_link_libraries(Forest PRIVATE sfml-window sfml-graphics)
install(TARGETS Forest)
