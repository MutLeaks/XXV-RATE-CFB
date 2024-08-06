# XXV-Rate-CFB


### Disclaimer

* These tools rely on access to cfb.fan datasets and infrastructure. Mut.gg and Cfb.fan are wonderful community resources, You can support them directly by going #pro if you can. In the event similar features are ever added directly to partner sites, this tool will be immediatly discontinued. 

### Description

* College Ultimate team ratings tool. Initially planned as a web app for M24, this is meant to serve as a modern replacement for MUTRank. Users define the formula used for calculation, Rerate players based on what you value most. This is a P.O.C/Prototype release, and as such is relativly barebones at the moment. The sheer volume of players featured in CFB vs Madden highlighted the need to push this out.


### Completed

* Run calculations against all player stats (including height and weight). Basic filtering (team, position, chem, archtype, name, ovr). For height and weight, define max values, which will scale as a percentage against your player data.
* Basic .fan integration. Double click a player to open the players listing on cfb.fan. Left click one player than right click another to compare.
* Moderm interface design styilzed to look and feel of game.

## TODO

* Fix dataset (.fan is currently still missing some data, some of our rips didn't run proper, etc)
* Add autoupdater (checks against current cfb.fan dataset and only rip new additions)
* Add filtering by abilitys
* Add filtering by stats
* Add threshold weighting system for calculations
* Add formula selection, allowing users to preset and quickly change between formulas
* Add ability system for calculations
* Add player traits for calculations
* Optimization, tool is currently very slow/clunky due to size of dataset and inefficencys (Nearly 8k players as of now vs 4k? current for m24)

## COMMENTS 
* This is meant to supplemant cfb.fan / mut.gg, not to replace them. This tool cannot function without access to there datasets, which could change at any time. If you wish for this tool to remain functional, sub to #pro and support gg/fan.
* As far as ratings formulas, we will not be putting out any stock formulas for CFB25. That will be left up to community/end user. Without access to gamedata, our guess/prefrence is honestly as good as your's there. We could surely make inferances based off madden, but we like hard data.
* This may also release for madden 25 if community intrest is reasonable. Long term plans on that end would be to integrate actual gameplay curve data, which would serve as a more user freindly form of our vault project from 24/lay against actual player data this time around.
* Community contributions are welcome.

## Authors
ML Team

## Version History
* 0.1
    * Prototype release

## Special Thanks
To Jrjay1 for initial react webapp design
