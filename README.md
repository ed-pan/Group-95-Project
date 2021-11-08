
# How To win League of Legends

## Overview 

League of legends is a free-to-play, Online Battle Arena (MOBA) video game that was developed by Riot Games in 2009. The aim of the game is to destroy the opposing teams base which is known as the Nexus. The gamemode we have analysed is known as Ranked Solo/Duo, players of roughly equal skill play against each other and the outcome of the game determines their place on the Ranked Solo Queue. 


## Aim

- Determine the factors that influence the likelihood of winning in each rank 
- To create a model that can help predict the outcome of a match prior to or during the game 

## Datasets 

The data was obtained using Riot Games' API through a third party wrapper package Riot-Watcher. Using the available methods we have created our own datasets using our MatchReader.ipynb file.

### data/
Contains the csv files for the different divisions: iron, bronze, silver, gold, platinum and diamond. 

### libraries/
Contains official .json libraries provided by Riot that provide information for fields that are stored as ID numbers, for example champId = 86 is stored as a field called 'key in the champion library and correlates to the character 'Garen'.

**by:**
- Aarya Hattangdi
- Edward Pan
- James D'Ugo
- Sarro Aghrel

