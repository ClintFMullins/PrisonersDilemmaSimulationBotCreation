This project was created by Clint Mullins and Peter Glennon for Algorithmic Game Theory. 

Clint created the inner workings of the PD game, the rule creating system, and the execution of all the above with the following class files:
Game
Player
RuleFactory

Peter created the GUI completely using the following class files:
Config
EditRulesPanel
EditRulesWindow
GameLogPanel
GameWindow
HelpWindow
NumericTextField
PayoffPanel
PlayerPanel
SelectionPanel
StrategyPanel



The project was debugged by both Clint and Peter. Some inefficiencies remain but the program should function flawlessly. The PDSimulation.jar is all one needs to run the program but if one wants to the file print out of results or the cute images to show up, the jar should be run from the highest directory. One can also navigate to the directory containing the files and type 'ant run' to compile and run the program.