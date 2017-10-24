# Test Case 

## Test Details

* Test Case ID:
  * 1.0
* Test Case Name:
  * Music settings
* Component: 
  * Testing input; whether changing settings actually change
* Test Case Designer:
  * Eugene Vasquez
* Creation Date:
  * 10/16/17
* Modified By:
  * Rick Sanchez
* Modified Date:
  * 10/17/17
* Requirements Covered:
  * Testing input
* Test Description/Purpose:
  * To determine whether Music change input works properly
* Pre-Test Conditions:
  * The level needs to be running along with the interaction buttons to determine whether they have any effect on Music
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 |Changing music settings |being able to change settings | (√)|			
| 2 |Making sure music loads correctly |Music preset it correct |(√) |			
| 3 |Plays current music properly|Volume is unnaffected unless player interacts with settings beforehand|(√) |			

## Overall Test Status:

No problems so far. might do another round fo testing in the future when other features are added

## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 |10/18/17 |Rick Sanchez |(√) |			
| 2 |10/20/17 |Rick Sanchez |(√) |			
| 3 |10/22/17 |Rick Sanchez |(√) |			

# Test Case 2

## Test Details

* Test Case ID:
  * 2.0
* Test Case Name:
  * Interaction 
* Component: 
  * Need game to be up and running; full game. Need enviroments to be completed, or near completion
* Test Case Designer:
  * Eugene Vasquez
* Creation Date:
  * 10/24/17
* Modified By:
  * Rick Sanchez
* Modified Date:
  * 10/25/17
* Requirements Covered:
  * Needs to make sure inputs are working correctly
* Test Description/Purpose:
  * To determine player input is registered correctly
* Pre-Test Conditions:
  * Player input needs to be working correctly when concerning decisions, or interacting with things
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Moving items in game|Moving items in desired direction |(√) |			
| 2 |Picking up items |Making sure that items are being placed in inventory |(√)|			
| 3 |When making decisions, player input is registered |Decisions are made by player, not defaulted if broken |(√)|			
		

## Overall Test Status:

No problems. Will have to do more tests as code is added to game

## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 |10/26/17 |Rick Sanchez |(√) |			
| 2 |10/28/17 |Rick Sanchez |(√) |			
| 3 |10/30/17 |Rick Sanchez |(√) |	

# Test Case 3

## Test Details

* Test Case ID:
  * 3.0
* Test Case Name:
  * Save Game
* Component: 
  * testing that save game function works
* Test Case Designer:
  * Eugene Vasquez
* Creation Date:
  * 11/01/17
* Modified By:
  * Rick Sanchez
* Modified Date:
  * 11/02/17
* Requirements Covered:
  * Needs to make sure that saves are working properly
* Test Description/Purpose:
  * To determine when saves are named correctly
* Pre-Test Conditions:
  * All assets need to be loaded before playing; needs to test with everything correctly
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 |Special characters dont break the file when naming |Saves no matter the name given |(√)|			
| 2 |Needs to have correct saving format |when saving, a file will be created when using correct format |(√)|			
| 3 |Creates file if one doesnt exit |if the file doesnt exist, it creates a new one to save to |(√)|			
		

## Overall Test Status:

Saving is working properly, but need to see how big of a file the game can handle, and whether itll make a new file to read from if
save file is too big, or not save at all.

## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 |11/04/17 |Rick Sanchez |(√) |			
| 2 |11/06/17 |Rick Sanchez |(√) |			
| 3 |11/08/17 |Rick Sanchez |(√) |			



