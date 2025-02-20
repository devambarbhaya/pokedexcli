# Pokedex CLI

Pokedex is a simple interactive programming environment that takes user input, evaluates it and returns the result to the user. It uses the **REPL** Loop (Read - Eval - Print Loop). This projects is made in Go which uses the PokeAPI to fetch the data about Pokemon.

I have implemented it by putting my knowledge about Go to learn and test valuable skills like **HTTP Networking** and **Data Serialization**

## Features

- Implemented Caching for the API calls we will make during the execution
- Added `map` & `mapb` command to find a location area to find pokemons which are available there displaying only certain number of places and you can move back and forth between pages.
- Added the `explore` command which lists all the pokemon in the region.
- It's time to catch some pokemon! Catching Pokemon adds them to the user's Pokedex using the `catch` command
- Our Pokedex will only allow players to see details about a Pokemon if they have seen it before (or in our case, caught it) using the `inspect` command
- Lastly, using the `pokedex` command, The main purpose of a Pokedex is to keep track of all the Pokemon you've caught. Gotta catch 'em all!

## Installation

1. Installation

```
git clone https://github.com/devambarbhaya/pokedexcli.git
cd pokedexcli
```

2. Build the program by running the command

```
go build
```

3. A new pokedexcli executable will be created. Run it

```
./pokedexcli
```

## Usage

ℹ️ help (Displays a help message)

```
Pokedex > help
```

🗺️ map (Get the next page of locations)

```
Pokedex > map
```

🗺️ mapb (Get the previous page of locations)

```
Pokedex > mapb
```

🔍 explore <location_name> (Explores a location to find available pokemons)

```
Pokedex > explore canaclave-city-area
```

🤾catch <pokemon_name> (Attempt to catch a pokemon)

```
Pokedex > catch pikachu
```

🧐 inspect <pokemon_name> (View details of a caught pokemon)

```
Pokedex > inspect pikachu
```

💻 pokedex (See all the pokemon you have caught)

```
Pokedex > pokedex
```

🔚 exit (Exit the Pokedex)

```
Pokedex > exit
```

# **Gotta catch them all!**
