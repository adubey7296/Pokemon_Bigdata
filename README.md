# Pokemon_Bigdata
Pig / Apache Pig

## Data Description
You can find data on https://data.world/data-society/pokemon-with-stats  or  
https://www.kaggle.com/abcsds/pokemon

This data set includes 721 Pokemon, including their number, name, first and second type, and basic stats: HP, Attack, Defense, Special Attack, Special Defense, and Speed. It has been of great use when teaching statistics to kids. With certain types you can also give a geeky introduction to machine learning.

This are the raw attributes that are used for calculating how much damage an attack will do in the games. This dataset is about the pokemon games (NOT pokemon cards or Pokemon Go).

#: ID for each pokemon

Name: Name of each pokemon

Type 1: Each pokemon has a type, this determines weakness/resistance to attacks

Type 2: Some pokemon are dual type and have 2

Total: sum of all stats that come after this, a general guide to how strong a pokemon is

HP: hit points, or health, defines how much damage a pokemon can withstand before fainting

Attack: the base modifier for normal attacks (eg. Scratch, Punch)

Defense: the base damage resistance against normal attacks

SP Atk: special attack, the base modifier for special attacks (e.g. fire blast, bubble beam)

SP Def: the base damage resistance against special attacks

Speed: determines which pokemon attacks first each round

Inspiration: The type of a pokemon cannot be inferred only by it's Attack and Deffence. It would be worthy to find which two variables can define the type of a pokemon, if any. Two variables can be plotted in a 2D space, and used as an example for machine learning. This could mean the creation of a visual example any geeky Machine Learning class would love.

###### Schema 

Schema : pokemon.csv

	col1	s.no
	col2	name
	col3	type
	col4	subtype
	col5	total_stats
	col6	hp
	col7	attack
	col8	defence
	col9	special attack
	col10	special defence
	col11	speed
	col12	generation
	col13	legendary

## Analysis
Below are some highlights of my analysis:
* List name & type of top 5 strongest(acco. to total_stats) pokemon.
* List top 3 strongest dragon type pokemon.
* List name of all pokemons with attack >= 100.
* List name and type of all legendary pokemon.
* List name of all pokemon with defence >= 100.
* List name,type & subtype of all pokemon with attack < 65.
* List name,type & subtype of all pokemon with defence < 80.
* List name of all pokemon with hp(health points) > 110.
* List names of fire type pokemons where attack and defence is b/w 80 & 120.
* List name of pokemon with same attack or defence power.
Check rest of analysis on https://github.com/adubey7296/Pokemon_Bigdata/blob/master/pokemon/pokemon.txt
